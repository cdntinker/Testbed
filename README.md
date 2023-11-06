well then...

VSC doesn't want to load the submodule when cloning...

In the local folder of the repo, you can type:

* git submodule update --init --recursive

& that'll download the submodule.

Tho syncing with the botton is kinda weird...

OR...

* git clone https://github.com/cdntinker/Testbed --recursive

In an empty folder sets it up & VSC mostly works from there...