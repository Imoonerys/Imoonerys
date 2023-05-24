<!DOCTYPE html>
<html>
    <head>
        <title>CETREKAN LAMPU</title>
    </head>
    <body>
        <img src="assets/images/off.gif"alt="" id="lampu1"/>
        <h1>CETREKAN LAMPU ON OF BRO</h1>
        <button onclick="saklar(`on`)">NYALAKAN LAMPU</button>
        <button onclick="saklar(`oFF`)">MATIKAN LAMPU</button>
   
        <!-- INI SCRIPT-->
        <script>
         function saklar(params) {
            
            let lampu1 = document.getElementById("lampu1");
           
            if (params == "on") {
             lampu1.src= "assets/images/on.gif";   
            }
            if (params == "off") {
             lampu1.src= "assets/images/off.gif";
            }
            
             return lampu;
         }


        </script>
    </body>
</html>
