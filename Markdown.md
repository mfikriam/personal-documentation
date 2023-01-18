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

<br>

## Images

```
1. Open the file containing the sad Pepe.
2. Marvel at its beauty.

    ![Pepe, the sad frog](/img/markdown/pepe.png)

3. Close the file.
```

1. Open the file containing the sad Pepe.
2. Marvel at its beauty.

    ![Pepe, the sad frog](/img/markdown/pepe.png)

3. Close the file.

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

### Relative links

```
[Contribution guidelines for this project](README.md)
```

[Contribution guidelines for this project](README.md)

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