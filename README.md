# Bropiler
[IGP](https://discord.gg/qGqCEWJrpm)'s compiler.
# Commands
yeah im lazy to document this, use the help menu
# FAQ
> Is this obfuscated?

Depends what "obfuscated" means for you.
Is it obfucated *intentionally*? **No**. That's just how I write code ;)

> How can i contribute?

open a pull request ig lol, and dont format the code too much

> Who all was making this?

Me, me and me. Nobody else really knows the raw api *and* python :(
The ideas? igp people. 

> How did this start?

Basically, the Compiler bot had some issues with nodejs. It got fixed by duro like 2 days later, but by that time I and imagine had already decided to make a custom compiler.
How did i get the idea to use raw api? My first wandbox tests were in python, and i wrote the first two important one-liners for getting the lang and compiling it. Converting it into js seemed kinda meh and so i said, lets make this bad boi in raw api! and so the challenge begun.
Over the time, `;compile` (and `;languages`) streched onto `;template`, sourcebin integrations, ai (`;fix`), and much more.

I've learned a lot through this, and I'm really happy for it lol

> Any associations with Sispiler?

Ah yes, my boy Jade. That lil boi has forked like everything igp has made, and since I didn't release the code, he made it on his own :) I never gave any code, ive never copied any code, so it's two entirely different projects.

> anything else?

mention me in igp for answering! ill be on as i dont have a life

# Installation
So, you want to have Bropiler for your own? Sure!
## Installing packages
To install the required packages, type
```bash
pip install requests websocket-client rel
```
(Note: you need to have Python and pip installed.)
## Env stuff
I have no idea how dotenv works, but the pypi page probably has it explained. There's a `.env.example` file for seeing what a .env looks like

but basically, you need the `HTML_API_KEY` and `TOKEN` entries. The html thingy is for https://screenshotone.com and the token is the bot token lol

## Running the script
Fill in the environment variables or replace them with the values. Idk any dotenv stuff for python btw so google it if you want that
Then, do `python3 main.py` and it should work.
**ALSO**, the script will crash after a few hours. Idk why this happens, probably cuz of the ws randomly getting closed, too lazy to fix it. Just make it run again when stopping like i do. Example, my startup command is
```bash
while true; do python3 main.py; done;
```
If you wanna fix it yourself, good luck!
If it doesnt work, open an issue ig, idk lol
# Notes
- it crashes after a while, like already said (put it in a while true loop to fix)
- theres a shit ton of print logs, because when you code on your own, production also becomes development. I may remove it idk
- its *extremely* unoptimized, but if it works, it works. If you wanna optimize it, go ahead! No ones stopping ya :) 
# That should be it!
Have fun exploring the code. 

Also, *nothing* was generated using ai.

Sans
