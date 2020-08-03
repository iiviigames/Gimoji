# Gimoji


![](https://github.com/iiviigames/Gimoji/blob/master/img/moji_v1.gif)

I like to put an ~~emoji~~ at the front of every commit that I :pushpin: on Github.
> _See any repo I run for proof._

 I don't care what they are, I just like to do it, because the visual element is way better than any words can be. Descriptions are good to write, but not commit messages. They should just be **emojis**. :triumph:

Still, it's hard to actually :think: when I need them! :disappointed: 


This :shit: is :no_good: :exclamation:

---

**So I made a thing that will get you what you want, quick!**

Usage
----------------

```bash
python -m moji
```

That will produce **one random emoji from the entire list of emojis**! :snowman:, right?

_But if you add a number after_, **baby, now we're cooking with** :fire:

```bash
python -m moji 20
```
---

If you have `moji.py` saved in the user site-packages folder, this will work from anywhere.

Otherwise, you'll have to call it from the folder you've got it saved in. Open a terminal there, and just type

```bash
moji
```
> **NOTE**: _If you use the `emoji.bat` file included in this repo, and place it in a Shortcuts folder, or somewhere on the PATH, then you can even call this without `python -m`_

![](https://github.com/iiviigames/Gimoji/blob/master/img/emoji_bat.gif)

**But wait! There's more!**

```bash
python -m moji 30 -d
```
The `-d` is a debug flag, and will help you see how many emojis were output, and from which categories. More on the categories below.


Specific Emojis, Arguments, and Help
------------------------------------

```bash
python -m moji -h
```
will produce some assitance for you , like so:

![](https://raw.githubusercontent.com/iiviigames/Gimoji/master/img/moji_help.gif)


### Getting Emojis from specific Groups

These are the categories I have the emojis grouped into:

|Category |Command| Description           |
|---------|-------|-----------------------|
|All      |`-a`   |_everything_           |
|Emotes   |`-e`   |_people and emotions_  |
|Objects  |`-o`   |_nouns, ya know?_      |
|Nature   |`-n`   |_the great outdoors_   |
|Places   |`-p`   |_man made:shit:_       |
|Symbols  |`-s`   |_all the weird and miscellaneous_|

![](https://raw.githubusercontent.com/iiviigames/Gimoji/master/img/moji_categories.gif)


> NOTE: _Only one of those arguments can be used at a time, or it won't give you anything at all!_

### Getting the Group You want by Name

You can use the optional argumen `-m` to supply the name of the emoji set you'd like as well:

```bash
python -m moji -m nature 30
```
_which would give you 30 random emojis selected from the nature category!_


---


