# Warning
<b>We are not responsible if your account gets banned for spammy activities, such as sending lots of messages to people you don’t know, sending messages very quickly, sending spammy looking URLs, logging in and out very quickly… Be responsible Facebook citizens.</b>

# Features
<ul style="list-style-type:circle;">
<li>Option for specific reply to specific or near specific messages.</li>
<li>Replies a specific message to every recipient whose messages aren't understood by the bot.</li>
<li>If anyone messages you twice which is not understood by bot, then secondary message system is available.</li>
<li>If primary and secondary messages are sent once to a recipient, then bot will not reply to the messages of the recipient anymore in an active session, but will reply to the messages which are recognised by the bot.</li>
<li>Waits for a random number (between 4 to 10) of seconds before sending every message to act as a human, to minimize the chance of getting blocked from Facebook.</li> 
<li>Avoids group messages.</li>
<li>Blacklist option available if you want the bot not to respond to specific users.</li>
</ul>

# Getting Started At A Glance
After cloning this repository, edit the <b>msg1.txt</b>, <b>msg2.txt</b>, <b>received.txt</b>, <b>reply.txt</b> and <b>blacklist.txt</b> files following the instructions written in them. Don't try to run the program without editing these files. You are definately gonna get error messages. Then, installed required modules from <b>pip3</b> following the instructions below. Finally, run the <b>run.py</b> program, type your credentials when asked and you're good to go.

# Installation
Make sure you have installed python3 in your machine. You can also use python2 by converting the whole code.
Then:
<ol>
<li>Install fbchat module: <code>pip3 install fbchat pygtail getpass --user</code></li>
<li>Clone this repository: <code>git clone https://github.com/MS-Jahan/fb-auto-reply-py</code></li>
<li>Change directory to this project folder: <code>cd fb-auto-reply-py</code></li>
<li>Edit the <b>msg1.txt</b>, <b>msg2.txt</b>, <b>received.txt</b>, <b>reply.txt</b> and <b>blacklist.txt</b> files following the instructions written in them.
<li>Now run the script: <code>python3 run.py</code></li>
<li>Type your email and password when asked. Password will not be visible when typing. (You will not need to type your credentials next time if you don't change your password or log out from session )</li>
<li>Now your bot is running!</li>
</ol>

# Credits
The main core of this project is the <b><a href = 'https://github.com/carpedm20/fbchat'>fbchat</a></b> module. Without the module, it would be a very difficult task.
I just read their <a href = 'https://fbchat.readthedocs.io/en/master/'>doc</a> and copied their <a href = 'https://github.com/carpedm20/fbchat/tree/master/examples'>example code</a> and modified it for beginner users. ;-)
