<template>
    <div id="blog-post">
        <div>
          <h3>{{title}}</h3>
        </div>
        <div class='content'>
          {{content}}
        </div>
    </div>
</template>

<script>
export default {
  name: 'BlogPost',
  props: {
    title: String,
    content: String
  }
}
</script>

<style>

h3 {
  float: left;
}

.content {
  float: left;
}

</style>

