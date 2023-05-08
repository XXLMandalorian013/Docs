###### Headings and layout
# Heading 1

## Heading 2

## Heading 3

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6


###### Bold Example - Simply type what you want, then highlight it and press ALT+M and select bold to make it bold. Alternatively, you can prefix and suffix a word with astrict :::no-loc text="**Bold**":::. 
**Bold Example**

###### Italic Example - Simply type what you want, then highlight it and press ALT+M and select italic to make it italic. Alternatively, you can prefix and suffix a word with astrict :::no-loc text="*italic*":::.

*Italic Example*

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

###### Alert - Note Example - Simply press ALT+M, select Alert and then note to 

> [!NOTE]
> Information the user should notice even if skimming





