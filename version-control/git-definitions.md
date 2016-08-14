# Git Definitions

 **Instructions: ** Define each of the following Git concepts.
  
  * What is version control?  Why is it useful?
 +Version control allows us to view the entire history of revisions to one or more files, and merge revisions made by different people. This is useful because it allows us to create save points and organize multiple people working on the same file.
  * What is a branch and why would you use one?
 +A branch is a copy of your project that you can freely edit without affecting the main copy until you merge them. You use branches to edit a copy of your project, which someone will review, before merging those changes into the real project.
  * What is a commit? What makes a good commit message?
 +A commit is a save point in Git that allows you to keep track of your editting. Commits need a commit message to go with them and usually you want the message to explain what changes you did in that save point.
  * What is a merge conflict?
 +Merge conflict occurs when two branches editted the same line in the same file and Git can't choose between the two when merging into the main branch. When the branches try to merge Git can't choose between the two changes and will mark the file as a conflict. This can also occur if a file is deleted and someone tries to merge a branch with the deleted file.