# pr.ofile.me

**A simple toolkit for creating digital, mobile optimised business cards.**

## Attribution and donations

pr.ofile.me is, as with all of my projects, totally free for people to download
and use. A requirement of pr.ofile.me is that you must maintain a visible
attribution link in the page.

If you would like to remove this link then please consider
**[purchasing pr.ofile.me via Gumroad for $3.99](http://gum.co/VqTV)**.

If you don’t mind the attribution link then feel free to download the project as
normal and get started!

### Try before you buy

If you want to use pr.ofile.me before deciding to donate then you can just
download the project files as usual and then retrospectively
[make a purchase through Gumroad](http://gum.co/VqTV) once you’re happy with
things.

## Demo

My demo card can be found at
[hry.rbrts.me/profile](http://hry.rbrts.me/profile/index.html)

## Installation and usage

Creating your own card couldn’t be easier; simply download pr.ofile.me and start
tinkering!

The app is built on [the inuit.css framework](http://inuitcss.com) and is put
together in four stages:

1. Firstly we have `_vars.scss` which we update to reflect our desired values.
2. Then we include inuit.css, comment out any unused includes.
3. Next up we have `_card.scss` which sorts out basic functionality.
4. Lastly we have our theme stylesheet which is where you do most of your work.

You will only need to edit `/css/_vars.scss` and `/css/pr.ofile.me/_theme.scss`.
[inuit.css](http://inuitcss.com) and `/css/pr.ofile.me/_card.scss` will take
care of the rest and shouldn’t need touching at all (except to comment out any
unused objects and abstractions in the inuit.css framework).

The HTML is entirely up to you; fill your card with whatever you wish using code
from the inuit.css framework and stuff of your own.

### Avatars

pr.ofile.me uses a single 128x128 PNG image for your avatar, favicon and Home
Screen icon. This gives us both performance and maintainability benefits but
does mean your avatar needs to be suited to the PNG format.

## Deployment

It is **imperative** that you only release a minified version of the CSS. The
demo site compresses and gzips to less than 2kB, the non-minified file is over
23kB.

## Using your card

Upload your card to a directory on your site (e.g. foo.com/profile) and navigate
to that URL on your phone. From here you can add your (and others’) card to your
Home Screen for fast, chromeless access to your information. To turn your
business card over simply rotate your phone.

---

## Donors

These lovely people have [donated to pr.ofile.me](http://gum.co/VqTV), why not
view their cards?

* **Name:** _Profile URL_