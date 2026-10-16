1\. "Path

\----

C:\\Windows\\system32"



2\. System files show up with ls -force but with not with normal ls. In the mode column, if it has the letter 's', it means it is a system file, and it only shows up with ls -force and not ls.



3\. I first thought it is the drive, like the C: and the D: drive, but I now know that 'd' means it's a directory, and if it starts with a '-', It means it is a file. The rest of the columns signify whether it is a system file, hidden file, read only file, etc.



4\. It is a relative path, an absolute path would include a whole address like C:/users.. It works because it is connected to the current location where 'coding-cafe' is.



5\. The first mv moved the file from the main folder to inside the week01 folder, the second mv renamed the 'README-backup.md' file to 'old-readme.md'.



6\. 19 (Nineteen)



7\.  C:\\Users\\ShivamGhosh\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe



8\. There is a path difference between mac and windows, and hence it is stored on different locations.



9\. "pyton : The term 'pyton' is not recognized as the name of a cmdlet,

function, script file, or operable program. Check the spelling of the

name, or if a path was included, verify that the path is correct and try

again.

At line:1 char:1

\+ pyton

\+ \~\~\~\~\~

&#x20;   + CategoryInfo          : ObjectNotFound: (pyton:String) \[], CommandNo

&#x20;  tFoundException

&#x20;   + FullyQualifiedErrorId : CommandNotFoundException"



Pyton is obviously not a real file or a program. When powershell searchers for it, no folder on 'PATH' contains anything by that exact name, so the shell reports it as unrecognized.



10\. .venv does not appear with plain ls because it is a hidden file which can only be seen with la -a.



11\. .venv starts to appear in the front of prompts.



12\. No, this is not the same path.



13\. Earlier it only showed pip version but now it shows full packages' versions. The number of contents has increased. 



14\. Python now again points to its earlier location i.e /usr/bin/python3. This means we've exited the .venv file.



15\. The recurse flag tells a command to apply its action not just to a target folder but to all subfolders inside it.



16\. ctrl+c starts the thing whereas ctrl+z ends it.

