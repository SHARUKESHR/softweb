# Ex.07 Software Product Company Website
## Date: 19.12.2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<html>
    <head>
        <link rel="stylesheet" href="stylehome.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./images/logo.jpg" alt="logo" height="60px"></div>
            <li><a href="./home.html">Home</a></li>
            <li><a href="peroson.html">People</a></li>
            <li><a href="./products.html">Products</a></li>
            <li><a href="./contact.html">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" >
            <button type="submit" class="button" >search</button>
            
        </div>
    </div>
    <div class="home">
        <div class="head">
        <h1>Dev Techonology and Software Agency</br>ideas into </br>Products</h1>
        <p class="quote">"People who are really in serious about Software </br>should make their hardware"- Robert </p>
        <button class="join">Join us</button>
    </div>
    <div class="login">
        <h2 class="log">login Here</h2> 
        <div class="logbox">
        <input type="text" placeholder="username or email" class="but"></input></br></br>
        <input type="text"  placeholder="password" class="but"> </input></br></br>
        <button type="submit" class="bute">Login</button></br></br>
        <hr id="loge">
        </div>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;Don't have an account </br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>Sign up</u> here.</p>

    </div>
    </div>
    <footer>
        <div  class="colored-line">
            <h5>Design and developed by Mr.Sharukesh.R &copy;2023</h5>
        </div>
    </footer>

    
    
    </body>
</html>

.nav{
    display: flex;
    justify-content:center;
    gap: 50px;
    margin-top: 25px ;  
}

li{
    list-style: none;
    font-weight: 100px;
    
}

body{
    background-color: rgb(0, 217, 255);

  }

*{
    font-size:20px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 10px;}
.home{
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 80vh;
    gap:250px;

}
.login{
    background-color: #545375;
    text-align: center;
    width:250px;

}
.log{
    padding: 5px;
    background-color: pink;
    border-radius: 8px;
}
.but{
    border-radius: 10px;
    background-color:;
}
.bute{
    border-radius: 10px;
    background-color: chocolate;

}
#loge{
    border-color: pink;
    border-width: 2px;
}
h1{
    color: red;
    font-size: 50px;
}
.join{
    border-radius: 10px;
    background-color:chocolate;
    padding:10px;
    width: 100px ;
    margin-top: 25px;
}
.quote{
    font-style: oblique;
    font-style: italic;
}
.colored-line {
    width: 100%; 
    height: 25px; 
    background-color:rgb(64, 255, 0);
    text-align: center;
    
  }
  .button{
    background-color: chocolate;
  }

<html>
    <head>
        <link rel="stylesheet" href="./personstyle.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./images/logo.jpg" alt="logo" height="60px"></div>
            <li><a href="./home.html">Home</a></li>
            <li><a href="peroson.html">People</a></li>
            <li><a href="./products.html">Products</a></li>
            <li><a href="./contact.html">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" >
            <button type="submit" class="button" >search</button>
            
        </div>
    </div>
    <div class="person">
        <li> <img src="./images/1.png" class="bod"></br><span> &nbsp;&nbsp;&nbsp;sharukesh</span><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CEO</p></li>
        <li> <img src="./images/2.jpg"  class="bod"></br><span>&nbsp;&nbsp;&nbsp;Arun</span><P>&nbsp;&nbsp;&nbsp;&nbsp;Founder</P></li>
        <li> <img src="./images/3.jpg" class="bod"></br><span>&nbsp;&nbsp;&nbsp;Pavithran</span><p>&nbsp;&nbsp;&nbsp;&nbsp;Co-Founder</li>
        <li> <img src="./images/111.jpg"class="bod" ></br><span>&nbsp;&nbsp;&nbsp;Karthi</span><p>&nbsp;&nbsp;&nbsp;&nbsp;Director</p></li>
        <li> <img src="./images/panda.jpeg" class="bod"></br><span>&nbsp;&nbsp;&nbsp;Sanjai</span><p>&nbsp;&nbsp;&nbsp;&nbsp;Assi Director</p></li>
        <li> <img src="./images/6.jpg" class="bod"></br><span>&nbsp;&nbsp;&nbsp;Kirba</span><P>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MD</P></li>
    </div>
    <footer>
    <div  class="colored-line">
        <h5>Design and developed by Mr.Sharukesh.R &copy;2023</h5>
    </div>
</footer>
    
    
    </body>
</html>

.nav{
    display: flex;
    justify-content:center;
    gap: 50px;
    margin-top: 25px ;  
}

li{
    list-style: none;
    font-weight: 100px;
    
}
.person{
    display: flex;
    margin-top: 230px;
    justify-content: center;
    gap: 20px;
}
.bod{
    height: 100px;
    border: 3px solid rgb(255, 255, 0);

}
*{
    font-size:20px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 60px;
}
span{
    font-size: 20px;
    font-weight: 1000;
    text-indent: 20px;
    
}
.colored-line {
    width: 100%; 
    height: 25px; 
    background-color:green;
    text-align: center;
    margin-top: 200px;
  }
  body{
    background-color: rgb(0, 174, 255);

  }
  .button{
        background-color: rgb(210, 30, 192);
      
  }

<html>
    <head>
        <link rel="stylesheet" href="styleproduct.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./images/logo.jpg" alt="logo" height="60px"></div>
            <li><a href="./home.html">Home</a></li>
            <li><a href="peroson.html">People</a></li>
            <li><a href="./products.html">Products</a></li>
            <li><a href="./contact.html">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" >
            <button type="submit" class="button" >search</button>
            
        </div>
    </div>
    <div>
        <img src="./images/product.jpg" alt="product" class="imge">
    </div>
    <footer>
        <div  class="colored-line">
            <h5>Design and developed by Mr.Sharukesh.R &copy;2023</h5>
        </div>
    </footer>
    
    
    </body>
</html>

.nav{
    display: flex;
    justify-content:center;
    gap: 50px;
    margin-top: 25px ;  
}

li{
    list-style: none;
    font-weight: 100px;
    
}


*{
    font-size:20px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 10px;
}

  body{
    background-color: rgb(0, 225, 255);

  }
.imge{
    border-radius: 10px;
    height: 450;
    margin-top: 60px;
    margin-left: 450px;
}
.colored-line {
    width: 100%; 
    height: 25px; 
    background-color:rgb(34, 255, 0);
    text-align: center;
    margin-top: 110px;
    border-radius: 0;
  }

  .contact{
    display: flex;
    justify-content:center;
    align-items: center;
    height: 80vh;
    gap: 300px;

  }
  span{
    font-weight: 1000px;
  }
  .info{
    background-color:pink;
    padding: 10px;
    border: 3px solid orange;
    border-radius: 30px;
    
  }
  .detail{
    background-color: pink;
    padding: 10px;
    border: 3px solid orange;
    border-radius: 30px;

  }
  .comment{
    padding:50px; }
  .submit{
    background-color: chocolate;
  }
  .button{
    background-color: chocolate;
  }
  
  <html>
    <head>
        <link rel="stylesheet" href="stylecontact.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./images/logo.jpg" alt="logo" height="60px"></div>
            <li><a href="./home.html">Home</a></li>
            <li><a href="peroson.html">People</a></li>
            <li><a href="./products.html">Products</a></li>
            <li><a href="./contact.html">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" class="button">
            <button type="submit" class="submit" >search</button>
                
    </div>
</div>
<div class="contact">
    <div class="detail">
    <h1> Contact Us</h1>
    <br>
    <input type="text" placeholder="Your Name"></inupt> 
    <br><br>
    <input type="text" placeholder="Your Email"></inupt>
    <br><br>
    <input type="text" placeholder="Your Message" class="comment"></inupt>
    <br><br>
    <button type="submit" class="submit">Submit</button>

</div>
<div class="info">
    <h1>Contact information</h1>
    <br>
    <span><strong>Address:</strong></span>    Harur , Dharmapuri 635305</p>
    <span><strong>Email:</strong></span>    shaar29@gmail.com</p>
    <span><strong>Phone: </strong></span> 044-4433566</p>

</div>
</div>
<footer>
    <div  class="colored-line">
        <h5>Design and developed by Mr.Sharukesh.R &copy;2023</h5>
    </div>
</footer>
    
  
    
    
    </body>
</html>

.contact{
    display: flex;
    justify-content:center;
    align-items: center;
    height: 80vh;
    gap: 300px;

  }
  span{
    font-weight: 1000px;
  }
  .info{
    background-color:rgb(255, 192, 246);
    padding: 10px;
    border: 3px solid orange;
    border-radius: 30px;
    text-align: center;
    
  }
  .detail{
    background-color: rgb(255, 192, 243);
    padding: 10px;
    border: 3px solid orange;
    border-radius: 30px;
    

  }
  .comment{
    padding:50px; }
  .submit{
    background-color: chocolate;
  }
  body{
    background-color: rgb(0, 179, 255);+

  }
  
*{
    font-size:20px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 10px;
}
li{
    list-style: none;
    font-weight: 100px;
    
}
.nav{
    display: flex;
    justify-content:center;
    gap: 50px;
    margin-top: 25px ;  
}
h1{
    font-size: 1.5rem;
  }
  .colored-line {
    width: 100%; 
    height: 25px; 
    background-color:rgb(11, 120, 32);
    text-align: center;
    margin-top: 35px;
  }

```


## OUTPUT:
![Alt text](121.png)
![Alt text](122.png)
![Alt text](123.png)
![Alt text](124.png)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
