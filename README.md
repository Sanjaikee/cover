# Ex.06 Book Front Cover Page Design
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    .bookpage{
        width: 400px;
        height: 530px;
        color:rgba(0, 246, 70, 0.986);
        margin-left: auto;
        margin-right: auto;
        padding: 40px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(hg.jpg);
        background-size: cover;
    }
        
    
    .insight{
        color: rgb(225, 69, 82);
    
    }
    
    
    .hrstyle{
        width:220px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: rgb(242, 255, 0);
        top:280px;
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 40px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:290px;
        
    }
    .pub{
        font-size: medium;
        position: relative;
        top:250px;
        left:330px;
    }
    .ed{
        color: rgb(255, 0, 242);
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:200px;
    
    }
    .subtitle{
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:60px;
    }
    .mypic{
        position: relative;
        top: 240px;
        left: 270px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body bgcolor="black">
    <div class="bookpage" style="background-color: whitesmoke;">
        <div class="insight">
            DESIGN IN DREAM
        </div>
        <div class="hrstyle">
            <hr style="color: rgb(246, 255, 0);">
        </div>
        <div class="booktitle">
            <h1>WEB DEVELOPMENT</h1></div>
        <div class="subtitle">DEVELOP YOUR OWN WEB WORLD
             
        </div>
        <div class="mypic">
            <img src="hg.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: rgb(218, 32, 32);">
        </div>
        <div class="author">
           <p><b>Sanjai(212223230186)</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>LEARN WITH</b>
        </div>
    </div>
    </body>


</body>
</html>
```


## OUTPUT:
![WhatsApp Image 2024-04-28 at 22 02 46_b46fcafc](https://github.com/Sanjaikee/cover/assets/150231888/8d55cf33-de95-4b13-ac44-78a595bde780)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
