
## Get Access List

```powershell
Get-ACL | Format-List
```

[Get Access List Including subfolders](http://www.enterprisedaddy.com/2015/05/powershell-how-to-get-folder-permissions-using-powershell/)

```powershell
Get-ChildItem .\MyFolder | where-object {($_.PsIsContainer)} | Get-ACL | Format-List
```        


