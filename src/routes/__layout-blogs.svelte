<div class="header">
    <div class="nav">
        <a href="/home" style="color:yellow">HOME</a>
        <a href="/about" style="color:white">ABOUT</a>
        <a href="/blogs" style="color:black">BLOGS</a>
    </div>
</div>

<main class="content">
    <slot></slot>
</main>


<div class="footer">
    This is Footer

</div>

<style>
    .nav{
        display: flex;
        padding: 10px;
        background-color: green;
    }
    .nav a{
        padding: 2rem
    }
    .content{
        min-height: 300px;
        background-color: pink;
        padding: 2rem;
    }

    .header{
        display:block;
        background-color: skyblue;
        color: black;
        height: 200px;
        padding: 2rem;
    }

    .footer{
        display:block;
        background-color: black;
        color: white;
        height: 100px;
        padding: 2rem;
    }
</style>