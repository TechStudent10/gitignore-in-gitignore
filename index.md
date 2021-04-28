# .gitignore-in-gitignore
What happens when you put .gitignore in .gitignore

So I added the .gitignore through [GitHub](https://github.com), and it got added. Well it'll get added regardless of if it's in the .gitignore or not, so I am going to do this in Github Desktop and see what it does.

## Update after GitHub Desktop
Soooooo... the .gitignore doesn't appear in [GitHub Desktop](https://desktop.github.com), so that's one big...
#### OOF!
So it cloned the repo along with the gitignore, however the way that [GitHub Desktop](https://desktop.github.com) (Someone correct me if I am wrong) works is that if there is a .gitignore file, read the contents of it, then remove all those files from the list of files of that repository. So GitHub Desktop found the file, just that it's doing it's job.
### Ignoring it.
So that means I cannot commit the thing right? 'Cause if I remove the .gitignore, it'll defeat the whole purpose of this repo, and if I leave it, then we cannot commit it cause git is gonna "ignore" it.

## Well, thanks for reading
So yeah this expriment wasn't a total failure, it showed you what happens if you add .gitignore to your .gitignore. Thanks for reading.
