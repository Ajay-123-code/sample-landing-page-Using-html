<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sample landing page html css</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    *{
        padding: 0;
        margin: 0;
        box-sizing: border-box;
    }
    header{
        width: 100%;
        height: 100vh;
        background: rgb(180, 222, 135);
        background-size: cover;
    }
    nav{
        width: 100%;
        height: 100px;
        
        color: blue;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
    .logo{
        font-size: 2em;
        letter-spacing: 2px;
    }
    .menu{
        text-decoration: none;
        color: bisque;
        padding: 10px 20px;
        font-size: 20px;
    }
    .menu a:hover{
        border: 1px solid rgb(132, 92, 205);
        background: transparent;
    }
    .register a{
        text-decoration: none;
        color: bisque;
        padding: 10px 20px;
        font-size: 20px;
        background: indianred;
        border-radius: 8px;
    }
    .register a:hover{
        border: 10px solid indianred;
        background:yellow;
        
    }
    .h-text{
        position: absolute;
        top: 50%;
        left: 50%;
        max-width: 650px;
        transform: translate(-50%,-50%);
        text-align: center;
        color: #fff;
    }
    .h.text span{
        letter-spacing: 1px;
    }
    .h-text h1{
        font-size: 2.8em;
    }
    .h-text a{
        text-decoration: none;
        background:rgb(255, 170, 0);
        padding: 20px 40px;
        color: #fff;
        letter-spacing: 5px;
        transition:0.4s;
    }
    .h-text a:hover{
        border: 1px solid blue;
        background:gree;
    }
    button{
        color: brown;
        text-align: center;
        background-color: rgb(0, 255, 72);
        height: 50px;
        width: 100px;
        text-align: center;
    }
</style>

<body>
    <header>
        <nav>
            <div class="logo">elevate lab
            </div>
            <div class="menu">
                <a href="#">home</a>
                <a href="#">about</a>
                <a href="#">contact</a>
                <a href="#">services</a>
                <a href="#">content</a>
            </div>
           <div class="register">
            <a href="#">register</a>
           </div>
        </nav>
        <section  class="h-text">
            <span></span>
            <h1> Elevate labs<em>(is a sanfrancisco-based company focused on improving cognitive skills through brain training programs and apps like elevate and balance)</em></h1>
            <br></br>
            <a href="#">easy customised</a>
            <br></br>
            <a href="#">conceptul learning</a>
            <br></br>
            <a href ="#">info</a>
            <br></br>
            <a href="#">free download</a>

        </section>

    </header>
    <footer>


    </footer>
    <form action="">
        <label form="email">EMAIL:</label>
        <input type="">
    </form>
    <br></br>
    <button>submit</button>
    <br>
    <h5>follow us on <em>(facebook,instagram,whatsapp)</em></h5>
</body>
</html>
