# Custom XELL Reloaded Logo & Colors Guide - Created By ROAN and uploaded here by me.
Hello, Roan here. I’ll be showing you how to make your own customized XELL Reloaded screen. You can have the “XELL RELOADED” logo be to a different logo, change the background and text colors, and change all of the other texts that print on the screen like motherboard revisions. No downloading programs, all of it is done online through GitHub. Without further ado, let’s get started.

## Step 1: Forking xell-reloaded on GitHub

You’ll first need to sign into your GitHub (create an account if you haven’t already) and were going to fork a copy of Octal450’s xell-reloaded to our GitHub: 
https://github.com/Octal450/xell-reloaded 

Click on the Fork button on the top right. You can leave the repository name and description unchanged if you don’t want to name it. Make sure the “Copy the master branch only” is checked and click on Create fork.

<img src="https://i.imgur.com/OQekViV.png" alt="create fork button" width="600"> 
<img src="https://i.imgur.com/PUlYkZd.png" alt="create fork button" width="600"> 

Once that’s done, you’ll have your own copy of xell-reloaded onto your GitHub.

## Step 2: Editing your XELL RELOADED Logo

Now here comes the fun part, customizing it. On the master branch, go to source, lv2, and open the asciiart.h file. This is the “XELL RELOADED” asciiart logo that we can edit to make it print something different. There are many Text to ASCII generators online that you can use, but the ones I use are here as well as making one from a picture:

https://patorjk.com/software/taag/

https://www.asciiart.eu/image-to-ascii

For this demonstration, I’ll be changing it to “ROAN” which is my name with the Big font. Once you got your logo made, select and copy the entire ascii. Go back to GitHub and edit the asciiart.h file.

<img src="https://i.imgur.com/Mfh9a02.png" alt="create fork button" width="600"> 
<img src="https://i.imgur.com/uoyZZ9v.png" alt="create fork button" width="600"> 
<img src="https://i.imgur.com/FDSbO0j.png" alt="create fork button" width="600"> 

NOTE:

If your getting a yellow error message about the file being encoded and you end up seeing garbage text on the first line instead of the actual code (<img src="https://i.imgur.com/dKtS3T1.png" alt="create fork button" width="600">), don’t worry. You can simply copy and paste the asciiart.h code that I provided here which is what it’s supposed to be in the actual file:

                static char* asciiart = "\n"
    	"       Ü    Ü       Ü     ÜÜ      ÜÜ\n"
    	"      ÞÛÝ  ÞÛÝ    ÜÛßÛÜ   ÛÛ      ÛÛ\n"
    	"      Þ°Ý  Þ°Ý   Þ°Ý Þ°Ý  ÝÞ      ÝÞ\n"
    	"ÜÜÜÜÜ Þ±Ý  Þ±Ý Ü ±± ÜÜÜÜÜ ±± ÜÜÜÜ ±± ÜÜÜÜÜ\n"
    	"²²²²²Ü Þ²ÝÞ²Ý Ü² ²² ßß²²² ²² ²²²² ²² ²²²²²\n"
    	"²²²²²²Ü ßÛÛß Ü²² ÛÛßß ²²² ÛÛ ²²²² ÛÛ ²²²²²\n"
    	"ßßßßßß Ü±ßß±Ü ßß ±± ßßßßß ±± ßßßß ±± ßßßßß\n"
    	"      Þ²Ý  Þ²Ý   Þ²Ý Û²Ý  ²²      ²²\n"
    	"      ÛÛ    ÛÛ    ßÛÜÛß   ÛÛ      ÛÛ\n"
    	"      ßß    ßß      ß     ßßßßßßß ßßßßßßß\n"
    	"   ÜÜÜ         Ü     ÜÜ         ÜÜ        Ü      ÜÜÜ        Ü      ÜÜÜ\n"
    	"  ÛÛ ßÛÜ     ÜÛßÛÜ   ÛÛ       ÜÛßßÛÜ    ÜÛßÛÜ   ÛÛ ßÛÜ    ÜÛßÛÜ   ÛÛ ßÛÜ\n"
    	"  ÝÞ  Þ°Ý   Þ°Ý Þ°Ý  ÝÞ      Þ°Ý  Þ°Ý  Þ°Ý Þ°Ý  ÝÞ  Þ°Ý  Þ°Ý Þ°Ý  ÝÞ  Þ°Ý\n"
    	"Ü ±± Ü ±± Ü ±± ÜÜÜÜÜ ±± ÜÜÜÜ ±± ÜÜ ±±Ü ±± Ü ±±Ü ±± Ü ±±Ü ±± ÜÜÜÜÜ ±± Ü ±±\n"
    	"² ²² ßÛ²Ý ² ²² ßß²²² ²² ²²²² ²² ²² ²²² ²² ß ²²² ²² ² ²²² ²² ßß²²² ²² ² ²²\n"
    	"² ÛÛßÛßß Ü² ÛÛßß ²²² ÛÛ ²²²² ÛÛ ²² ÛÛ² ÛÛßßßÛÛ² ÛÛ ² ÛÛ² ÛÛßß ²²² ÛÛ ² ÛÛ\n"
  	  "ß ±± ß±Ü ßß ±± ßßßßß ±± ßßßß ±± ßß ±±ß ±± ß ±±ß ±± ß ±±ß ±± ßßßßß ±± ß ±±\n"
    	"  ²²  Þ²Ý   Þ²Ý Þ²Ý  ²²      Þ²Ý  Þ²Ý  ²²   ²²  ²²  Þ²Ý  Þ²Ý Þ²Ý  ²²  Þ²Ý\n"
    	"  ÛÛ   ÛÛ    ßÛÜÛß   ÛÛ       ßÛÜÜÛß   ÛÛ   ÛÛ  ÛÛ ÜÛß    ßÛÜÛß   ÛÛ ÜÛß\n"
    	"  ßß   ßß      ß     ßßßßßßß    ßß     ßß   ßß   ßßß        ß      ßßß\n\n";
    static char* asciitail =
    	"              Free60.org XeLL RELOADED - Xenon Linux Loader\n\n";

Simply paste your ascii logo into the code. You can also change what it says below on the asciitail. You still need to have the quotation marks (“) followed by the \n on each line and double \n on the last line. You still need to have static char* asciiart and static char* asciitail in the code. If one of these are not there in the code, your Xell won’t build successfully. It should look like this when your done:

        static char* asciiart = "\n"
        "  _____                   \n"
         "|  __ \                  \n"
         "| |__) |___   __ _ _ __  \n"
         "|  _  // _ \ / _` | '_ \ \n"
         "| | \ \ (_) | (_| | | | |\n"
         "|_|  \_\___/ \__,_|_| |_|\n\n";
        static char* asciitail =
        	"              ROAN'S XeLL RELOADED - Xenon Linux Loader\n\n";

Once your done, click on Commit changes… You can leave the Commit message and description unchanged if you don’t want to change it. Make sure Commit directly to the master branch is selected. Once it’s saved, that’s it. You have changed the XELL RELOADED logo.

<img src="https://i.imgur.com/dKu1MiC.png" alt="create fork button" width="600">             

## Step 3: Changing the Background/Text Color

If you want to have a different background and text color instead of the default white text on blue, go to source, lvl2, and open and edit main.c file. You want to scroll down until you see the themes. You want to edit the “DEFAULT_THEME” as it’s the selected theme that it will already be using. Under “console_set_colors”, change the name of the color to whatever you want. For me, I’m going to choose white text on green background. So I would only need to change the first “CONSOLE_COLOR_BLUE” to “CONSOLE_COLOR_GREEN” for it to change the background color to green. The second one is the text color which I’ll leave unchanged as it’s already set to white.

<img src="https://i.imgur.com/7SDyAZu.png" alt="create fork button" width="600">   

## Bonus:

If you want your Xell to print out something different under the motherboard revision, scroll down until you see “xenon_get_console_type”. From there, you can have it say something different for each motherboard revision that comes up on Xell when you get your keys. I’ll leave this unchanged for myself, but want to point this out for those who want to edit it for fun.

<img src="https://i.imgur.com/XixdTUA.png" alt="create fork button" width="600"> 

Once your finished, click on Commit changes… You can leave the Commit message and description unchanged if you don’t want to change it. Make sure Commit directly to the master branch is selected. Once it’s saved, that’s it. You have changed the background and text color for Xell.

## Step 4: Building your custom Xell Reloaded

Once your done editing your Xell to your liking, it’s time to build it. Go to the Actions tab. If you get the Get started with GitHub Actions screen, just skip it and set up a workflow yourself. On the edit screen, rename the main.yml file to “build.yml”. Next we need to put down the required code for it to build our Xell. I have already put the code here so all you need to do is copy and paste it.

Credit to Cheez for making the workflow code. This one has the actions updated to use the latest version for checkout and artifacts (v4 instead of v2) and has workflow_dispatch.

    name: build
 
    on: [push, pull_request, workflow_dispatch]
 
    jobs:
      build:
        runs-on: ubuntu-latest
        container: npmaile/libxenon-builder:latest
 
        steps:
        - uses: actions/checkout@v4
          with:
            fetch-depth: 0
        - name: Export variables
          run: |
            echo DEVKITXENON=/usr/local/xenon >> $GITHUB_ENV
            echo /usr/local/xenon/bin >> $GITHUB_PATH
            echo /usr/local/xenon/usr/bin >> $GITHUB_PATH
        - name: Build
          run: make
        - name: Build (dist)
          run: make dist
        - uses: actions/upload-artifact@v4
          with:
            name: XeLL-binaries
            path: XeLL_Reloaded-2stages-*.tar.gz      





Click on Commit changes… You can leave the Commit message and description unchanged if you don’t want to change it. Make sure Commit directly to the master branch is selected.

Once it’s done, you should see your build.yml file uploaded to your xell-reloaded through the workflows folder. Next we need to go back to Actions. If everything went successful, you should see a green checkmark on your build.yml workflow run that we just did. Open up the build.yml workflow and you should see an Artifact called “XeLL-binaries”. This is your Xell build with the .bin files, download it. We’re all done with using GitHub.

<img src="https://i.imgur.com/KyMISA9.png" alt="create fork button" width="600">
<img src="https://i.imgur.com/7lubZTE.png" alt="create fork button" width="600">
<img src="https://i.imgur.com/EIuX9nt.png" alt="create fork button" width="600">
<img src="https://i.imgur.com/rHfBvjJ.png" alt="create fork button" width="600">


## Step 5: Applying Xell to J-Runner & Flashing it

Extract your XeLL-binaries.zip file that you downloaded. There will be another file called XeLL_Reloaded-2stages-.tar.gz, extract that too. You should then see your xell.bin files, this is your Xell build that we need to apply to your RGH through J-Runner. Go to your J-Runner with Extras folder, xeBuild, and the data folder. Move all of your xell.bin files from XeLL-binaries into the data folder. If it asks if you want to replace the .bin files with the same name, say yes to all. You should then have your xell .bins files in the data folder. You now have your customized Xell into J-Runner.

<img src="https://i.imgur.com/83Iv6rx.png" alt="create fork button" width="600">
<img src="https://i.imgur.com/RbbZbav.png" alt="create fork button" width="600">


All that’s left is to flash it to your RGH. Nothing special you need to do here, simply just dump your nand, re-create your XeBuild image, and flash it. Once it’s flashed, boot up Xell as usual with the disc eject button, and your customized Xell Reloaded will come up.

And that’s it, you just made your own custom Xell with your own logo and color.

<img src="https://i.imgur.com/YRKAfZl.jpeg" alt="create fork button" width="600">

Hope this guide helps. If there’s something incorrect in the guide, let me know and I’ll update it. Thanks for reading! :)

# -Roan
