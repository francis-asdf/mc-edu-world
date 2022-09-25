# mc-edu-world

Repository for sharing a Minecraft Educational Edition world.

I haven't gotten around to making a server for this so this will temporarily be the place where you add your changes to the world.

# How to use this thing

1. **Create a Github account** <!-- TODO: add link -->
2. **Install [Git](https://git-scm.com/) and [Github Desktop](https://desktop.github.com/) on your computer**
3. **Fork this repository**
   
   There's this button on the top-left corner that says "Fork". Click that and Github will make a copy of this in your own Github account
4. **Clone the repo to your Minecraft Edu folder**

   On Windows this is at `%APPDATA%\Minecraft Education Edition`. I forgot where it was on MacOS but in any case you can search up "minecraft edu folder" or something. Afterwards navigate to `games > com.mojang > minecraftWorlds`. This is the location your Minecraft worlds are stored.
   
   Now start up a terminal in this folder, then type
   
   ```
   git clone https://github.com/<username here>/mc-edu-world.git
   ```
   
   this will copy your version of this repo into your saves folder.
   
   Next, open Github Desktop, and **add a local repository** (either `Ctrl/Cmd+O` or `File > Add local repository` to open this repo in Github Desktop
5. **Minecraft**

   yay
6. **Save your world**

   After wrapping up press "save and exit" in the world menu, and wait for the world to save.
   Open up Github Desktop, which *should* have the world open. On the left, there should show changes to the world. On the bottom-left corner, you type commit info (basically describe what you added), and press commit.
   Github Desktop should then prompt you to push your changes to Github. Do that.
7. **[Make a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) to this repository**

   Someone should be able to accept it shortly.
