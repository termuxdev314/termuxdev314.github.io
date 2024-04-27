# Over python-repo

Termux is not a normal Linux, which often leads to problems when compiling certain Python modules. But even if it worked one time, it may not work the next time, and that happens very often and is not unusual. I have therefore made it my task to compile such packages on Termux, which can take a lot of time. The most common problems usually occur with Openai, Discord.py, Maturin and Twine. Whenever I manage to compile them, I pack them into a .deb so that they can be easily installed via my repo. This can be done by installing the .deb from my release, which imports the gpg key and packs the list. Please only use the packages if compilation fails, as there may be problems between the packages, as they are now treated like Debian packages. However, you can simply import them as usual. If you have any suggestions, send the .deb with the module via pull request.

# Pacman User

For Pacman users, you can simply install apt alongside pacman and configure it properly. Then you can also install the repo here
