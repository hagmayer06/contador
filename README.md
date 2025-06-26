<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contador</title>
    <style>
     * {margin:0; box-sizing: border-box;}
     body {
        min-height:100vh; 
           background-color: black;
           display: grid;
           place-items: center;}
     
     p      {font-size: 60px;
    
    }
     section{
       background-color: #880808; 
       text-align: center;
       color:white;
       padding: 20px; 
       border-radius: 15px;

     }
     
    </style>
</head>
<body>
   <section>
       <h1>Contador</h1>
       <p>0</p>
       <button onclick="aumentar()">mais</button>
       <button onclick="diminuir ()">menos</button>
   </section>
   <script>
    function aumentar() {
      console.log("aumentar...")
    }
    function diminuir() {
      console.log("diminuir...")
    }
   </script>
    
</body>
</html>
