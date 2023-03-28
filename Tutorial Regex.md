17 Computer Science for JavaScript: Regex Tutorial
Contents

User Story 1
What Is a Regex? 2
Example 3
Author 3

User Story
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines
GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile

What Is a Regex?

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.
These expressions are best in cases where you search and replace functions or actions.
For example, the following regular expression can be used to verify that user input is a valid email address:
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the @ symbol, followed by a domain.
Before you get started, watch this introduction to regular expressions video and read Regex Tutorial: Matching a Username to learn how to identify the different components that make up a regex. If you need any additional help, there are many resources on the web. Feel free to do your own research to find one that can help you complete this assignment.

Once you have a better understanding of what these different parts of a regular expression do, you’ll need to explain what they do for a specific regex.

You can choose one of the following regular expressions or you can choose one that you found on your own (with the exception of the one that is covered in the Regex Tutorial: Matching a Username:

Matching a Hex Value: /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

Matching an Email: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Matching a URL: /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

Matching an HTML Tag: /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/
Though regex might look like craziness it is a strategic and written to catch all of its requirements. For example a piece that looks for a password or user name is going to look for any numbers, any symbols, lengths of characters, as well as lower case or capital. If it matches that pattern it finds it!
Example
With Regex there are a lot of patterns and things you can do. For example it can help with email searches,

contain any space or special characters(excep @ and .)
should not start with dot(.) or should not end with .(before @ symbot)
two dots should not come near.
the @ symbol should not repeat.
Allowing you to find the pattern, as you search through email. “^[a-zA-Z0-9]+(?:.[a-zA-Z0-9]+)@[a-zA-Z0-9]+(?:.[a-zA-Z0-9]+)$“

There is also a email validation which looks even stranger “/^(([^<>()[][\.,;:\s@"]+(.^<>()[]\.,;:\s@"]+)*)|(".+"))@(([[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}])|(([a-zA-Z-0-9]+.)+[a-zA-Z]{2,}))$/%7C(%22.+%22))@((/%5b%5b0-9%5d%7b1,3%7d/.%5b0-9%5d%7b1,3%7d/.%5b0-9%5d%7b1,3%7d/.%5b0-9%5d%7b1,3%7d/%5d)%7C((%5ba-zA-Z/-0-9%5d+/.)+%5ba-zA-Z%5d%7b2,%7d))$/)”

Author
Julia Devine / jujubea22 (github.com)
