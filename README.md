# JavaServerPages (Information Technology)

## Practicals

1.	Display the pattern: \
        1 \
	1 	2 \
	1 	2 	3 \
Take ‘n’ in a textbox from user. Display this pattern using  
*	Scriptlets 
*	<c:forEach> loop 
2.	Make two files as follows: 
                  1.	main.html: shows 2 text boxes and 3 radio buttons with values "addition",  "subtraction" and "multiplication"  
                  2.	operate.jsp: depending on what the user selects perform the corresponding function (Give two implementations: using request.getParameter() and using expression language) 
3.	Validate User input entered in a form. The input must include Name, DOB, Email ID, Lucky Number, Favorite food etc. (Refer Chapter 8) 
4.	Display Good Morning <uname>, Good Afternoon <uname> or Good Evening <uname> based on the current time of the day. 
5.	Let the user enter a word a in a textbox and let her/him select one of even or odd radio buttons. If she/he selects odd, check the odd positions in the word entered, if they all contain vowels, then display the message ‘You win’, else display ‘You lose’. Similarly, if the user selects even, check for vowels in all even positions in the word entered. Use jstl’s ‘fn’ library. 
6.	Create your custom library which contains two tags: <hello>, <choco>. Usage of the tags: 
•	<hello name=”Ajay”>: Output should be Hello  Ajay. It contains a mandatory attribute ‘name’ which can accept Dynamic value. 
•	<choco texture=”Chewy”>: Output should be FiveStar, BarOne.  
<choco texture=”Crunchy”>: Output should be Munch. KitKat. 
That means the mandatory attribute must accept a value, and based on the attributes value, it should give output. You must use a bean ChocoBean for this purpose. 
7.	Create a custom tag “substring” with 3 mandatory attributes “input”, “start”, “end” which will do substring operation on given input 
8.	Create a custom tag “reverse” with a mandatory attribute “input” to reverse a string. 
9.	Create a custom tag "today" that displays today's date and time 
10.	Ask a user's name and age on a HTML form. Then display Hello <uname> on a JSP. On the same page ask the product the user would like to buy. Then redirect to another 
JSP which would display: Hello <uname>, You have ordered <product>. (Use Session Scope Variable using setTag) 
 

