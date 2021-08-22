# webtools-test-README

<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Italics -->
ITALICS
Use single asterisks   *to italicize text*
Or use single underscores _to italicize text_

<!-- Make your text strong -->
STRONG TEXT
You can use double asterisks **to make text strong**
Or use double underscores __to make text strong__

STRONG AND ITALIC
Use three asterisks or three understores
to make it ***strong and italic***
to make it ___strong and italic___

<!-- Strikethrough Some Text -->
STRIKETHROUGH
Use the double tildes   ~~to STRIKETHROUGH text~~ 

<!-- Horizontal Rule -->
HORIZONTAL RULE
Use triple underscores for Horizontal Rule
___

Also use triple hyphens for Horizontal Rule

---

<!-- ESC Characters to Display -->
DISPLAY MARKDOWN CHARACTERS
To show some of the characters, you can ESC them so they don't use Markdown.
\*Italics\*  shows you the asterisk w/o formatting
\#Heading\#  shows you the hashtag w/o formatting

<!-- Blockquotes -->
BLOCKQUOTES
> A horse is a horse is a horse of course.
> Noone can talk to a horse of course.

<!-- Links -->
BROWSER LINKS
***Name*** in brackets
***URL*** in parens
***Hover Over Text*** in quotes inside the parens
[Dunwoody Website](https://dunwoody.edu "Hover over link to see this title")

<!-- Unordered Lists  -->
UNORDERED LISTS
* One asterisk and space per item
* Item 2
* Item 3
    * Nest items with TAB asterisk space

<!-- Ordered Lists -->
ORDERED LISTS
1. One dot for item one
1. One dot for item two
1. One dot for item three

<!-- Code Block -->
Use the back tick  \`
`<html>`
`<h1>Header 1</h1>`
`<p> paragraph text </p>`

<!-- Images -->
IMAGES
![Markdown LOGO](https://markdown-here.com/img/icon256.png)

![Local LOGO](./logo.png)


<!-- GitHub Specific -->
GITHUB SPECIFIC MARKDOWN

<!-- GitHub Code Blocks -->
set of three back ticks \'\'\'
on top and bottom of code block
You can also specify language specific language after the ticks and the markdown will color code the block for that language

```git
git status
git add .
git commit -m "sample"
```

```javascript
function add(num1, num2){
    return num1*num2;
}
```
```python
#python code
def convert(s):
    # initialization of string to ""
    str1 = ""
    # using join function join the list s by
    # separating words by str1
    return (str1.join(s))
```

<!-- Tables -->
TABLES

| Header     | Column 1    | Column 2     | Column 3    |
|------------|-------------|--------------|-------------|
|1. Alpha    | 55555555    | aaaaaaaa     | cat         |
|2. Bravo    | 77777777    | bbbbbbbb     | dog         |
|3. Charlie  | 88888888    | cccccccc     | bird        |
|            |             |              |             |

The tables can be a little problematic. You really need to 
be using a monospaced font. As long as the rows and column
bars line up, you will get the nice formatting.

<!-- Task Lists -->
TASK LISTS
These should diplay as check boxes on GitHub in README files

Asterisk space brackets for a task list item
X the boxes you want checked
leave empty the boxes you want empty

* [x] Task 1
* [x] Task 2
* [ ] Task 3

* [x] Code
* [x] Document
* [ ] Test
* [ ] Task 4

