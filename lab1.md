## Lab 01

- Name: Trevor Sclesky
- Email: sclesky.2@wright.edu

## Part 1 - GitHub Profile

1. [your_github_username_here's GitHub Profile](FIXTHISURL-https://github.com/your_username)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         | decribes powershell cmdlets and concepts       |
| Get-Location | pwd    | used to determin what the current working directory is.      |
| Get-ChildItem | ls    | gets the items in one or more specified locations       |
| mkdir   | mkdir       | creates a new directories        |
| Set-Location | cd     | sets the working location to the specified location       |
| New-Item | touch      | creates a new item and sets its value       |
| Move-Item | mv        | moves an item, its properties, contents, and child items from one location to another.       |
| Copy-Item | cp        | copies an item from one location to another within the same namespace       |
| Remove-Item | rm      | deletes one or more items       |
| notepad.exe | vim     | opens the note pad       |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Powershell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: C:\Users\trevor> cd $env:USERPROFILE
2. Create a directory named `DirA`: mkdir DirA
3. Create a directory named `Dir B`:  mkdir DirB
4. Go into `DirA`: cd dirA
5. Go into `Dir B` from `DirA`: cd C:\Users\trevor\dirB
6. Return to your user's home directory: cd C:\Users\trevor
7. Create a file named `test.txt`:  New-Item test.txt
8. Move the file named `test.txt` into `DirA`: Move-Item -Path C:\Users\trevor\test.txt -Destination C:\Users\trevor\dirA
9. Contents of `test.txt`: nothing it is blank??????
```
Put your words here
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item "C:\Users\trevor\DirA\test.txt" -Destination "C:\Users\trevor\DirA\copy.txt"
11. View the contents of `DirA`: cd C:\Users\trevor\DirA >then> ls
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: Copy-Item "C:\Users\trevor\DirA\test.txt" -Destination "C:\Users\trevor\DirB\fodder.txt"
13. Delete / remove both `fodder.txt` AND `Dir B`: Remove-Item C:\Users\trevor\DirB

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

[Get-Location](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/get-location?view=powershell-7.5)
[Get-ChildItem](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/get-childitem?view=powershell-7.5)
[mkdir](https://stackoverflow.com/questions/70988505/what-is-the-mkdir-p-equivalent-in-powershell)
[Set-Location](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/set-location?view=powershell-7.5)
[New-Item](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/new-item?view=powershell-7.5)
[Move-Item](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/move-item?view=powershell-7.5)
[Copy-Item](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/copy-item?view=powershell-7.5)
[Remove-Item](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/remove-item?view=powershell-7.5)
[notepad.exe](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/start-process?view=powershell-7.5)
[ Full / absolute path to your user's home directory:](https://stackoverflow.com/questions/65123462/get-path-to-the-user-home-directory-on-windows-in-powershell)
[Contents of `test.txt`](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/get-content?view=powershell-7.5)


