## Two important things
To make a good ReadMe file you need to think about two important areas.
The first is the *content*, the other is the *presentation*.

The ReadMe is usually the first thing a visitor will see. It is partly as advertising, and your target audience is probably a casual browser who is looking for something interesting. Maybe a student. It must first help the reader to understand if she should read any further or not. Then she should understand that this is something to try. Then she should get all information about installing and using.

## Content
Project Title should be something that helps understand what it is or does. "Moesha experiment 2" is not a good title. "Dice game using JavaScript" is better.

### Screen Shots
Optional but can be cool, but don't overdo it. Create a folder like "media", "screenshots" or "docs" and put the pictures there.

### Description
What it does

Wy you made it

What Technology is used

When the reader has come here she should know that she really wants to install it and try it.

Using adjectives can be offensive; you should try to be non-biased and objective. "Easy" is ok but "fantastic" can be too subjective. We are not selling soap here, we are trying to convince a fellow engineer to test our work.

### Installation
Which libraries are required, what server is required. Any specific versions? (at least you can say "known to work with version X")
How do you download and install the SW. 

### Usage
How to use the SW. Again you can use screen shots.

### Credits
in case you have contributors they should be listed.

### Licence
If you use or modify something you probably have to use the same licence as the source and give them due credit. Typical for e.g. GPL.

If you write it all yourself you can chose what you want. I might chose the MIT Licence, or the WTF Public Lincence.

You can sometimes link to the licence document on internet, or you can have a Licence document in your repo and link to that, or you can put the text directy in the ReadMe. All licenses have advice on how to reference them.

You should include a copyright notice in the ReadMe even if the licence terms are in a linked document.

Example:

The MIT License (MIT)

Copyright (c) 2021 Bengt Månsson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

WTF :

Copyright (c) 2021 Bengt Månsson

0. You just DO WHAT THE FUCK YOU WANT TO.

(for full instruction read http://www.wtfpl.net/faq/)

## Presentation

GitHub uses markdown (.md) files. The markdown name is a joke for those who know markup like HTML. Server plug-ins convert .md to html on the fly.

It is easier for the non html savvy person to write good looking documents. It is almost just plain text and not so much cluttered with tags. On GitHub you alse get a TOC automatic.

You see how it is used in this document if you view the raw format. You see text and headers. Check the README.md in the same repo to see how to include pictures and hyperlinks.
(It took me some time to remember to put in all these extra blank lines.)

Google "[github markdown](https://letmegooglethat.com/?q=github+mardown)" and you will find some short descriptions as well as the full spec (which I haven't read). [Here](https://guides.github.com/features/mastering-markdown/) is a good start.

(Ha ha, that LMGTFY link is considered a bit rude and should not be used, unless you are really angry. Sorry for that.)

You can use html inside md. I have not tried that.

You can get syntax coloured code snippets with three backticks:
```javascript
var randomDiceImage = "images/dice" + randomNumber1 + ".png";
var image1 = document.querySelectorAll("img")[0];
image1.setAttribute("src", randomDiceImage);
```
or
```sh
sudo rm file.txt
```

If you have just one screenshot you may show it in the ReadMe directly. If you have many it can be better to show them in a screenshots.md, and link to that from the ReadMe.

It is probably good to only have the README.md in the top folder, and to put all lined files in a docs folder.


