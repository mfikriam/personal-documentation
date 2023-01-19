# Markdown Documentation

## Table of Contents

<br>

## Headings

    # H1 Heading
    ## H2 Heading
    ### H3 Heading
    #### H4 Heading
    ##### H5 Heading
    ###### H6 Heading

> # H1 Heading
> ## H2 Heading
> ### H3 Heading
> #### H4 Heading
> ##### H5 Heading
> ###### H6 Heading

<br>

## Paragraphs & Line Breaks

```
Don't put tabs or spaces in front of your paragraphs.

Keep lines left-aligned like this.<br>
And this is the third line.
```

Don't put tabs or spaces in front of your paragraphs.

Keep lines left-aligned like this.<br>
And this is the third line.

<br>

## Styling Text

| Style | Syntax | Output |
| --- | --- | --- |
| Bold | `**bold text**` <br> `__bold text__` <br> `this**bold**text`| **bold text** <br> __bold text__ <br> this**bold**text |
| Italic | `*italicized text*` <br> `_italicized text_` <br> `this*italicized*text`| *italicized text* <br> _italicized text_ <br> this*italicized*text |
| Strikethrough | `~~strikethrough text~~`| ~~strikethrough text~~ |
| Bold and Italic | `***important text***` <br> `___important text___` <br> `**this*important*text**`| ***important text*** <br> ___important text___ <br> **this*important*text** |
| Subscript | `this <sub>subscript</sub> text`| this <sub>subscript</sub> text |
| Superscript | `this <sup>superscript</sup> text`| this <sub>superscript</sub> text |

<br>

## Quoting

### Quoting Text

You can quote text with `>`

    text that is not a quote
    > text that is a quote
    >> text that is a nested quote

text that is not a quote
> text that is a quote
>> text that is a nested quote

### Quoting Code

    You can use `example` for inline text for your code.

    Code blocks are normally indented four spaces or one tab.

        <html>
            <head>
                <title>Test</title>
            </head>

    or you can use ``` for block of code

    ```
    git status
    git add
    git commit
    ```

You can use `example` for inline text for your code.

Code blocks are normally indented four spaces or one tab.

    <html>
        <head>
            <title>Test</title>
        </head>

or you can use ``` for block of code

```
git status
git add
git commit
```

### Escaping Backticks

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (``).

    ``Use `code` in your Markdown file.``

``Use `code` in your Markdown file.``

<br>

## Lists

### Ordered Lists

```
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item
```
   
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

### Unordered Lists

```
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
    1. Indented item
    2. Indented item
```

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
    1. Indented item
    2. Indented item

### Task Lists

```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

<br>

## Images

### Add Image

```
![Pepe, the sad frog](/img/markdown/pepe.png)
```

![Pepe, the sad frog](/img/markdown/pepe.png)

### Change Image Size

```
<img src="drawing.jpg" alt="drawing" width="200"/>
```

<img src="img/markdown/pepe.png" alt="drawing" width="200"/>

<br>

## Links

### Create A Link

```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

### Adding Titles

```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
```

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

### URLs and Email Addresses

```
<https://github.com/mfikriam/personal-documentation/blob/main/Markdown.md>  
<yapkun17@gmail.com>
```

<https://github.com/mfikriam/personal-documentation/blob/main/Markdown.md>  
<yapkun17@gmail.com>

### Reference-style Links

```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
```

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

### Footnotes

```
Here is a simple footnote[^1].  
A footnote can also have multiple lines[^2].  
You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
```

Here is a simple footnote[^1].  
A footnote can also have multiple lines[^2].  
You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

### Relative links

```
[Contribution guidelines for this project](README.md)
```

[Contribution guidelines for this project](README.md)

| Context | Relative Link |
| --- | --- |
| In a `.md` file on the same branch | `/assets/images/electrocat.png` |
| In a `.md` file on another branch | `/../main/assets/images/electrocat.png` |
| In issues, pull requests and comments of the repository | `../blob/main/assets/images/electrocat.png?raw=true` |
| In a `.md` file in another repository | `/../../../../github/docs/blob/main/assets/images/electrocat.png` |
| In issues, pull requests and comments of another repository | `../../../github/docs/blob/main/assets/images/electrocat.png?raw=true` |

<br>

## Horizontal Rules

```
***
---
_________________
```

***
---
_________________

<br>

## Using Emojis

```
:+1: :eyes: :tongue: :angel: :family:
```

:+1: :eyes: :tongue: :angel: :family:

For a full list of available emoji and codes, check out the [Emoji-Cheat-Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).