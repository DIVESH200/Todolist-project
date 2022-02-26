##MY Dharmasksha Project

#Todolist App

### MY Todo Home Page

`<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../CSS/style.css">
    <title>Todo - Complete Your Tasks...</title>
</head>

<body>
    <nav class="navbar background">
        <ul class="nav-list">
            <div class="logo"><img src="https://i.pinimg.com/474x/f9/df/70/f9df70c16e322bc66036444f2fd48bb7.jpg"
                    alt="Todo"></div>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact Us</a></li>
            <li><a href="../HTML/signin.html">Sign in</a></li>
            <li><a href="../HTML/signup.html">Signup</a></li>
        </ul>
        <div class="rightnav">
            <input type="text" name="Search" id="search">
            <button class="btn btn-sm">Search</button>
        </div>
    </nav>
    <section class="background firstsection" id="home">
        <div class="box-main">
            <div class="fhalf">
                <p class="text-big">The one stop to keep Track of your Work</p>
                <p class="text-small">Succesfull People Plan their Work...Who don't want sucess everyone want it..Plan
                    your Daily Goals and achieve it..</p>
                <div class="buttons">
                    <button class="btn">Subscribe</button>
                    <button class="btn">Watch Video</button>
                </div>
            </div>
            <div class="sechalf">
                <img src="https://i.pinimg.com/474x/f9/df/70/f9df70c16e322bc66036444f2fd48bb7.jpg" alt="To Do List">
            </div>
        </div>
    </section>
    <section class="secRight section" id="about">
        <div class="paras">
            <p class="sectionTag text-big">About Us</p><br><br>
            <pre class="sectionSubTag text-small">What is a ToDo List?
                What is a ToDo List? The definition is a simple one. It’s a list of tasks you need to complete or things
                that you want to do.

                Most typically, they’re organised in order of priority. Traditionally, they’re written on a piece of
                paper or post it notes and act as a memory aid. As technology has evolved we have been able to create a
                todo lists with excel spreadsheets, word documents, email lists, todo list apps, Microsoft to do and
                google to do list to name a few. You can use a to do list in your home and personal life, or in the
                workplace.

                Having a list of everything you need to do written down in one place means you shouldn’t forget anything
                important. By prioritising the tasks in the list you plan the order in which you’re going to do them and
                can quickly see what needs your immediate attention and what tasks you can leave until a little later.
            </pre>
        </div>
        <div class="thumbnail">
            <img src="https://source.unsplash.com/900x900/?tasks,workout" alt="To Do List" class="imgFluid">
        </div>
    </section>
    </section>
    <section class="secLeft section" id="services">
        <div class="paras">
            <p class="sectionTag text-big">Services</p><br><br>
            <p class="sectionSubTag text-small">We provide all kind of custom software or application based on the
                requirements of user or Company:
            <div class="services">
                <li>Custom preferences</li>
                <li>Enhanced UX and UI</li>
                <li>Life time Maintainence for Application</li>
                <li>Anywhere and Any Device Usage</li>
            </div>

            </p>
        </div>
        <div class="thumbnail">
            <img src="https://source.unsplash.com/900x900/?tasks,meetings" alt="To Do List" class="imgFluid">
        </div>
    </section>
    </section>
    <section class="contact " id="contact">
        <div class="form">
            <p class="sectionTag text-big">Contact Us</p>
            <br>
            <br>
            <pre class="text-small">
It is our Pleasure to Hear from You!
Do you have a business inquiry or a query? Do not hesitate to reach out.
Fill out the quick form to drop us a mail
            </pre>
            <br>
            <br>
            <div class="datafil">
                <label>
                    <b>Name </b>
                </label><br>
                <input type="text" name="name" id="name" placeholder="Enter Name"><br><br>
                <label>
                    <b>Phone Number </b>
                </label><br>
                <input type="text" name="phone" id="phone" placeholder="Enter Phone number"><br><br>
                <label>
                    <b>Email </b>
                </label><br>
                <input type="email" name="email" id="name" placeholder="Enter Email"><br><br>
                <label>
                    <b> Enquiry Details</b>
                </label><br>
                <input type="text" name="enquiry" id="enquiry" placeholder="Enter Enquiry Details"><br><br>
                <input type="button" class="btn" value="Submit">
            </div>
        </div>
    </section>

</body>

</html>`

### style.css:

`@import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@1,500&display=swap');
*{
    margin: 0;
    padding: 0;
}
.navbar
{
    display:flex;
    align-items: center;
    justify-items: center;
    position: sticky;
    top:0;
    cursor: pointer;
    border: 4px solid whitesmoke;


}

.nav-list
{ width: 50%;
  display: flex;
  align-items: center;
  padding: 0 24px;
}

.nav-list li
{
    display: flex;
    list-style: none;
    padding: 5px;
}
.nav-list li a
{   
    color: white;
    text-decoration: none;
    padding: 0px 10px;
}

.rightnav
{   
    width: 50%;    
    text-align: right;
    padding: 0 23px;
}


.logo img
{ 
   
    height:70%;
    width: 60%;
    border: 10px solid  white;
    border-radius: 5px ;
    margin: 10%;
}
.logo
{width:20%;
 display: flex;
}

#search
{
    padding: 5px;
    font-size: 17px;
    border: 4px solid white;
    border-radius: 9px;
}
.background
{
    background: rgba(0, 0, 0, 0.7) url('https://clickup.com/blog/wp-content/uploads/2019/01/to-do-list-apps.png');
    background-size: cover;
    background-blend-mode: darken;
}

.firstsection
{
    height: 100vh;
}

.box-main
{   height: 90%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(231, 219, 219);
    font-family: 'Times New Roman';
    font-size: 120%;
    max-width: 50%;
    margin: auto;
}

.fhalf
{width: 80%;
 display: flex;
 flex-direction: column ;
 text-align: center;
 justify-content: center
}

.sechalf img
{ width: 100%;
  border: 10px solid  white;
  border-radius: 5px ;
}

.text-big
{
    font-size: 50px;
}

.text-small
{
    font-size: 18px;
}

.btn
{
    padding: 8px 20px;
    margin: 7px 0;
    border: 2px solid white;
    border-radius: 80px;
    font-size: 18px;
    background: white;
    color: black;
    cursor: pointer;
    padding: 6;
}

.section
{
    height: 600px;
    display: flex;
    justify-content: space-evenly;
    padding:  60px;
    align-items: center;
    margin: auto;
    font-family: 'Ubuntu', sans-serif;
    border: 4px solid whitesmoke;
}
.secRight
{   background-color: #8946A6;
}

.paras
{  
    max-width: 80%;
    text-align: center;
}

.secLeft
{   background-color: #EA99D5;
    flex-direction: row-reverse;
}



.sectionSubTag
{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.thumbnail img
{
    border-radius: 20px;
    border: white solid 8px;
    width:250px;
}

.contact
{
    background-color: #FFCDDD;
    height: 650px;
    font-family: 'Ubuntu', sans-serif;
   margin: auto;
}

.form
{   
    padding: 10px ;
    align-items: center;
    max-width: 90%;
    margin: auto;
   
}

.form input
{   
    max-width: 40%;
    margin: 8px;
    margin:auto;
    border: black solid 2px;
    border-radius: 5px;
}

#enquiry
{
    padding:40px;
}

label 
{
    padding:10px;
}

.services
{
    text-align: left;
    font-size: 30px;
}

.datafil
{
    font-size: 20px;
    justify-content: center;
    padding: auto;
}

label
{
    margin-bottom: 5px;
}

pre
{
    font-size: 16px;
    font-family:'Times New Roman', Times, serif;
}`
### Signin.html:
`<!DOCTYPE html>
<html>

<head>
    <title>To Do Sign-in</title>
    <link rel="stylesheet" type="text/css" href="../CSS/Signin.css">
</head>

<body>

    <div class="login">
        <form id="login" method="get" action="login.php">
            <h2>Sign in</h2><br>
            <div>
            <img src="https://i.pinimg.com/474x/f9/df/70/f9df70c16e322bc66036444f2fd48bb7.jpg" alt="To Do List" class="imgFluid">
        </div>
            <label>
                <b>User Name </b>
            </label>
            <input type="text" name="Uname" id="Uname" placeholder="Username">
            <br><br>
            <label><b>Password
                </b>
            </label>
            <input type="Password" name="Pass" id="Pass" placeholder="Password">
            <br><br>
            <a href="../HTML/todo.html" "><input type="button" name="log" id="log" value="Log in "></a>
            <br><br>
            <input type="checkbox" id="check">
            <span>Remember me</span>
            <br><br>
             <a href="#">Forgot Password ?</a>
        </form>
    </div>
</body>

</html> `

### Signin.css

`
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@1,500&display=swap');

body  
{  
    margin: 0;  
    padding: 0;  
    background-color:#8946A6;  
    font-family: 'Ubuntu', sans-serif;;  
    padding: 80px 80px;
}  

.imgFluid
{
    border-radius: 8px;
}
.login{  
        align-items: center;
        width: 300px;  
        position: sticky;
        margin: auto;  
        margin: 20 0 0 450px;  
        padding: 20px 150px;  
        background: #B762C1;  
        border-radius: 15px ;  
          
}  
h2{  
    text-align: center;  
    color: black;  
    padding: 20px;  
}  
label{  
    color: black;  
    font-size: 17px;  
}  
#Uname{  
    width: 300px;  
    height: 30px;  
    border: none;  
    border-radius: 3px;  
    padding-left: 8px;  
}  
#Pass{  
    width: 300px;  
    height: 30px;  
    border: none;  
    border-radius: 3px;  
    padding-left: 8px;  
      
}  
#log{  
    width: 300px;  
    height: 30px;  
    border: none;  
    border-radius: 17px;  
    padding-left: 7px;  
    color: black;    
}  
span{  
    color: white;  
    font-size: 17px;  
}  
a{  
    float: right;  
    color: black;
    text-decoration: none;
}  

img{
    height:90%;
    width:98%;
}`

### Signup.html:

`<!DOCTYPE html>
<html>

<head>
    <title>To Do Sign-up</title>
    <link rel="stylesheet" type="text/css" href="../CSS/signup.css">
</head>

<body>

    <div class="Signup">
        <div class="form">
        <form id="Sign" method="get" action="signup.php">
            <h2>Sign Up</h2><br>
            <img src="https://i.pinimg.com/474x/f9/df/70/f9df70c16e322bc66036444f2fd48bb7.jpg" alt="To Do List" class="imgFluid">
            <label>
                <b>User Name </b>
            </label>
            <input type="text" name="Uname" id="Uname" placeholder="Username">
            <br><br>
            <label>
                <b>Email</b>
            </label>
            <input type="text" name="Email-id" id="Email-id" placeholder="Email">
            <br><br>
            <label><b>Password
                </b>
            </label>
            <input type="Password" name="Pass" id="Pass" placeholder="Password">
            <br><br>
            <a href="./Home.html">
            <input type="button" name="submit" id="submit" value="Submit">
            </a>
            <br><br>
        </form>
    </div>
    </div>
</body>

</html>`

### Signup.css:

`@import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@1,500&display=swap');

body  
{  
    margin: 0;  
    padding: 0;  
    background-color:#8946A6;  
    font-family: 'Ubuntu', sans-serif;;  
    padding: 80px
}  

.imgFluid
{
    border-radius: 8px;
}
.Signup{  
        
        width: 300px;  
        position: sticky;
        margin: 20 0 0 450px;
        margin: auto;    
        align-items: center;
        padding: 0px 150px;  
        background: #B762C1;  
        border-radius: 15px ;  
          
}  
h2{  
    text-align: center;  
    color: black;  
    padding: 20px;  
}  
label{  
    color: black;  
    font-size: 17px;  
}  
#Uname{  
    width: 300px;  
    height: 30px;  
    border: none;  
    border-radius: 3px;  
    padding-left: 8px;  
}
#Email-id
{
    width: 300px;  
    height: 30px;  
    border: none;  
    border-radius: 3px;  
    padding-left: 8px; 
}  
#Pass{  
    width: 300px;  
    height: 30px;  
    border: none;  
    border-radius: 3px;  
    padding-left: 8px;  
      
}  

#submit{  
    width: 300px;  
    height: 30px;  
    border: none;  
    border-radius: 17px;  
    padding-left: 7px;  
    color: black;  
  
}  

span{  
    color: white;  
    font-size: 17px;  
}  
a{  
    float: right;  
    text-decoration: none;
    color: black;
}  

img{
    height:90%;
    width:98%;
}`

### Todo.html:

`<!DOCTYPE html>
<html>

<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      margin: 0;
      min-width: 250px;
      background-color: #8946A6;
    }


    * {
      box-sizing: border-box;
    }


    ul {
      margin: 0;
      padding: 0;
    }


    ul li {
      cursor: pointer;
      position: relative;
      padding: 12px 8px 12px 40px;
      list-style-type: none;
      background: #eee;
      font-size: 18px;
      transition: 0.2s;


      -webkit-user-select: none;
      -moz-user-select: none;
      -ms-user-select: none;
      user-select: none;
    }


    ul li:nth-child(odd) {
      background: #f9f9f9;
    }


    ul li:hover {
      background: #ddd;
    }


    ul li.checked {
      background: #888;
      color: #fff;
      text-decoration: line-through;
    }


    ul li.checked::before {
      content: '';
      position: absolute;
      border-color: #fff;
      border-style: solid;
      border-width: 0 2px 2px 0;
      top: 10px;
      left: 16px;
      transform: rotate(45deg);
      height: 15px;
      width: 7px;
    }


    .close {
      position: absolute;
      right: 0;
      top: 0;
      padding: 12px 16px 12px 16px;
    }

    .close:hover {
      background-color: #B762C1;
      color: white;
    }


    .header {
      background-color: #B762C1;
      padding: 30px 40px;
      color: white;
      text-align: center;

    }


    .header:after {
      content: "";
      display: table;
      clear: both;
    }


    input {
      margin: 0;
      border: none;
      border-radius: 0;
      width: 75%;
      padding: 10px;
      float: left;
      font-size: 16px;
    }


    .addBtn {
      padding: 10px;
      width: 25%;
      background: #d9d9d9;
      color: #555;
      float: left;
      text-align: center;
      font-size: 16px;
      cursor: pointer;
      transition: 0.3s;
      border-radius: 0;
    }

    .addBtn:hover {
      background-color: #bbb;
    }

    .right {
      width: 70%;
      float: right;
      height: 700px;
      background-color: #8946A6;
      border: rgb(90, 84, 84) solid 2px;
    }

    .Header {
      background-color: #B762C1;
      text-align: center;
      font-size: 30px;
      border: rgb(90, 84, 84) solid 2px;
    }

    .left {
      width: 30%;
      float: left;
      background-color: #8946A6;
      height: 700px;
      border: rgb(90, 84, 84) solid 2px;
    }

    .panim {
      margin-top: 10px;
      margin-left: 2px;
      width: 200px;
      margin-bottom: 5px;
    }

    .button {
      border: none;
      color: white;

      text-align: center;
      text-decoration: none;
      font-size: 16px;
      margin: 2px 2px;
      transition-duration: 0.4s;
      cursor: pointer;
    }

    .button1 {
      background-color: white;
      color: black;
      border: 2px solid #FFFAF0;
      width: 50%;
      text-align: center;

    }

    .button1:hover {
      background-color: #D3D3D3;
      color: blue;
    }

    .button2 {
      background-color: white;
      color: black;
      border: 2px solid #FFFAF0;
      width: 50%
    }

    .button2:hover {
      background-color: #D3D3D3;
      color: blue;
    }

    .button3 {
      background-color: white;
      color: black;
      border: 2px solid #FFFAF0;
      width: 50%;
      text-align: center;
    }

    .button3:hover {
      background-color: #D3D3D3;
      color: blue;
    }

    .button4 {
      background-color: white;
      color: black;
      border: 2px solid #FFFAF0;
      width: 50%;
      text-align: center;
    }

    .button4:hover {
      background-color: #D3D3D3;
      color: blue;
    }

    .addbn
    { font-size: 16px;
      width:200px;
      height: 40px;
    }
  </style>
</head>
<h2 style="margin:5px  " class="Header">TODO</h2>

<body>
  <sec class="left">
    <CENTER>
      <img src="../img/OIP (1).jpg" alt="Hello user" class="panim">
      <h2> Welcome to TODO</h2>
      <a href="todo.html"><button class="button button1" , img src="img_snow.jpg" ;>
          <br>
          <h4>My Day</h4>
        </button></a>
      <br>
      <a href="todo.html"><button class="button button2">
          <h4>Important</h4>
        </button></a>
      <br>
      <a href="todo.html"><button class="button button3">
          <h4>Planned</h4>
        </button></a>
      <br>
      <a href="todo.html"><button class="button button4">
          <h4>Assigned to me</h4>
        </button></a>
        <br>
      <a href="todo.html"><button class="button button3">
          <h4>Planned</h4>
        </button></a>
      <br>
    </CENTER>
  </sec>
  <sec class="right">
    <div id="myDIV" class="header">
      <h2 style="margin:5px">Tasks</h2>
      <input type="text" id="myInput" placeholder="Title...">
      <button class="addbn">Add</button>
    </div>

    <ul id="myUL">
      <li>Hit the gym</li>
      <li class="checked">Pay bills</li>
      <li>Meet George</li>
      <li>Buy eggs</li>
      <li>Read a book</li>
      <li>Organize office</li>
    </ul>
  </sec>
</body>

</html>`