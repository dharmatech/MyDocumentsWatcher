
I keep most of my Visual C# solution directories in my `Documents` folder. In my file browser, I like sorting by modified time in descending order so that I can see what I've worked on recently. Unfortunately, when I update a C# code file in a solution, this doesn't trigger an update of the solution directory's modified time and so the directory doesn't get moved to the top of the list in my file browser...

This little utility program watches my `Documents` folder for any C# code file changes. It touches the corresponding solution folder so that it's modified time is also updated.