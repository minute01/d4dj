<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
    <script type="text/javascript">
            //난수를 발생 시켜서
            var imgArray = new Array();
 
            imgArray[0]="img/3.jpg";
            imgArray[1]="img/해병.jpg";
            imgArray[2]="img/해병대 증명.png";
            imgArray[3]="img/images.jpg";
 
            function showImage(){
                    var imgNum =Math.round(Math.random()*3);
                    var objImg = document.getElementById("introImg");
                    objImg.src =imgArray[imgNum];
            }
            setInterval(showImage,80);//자동으로 바낌
 
 
    </script>
  </head>
  <body onload="showImage()">
 
      <img id="introImg" border="0">
  </body>
</html>
