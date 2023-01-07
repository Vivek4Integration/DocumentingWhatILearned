# 31 December 2022

## PowerShell

### Comments

Looked at common comments and below comment type for PowerShell, following fits the bill, will be using from going forward.

```PowerShell
<# 
.SYNOPSIS 
This script/function does - What? 
.DESCRIPTION 
A more detailed description of why and how the function works. 
.PARAMETER DemoParam1 
The parameter DemoParam1 is used to define the value of blah and also blah. 
.PARAMETER DemoParam2 
The parameter DemoParam2 is used to define the value of blah and also blah. 
.EXAMPLE 
The example below does blah 
PS C:\> Example 
.EXAMPLE 
Another example 
.NOTES 
Author: Name 
Last Edit: yyyy-mm-dd 
Version 1.0 - initial release of blah 
Version 1.1 - update for blah 
#> 
```

### Adding member to json

I was converting a json to json object and found the need to add member to json object.

``` PowerShell
$jsonObject | add-member -Name subscriptionid -value "1eddf917-54c8-4d34-aeda-397d2c7f2446" -MemberType NoteProperty;
```

## az cli command

Found way to fetch sp filtered by appid, which is as follows.

``` powershell
az ad sp list --filter "appid eq 'f88d7c63-4b09-4448-a7e6-1732c63269f9'"
```

## Markdown

Following is way to add to do list,

- [x] Todo list item 1
- [ ] Todo list item 2
