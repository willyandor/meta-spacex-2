---
title: Markdown格式测试
tags: []
updated: '2021-10-20T01:50:44.919Z'
categories: []
excerpt: |-
  __Advertisement :)__

  - __[pica](https://nodeca.github.io/pica/demo/)__ - high quality and fast i...
date: 2021-10-20 01:50:44
---

```yaml
__Advertisement :)__

- __[pica](https://nodeca.github.io/pica/demo/)__ - high quality and fast image
  resize in browser.
- __[babelfish](https://github.com/nodeca/babelfish/)__ - developer friendly
  i18n with plurals support and easy syntax.

You will like those projects!
```

# h1 Heading 8-)

## h2 Heading

### h3 Heading

#### h4 Heading

##### h5 Heading

###### h6 Heading

## Horizontal Rules

***

***

***

## Typographic replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'

## Emphasis

**This is bold text**

**This is bold text**

*This is italic text*

*This is italic text*

\~Strikethrough~

## Blockquotes

> Blockquotes can also be nested...
>
> > ...by using additional greater-than signs right next to each other...
> >
> > > ...or with spaces between arrows.

## Lists

Unordered

*   Create a list by starting a line with `+`, `-`, or `*`
*   Sub-lists are made by indenting 2 spaces:
    *   Marker character change forces new list start:
        *   Ac tristique libero volutpat at

        *   Facilisis in pretium nisl aliquet

        *   Nulla volutpat aliquam velit
*   Very easy!

Ordered

1.  Lorem ipsum dolor sit amet
2.  Consectetur adipiscing elit
3.  Integer molestie lorem at massa
4.  You can use sequential numbers...
5.  ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
58. bar

## Code

Inline `code`

Indented code

// Some comments

line 1 of code

line 2 of code

line 3 of code

Block code "fences"

    Sample text here...

Syntax highlighting

```js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description                                                               |
| -------- | --------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

Right aligned columns

| Option |                                                               Description |
| -------: | --------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |

## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)

## Images

![5feb35da-e06e-4192-ae4c-388f76f429e4](ipfs://QmdM7TTqPN5Ew5LLthsqSiorEP2317JqKQQjVYerjhmkXk)

![b9d92c78-f3a6-42a3-bdbc-384c482ab919](ipfs://Qmcw6knJJntFsmiYTw3GpBRUmLbqbUdjJ7f38c9L6ycCbv "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![87422e6a-f5fb-424f-8669-a1c0d702a2f5](ipfs://QmS7MVSdVUgcfC3pLFpGBph5cFPcMr6fYJ6JxvTxRQ7L3P)"The Dojocat"

With a reference later in the document defining the URL location:

## Plugins

The killer feature of `markdown-it` is very effective support of

[syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).

### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: 😉 :crush: 😢 :tear: 😆 😋
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.

### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

*   19^th^
*   H~2~O

### [\<ins>](https://github.com/markdown-it/markdown-it-ins)

\++Inserted text++

### [\<mark>](https://github.com/markdown-it/markdown-it-mark)

\=Marked text=

### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link ^[1](#footnotes-def-1)^ .

Footnote 2 link ^[2](#footnotes-def-2)^ .

Inline footnote^\[Text of inline footnote] definition.

Duplicated footnote reference ^[2](#footnotes-def-2)^ .

### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

:   Definition 1

with lazy continuation.

Term 2 with *inline markup*

:   Definition 2

{ some code, part of Definition 2 }

Third paragraph of definition 2.

*Compact style:*

Term 1

\~ Definition 1

Term 2

\~ Definition 2a

\~ Definition 2b

### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

\*\[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning

*here be dragons*

:::

***

1.  Footnote **can have markup**
    and multiple paragraphs. [↩](#footnotes-ref-1)
2.  Footnote text. [↩](#footnotes-ref-2) [↩](#footnotes-ref-2:2)

