<html> 
<head> 
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Technex Hackaton 2020</title> 
	<style> 
                 *{
                    box-sizing:border-box;
                  }

                .menu{
                       float: left;
                       width:20%;
                     }
                .right{
                        background-color:lightblue;
                        float:left;
                        width:20%;
                        padding:10px 15px;
                        margin-top:7px;
                     }
                .main{
                       float:left;
                       width:60%;
                       padding: 0 20px;
                       overflow:hidden;
                     }
                @media (min-width:481px) and (max-width:767px) /*for tablets*/
                 {
                   .main{
                          width:80%;
                          padding:0;
                        }
                   .right{
                         width:100%;
                         }
                 }
  
               @media only screen and (max-width:480px) /*mobile phones*/
                 {
                   .menu, .main, .right{
                          width:100%; 
                        }
                 }
             @media (min-width:1025px) and (max-width:1280px) /*for desktop*/
                 {
                   .main{
                          width:80%;
                          padding:0;
                        }
                   .right{
                         width:100%;
                         }
                 
                 }
              
            

		.head1 { 
			font-size:40px; 
			color:#FFFFFF; 
			font-weight:monaco; 
		} 
		.head2 { 
			font-size:15px; 
			margin-left:10px; 
			margin-bottom:15px; 
		} 
		body { 
			margin: 0 auto; 
			background-position:center; 
			background-size: contain; 
		} 
              .button {
                       right: auto; 
		       float: right;
                       background-color: #4CAF50;
                       border: none;
                       color: white;
                       padding: 15px 32px;
                       text-align: center;
                       text-decoration: none;
                       font-size: 16px;
                       margin: 4px 2px;
                       cursor: pointer;
                       }
                       .note
                       {
                        font-size: 30px;
                        cursor:text;
                       }
              .menu-log {  
			float: right;
                        background-color: #4CAF50; 
		        cursor:pointer;
                        font-size: 16px;
                        
                  }
		footer { 
			width: 100%; 
			bottom: 0px; 
			background-color: #000; 
			color: #fff; 
			position: absolute; 
			padding-top:20px; 
			padding-bottom:50px; 
			text-align:center; 
			font-size:30px; 
			font-weight:bold; 
		} 
		.body_sec { 
			margin-left:20px; 
		}
               header
               {
                background-color:#ECF3F3;
               } 
	</style> 
</head> 

<body style="background-color:#FFFFFF;">
   <div style="background-color:#243B55;padding:5px">
      <h1><font color="white"><center>Duoly Done Authorization System(DDAS)</center></font></h1>
   </div>
    

    <!--Objective-->
    <br><br><br>
    <div class="titles"><h2 onclick="objectivej();"><center>The problems it solved</center></h2></div>
	<div style="display: none" id="objective" class="note"><center> <p>Our project focus on the Double Authentication of transactions made in co-operate firms for the transactions which are really huge for the firm or above clearence level of the employee handling that transactions. As well as, For small transactions,transaction will be hassle free even for lower level employees. Limit can be decided and will be seted and changed by admins any time. </p> </center></div>
  

<!--Technology used-->
  <div class="titles"><h2 onclick="tuj();"><center>Technology Used</center></h2></div>
  <div style="display: none" id="tu" class="note"> <ul type=""><center><li>Flutter</li><li>Firebase</li><li>Node.js</li></center></ul> </div>

<div ><center><a href="https://www.dropbox.com/s/b04sg1cj0ysp0su/Get%20Started%20with%20Dropbox.pdf?dl=1" download="Hii.pdf"><button >Click Here to Download</button></center></div>
<script >
function removeAll()
{
  var x=document.getElementsByClassName("note");
  var i;
  for (i = 0; i < x.length ; i++) {
    x[i].style.display="none";
  }
}
function objectivej()
{
  if (document.getElementById("objective").style.display=="block") 
  {
    removeAll();

  }
  else
  {
    removeAll();
    document.getElementById("objective").style.display="block";
  }

}
function tuj()
{
  if (document.getElementById("tu").style.display=="block") 
  {
   removeAll();

  }
  else
  {
    removeAll();
    document.getElementById("tu").style.display="block";
  }
  
}
</script>
	</body> 
</html>			 
