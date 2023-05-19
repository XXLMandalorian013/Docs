# GitHub Markdown Template

###### Table of Contents

<details>
<summary>Click to expand</summary>

- [GitHub Markdown Template](#github-markdown-template)
          + [Table of Contents](#table-of-contents)
  * [Headings](#headings)
- [first-level heading](#first-level-heading)
  * [second-level heading](#second-level-heading)
    + [third-level heading](#third-level-heading)
      - [fourth-level heading](#fourth-level-heading)
        * [fifth-level heading](#fifth-level-heading)
          + [sixth-level heading](#sixth-level-heading)
  * [Styling](#styling)
    + [Bold Example](#bold-example)
    + [Italic Example](#italic-example)
    + [Bold and Italic Example](#bold-and-italic-example)
    + [Strikethrough Example](#strikethrough-example)
  * [Example of a table](#example-of-a-table)
  * [Collapsed Section](#collapsed-section)
      - [Example of a pre-collapsed section.](#example-of-a-pre-collapsed-section)
      - [Example of an open collapsed section.](#example-of-an-open-collapsed-section)
  * [Quote](#quote)
      - [Example of a quote.](#example-of-a-quote)
  * [Comment](#comment)
  * [Table of Contents](#table-of-contents-1)

</details>



## Headings

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

## Styling

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

## Images

If writing this in VS code, it will not render when preview, but it will render on GitHub.

<img src="https://github.com/XXLMandalorian013/Docs-Sofware-SAS-Public/blob/a1109635cf80efe63821b1e1f7e56395b55c7488/GitHubMDTemplate/Images/friendlyNeighborhoodPS.png">


## Code Blocks

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


## Escaping Markdown



## Example of a table

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

## Section

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

## Quote

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

## Comment

To add a comment type the following. You will not see it rendered as its for your reference only.

<!-- TO DO: add more details about this later -->

```markdown
<!-- TO DO: add more details about this later -->
```

## Subscript

co<sub>2</sub>

Here is the raw markdown for subscript.

```md
co<sub>2</sub>
```

## Superscript

E=mc<sup>2</sup>

Here is the raw markdown for superscript.

```md
E=mc<sup>2</sup>
```


## Table of Contents


That said, once you understand how this works, you can use the following to create a table of contents automatically by navigating to https://ecotrust-canada.github.io/markdown-toc/.

