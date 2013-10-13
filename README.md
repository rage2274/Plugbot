## plug.bot

A collection of extensions to the growing online DJing website, [plug.dj](http://plug.dj).  The source code is written in JavaScript and uses the Plug.dj API anywhere possible.  Easily embeddable as a bookmark in your favorite browser.  Initially inspired by TechGuard's AutoWoot script from April 2012.


### Features List ###

Feature | Purpose
--------|--------
Auto Woot | Automatically WOOT! each song as it is played
Auto Queue | Automatically add yourself back to the DJ Waitlist once you've been moved back into the crowd
Userlist | A dynamic list of every user in the room, color-coded by their current vote.  Green = "Woot", Red = "Meh", White = No vote  Special usergroups (i.e. moderator) are denoted by the icon you'd normally see in the chat
Toggle UI | Allows you to easily configure your Plug.bot experience;  enable or disable each of its features at the click of a button.  Red = Off, Green = On
Hide Video | Hides videos from view on the site -- this is in effect until disabled
Skip Video | This is exactly like hide video, except it additionally mutes the audio and will automatically re-enable everything after the current video is over



### Bugfixes ###

This is where I will map out any bug fixing, in other words small issue solving that doesn't equate to a full version change.  Started September 14, 2013.

Release Date | Change
-------------|--------
October 10, 2013 | <ul><li>Fixed broken link to JavaScript file for cookies feature, thanks MauriceS!</li></ul>
September 20, 2013 | <ul><li>Fixed userlist icons except for Featured DJ.  Sorry DJs :(</li></ul>
September 14, 2013 | <ul><li>Temporarily removed adding pictures to the userlist based on the user's permissions because I no longer have said pictures.  Looking to recover them or make new ones soon.</li><li>Minor tweaks in documentation.</li></ul>



### Installation ###

Drag the text from the link below (it will look like code) into your Bookmarks Bar and it should make a new bookmark.  You can label it yourself, it doesn't matter.  Then just click the bookmark whenever you're on Plug.dj and you're good to go.

Install [this bookmarklet](http://pastebin.com/raw.php?i=ywuQK2XA) in order to run Plug.bot.  If you have a problem with installing the bookmarklet, just Google it, there are plenty of solutions to be found.  DO NOT e-mail me about it.  The ONLY time the bookmark will ever not work is if Github is down, and that's pretty rare so don't be worried (it happened for less than 24 hours last year and then it was back to normal.)



### YouTube Video Install Guides ####

**English** - https://www.youtube.com/watch?v=ClpQDwl5GPg

**French (thanks Xbird!)** - https://www.youtube.com/watch?v=Sfa6bktNQrc



### Author ###

+ **Conner Davis &lt;connergdavis@gmail.com&gt;** *a.k.a. Fugitive.*  

If you knew me as Logic, you can feel free to get mad at them for taking my original name.



### Copyright Notice ###

plug.bot is licensed under the GNU General Public License, or GPL. Basically, what this means is that you're free to do what ever your heart desires with this code.  Please leave the header comments (the license, terms of reproduction use, and the @author statement) at the top of whatever variation of the code you create, so people know a) the license and b) that I'm the original author.  That's all.  Thanks for playing fair & supporting free software!



### For any question that isn't "How do I install Plug.bot" ###

connergdavis@gmail.com

Seriously.  If you e-mail me about a problem installing Plug.bot, it's getting deleted without a second thought.  If you have a legitimate question about something related to the project, THAT'S something I'll read. 



### Version History ###


Version | Release Date | Changes
--------|--------------|--------
1.3 | October 13, 2013 | <ul><li>Renamed Plug.bot to plug.bot</li><li>Isolated underlying plug.bot code so there is now a loader, separate from the actual code, which will grab the latest plug.bot from git and then print success/fail to the chatbox</li><li>Fixed problem where userlist div is still drawn even when userlist hasn't been enabled on script startup</li><li>Finally decided on a consistent format with code readability.  I am so sorry</li><li>Did some overall code cleanup and made an effort to simplify & organize</li><li>Oh and I messed with the readme</li></ul>
1.2 | September 20, 2013 | <ul><li>DOGE MODE is now a thing! If you don't understand it then feel free to just ignore it by just hitting enter (prompt only checks for 'yes' and will otherwise totally ignore)</li></ul>
1.1 | March 21, 2013 | <ul><li>Added skip video, cappie01's idea</li><li>Cleaned up code consistency</li><li>Removed custom username FX (it was bad anyway)</li></ul>
1.0 | November 23, 2012 | <ul><li>Supports Plug.dj "Pepper", the newest version, introduces mostly rank changes</li><li>Revamped userlist code, faster and completely stable at this point</li><li>Userlist now allows you to @mention users by clicking their name, you can @mention multiple users as well</li><li>Over 1,000 users now!</li></ul>
0.5a | August 1, 2012 | <ul><li>Userlist font is smaller due to more users being in rooms, thanks Monstercat</li><li>Hide video now lasts until you disable it, rather than resetting each time a new song comes around</li><li>Moved the UI to be beside the chat for more space for buttons</li><li>Buttons are now HTML-generated instead of pictures</li><li>Custom username FX now allows you to highlight specific people with custom colors</li></ul>
0.4a | July 19, 2012 | <ul><li>Userlist has been re-styled!  It now looks much sleeker</li><li>Above the userlist is your current spot in the DJ waitlist, if you are in it.  This should make it easier to check instead of having to click the button and look for yourself</li><li>Removed external CSS dependency, fixes a lot of consistency problems</li></ul>
0.33a | July 12, 2012 | <ul><li>Userlist now recognizes moderators -- the color is changed, they're bold, and the little chat icon that denotes them is also on the userlist in the same spot</li><li>Patched a problem with moderators being the current DJ and the star being white</li><li>Patched the userlist still populating even when disabled</li></ul>
0.3a | July 6, 2012 | <ul><li>Woot/Meh Ratios nerfed, replaced with Userlist that properly updates and doesn't have ANY problems</li><li>Clean UI with pictures instead of HTML text</li></ul>
0.2a | June 29, 2012 | <ul><li>Introduced Woot/Meh Ratios List</li></ul>
0.1a | June 6, 2012 | <ul><li>Auto Woot introduced</li><li>Basic HTML UI</li><li>Auto Queue WIP</li></ul>
