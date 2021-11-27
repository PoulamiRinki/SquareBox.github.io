<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8"> 
     <meta http-equiv="X-UA-Compatable" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
      <title> SquareBox</title> 
      <link rel="stylesheet" href="index.css">
      </head>
      <body>
      <div class="parent_div"> 
          <div class="child_div"> 
               </div> 
        </div>
      
    </body>
    </html>
    *{ 
    margin: 0; 
    padding: 0;
}
.parent_div{
     width: 100vw;
      height: 100vh; 
      background-color: aqua; 
      display: flex;
       justify-content: center; 
       align-items: center;
    }
.child_div{
     width: 40vw;
      height: 30vh;
       background-color: blueviolet; 
       display: flex; 
       align-items: center; 
       color: white; 
       padding: 10px; 
       text-align: center; 
    }
