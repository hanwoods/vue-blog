<template>
    <div id="BlogFeed">
        <BlogPost title="My First Blog Post" content="This is how you blog, you write long paragraphs, that people will probably never read."/>
    </div>
</template>

<script>
import BlogPost from './BlogPost.vue'

export default {
    name: "BlogFeed",
    components: {
        BlogPost
    }
}
</script>
