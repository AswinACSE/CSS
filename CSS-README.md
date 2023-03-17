CSS styling:
=>To make background-color

body{
    background-color: antiquewhite;
}
-----------
=>To make multi background color

body{
    background: linear-gradient(red ,green);
    background-repeat: no-repeat//to blank next of no content
    background-attachment: fixed//to set whole page with same color
}
-----------
=>To set background image

body{
    background-image: url(background.jpg);//image file name
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: center;//to set the image center
    background-size: cover;//to fix the image in website
}
-----------
=>To create box and align some position
 .box{
    text-align: center;//text in center
    border: solid;
    width: 80px;
    height: 50px;
    background-color: white;
    float:left;// set the box at left corner of page
}
-----------
=>To link a website and color change when we place the cursor
a:link{
    color: green;//link color
}
a:hover{
    color: yellow;//when place the cursor on link color change
}
-----------
=>Create a button and color change
button{
    background-color: blue;//background color of the button
}
button:hover{
    color: red;//to change color when place the cursor on link
}
-----------
=>To set shadow of a text
h1{
    text-shadow: 0px 0px 5px color,0px 0px etc...
}
h1{
    box-shadow: 5px 5px 5px color;//to make a box of text
}
-----------
=>To set icons logo like google or youtube
.icon{
    height: 100px;
    width: 100px;
    position:absolute;
    
    transform: translate(500px,10px);
    top: 10px;
} // for above code we have to link logo we have to create a class and give some address E.g: class="fa-brands fa-youtube" -->youtube logo.
-----------
