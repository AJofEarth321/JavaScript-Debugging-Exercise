JS Debugging Exercise
An elementary school hired you to build a word search generator for them. You built one that met the following requirements:

User can specify the width and height of the grid
User can add words to a word bank if they meet the following conditions:

Word is at least 3 characters long
Word includes only English letters
Word is unique


User can remove individual words from the word bank by clicking the trash can icon for that word
When user clicks "Create", a grid is generated

Grid has random letters
Grid has the width and height that were specified
Grid places all words from word bank or informs user that it couldn't



Unfortunately, someone edited the code and broke the generator. The school has asked us to give them a working copy again, but we already deleted the original. The school gave us the currently broken code. It's your job to find and correct the errors. The school would also like a record of all the changes that were made. You can put this into a changelog section in this README. They want to know the line of code that was changed, as well as a brief description of what was changed. For example:


Line 10: change with to width


Line 2: change too to to


Take a look at the following resources for how to create a changelog using proper Markdown Syntax.

What is a README
A README is a document designed to inform someone about your program. This can include installation, documentation, the most recent changes, etc. Modern READMEs are written in Markdown, which allows them to be formatted using simple syntax.

Why Create a README
READMEs have become the standardized way of providing critical information about software to users. They allow you to document your work, give instructions and references, encourage interest, and facilitate understanding of your program.

The Basic Structure of a README
The following is an example README structure:



Title



Description



Installation Instructions



Usage Instructions



Credits



License


However, it is important to keep in mind that every element in your README should provide pertinent and useful information. Some sections may not be relevant, so be sure to tailor your README to best serve the user. Your README should almost always include a title, a description, setup instructions, and contact information for issues.

Moving Forward
Get into the habit of writing a README for every program you write. The more practice and feedback you get now the less of a headache writing READMEs will be in the future.

Additional Resources
How to Write a Good README - overview of what and why for a README
makeareadme.com - information and resources on READMEs
dillinger.io - preview your README in browser
Purdue OWL - tips and tricks for keeping your writing concise and impactful

Changelog


Line 8: changed "getElementsByClassName" to "getElementbyId"

Line 19: changed ".innerText" to ".value"

Line 21: removed "!" from isValidWord function

Line 27: added missing curly bracket to close If Statement

Line 40: changed "word" to "words"

Line 46: corrected the order of 'words', 'width', and 'height'

Line 66: added missing single quote to ('add-ward')

Line 81: changed '<' to '>='

Line 90: changed "writeWrodToList" to "writeWordToList"

Line 94: changed '.class' to '.classlist'

Line 94: added semicolon after parenthesis

Line 115: changed "li.parentNode.remove(li)" to "li.remove()"

Line 124: changed ".child" to ".children"

Line 129: changed "return liElements" to "return words"