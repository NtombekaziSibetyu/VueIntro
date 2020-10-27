<template>
    <div>
        <show-blog></show-blog>
        <list-blog></list-blog>
    </div>
</template>

<script>
// Imports<add-blog></add-blog>
import addBlog from './components/addBlog.vue';
import showBlogs from './components/showBlogs.vue';
import listBlogs from './components/listBlogs.vue'

export default {
    components: {
        'add-blog': addBlog,
        'show-blog': showBlogs,
        'list-blog' : listBlogs
    },
    data () {
        return {
        }
    },
    methods: {
    }
}
</script>

<style>
body{
    margin: 0;
    font-family: 'Nunito SemiBold';
}
</style>