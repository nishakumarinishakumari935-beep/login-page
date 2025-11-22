<!DOCTYPE html>
<html lang="en">
<head>
    <title>Login page</title>
   <link rel="stylesheet" href="style.css">

</head>
<body> 
    
    
    <div>
        <h1>Enter Your Details</h1>
    <input type="text" id="name" placeholder="Enter Name ">
    <input type="email" id="email" placeholder="Enter Email">
    <input type="password" id="Password" placeholder="Enter password"><br>
    
<a href="webpage.html">
    <button id="loginBtn">Login</button></a>
     </div>
</body>

    
</html>
*{

  padding: 20px 20px;
  box-sizing:border-px;
}
body{
    height: 100%;
    width: 100%;
    background-color:rgb(84, 84, 250);
    margin:0;
    margin-left: 25%;
    padding: 20px 20px;
    color:#111827;
}  
div{ height: 40%;
    width: 40%;
    background-position: 20px;
    background-color:white;
    border: 1px solid black;
}


h1{
    text-align: center;
    
}

input{
    width: 95%;
    height: 100%;
    margin: 10px; 
    padding: 10px 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 5px;
    border: 1px solid black;
    background-color: white;
}
#name{
    background-color:white;
    
}
#email{
    background-color: white;
    
}
#password{
    background-color:white;
    
}
#loginBtn{
   background-color: rgb(73, 70, 243);
   color: black;
   padding: 10px 10px;
   border: none;
   border-radius: 8px;
   font-size: 18px;
   cursor: pointer;
   display: block;
   margin: 10px auto;
   

}

