Q1: Is the keyword "fixes" the only way to auto-close an issue from a PR 
(pull request). Is there other keywords that can accomplish the same thing?
No, there are multiple keywords that you can use such as close, closes, fix, resolved etc.

Q2: Do you have to create a new PR EVERYTIME you want to close an issue,
or is it possible to close multiple issues within a single PR? If so, 
how?
You can write fixes #x on multiple lines with different values for x.  That fixes more than one in a single PR.

Q3: Provide an example of using map that is different from the one I have done.
Your example must use map both as a named function declaration and with an
anonymous function. 

import math
function myFunction() {
	var numbers = [4, 9, 16, 25]
	numbers.map(math.sqrt);
}

numbers.map(num => {
	num = num ** 0.5
}

Within comments, explain exactly what map is doing. Finally, why is the
"transformation function" we discussed in class sometimes referred to 
as a callback function. 

Map does calculations on every element of an array based on the function.
It is called a callback function because the code after it will no longer be used so there is no need to go through it.  so it "calls back" to the rest of the needed function.