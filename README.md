# facebookloginpage
<html> 
    <head>
<style>
    *{
        padding: 0;
        margin: 0;
        box-sizing: border-box;
    }
    body{
        font-family: 'Poppins',sans-serif;
        background-color: #f0f2f5;
        color: #1c1e21;
    }
    main{
        height: 50vh;
        width: 50vw;
        position: relative;
        margin: 0 auto;
    }
    footer{
        height: 30vh;
        background-color: #ffffff;
    }
    .row{
        display: flex;
        justify-content: space-around;
        align-items: center;
        width: 100%;
        max-width: 1000px;
        position: absolute;
        top: 50%;
        transform: transalte(-50%, -50%);
        left: 50%;
    }
    .col-logo{
        flex: 0 0 50%;
        text-align: left;
    }
    .col-form{
        flex: 0 0 40%;
        text-align: center;
    }
    .col-logo img{
        max-width: 300px;
    }
    .col-logo h2{
        font: 26px;
        font-weight: 400;
        padding: 0 30px;
        line-height: 32px;
    }
    .col-form .form-container{
        background-color: #ffffff;
        border: none;
        border-radius: 8px;
        box-shadow: 0 2px 4px rgba(0,0,0,0.1), 0 8px 16px rgba(0,0,0,0.1);
        margin-bottom: 30px;
        padding: 20px;
        max-width: 400px;
    }
    .col-form .form-container input, .col-form .form-container .btn-login{
        width: 100%;
        margin: 5px 0;
        height: 45px;
        vertical-align: middle;
        font-size: 16px;
    }
    .col-form .form-container input{
        border: 1px solid #dddfe2;
        color: #1d2129;
        padding: 0 8px;
        outline: none;
    }
    .col-form .form-container input:focus{
        border-color: #1877f2;
        box-shadow: 0 0 0 2px #e7f3ff;
    }
    .col-form .form-container .btn-login{
        border:none ;
        background-color: #1877f2;
        border-radius: 6px;
        font-size: 20px;
        padding: 0 16px;
        color: #ffffff;
        font-weight: 700;
    }
    .col-form .form-container a{
        display: block;
        color: #1877f2;
        font-size: 14px;
        text-decoration: none;
        padding: 10px 0 20px;
        border-bottom: 1px solid #dadde1;
    }
    .col-form .form-container a:hover{
text-decoration: underline;
    }
    .col-form .form-container .btn-new{
        background-color: #42b72a;
        border: none;
        border-radius: 6px;
        font-size: 17px;
        line-height: 48px;
        padding: 0 16px;
        color: #ffffff;
        font-weight: 700;
        margin-top: 20px;
    }
    .col-form p{
        font-size: 14px;
    }
    .col-form p a{
        text-decoration: none;
        color: #1c1e21;
        font-weight: 600;
    }
    .col-form p a:hover{
        text-decoration: underline;
    }
    .footer-contents{
        position:absolute;
        max-width: 1000px;
        max-height: 1000px;
        margin: 0 auto;
    }
    footer ol{
        display: flex;
        flex-wrap: wrap;
        list-style-type: none;
        padding: 10px 0;
        height: 100px;
        width: 1000px;
    }
    footer ol:first-child{
        border-bottom: 1px solid #dddfe2;
        height: 100px;
        width: 1000px;
    }
    footer ol:first-child li:last-child button{
        background-color: #f5f6f7;
        border: 1px solid #ccd0d5;
        outline: none;
        color: #4b4f56;
        padding: 0 8px;
        font-weight: 700;
        font-size: 16px;
    }
    footer ol li{
        padding-right: 15px;
        font-size: 12px;
        color: #385898;
    }
    footer ol li a{ 
        text-decoration: none;
        color: #385898;
    }
    footer ol li a:hover{
        text-decoration: underline;
    }
    footer small{
        font-size: 11px;
    }
    </style>
    <title>Fcebook -login or sign up</title>
    </head>
    <body>
<main>
    <div class="row">
<div class="col-logo">
    <img src="image/fb_logo.svg" alt="logo">
    <h2>Facebook helps you connect and share with the people in yoour life.</h2>
    </div>
    <div class="col-form">
        <div class="form-container">
            <input type="text" placeholder="Email address or phone number">
            <input type="password" placeholder="Password">
            <button class="btn-login">Login</button>
            <a href="#">Forgotten password</a>
            <button class="btn-new">Create new Account</button>
        </div>
        <p><a href="#" ><b>Create a Page</b></a>for a celebrity, band or business.</p>
    </div>
    </div>
</main>
<footer> 
    <div class="footer-contents"> 
        <ol>
            <li>English(UK)</li>
            <li><a href="#">हिन्दी</a></li>
            <li><a href="#">اردو</a></li>
            <li><a href="#">ਪੰਜਾਬੀ</a></li>
            <li><a href="#">বাংলা</a></li>
            <li><a href="#">ગુજરાતી</a></li>
            <li><a href="#">मराठी</a></li>
            <li><a href="#">தமிழ்</a></li>
            <li><a href="#">తెలుగు</a></li>
            <li><a href="#">മലയാളം</a></li>
            <li><a href="#">ಕನ್ನಡ</a></li>
            <li><button>+</button></li>
        </ol>
            <ol>
                <li><a href="#">Sign Up</a></li>
                <li><a href="#">Log In</a></li>
                <li><a href="#">Messenger </a></li>
                <li><a href="#">Facebook Lite </a></li>
                <li><a href="#">Watch </a></li>
                <li><a href="#">Places </a></li>
                <li><a href="#">Games </a></li>
                <li><a href="#">Marketplace </a></li>
                <li><a href="#">Facebook Pay </a></li>
                <li><a href="#">Instagram </a></li>
                <li><a href="#">Bulletin </a></li>
                <li><a href="#">Fundraisers </a></li>
                <li><a href="#">Groups </a></li>
                <li><a href="#">About </a></li>
                <li><a href="#">Create ad </a></li>
                <li><a href="#">Voting Information Centre </a></li>
                <li><a href="#">Create Page </a></li>
                <li><a href="#">Cookies </a></li>
                <li><a href="#">Privacy </a></li>
                <li><a href="#">Terms </a></li>
            </ol>
            <small>Meta © 2021</small>
    </div>
</footer>
</body>
</html>
