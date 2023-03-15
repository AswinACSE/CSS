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
