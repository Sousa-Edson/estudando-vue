<template>
  <ul>
    <li><a href="#">HOME</a></li>
    <li><a href="#">PROJETOS </a></li>
    <li><a href="#">CONTATO</a></li>
  </ul>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style   scoped>
ul{
    list-style: none;
    display: flex;
    background-color: #999;
    }
    li{
        margin-right: 10px;
    }
    a{
        color: ddd;
        text-decoration: none;
        transition: .5s;
    }
    a:hover{
        color: turquoise;
    }
</style>