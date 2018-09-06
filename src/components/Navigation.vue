<template>
    <div>
        <ul>
            <li><a class="active" href="#blog">Blog</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#about">About</a></li>
        </ul>
    </div>
</template>

<script>
export default {
  name: 'Navigation'
}
</script>

<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
}

li {
    float: left;
}

li a {
    display: block;
    color: #C1B098;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}
</style>