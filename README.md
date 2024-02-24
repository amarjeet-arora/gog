

function checkValue(){
   const data= document.demoform.uname.value
   if(data=="")
   document.getElementById('show').innerHTML='Name cant be blank...!'
   console.log("data must be thr");
   
}






<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="demo.js"></script>
    <style>
        div {
            color: red;
        }
    </style>
</head>
<body>
    <form name='demoform'>
        <div id='show'>
            <p>This is Form</p>
        </div>
        <input type='text'  name='uname' id='un'/>
        
        <button type="button" onclick="checkValue()">Check</button>

    </form>
  
</body>
</html>
