 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Login Form </title>
    <link rel="stylesheet" href="style.css">
</head>
<style>* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}

body {
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background-image:url('back.jpg')
   
}

.container {
    width: 20rem;
    margin: 1rem;
    padding: 2rem 1rem;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    border:solid pink 5px;
    
}

 h2 {
    margin-bottom: 2rem;
    font-size:40px;
}

 form {
    display: flex;
    flex-direction: column;
}

.container form label {
    width: 100%;
    margin-bottom: 5px;
    font-size:20px;
}

 input {
    width: 16rem;
    outline: none;
    padding: 5px 10px;
    margin-bottom: 1rem;
    border: 3px solid rgb(133, 129, 129);
}

button {
    border: none;
    color: #fff;
    margin: 1rem 0;
    font-size: 18px;
    padding: 0.5rem;
    cursor: pointer;
    font-weight: bold;
    border-radius: 5rem;
    background: linear-gradient(to right, red, yellow);
}

.newUser span {
    color: rgb(25, 176, 176);
}
</style>

<body>

    <section class="container">

        <h2> Login Form </h2>
        <form action="" class="form">
            <label for="userId"><span> Email or Phone </span></label>
            <input type="text" name="username" id="userId">


            <label for="password"><span> Password </span></label>

            <input type="password" name="password" id="password">

            <button onclick="alert('Your Login  is Successful')">Login</button>
        </form>

        <p class="newUser">
            Not a member
            <a href="register.html">Register now</a>
        </p </section>

</body>
</html>
