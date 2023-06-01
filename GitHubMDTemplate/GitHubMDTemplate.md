# GitHub :octocat: Markdown Template :page_facing_up:

###### Table of Contents

<details>
<summary>Click to expand</summary>

- [GitHub :octocat: Markdown Template :page_facing_up:](#github--octocat--markdown-template--page-facing-up-)
          + [Table of Contents](#table-of-contents)
  * [Headings :man_beard:](#headings--man-beard-)
- [first-level heading](#first-level-heading)
  * [second-level heading](#second-level-heading)
    + [third-level heading](#third-level-heading)
      - [fourth-level heading](#fourth-level-heading)
        * [fifth-level heading](#fifth-level-heading)
          + [sixth-level heading](#sixth-level-heading)
  * [Styling :man_in_tuxedo:](#styling--man-in-tuxedo-)
    + [Bold example:](#bold-example-)
    + [Italic example:](#italic-example-)
    + [Bold and italic example:](#bold-and-italic-example-)
    + [Strikethrough example:](#strikethrough-example-)
  * [Images :framed_picture:](#images--framed-picture-)
  * [Code Blocks :shell:](#code-blocks--shell-)
    + [Code blocks without syntaxing:](#code-blocks-without-syntaxing-)
    + [Code blocks with syntaxing:](#code-blocks-with-syntaxing-)
    + [Display code blocks within a code block:](#display-code-blocks-within-a-code-block-)
    + [Quoting Code:](#quoting-code-)
  * [:running_woman: Escaping Markdown](#-running-woman--escaping-markdown)
  * [Example of a table :bar_chart:](#example-of-a-table--bar-chart-)
  * [Section :bookmark_tabs:](#section--bookmark-tabs-)
      - [Pre-collapsed section.](#pre-collapsed-section)
      - [Collapsed section.](#collapsed-section)
  * [Quote :speech_balloon:](#quote--speech-balloon-)
    + [Quote Style 1](#quote-style-1)
    + [Quote Style 2](#quote-style-2)
  * [Comment :memo:](#comment--memo-)
  * [Subscript :alembic:](#subscript--alembic-)
  * [Superscript](#superscript)
  * [Emojis :grin:](#emojis--grin-)
  * [Table of Contents :open_book:](#table-of-contents--open-book-)

</details>

Note: The short cuts referneced here are a combination of exsisting VSCode and a plug it from MS called [learn-markdown](https://marketplace.visualstudio.com/items?itemName=docsmsft.docs-markdown). Also the MD discribed below renders properly on GitHub, but may look off or broken in VSCode's defualt previewer. Just roll with my examples and push them to your repo and see for yourself.

## Headings :man_beard:

There are six recognized heading sizes. The largest is Heading 1, the smallest is Heading 6. The # symbol followed by a space and what you want to type is used to create a heading. See below for examples. You can also not use # at all and just type what you want.

```markdown
# first-level heading

## second-level heading

### third-level heading

#### fourth-level heading

##### fifth-level heading

###### sixth-level heading

no heading
```

# first-level heading

## second-level heading

### third-level heading

#### fourth-level heading

##### fifth-level heading

###### sixth-level heading

no heading

## Styling :man_in_tuxedo:

### Bold example:

Simply type what you want, then highlight it and press ALT+M and select bold to make it bold. Alternatively, you can prefix and suffix a word with astrict.
**Bold Example**

Here is the raw markdown for bolding.

```md
**Bold Example**
```

### Italic example:

Simply type what you want, then highlight it and press ALT+M and select italic to make it italic. Alternatively, you can prefix and suffix a word with astrict.

*Italic Example*

Here is the raw markdown for italicizing.

```md
*Italic Example*
```

### Bold and italic example:

Simply prefix and suffix a word with astricts.

***bold and italic***

Here is the raw markdown for bolding and italicizing.

```md
***bold and italic***.
```
### Strikethrough example:

~~This was mistaken text~~

Here is the raw markdown for bolding and italicizing.

```markdown
~~This was mistaken text~~
```

### Numbered List

To create a numbered list, just type `1.` as you would normaly in most word processors.

1. First item
2. Second item
3. Third item

Here is the raw markdown for numbered list.

```markdown
1. First item
2. Second item
3. Third item
```

### Bulleted List

To make a bulleted list, just type `*` as you would normaly in most word processors.

* First item
* Second item
* Third item

Here is the raw markdown for bulleted list.

```markdown
* First item
* Second item
* Third item
```


## Images :framed_picture:

1. When I add images to GitHubs flavored markdown, I save them in a subfolder I have created called images.

RepoName
├── FolderInRepo
├    └──images
├        └──ImageName.png

2. I then push them up to the Repo in github. 

3. You can then paste the URL where your images are hosted at from your repo into the GitHub flavored mardown syntax `![SpiderManW/PSLogo](https://github.com/XXLMandalorian013/Docs-Sofware-SAS-Public/blob/main/GitHubMDTemplate/Images/friendlyNeighborhoodPS.png)` or drag and drop the image by left clicking and holding, and it will automatically add the syntax for you.

![SpiderManW/PSLogo](https://github.com/XXLMandalorian013/Docs-Sofware-SAS-Public/blob/main/GitHubMDTemplate/Images/friendlyNeighborhoodPS.png)


## Code :shell:

### Code blocks without syntaxing:

```
Add-VMDvdDrive -VMName "$Global:VMName" -Path "$Global:ISOPath"
```
Here is the raw markdown for code blocks without syntax.

````
```
Add-VMDvdDrive -VMName "$Global:VMName" -Path "$Global:ISOPath"
```
````

### Code blocks with syntaxing:

```powershell
$Global:VMName = 'Win10VM'

$Global:ISOPath = 'E:\ISOs\WindowsServer2019.iso'

Add-VMDvdDrive -VMName "$Global:VMName" -Path "$Global:ISOPath"
```

Here is the raw markdown for code blocks with or without syntax.

````
```powershell
$Global:VMName = 'Win10VM'

$Global:ISOPath = 'E:\ISOs\WindowsServer2019.iso'

Add-VMDvdDrive -VMName "$Global:VMName" -Path "$Global:ISOPath"
```
````

### Display code blocks within a code block:

<img src="https://github.com/XXLMandalorian013/Docs-Sofware-SAS-Public/blob/a1109635cf80efe63821b1e1f7e56395b55c7488/GitHubMDTemplate/Images/DisplayCodeBlocksWithinACodeBlock.png">

### Quoting Code:

To quote code withing a sentence, use a single backtick prefix and suffix a word or phase as so `$Global:VMName = 'Win10VM'`.

Here is the raw markdown for quoting code.

```markdown
`$Global:VMName = 'Win10VM'`
```

## :running_woman: Escaping Markdown

Escaping markdown can be a bit tricky but works for most cases. Simply put a `\` in front of what you dont want to be rendered as Markdown.

In this example I had a PowerShell code block that I escaped.

\```powershell
$Global:VMName = 'Win10VM'

$Global:ISOPath = 'E:\ISOs\WindowsServer2019.iso'

Add-VMDvdDrive -VMName "$Global:VMName" -Path "$Global:ISOPath"
\```

Here is the raw markdown for escaping Markdowns code block.

```
\```powershell
$Global:VMName = 'Win10VM'

$Global:ISOPath = 'E:\ISOs\WindowsServer2019.iso'

Add-VMDvdDrive -VMName "$Global:VMName" -Path "$Global:ISOPath"
\```
```

## Example of a table :bar_chart:

Here is an example of a table.

| Kowlage | Computer Lauguage |
|--------:|-------------------|
|    1    |     PowerShell    |
|    2    |      MarkDown     |
|    3    |        HTML       |
|    4    |        CSS        |

Here is the raw markdown for the table above.

```markdown
| Kowlage | Computer Lauguage |
|--------:|-------------------|
|    1    |     PowerShell    |
|    2    |      MarkDown     |
|    3    |        HTML       |
|    4    |        CSS        |
```

## Section :bookmark_tabs:

#### Pre-collapsed section.

<details>
<summary>Collapsed Section</summary>

Here is some text within the pre-collapsed section above.

</details>

```markdown
<details>
<summary>Collapsed Section</summary>

Here is some text within the pre-collapsed section above.

</details>
```

#### Collapsed section.

<details open>
<summary>Collapsed Section</summary>

This is some text within the open collapsed section.

</details open>

Here is the raw markdown for the open collapsed section above.

```markdown
<details open>
<summary>Collapsed Section</summary>

This is some text within the open collapsed section.

</details open>
```

## Quote :speech_balloon:

### Quote Style 1

---
> “If you give a man a fish, you feed him for a day. If you teach a man to fish, you feed him for a lifetime.”

— Unknown

Here is the raw markdown for Quote Style 1.

```markdown
---
> “If you give a man a fish, you feed him for a day. If you teach a man to fish, you feed him for a lifetime.”

— Unknown
```

### Quote Style 2

> Text that is a quote

Here is the raw markdown for Quote Style 2.

```markdown
> Text that is a quote
```

## Comment :memo:

To add a comment type the following. You will not see it rendered as its for your reference only.

<!-- TO DO: add more details about this later -->

```markdown
<!-- TO DO: add more details about this later -->
```

## Subscript :alembic:

co<sub>2</sub>

Here is the raw markdown for subscript.

```markdown
co<sub>2</sub>
```

## Superscript

E=mc<sup>2</sup>

Here is the raw markdown for superscript.

```markdown
E=mc<sup>2</sup>
```

## Emojis :grin:

A list of emoji have been compiled here. https://github.com/ikatyang/emoji-cheat-sheet/tree/master

## Links

Should you want to include links in your MD page, you can simply type the URL and it will be rendered as a link.

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links

A way to shorten a URLs is to use the GitHub flavored way to add links

[learn-markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)

```makrdown
[learn-markdown](https://marketplace.visualstudio.com/items?itemName=docsmsft.docs-markdown)
```

## Table of Contents :open_book:

Github creates a table of contense based off your headings, they call it an "Outline".

<img src="https://github.com/XXLMandalorian013/Docs-Sofware-SAS-Public/blob/main/GitHubMDTemplate/Images/MarkdownTOC.png">

Should you want to include a table of contense withing your MD page, you can use [markdown-toc](https://ecotrust-canada.github.io/markdown-toc/).





