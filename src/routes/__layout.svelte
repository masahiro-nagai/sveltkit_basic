<div class="header">
    <div class="nav">
        <a href="/home">HOME</a>
        <a href="/about">ABOUT</a>
        <a href="/blogs">BLOGS</a>
    </div>
</div>

<main class="content">
    <slot></slot>
</main>


<div class="footer">
    


</div>

<style>
    .nav{
        display: flex;
    }
    .nav a{
        padding: 2rem
    }
    .content{
        min-height: 300px;
        padding: 2rem;
    }

    .header{
        display:block;
        background-color: orange;
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