<div style="display: flex; color:white">
    <div style="flex-basis: 50%; color: white;">
<h1>
    Welcome to my blog page.
</h1></div>
<h3>
    I have many categories of blogs in this page,please feel to have a look.
</h3>
</div>
<div class="nav">
    <a href="/blogs/movies">Movies</a>
    <a href="/blogs/food">Food</a>
    <a href="/blogs/travel">Travelling</a>
</div>

<div class="blog-main-content">
<slot></slot>
</div>

<style>
    .nav{
        display: flex;
        min-height: 60px;
        background-color: black;
    }

    .nav a{
        color: white;
        padding: 10px;
        text-decoration: none;
    }

    .blog-main-content{
        margin-top: 20px;
        min-height: 200px;
        background-color: white;
        border: solid;
        padding: 20px;
    }
</style>