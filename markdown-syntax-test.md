# Basic Syntax

## Headings

# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6

Heading level 1
===============

Heading level 2
---------------

## Paragraphs

I really like using Markdown.

I think I'll use it to format all of my documents from now on. 

## Line Breaks

This is the first line.  
And this is the second line.

## Emphasis

I just love **bold text**.

I just love __bold text__.

Love**is**bold

Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

A*cat*meow

This text is ***really important***.

This text is ___really important___.

This text is __*really important*__.

This text is **_really important_**.

This is really***very***important text.

## Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

## Lists

1. First item
2. Second item
3. Third item
4. Fourth item

<br>

1. First item
1. Second item
1. Third item
1. Fourth item

<br>

1. First item
8. Second item
3. Third item
5. Fourth item 

<br>

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item 

<br>

- First item
- Second item
- Third item
- Fourth item

<br>

* First item
* Second item
* Third item
* Fourth item

<br>

+ First item
+ Second item
+ Third item
+ Fourth item 

<br>

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

## Code

At the command prompt, type `nano`.

    <html>
      <head>
      </head>
    </html>

## Horizontal Rules

***

---

_________________

## Links

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

<https://www.markdownguide.org>

<fake@example.com>

I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

## Images

![The San Juan Mountains are beautiful!](imgs/san-juan-mountains.jpg "San Juan Mountains")

[![An old rock in the desert](imgs/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

# Extended Syntax

## Tables

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## Fenced Code Blocks

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

## Heading IDs

### My Great Heading {#custom-id}

[My Great Heading](#custom_id)

## Definition Lists

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## Strikethrough

~~The world is flat.~~ We now know that the world is round.

## Task Lists

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## Emoji

Gone camping! :tent: Be back soon.

That is so funny! :joy:

## Highlight

I need to highlight these ==very important words==.

## Subscript

H~2~O

## Superscript

X^2^

## Automatic URL Linking

http://www.example.com
