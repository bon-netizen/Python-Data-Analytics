# How to Make Markdown Files

Here is a link to a very clear guide on [basic syntax](https://www.markdownguide.org/basic-syntax/).  
And yet here is a link to [extended syntax](https://www.markdownguide.org/extended-syntax/).

## Headings

    # Heading level 1
    ## Heading level 2
    ### Heading level 3
    #### Heading level 4
    ##### Heading level 5
    ###### Heading level 6

After render it will look likt this:
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6  


## Text
Test is just as normal typed.
use 2 spaces when need a line break at the end of line.  
This will be next line if the above line end has 2 spaces.\
Or can use `\` at end of line, create line break.

## Horizontle rule
You can add Horizontle rule with those. 

    ___  
    ---  
    ***  

will give you something like fillowing line:

---
___
***

A heading with horizontal rule like the following:

### Section 3: Section Title
---
Section text goes here.


## block quotes
If you want a block quotes from other articles, use `>` in front of each line  
> SciPy (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering. In particular, these are some of the core packages:
> - Numpy
> - SciPy Library
> - Matplotlib
> - IPython
> - SymPy
> - pandas

## code block

an empty line before block
an empty line after block
indent at least 4 space.
see the above 2 code blocks, one is for the headings syntax, another is for the horizontle rule.

you can also use 3 backticks for code block. this method also support syntax highlighting to your code block

```python  

# simple python code    
for number_i in range(10):
    print('value of i is', number_i)
else:
    print('all finished!')
    
```

if you want put inline code into your text, can put it like this with backquotes `x = [i for i in range(10)]`  

## Links

To create a link, enclose the link text in brackets (e.g., `[Duck Duck Go]`) and then follow it immediately with the URL in parentheses (e.g., (`https://duckduckgo.com`)).
You can check above, there are 2 links for the markdown syntax.


## List

- unordered list items
- unordered list items
  
1. ordered list items
2. ordered list items
  
## Table

|  id  |   Full Name |  Salary(Per Month)  |  
| ---- | ---    | ---     |  
| 1   |  abc    |  400.00 |
| 2  |  def     | 230.00  |  

By defaul all data in table aligned to left.  
You can specify alignment with column `:`

|  id  |   Full Name | Salary(Per Month)  |  
| :--- | :---:    | ---:     |  
| 1   |  abc    |  400.00 |
| 2  |  def     | 230.00  |  


## Task List  

- [x] the first task
- [ ] the second task
- [ ] the third task



## font weight, font style, font decoration

**bold text**  
*Italic text*  
***bold and Italic text***  
~~strike through text~~  



## Emoji in your text

You can copy and paste emoji from other place into your markdown file. like this: 😀❤️  

You can find emoji from website like [emojipedia](https://emojipedia.org/)  

Some markdown interpreter allow you to use shortcodes for emoji in the markdown file. For example: :smiley: :heart-eyes: but this feature is not with notebook yet.

## Simulate a block note  

---
⚠️**NOTE**

Some content which is important and need get reader to pay attention on it.  

---

Notice the blank line in the above note created. it is necessary to keep the blank line in order for the format to work.


## adding image  

can add image if know the url link.  
![python logo](https://www.python.org/static/img/python-logo.png)

![jupyter logo](https://jupyter.org/assets/main-logo.svg 'This is tip text when hover mouse')  


## adding math formula  

the add a formula inline your text use `$` at the beginning and end. Like: $e^{i\pi} = -1$  

or can use `$$` to put the equation as block.  
$$ c = \sqrt{a^2 + b^2} $$

Also for block equation you can use `\begin{equation}` and `\end{equation}`, like following:

\begin{equation}  
e^x=\sum_{i=0}^\infty \frac{1}{i!}x^i  
\end{equation}  

\begin{equation}
F(k) = \int_{-\infty}^{\infty} f(x) e^{2\pi i k} dx
\end{equation}  
   
For more details on LaTeX syntax, you can refer to the [wikibooks on LaTeX/Mathematics](https://en.wikibooks.org/wiki/LaTeX/Mathematics) 
