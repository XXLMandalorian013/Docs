###### Headings and layout
# Heading 1

## Heading 1 is the largest size of Makrdown. See below to do so.
:::no-loc text="# Heading 1":::

## Heading 2, see the text below.
:::no-loc text="## Heading 2":::

### Heading 3, see the text below.
:::no-loc text="### Heading 3":::

#### Heading 4, see the text below.
:::no-loc text="#### Heading 4":::

##### Heading 5, see the text below.
:::no-loc text="##### Heading 5":::

###### Heading 6 is the smallest, see the text below.
:::no-loc text="###### Heading 6":::


###### Bold Example - Simply type what you want, then highlight it and press ALT+M and select bold to make it bold. Alternatively, you can prefix and suffix a word with astrict :::no-loc text="**Bold**":::. 
**Bold Example**

###### Italic Example - Simply type what you want, then highlight it and press ALT+M and select italic to make it italic. Alternatively, you can prefix and suffix a word with astrict :::no-loc text="*italic*":::.

*Italic Example*

###### Bold and Italic Example - Simply prefix and suffix a word with astrict :::no-loc text="***bold and italic***":::.

***bold and italic***.

###### Code Example - Simply type what you want, then highlight it and press ALT+M and select code. It will then ask for the langue you are writing. Alternatively, you can prefix and suffix a code block with the backtick like so ```powershell
some code here```. Be sure to change *powershell* to the langue you are showing.


```powershell
function Write-ScriptBoilerplate {
    try{

        $ScriptBoilerplate = "$ScriptName script starting...written by $ScriptAuthor, last modified on $ModifiedDate"

        Write-Verbose -Message "$ScriptBoilerplate" -Verbose

        Write-ScriptStep -Text "$ScriptBoilerplate"

    }catch {

    }  
}
```

###### Alerts - Simply press ALT+M, select Alert > then pick one of the following: Note, Tip, Important, Caution, or Warning and it will place your designated alert. Alternatively, you manually create an alert by typing, To create the Note style alert. The same goes for changeing NOTE to Tip, Important, Caution, and Warning. Note, the name of the alert type ***MUST*** be capitalized.

```
> [!NOTE]
> Information the user should notice even if skimming.
```

> [!NOTE]
> Information the user should notice even if skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Essential information required for user success.

> [!CAUTION]
> Negative potential consequences of an action.

> [!WARNING]
> Dangerous certain consequences of an action.
###### That said you can change the text of the alert's body to anything you want, but the type of alert ie :::no-loc text="!Note"::: must be least as is or it will break.

> [!WARNING]
> Danger, Danger Will Robbinson!!!




