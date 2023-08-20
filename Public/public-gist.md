# Regex - Matching Email

During this gist tutorial how to match an e-mail using `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` expressions will be completed once the reader has finished the overview and read through the table of contents for the understanding of creating this functionality.
Happy Reading! 📖

## Summary

Using this informative RegEx gist the reader will then have an understanding of how to start/complete the use and sequence of making the expression for matching e-mails in their code.

## Table of Contents

- [Anchors](#anchors-⚓)
- [Quantifiers](#quantifiers-☝️)
- [Grouping Constructs](#grouping-constructs-👨‍👩‍👦‍👦)
- [Bracket Expressions](#bracket-expressions-😬)
- [Character Classes](#character-classes-👨‍🏫)
- [The OR Operator](#the-or-operator-🔧)
- [Flags](#flags-🏳️)
- [Character Escapes](#character-escapes-🏃🏻‍♀️)

## Regex Components ⚙️ :

### Anchors ⚓
Ancor links are simply links in the e-mail that once clicked it accesses the opening of a seprate tab/window for the link to be populated cleanly. Ancors can be added to newsletters, headers, and so on. Ancors a great way to simplify and expand the user experience.
A simple way to add an anchor would be in the HTML is adding an ``id='anchor'`` in a ``<p></p>`` or a ``<h1></h1>``
### Quantifiers ☝️
Quantifiers to specify the amount of times an element is matched throughout the code. 
A few ways to incorporate quantifiers is ``+`` for the connection of two or more pieces of code 
Example: `` firstName + lastName + .com ``
### Grouping Constructs 👨‍👩‍👦‍👦
Grouping constructs `` () `` controls the evaluation of the contained expressions used in the code lines. 
Example: `` ([a-zA-Z0-9\._]+)@([a-zA-Z0-9])+. ([a-z]+)(. [a-z]+) ``
### Bracket Expressions 😬
Bracket expressions these indicate a specific set of listed characters to be matched `` [abc] `` ``[ABC] ``
The `` ^ `` can be used to negate the code listed in the brackets.
### Character Classes 👨‍🏫
Character classes or character set is used for matching one out of serveral characters. Using the bracket expression to list the characters specifically to be searched.
These are very commonly used.
Example: This code snippet would match any letter or integer
`` /[a-zA-Z0-9]/ ``
### The OR Operator 🔧
OR operator is quite simply an "or" expression, expressed by a `` | `` in code lines. 
Example: `` const pets = /cat|dog/ ``
### Flags 🏳️
Flags are a regexpression which consists of the parameters `` ('pattern', 'flags' ); `` 
This can also be coded out with `` / ``, the difference in the syntax being that  `` / `` does not allow for expressions to be used in string literals `` ${...} `` 
### Character Escapes 🏃🏻‍♀️
Character excapes simply being the use of a  `` \ `` for use of excaping a coding sequence or specific character/special character.
Example:  `` \a `` , ``\.``
## Author ✍🏼

Starting out as an entry-level coder and aspiring developer; I have started work through: HTML, CSS, JavaScript, and more through the BootCamp at UNC-Charlotte. I am progressing my working knowledge of multiple languages past the directive of the BootCamp, also by continuing to strengthen my abilities.

[GitHub](#https://github.com/KEINance)

[Repo Link](#https://github.com/KEINance/regex)

[Deployed Link](#https://keinance.github.io/regex/)

## Mentions
[Emoji Icons](#https://emojidb.org/components-emojis?user_typed_query=1&utm_source=user_search)