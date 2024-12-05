# Ex.06 Book Front Cover Page Design
## Date:29/11/2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html

<html>
    <head>
<style>
    .bookpage{
        width: 400px;
        height: 600px;
        color:rgb(255, 30, 0);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(back1.jpg);
        background-size: cover;
    }
        
    
    .insight{
        color: rgb(229, 255, 0);
    
    }
    
    
    .hrstyle{
        width:170px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: cyan;
        top:270px;
        
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        font-style: italic;
        top: 30px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:280px;
        
    }
    .pub{
        color: greenyellow;
        font-size: medium;
        position: relative;
        top:235px;
        left:350px;
    }
    .ed{
        color: rgb(225, 17, 211);
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:185px;
    
    }
    .subtitle{
        color:bisque;
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:40px;
        font-style: oblique;
    }
    .mypic{
        position: relative;
        top: 230px;
        left: 260px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body>
    <div class="bookpage">
        <div class="insight">
            SEC WORK
        </div>
        <div class="hrstyle">
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1>ETHICAL HACKING COURSE</h1></div>
        <div class="subtitle">
            Learn the Ethical Way of HACKING!!!
        </div>
        <div class="mypic">
            <img src="my pic.jpeg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: goldenrod;">
        </div>
        <div class="author">
           <p><b>K Barathraj(24001402)</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>III Edition</b>
        </div>
    </div>
    </body>
</html>
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/43c2377f-4853-485c-987c-05f26d273b1e)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
