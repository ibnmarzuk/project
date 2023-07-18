# project
30 days html
# Header H1
Header H1 is used to display the Project heading. 

## Sub Topic Headings H2
Sub Topic Headings H2 is used for sub sections like Configurations, Authors etc.

````
pip install boto
````

The above formatting is used to create a box which can display code or command in a well formatted manner.


## Usage

Below is another example of displaying
````python
import csv

with open("sample.csv","r") as csvinput: # read input csv file
    reader = csv.reader(csvinput) # create a reader
    for row in reader:
        print(row[0])
````

 
OUTPUT README :

The output of sample README.md after committing the file in git looks like below.


Markdown Syntax
As git README.md file is created using markdown language, learning some basic markdown syntax can be very useful to style your README.md file.

Learn syntax for the following most commonly used elements in the git README.md

Text formatting
List creation
Code block creation
Table creation
Text Formatting:
Bold: To create text as bold enclose it in double stars or double underscore.

Italic :  To create text as bold enclose it in single star or single underscore.

Syntax:

**bold** OR __bold__

*Italic* OR _Italic_

Output:

bold OR bold
Italic OR Italic

Lists:
Ordered lists: Markdown syntax for creating numbered list is just by putting numbers in front of each row.

Syntax:

1. One
2. Two
3. Three
Output:

One
Two
Three
Unordered lists: Bulleted lists can be created using star or dashes.

Syntax 1:

* Star is used to create a bullet list item
* Item 2
Output:

Star is used to create a bullet list item
Item 2
Syntax 2:

- You can also use Dashes instead of stars
- Parent Item
 - Item 1
 - Item 2
Output:

You can also use Dashes instead of stars
Parent Item
Item 1
Item 2
Code Blocks:
Backticks are used to create code blocks .For inline code wrap it in single backticks.

Syntax:

`variable a = 20`

Output:

variable a = 20
For multiline code block : Use spaces for indentation & use 4 backticks for code blocks without indentation:

Syntax:

if(IndentationRequired)
print(“use 4 spaces”)
Output:

    if(IndentationRequired) 
        print(“use 4 spaces”)
Syntax:

````
if(IndentationNotRequired)
print(“use 4 spaces”)
````
Output:

if(IndentationNotRequired) 
print(“use 4 spaces”)
Create Tables:
Tables are created using dashes and pipes. Dashes are used to underline the headers and pipes are used to separate the columns.Check the example below.

Syntax:

Column 1|Column 2
--------------|--------------
Row element| Row element
Output:

Column 1	Column 2
Row element	Row element
Summary
In this article, we learnt what is readme and we also learnt how to create a readme file for your project.
I hope you liked it !

