# Regular Expression / Catregex

A Walkthrough room to teach you the basics of bash scripting

Nov 25, 2021

#### Task 1: Introduction
- Are you ready to go!
	- `no answer needed`

#### Task 2: Our first simple bash scripts
- What piece of code can we insert at the start of a line to comment out our code?
	- `#`
- What will the following script output to the screen, echo “BishBashBosh”
	- `BishBashBosh`

#### Task 3: Variables
- What would this code return?
	- `Jammy is 21 years old`
- How would you print out the city to the screen?
	- `echo $city`
- How would you print out the country to the screen?
	- `echo $country`

#### Task 4: Parameters
- How can we get the number of arguments supplied to a script?
	- `$#`
- How can we get the filename of our current script(aka our first argument)?
	- `$0`
- How can we get the 4th argument supplied to the script?
	- `$4`
- If a script asks us for input how can we direct our input into a variable called ‘test’ using “read”
	- `read test`
- What will the output of “echo $1 $3” if the script was ran with “./script.sh hello hola aloha”
	- `hello aloha`

#### Task 5: Arrays
- What would be the command to print audi to the screen using indexing.
	- `echo "${cars[1]}"`
- If we wanted to remove tesla from the array how would we do so?
	- `unset cars[3]`
- How could we insert a new value called toyota to replace tesla?
	- `cars[3]='toyota'`

#### Task 6: Conditionals
- What is the flag to check if we have read access to a file?
	- `-r`
- What is the flag to check to see if it's a directory?
	- `-d`

#### Task 7: Further reading
- Well done!
	- `no answer needed`
