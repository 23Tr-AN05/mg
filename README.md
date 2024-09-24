<meta chartes="utf-8" />
<html>
 <head>
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <style>
 .collapsible {
  background-color: #A1FCDC;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
 }
 .active, .collapsible:hover {
    background-color: #FFFF5B;
 }
 .content {
    padding: 0 18px;
    display: none;
    overflow: hidden;
    background-color:#E1E5FF;
 }
 </style>
</style>
 <style>
    #para1{
        font-size:50px;
        text-align:center;
        color:red;
    }
    #para2{
        font-size:30px;
        text-align:center;
        color:red;
    }
    #para3{
        font-size:20px;
        text-align:left;
        color:#000000;
    }
    #para4{
        font-size:20px;
        text-align:left;
        color:#00FF00;
    }
    #para5{
        font-size:40px;
        text-align:center;
        color:#FF1000;
    }
    #para6{
        font-size:20px;
        text-align:left;
        color:#13A640;
    }
     #para7{
        font-size:30px;
        text-align:center;
        color:red;
    }
    #para8{
        font-size:30px;
        text-align:left;
        color:#00FF00;
    }
    #para9{
        font-size:20px;
        text-align:right;
        color:#000000;
    }
     #para10{
        font-size:20px;
        text-align:right;
        color:#FF0000;
        background-color:yellow;
    }
    mark{
        background-color:yellow;
        color:black;
    }
    #m1{
        background-color:#FFDCDA;
        color: black;
    }
    #m2{
         background-color:#8FFF6D;
        color: black;
    }
    #m3{
         background-color:#C1FFFC;
        color: black;
    }
    #p1{
        text-align:center;
    }
    #p2{
        font-size:20px;
        text-align:center;
    }
   
 </style></head>

 <body>
 <h1 id="para1">COMMENT PEUT-ON DEFINIR LA LIBERTE?</h1>
 <h2 id="para2">Comment peut-elle s'exprimer?</h2>
 <br>  
 <br>



 



 <body>

 <script>
 var coll = document.getElementsByClassName("collapsible");
 var i;

 for (i  = 0; i < coll.length; i++) {
     coll[i].addEventListener("click", function() {
         this.classList.toggle("active");
         var content = this.nextElementSibling;
         if (content.style.display === "block") {
             content.style.display = "none";
         } else {
             content.style.display = "block";
         }
     });
 }
 </script>




 </body>
