<!DOCTYPE html>
<hmtl>
    <head>
        <meta charset="utf-8">
        <title>SHOAIB's Porfolio</title>
        <link rel="stylesheet" type="text/css" href="style.css">
        <link href="https://fonts.googleapis.com/css?family=Fira+Sans" rel="stylesheet">
    </head>
    <body>
        <header>
            <div class="Soon">
            <p>Building Awesome Website</p>
            <h1>COMING SOON</h1>
            <hr>
            <p id="launch"></p>
            </div>
        </header>
    </body>
    
    
    
 <script>
 var countDownDate = new Date ("July 20, 2023 00:00:00").getTime();

 var x = setInterval(function() {

 var now = new Date ().getTime();

 var distance = countDownDate - now;

 var days = Math.floor (distance /(1000*60*60*24));
         var hours = Math.floor ((distance % (1000*60*60*24)) / (1000*60*60));
          var minutes = Math.floor ((distance % (1000*60*60)) / (1000*60));
           var seconds = Math.floor ((distance % (1000*60)) / 1000);

document.getElementById("launch").innerHTML=days + "d " + hours + "h " + minutes + "m " + seconds + "s";
    
if (distance < 0) {
    clearInterval(x);
    document.getElementById('launch').innerHTML=" ";
    }
            
}, 1000);
    
</script>
</hmtl>
