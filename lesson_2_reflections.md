What happens when you initialize a repository? Why do you need to do it?
* A new directory named `.git` is created in the root directory of the repository.
* So that Git can recognize the current folder as a repository.

How is the staging area different from the working directory and the repository? What value do you think it offers?
* I can commit the files in the staging area whereas I cannot commit in files from the working directory.
* It allows me to choose the file that I think they hold a reasonable-sized logical change.

How can you use the staging area to make sure you have one commit per logical change?
* To add only the files that have a logical change, commit them .. then go add some other files which contain another logical change, commit them and so on ...
