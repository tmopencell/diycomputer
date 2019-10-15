# Make your own computer:

This is a project where you will make your own computer and learn the basics of coding! It is intended for people who have never coded before but could still have some interesting bits for people who like low-cost DIY computer projects.
This is the accompanying notes for a lecture course given at the RCA 23rd October 2019. However, I wrote it so that anyone can use it! Please give feedback so we can imprve the course! 

It is broken into 3 main chapters:

1. [BUILD](https://github.com/tmopencell/diycomputer#build)
    - a. DIY Version
    - b. PI-Top (Laptop) Version
    - c. Cheap Laptop Version
2. [OPERATING SYSTEMS](https://github.com/tmopencell/diycomputer#operating-systems)

3. [INTRO TO CODING](https://github.com/tmopencell/diycomputer#intro-to-coding)

4. [COOL PROJECT IDEAS](https://github.com/tmopencell/diycomputer#cool-project-ideas)

## 1. BUILD
This section describes how you can build a very cheap computer. By "_computer_" we mean a machine with a monitor and keyboard for interaction. Three options are available. The DIY version described here is the reason we wrote this course so it is our recommended version! It is very cheap and will create a very useful hackable computer.  

### 1. a. DIY Version (under £200)
This is why we created this tutorial since there was no DIY project online for building a portable computer that you could use like a computer/laptop. But it is possible and very cheap! You just need to buy about 7 parts and you are ready to go.

**LAZY? PARTS LIST: [CLICK HERE (UK SHOPPERS) for amazon prime list](http://amzn.eu/8gzaK4K)**

**Full list of parts:**
This list gives you the details about each item and why it was chosen and what to look for if you want to replace it with something different. While the goal was to keep the cost as low as possible we didn't just choose the cheapest item but rather the best based on a balance of performance/price. 

* [Touch Screen Display](https://www.amazon.co.uk/Raspberry-Pi-7-Inch-Screen-Display/dp/B014WKCFR4/ref=sr_1_4?keywords=smartpi+touch&qid=1570984115&sr=8-4)
This is the screen (about 7 inches) for interacting with the computer

* [Touchscreen and Computer Housing](https://www.amazon.co.uk/gp/product/B01HV97F64/ref=ox_sc_act_title_6?smid=A337FVOX35P1H8&psc=1)
This is the housing for the touchscreen and on the back the computer location

* [Raspberry Pi 3 Model B+](https://www.amazon.co.uk/gp/product/B07BDR5PDW/ref=ox_sc_act_title_2?smid=A1TGP1G2G7H27C&psc=1)
The actual computer. It is a credit card sized computer that was designed in Cambridge about 10 years ago. Depite being less than £40 it is still pretty nifty and we will make good use of it. 

* [microSD card](https://www.amazon.co.uk/gp/product/B06XFZV9JY/ref=ox_sc_act_title_1?smid=A3P5ROKL5A1OLE&psc=1)
This is the storage (memory) for the computer. It is where all the files and programs are stored. This one is pretty good, it has 64gb of memory which is fine but the read/write speed is impressive at about 100mb/sec. Basically the higher this number the better. 

* [Keyboard](https://www.amazon.co.uk/gp/product/B01G6XGLQQ/ref=ox_sc_act_title_5?smid=A2CBW8FNZCDSJI&psc=1)
You can use almost any keyboard. This one was cute and small wireless model and has a built in trackpad mouse which seemed convenient. Amazon also has the amazon basic range and that would be a good option too. 

* [MicroUSB power plug](https://www.amazon.co.uk/gp/product/B07FR9L4RC/ref=ox_sc_act_title_4?smid=A1FRA7QRK2Q428&psc=1)
This one is **5V** can deliver up to **3.0 A** meaning your computer, or battery will have plenty of juice (and is regulated meaning device will only draw as much current as they need). 

* [Battery (optional but good to have)](https://www.amazon.co.uk/gp/product/B075M9LXNY/ref=ox_sc_act_title_3?smid=A1BGBH9ECNVD5F&psc=1)
This is perfect if you want to make the device portable. You ideally want something with lots of energy and the units **mAh** indicates how much it has and a bigger number the better. This battery can deliver 24800 **mA** each hour **h**, this should mean that the computer can last 1-2 hours on a full charge! 

**Assembly Instructions**

Pictures and details to follow! Probably after the lecture on 23rd October... 

Once assembled skip to [this section](https://github.com/tmopencell/diycomputer#raspbian) to read about software installation.

**Other resources**

Here are some [different style cases](https://tutorials-raspberrypi.com/raspberry-pi-3-cases-2b/) for the screen and the computer.

Cool guide on how to [build a tablet (Adafruit)](https://learn.adafruit.com/7-portable-raspberry-pi-multitouch-tablet/overview).

Other [handy touchsreen cases](https://averagemaker.com/2016/05/touchscreen-display-case-options.html).

A [raspi touchscreencase from pihut](https://thepihut.com/products/raspberry-pi-official-7-touchscreen-case).

### 1. b. PI-Top (Laptop) Version (under £300)

This is a laptop built using a Raspberry Pi and is very cool! It is a little more expensive and you can choose from two different options. I just bought the V1 (cheaper model) and update this once I have had a chance to build it. There is a comparison sheet [Pitop V1 vs Pitop V2:](https://docs-emea.rs-online.com/webdocs/15ea/0900766b815ea49b.pdf) that explains the differences in more detail. Basically the V1 is cheaper, few less features and is a bit more fiddly to assemble.

* [Pitop V1 DEVELOPMENT kit @ RSComponents](https://uk.rs-online.com/web/p/processor-microcontroller-development-kits/9176213/) **£229**
You can pick up this kit quite cheaply and it is worth checking the manual [Pitop V1 Manual:](https://docs-emea.rs-online.com/webdocs/1561/0900766b81561abb.pdf) it looks like it will take a little time to assemble. It was slightly unclear from the website exactly what is included. 

* [Pitop V2 DEVELOPMENT kit @ RSComponents](https://uk.rs-online.com/web/p/processor-microcontroller-development-kits/1469335/) **£265**
The new version has a rail where you can plug in additional expansion packs like a sound board etc. 

**Assembly Instructions**

Follow the instructions in [Pitop V1 Manual:](https://docs-emea.rs-online.com/webdocs/1561/0900766b81561abb.pdf). I have not built it yet,  so will update once I have. 

Once you have assembled skip to [this section](https://github.com/tmopencell/diycomputer#pitop-os) for software installation instructions. 

### 1. c. Cheap Laptop Version (between £100 - £500)

Building your own computer is a good experience and is not too expensive either. But, another option is to buy a really cheap laptop. There are a few out there that are worth noting. 

**Ultra cheap:**

* [Pink Mini Laptop](https://www.amazon.co.uk/dp/B006HDQE9U/ref=psdc_429886031_t2_B07X39YFY8)
**£65** 0.5gb ram with VIA processor (which I had never heard of before this) and runs android. No idea if it runs Linux 
**NOTE** I bought this since it was the cheapest machine I could find. Will update with a review. 

* [BIGMAC 10 Inch](https://www.amazon.co.uk/BIGMAC-Computer-Android-Notebook-Netbook/dp/B07X39YFY8/ref=sr_1_13?keywords=laptop&qid=1570990690&sr=8-13&th=1)
**£112** 1gb ram with an ARM quad core (*not intel*) processor and runs android (like a cell phone). No idea if this will run Linux but if it does it would be very handy.  But it does come in pink!

* [Pinebook 64](https://store.pine64.org/?product=11-6-pinebook)
**$99** 2gb ram with an ARM quad core processor and is built for linux. It says out of stock and not sure what shipping costs (or speeds) to UK would be. 

* [ASUS Chromebook](https://www.amazon.co.uk/ASUS-Chromebook-C223NA-GJ0014-Notebook-Processor/dp/B07HJHMCX2/ref=sr_1_fkmr0_1?keywords=ASUS+F556UA-EB71+Notebook+15.6%22+FHD%2C+Intel+Dual-Core+i7+8GB+DDR3+1TB+Windows+10%2C+Dark+Blue&linkCode=gs3&qid=1570992354&s=computers&sr=1-1-fkmr0)
**£170** 4gb ram wth an Intel dual core processor and used (and [recommended](https://portableobserver.com/best-cheap-laptop-for-linux/) by) lots of Linux users. 

**Affordable:**

* [Linux compatible and affordable:](https://starlabs.systems/pages/star-labtop-compare)
This is designed and build for linux flavoured operating systems. I have not used it but at ~ £500 it is pretty good value. 

## 2. OPERATING SYSTEMS
Once you have the computer you will need to put an operating system on it to be able to run programs and go online. We will not be using any Microsoft products like Windows but instead will rely on _opensource_ Liunx based system. 

### Raspbian
This is the go-to way to get started for the DIY computer build (version [1. a.](https://github.com/tmopencell/diycomputer#1-a-diy-version-under-200) above). You head over to the Raspberry Pi official website [downloads section](https://www.raspberrypi.org/downloads/raspbian/) and download the zip file for Raspbian Buster with desktop and recommended software. They have an [install guide](https://www.raspberrypi.org/documentation/installation/installing-images/README.md)

### Pitop OS
If you built the Pi-Top Laptop (version [1. b.](https://github.com/tmopencell/diycomputer#1-b-pi-top-laptop-version-under-300) above) then also has its own operating system. It is very similar and based on raspbian.

You can choose which version on their [downloads](https://www.pi-top.com/products/os) page and follow their [installation instructions](https://blog.pi-top.com/2016/10/13/how-to-install-pi-topos-to-a-microsd-card).

### Kali Linux
If you want to be a hacker then this is your go to option. It comes preloaded with a ton of **pentesting** software. Tools for hacking wifi and bluetooth and more. Watch [Mr. Robot](https://en.wikipedia.org/wiki/Mr._Robot) and you will see them use this ALLLLL the time. 

There is a special version built for the Raspberry Pi but in general expect lots of issues.. It is built for hackers and it's always very buggy. [Visit the Kali instruction/download page](https://docs.kali.org/kali-on-arm/install-kali-linux-arm-raspberry-pi).

If you just want to give it a try you can use your own laptop and a [**bootable USB**](https://docs.kali.org/downloading/kali-linux-live-usb-install) is your best option ([for mac installers](https://gist.github.com/widdowquinn/90eecc3a9a52ceb997a1715894df1cc3)). This turns your usb into a little hard drive and while booting your system you can select the usb installed operating system. 

### Other flavours and build your own!

Raspbian is a flovour of Linux and is completely **opensource**. You can modify or build a version from scratch. The Raspberry Pi was invented in the Cambridge Computer Science department and their website still has some [great documentation and resources](https://www.cl.cam.ac.uk/projects/raspberrypi/)! In particular it has a tutorial on [building an operating system from scratch](https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/os/). I have never done that one but I think if you did it would teach you a lot!

## 3. INTRO TO CODING

### The Toolkit
Github, Terminal and Sublime Text

**Github**
Something that is very useful if you plan to start coding is a github profile. Well, you don't actually need a profile but if you have one it can be a convenient place to share your projects. 

* Step 1 - [Join](https://github.com/join)
Sign up like you would for any webpage with a username and a password. You will likely have to verify your email as well.

* Step 2 - Create your first respository. There should be a button that you click on. 

* Step 3 - Label your repository name as <your username>.github.io. Give it a description "_My Webpage_". Initialize with a readme.md

* Step 4 - Click on settings and scroll down to  **Github Pages** and click on use **theme** button. Then copy your repository name (It will be <your username>.github.io) and paste it into a new tabe and your will see your first webpage! 

* Step 5 - Git at the command line:

    - `git clone https://github.com/<your username>/<your repository name>.git`

    - nano index.md
    - `git add *`
    
    - `git commit -m "my first commit"`

    - `git push origin master`

    - You made your first local change and pushed it to the online repository!

    - Markdown introduction

    - `open -a Sublime Text 2 ` 
* Step 6 - (optional) Customise your webpage! Skip to [Build a webpage section](https://github.com/tmopencell/diycomputer#build-a-website).
    
    - 
**Terminal**
A terminal is your "_command line interface_" and is you link to the under the hood of your computer. If you are using a Raspberry Pi then all you need to do is to select the terminal from the drop down menu in the right corner! If you are a mac user then you can type **cmd** + **space** and then type **terminal** and the default terminal will open. Using Windows? God help you.. Go elsewhere, this tutorial is not for you. **NOTE** for mac users you can install [**iterm2**](https://iterm2.com/) which is a nice alternative to the not so nice built-in terminal.

**Sublime Text 2**
If you want to be lazy and write code then [Sublime Text 2](https://www.sublimetext.com/2) is your friend. It will have different colours for different commands and auto fill stuff out for you. Complete laziness. 

You need to edit your .bash_profile in order to use subl at the cmd line!!

and source ~/.bash_profile

### *Bash* 5 commands is all you need to get started!
Seriously, 5 commands will get you VERY far in coding. Open a Terminal and getting a feel of what is happening and start playing. 

**Navigation** 
Getting to grips with the basics of coding starts with a little navigation. Once you open your terminal you will be in the "_home directory_". This just means that you are in your main folder. All your files live here, things like your programs, documents etc.  

1. `sudo` is the master command. It grants you "_superuser priviledges_" meaning you can have "_root_" access when you use it. If this doesn't make sense right away don't worry, it will soon.   

2. `ls` means "_list current directory_". When you type it it will print all the files and folders that are present in the folder you are currently in.  

3. `cd` means "_change directory_". If you type ls and you see a folder that you would like to enter then type `cd <insertfoldername>` and you will enter that folder. Tired of that folder? You can type `cd` and it brings you back to your home directory or `cd ..` to move up one directory.

4. `mkdir` "_creates a new directory_" (or folder). Say you decide you want to creat a new folder called "_myprojects_", you would just type `mkdir myprojects`. The type `ls` and you will see your new folder listed. You can then type `cd myprojects` and you will enter your new folder.

5. `nano` "_a file editor_". `Nano` allows you to edit files or "_scripts_" and this is one of the ways you will create your first program. Type `nano helloworld.sh` and you will be brough to a blank screen. Now type `echo "Hello World!"` and then type the **ctrl** and **x** button on your keyboard at the same time. It will ask "do you want to save (y/n)" and type **y** and **enter** (the return key). Now you are back to the command line! type `ls` and you should see your first program "_helloworld.sh" sitting there! If you then type `chmod +x helloworld.sh` you file will now be "_executable_" meaning  you can run it like any other program. Now type `./helloworld.sh` and you should see the statement `Hello World!` appear on your terminal! This sounds very simple, but it is the routine way to start when learning a new language or even just tring to make sure your code is running. Well done! 

### Python 
Python is great. Everybody uses python and that means so much has already been tried. It makes it ideal for beginners and lazy copy/paste programmers. 

### Git
I hate git. I have never really understood it and I exclusively copy and paste the essential commands from the web. But, you do need it for getting repositories from github and to keep your repositories up to date with your profile...  

This is the [intro](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners) I would recommend.

### Real programming: copy, paste and debug.

I forget everything all the time. I just try to remember how to quickly and conveniently find the answers. For example, using github can be fiddly. I often forget exactly how to `push` a change or `pull` the most recent version of a repository. Just googling "_How to pull most rcent version of a repo_" and clicking the first or second hit is all it takes. 

This goes for everything. In general before you even try to write a script, go ahead and google it to see if someone has already written it and you could copy/paste. This is as fast (or usually faster) than being an awesome programmer. You can *hack* code together this way and it gets you surprisingly far. 

The other best resource on the web is [StackOverflow](https://www.stackoverflow.com). Here you will find people asking questions they are having with writing a piece of code. About 90% of the time if you are having a problem writing a piece of code then someone else has already had that problem. So, you get an error? Perfect, copy and paste it into google. Usually, the first hit will be stack overflow and very often the first answer will solve your problem.

Don't be ashamed of using these techniques! Coders rarely type super fast and look like Mr. Robot. The dirty truth is they sit around most of the day scratching their heads to find out why their software won't run. So copy, paste and debug.   

## 4. COOL PROJECT IDEAS

### Build a website
You can buid a github webpage free and easily as described above but you could also host your own webpage! Read on.. 

```
Coming Soon..
```

### Build a game
Minecraft is a very simple (but additictive) game and you can use a [Raspberry Pi to program your own game](https://www.minecraft.net/en-us/edition/pi/)! 
