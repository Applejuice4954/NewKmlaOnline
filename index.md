<html>
	<head>
		<title> 유세진의 코딩 도전기</title>
		
		<script> 
         		//function that display value 
         		function dis(val) 
         		{ 
             		document.getElementById("result").value+=val 
         		} 
           
         		//function that evaluates the digit and return result 
         		function solve() 
         		{ 
             		let x = document.getElementById("result").value 
             		let y = eval(x) 
             		document.getElementById("result").value = y 
         		} 
           
         		//function that clear the display 
         		function clr() 
         		{ 
             		document.getElementById("result").value = "" 
         		} 
      		</script> 
      		<!-- for styling -->
      		<style> 
         		title{ 
         		margin-bottom: 10px; 
         		text-align:center; 
         		width: 105px; 
         		color: black; 
         		border: solid black 2px; 
         		} 
  
         		input[type="button"] 
         		{ 
        		background-color:ghostwhite; 
         		color: black; 
         		border: solid black 2px; 
         		width: 100%
         		} 
  
         		input[type="text"] 
         		{ 
         		background-color:white; 
         		border: solid black 2px; 
         		width: 100%
         		} 
			
			footer {
 			text-align: center;
 			padding: 3px;
			color: #808080;
			}
      		</style> 
		
	</head>
	
	<body>
	
		<div>
			<h2 style="text-align: center;"><span style="color: #00ffff;"><strong><a href="https://www.geeksforgeeks.org/html-calculator/" target="_blank">어디선가</a> 퍼온 계산기<br></strong></span></h2>
		</div>
	
      			<table border="1"> 
		 	<tr> 
          		<td colspan="3"><input type="text" id="result"/></td> 
            		<!-- clr() function will call clr to clear all value -->
            		<td><input type="button" value="c" onclick="clr()"/> </td> 
         		</tr> 
         		<tr> 
            		<!-- create button and assign value to each button -->
            		<!-- dis("1") will call function dis to display value -->
            		<td><input type="button" value="7" onclick="dis('7')"/> </td> 
            		<td><input type="button" value="8" onclick="dis('8')"/> </td> 
            		<td><input type="button" value="9" onclick="dis('9')"/> </td> 
            		<td><input type="button" value="/" onclick="dis('/')"/> </td> 
         		</tr> 
         		<tr> 
            		<td><input type="button" value="4" onclick="dis('4')"/> </td> 
            		<td><input type="button" value="5" onclick="dis('5')"/> </td> 
            		<td><input type="button" value="6" onclick="dis('6')"/> </td> 
            		<td><input type="button" value="-" onclick="dis('-')"/> </td> 
         		</tr> 
         		<tr> 
            		<td><input type="button" value="1" onclick="dis('1')"/> </td> 
            		<td><input type="button" value="2" onclick="dis('2')"/> </td> 
            		<td><input type="button" value="3" onclick="dis('3')"/> </td> 
            		<td><input type="button" value="+" onclick="dis('+')"/> </td> 
         		</tr> 
			 <tr> 
            		<td><input type="button" value="0" onclick="dis('0')"/> </td> 
            		<td><input type="button" value="." onclick="dis('.')"/> </td> 
            		<!-- solve function call function solve to evaluate value -->
            		<td><input type="button" value="=" onclick="solve()"/> </td> 
            		<td><input type="button" value="*" onclick="dis('*')"/> </td> 
         		</tr> 
      		</table> 
	
		<footer>
		
			<p>유세진 짱짱맨<br><br>
			계산기 코드 출처: https://www.geeksforgeeks.org/html-calculator
			<a href="https://www.geeksforgeeks.org/html-calculator/" target="_blank"> [클릭하여 바로가기]</a><br><br>
			<a href="http://main.minsacraft.kro.kr/" target="_blank"> [눌러봐ㅎㅎ] </a>
			</p>
		
		</footer>
	</body>
	
</html>
