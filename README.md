# AXE
The compiler of the AXE - programing language 
First of all I have to make it clear that this is only a hobbi project and I'am a beginner at creating programin languages.
This is the first version, it's able to handle loops, conditions, the four basic math operation (only one in a line) and can read from the console and can write on it.

HOW TO USE IT
When you run the compiler it will ask you for a filepath. This file can be a .txt and this is where you should write your axe code.

Important: you always need a main function.
Examples:
Declare a variable: 
let x = 20

Write on console
write ("x" + x + "x")

Read from console
let input = ""
read (input)

Conditions
if (21 <= x)
{
	write ("True")
}	
else
{
	write ("False")
}

Loop
for (let x = 10 => 5, 2)
{
	write ("x" + x + "/")
}

Complete example
function void main ()
{
	let x = 20

	write ("x" + x + "x")
	for (let x = 10 => 5, 2)
	{
		write ("x" + x + "/")
	}
	if (21 <= x)
	{
		write ("True")
	}	
	else
	{
	write ("False")
	}
	let input = ""
	read (input)
	write ("Hello " + input + ", do you like this programing language?") 
}
