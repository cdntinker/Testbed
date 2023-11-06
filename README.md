well then...

VSC doesn't want to load the submodule when cloning...

In the local folder of the repo, you can type:

* git submodule update --init --recursive

& that'll download the submodule.

Tho syncing with the botton is kinda weird...

OR...

Clone the repo before you use VSC on it.

* git clone https://github.com/cdntinker/Testbed --recursive

In an empty folder sets it up & VSC mostly works from there...

But syncing is still weird.

If you update anything in the submodule, you have to sync them both explicitly.

# Some links:

* [SUBMODULES: A git repo inside a git repo.](https://dev.to/jjokah/submodules-a-git-repo-inside-a-git-repo-36l9)
* [Git Submodules basic explanation](https://gist.github.com/gitaarik/8735255)