
Anon

Anon is a localized Command line password and user manager with the ability to add, edit, and delete information on multiple accounts. With a Profile Wizard optimized for
compatibility with most common security questions. All information is stored in JSON Text format in the working directory with a built in 64 bit encryption and decryption tool.


Backstory
There's not much of a back story other than need for having a localized way of storing my passwords. I Had an awfully bad habit of using close to the same password for multiple accounts online for years (Neopets RIP) which I since remedied, but still needed a way to keep that information. There's a large part of this program that's designed around multiple accounts or profiles for multiple personalities to further enable anonymity with securing and managing your online accounts.

How it was made
I made this Project in Python using and certainly improving on some of my own ideas in menu based CLI interfaces from earlier projects. When it came down to encryption I struggled somewhat in finding a way to make this work learning a how  it works bare bones was a bit more daunting than first anticipated. I ended up using two excerpts I found somewhere which worked well enough for me to write around and edit. Hilariously i've stored the whole program an a 3.5inch floppy to better thwart any 3 letter agencies snooping. And having that mechinal feel of floppies still feels so good to this day.

How To Use Anon
After downloading the source, execute the “Anon.py” file. You'll want to make sure that “Anon.py” is in its own empty folder, this will be important later when it come to encryption. When first starting the program you'll be prompted with the main menu screen or Home Screen with the “ANON” banner displayed overhead. Below will be the Home menu title along with blue text displaying all working profiles in the current working directory, if you’ve placed the program in an empty folder you should see nothing. Under the working Profiles which are not yet listed you should see a list of options along with instruction on how to access each option.

Options:
1. Make new Profile
2. Profile Encryption/Decryption options
3. Exit
Type a number of an option, or type the of name of a profile view or edit that profile
The profile must not be encrypted to view.
Enter choice:


Making a New Profile:
To start to make your first profile either type new or enter in “1” and press enter. You'll be prompted with the Profile Wizard. The option to enter in your own information or have an answer automatically filled is controlled  by leaving the prompt field blank or not. The program will then continue to ask you personal details and common information for top security questions.
Example:
----------Create Profile
Welcome to the Profile Wizard!
Create a new profile by entering info followed by the Enter key or
or just press Enter at any question for a random answer.
Name:
Andy
Sex:
female
FavoriteBook:
Catcher in the Rye
MothersMaiden:
King
HighSchoolMascot:

Etc...

Once you’ve entered all the information for each questions, you'll be brought back to the home page and you should see a new file named whatever name you choose.txt so for the example above it would be Andy.txt


Adding information and website accounts to your profile:
To add information to our just created profile Andy.txt all we have to do is type Andy in the home screen. This works for all profiles in the working directory ie, for Duncan.txt you type “Duncan” and press Enter. Here after entering the profile we want to use we see the Browse Profile screen. You should see all the information that you or the program already enter in the profile wizard. Below that, is a prompt for your choice and a list of options, leaving the prompt empty and pressing enter will take you back to the home screen. 

Viewing Entries and information:

To view information of and entry just type the name of that entry which will be in a lighter blue.For example enter “HomeTown” to view your hometown.

Adding and editing Entries and information:

To add a new Entry type “new” this will bring up the Edit Entry screen where a random password if you need will be generated at the top of the page. Below in light blue you will see a list of all the Entry titles. Let's add one by entering a new field lets say “Email” type in Email and press enter. You'll then be prompted to enter all the info regarding that email. So lets say UserName: AndyOnline Password: 1234(you can virtually put whatever you want here). Press enter and you should see the the main Profile screen with your new entry and its data next to it at the bottom of the list of Entries. To edit and existing Entry type new then in the Edit Entry screen type in the name of that entry. Whatever you write will replace what was written before so be carefull. Press enter to seal the deal.

Deleting Entries:
In the Browse Profile screen type “del” followed by pressing enter to be taken to the Delete Entry Page. On this page you will see a list of all entries under the profile your working with. Type the name of the entry you want to delete then hit enter. THE INFORMATION WILL IMMEDIATELY BE DELETED so be carefull.

Encryption/Decryption
Now we get to the fun part, the encryption used for this is 64 bit so it's not the most secure but it is something. From the Home screen enter “2” to navigate to the Encryption Options screen. Here you should see a list of all working profiles in your current working directory, simalar to the the way you see them on the home screen. By default and for safety all other files in directory that are not encrypted will be when the encryption option is chosen. To encrypt our files we enter the “E” (for encryption (duh)) or leave blank to return home. You'll be prompted for a password twice to make sure it matches. Once confirmed all files not already encrypted in the working directory will be encrypted with said password. To Decrypt type “D” instead and enter the password followed by the name of the file you want to decrypt, for example the file name used would be “(encrypted)andy.txt” when you return you should see andy.txt shown without the (encrypted) prefix attached.




Known Bugs
If file is decrypted with wrong password file becomes unusable

Points for improvement:
I'd like to increase the encryption strength for obvious reasons. As Well as the known bug above. Perhaps add some functionality with web browsers

Programed By:
Duncan Andrews
2018
For my Dad because well he's the best.

Links:
https://github.com/DuncDude/Anon
www.Sublimate.blog
www.dalliance.site


https://twitter.com/SpongeBotNews

