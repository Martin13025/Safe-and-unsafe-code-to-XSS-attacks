# Safe-and-unsafe-code-to-XSS-attacks
Vulnerable and non-vulnerable code to XSS attacks

Vulnerable code: 
  If userData contains a malicious script, it will be executed in the user's browser when the data is inserted into the HTML.
  
Unbreakable code:
  Even if userData contains a competing script, it will not be executed because we are inserting the data as text and not HTML. This is one way to protect against XSS attacks.
  
In addition to converting data into actual text, we can also escape characters in our code. So-called dangerous symbols, thanks to which you can penetrate the structure of a web application and change it from the inside. Escaping characters essentially replaces them with alternative characters, making it impossible to infiltrate the code.
