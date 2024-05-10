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
DEVELOPED BY: SHRIKRISHNA V
REG. NO.: 212223040198


<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style type="text/css">
      .bookcover {
        width: 400px;
        height: 640px;
        color: rgb(240, 239, 220);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family:Georgia, Times, 'Times New Roman', serif;
        background-image: url(image.png);
        background-size: cover;
      }
      .insight {
        color: white;
      }
      .hr {
        width: 100px;
      }
      .h1 {
        font-size: medium;
        font-family: Georgia, Times, 'Times New Roman', serif;
        color: rgb(0, 0, 0);
        text-align: center;
        position: relative;
        top: 30px;
      }
      .h3 {
        font-size: larger;
        font-family: Georgia, Times, 'Times New Roman', serif;
        color: rgb(0, 0, 0);
        text-align: center;
        position: relative;
        top: 10px;
      }
      .p {
        font-size: medium;
        font-family: Georgia, Times, 'Times New Roman', serif;
        position: relative;
        top: 60px;
      }
      .edition {
        font-size: large;
        font-family: Georgia, Times, 'Times New Roman', serif;
        color: rgb(0, 0, 0);
        top: 60px;
        position: relative;
      }
      .photo {
        position: relative;
        top: 100px;
        left: 270px;
        width: 100px;
        height: 70px;
        background-size: cover;
      }
      .hrstyle {
        position: relative;
        width: 400px;
        top: 170px;
      }
      .author {
        font-size: medium;
        font-family: Georgia, Times, 'Times New Roman', serif;
        display: inline;
        position: relative;
        color: whitesmoke;
        top: 165px;
      }
      .publisher {
        font-size: large;
        position: relative;
        top: 135px;
        left: 330px;
      }
    </style>
    <title>Book Front Cover Page</title>
  </head>
  <body>
    <div class="bookcover">
      <div class="insight">SEC INSIGHT</div>
      <div class="hr">
        <hr />
      </div>
      <div class="h1">
        <h1>DNA DATA STORAGE</h1>
        <br>
        <h3>"Unlocking the Code: Where Data Meets DNA"</h3>
      </div>
      <div class="p">
        <p>
            DNA data storage involves encoding digital information into the four nucleotide bases of DNA, offering an incredibly dense and durable medium for long-term data storage, potentially revolutionizing information archiving and retrieval.
    
        </p>
      </div>
      <div class="photo">
        <img src="mypic.jpeg" width="120" height="150" alt="" />
      </div>
      <div class="hrstyle">
        <hr />
      </div>
      <div class="author">
        <p><b> SHRIKRISHNA V </b></p>
      </div>
      <div class="publisher">
        <b> SEC </b>
      </div>
      <div class="edition">
        <b>EXTENDED EDITION</b>
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:
![image](https://github.com/Wkrish28/cover/assets/144295230/70ebf9f5-575f-432a-aaf2-0c6a6fb05de9)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
