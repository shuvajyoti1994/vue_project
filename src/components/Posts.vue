<template>
    <h1 class="title is -2">This is  Dummy Json placeholder data</h1>
    <div class="box" v-for="post in posts" :key="post.id">
        <h1 class="title is -6">{{post.title}}</h1>
        <p>{{post.body}}</p>
    </div>
</template>

<script>
    export default{
        data() {
            return{
                posts: []
            }
        },
        created() {
            fetch('https://jsonplaceholder.typicode.com/posts')
            .then(response=>response.json())
            .then(data=>{
                this.posts = data
                // console.log(data);
            })

        }
    }
</script>