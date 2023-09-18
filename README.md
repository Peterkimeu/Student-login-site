<!DOCTYPE html>
<html>
    <head>
        <meta name ="viewpoint"content="width=device-width, initial-scale=1">
        <title>Login Page</title>
        <style>
            body{
                font-family:Arial, Helvetica, sans-serif;
                background-color: pink;
            }
            button{
                background-color:gray;
                width:100%;
                color:orange;
                padding:15px;
                margin: 10px 0px;
                border: none;
                cursor: pointer;
            }
            form{
                border: 3px solid #f1f1f1;
            }
            input[type=text], input[type=password]{
                width:100%;
                margin: 8px 0px;
                padding: 12px 20px;
                display: 2px solid green;
                box-sizing: border-box
            }
            button:hover{
                opacity:0.7;
            }
            .cancelbtn{
                width: auto;
                padding: 10px 18px;
                margin: 10px 5px;
            }
            .container{
                padding: 25px;
                background-color: light blue;
            }
        </style>
    </head>
    <body>
        <center><h1>Students Login form</h1></center>
        <form>
            <div class="container">
                <label>Username:</label>
                <input type="text"placeholder="Enter Username"name="username"required>
                <label>password:</label>
                <input type="password"placeholder="Enter Password"name="Password"required>
                <button type="Submit">Login</button>
                <input type="checkbox"checked="checked">Remember me 
                <button type="button"class="cancelbtn">Cancel</button>
                Forgot<a href="#"> password?</a>
            </div>
        </form>
    </body>
</html>
