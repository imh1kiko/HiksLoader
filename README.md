# HiksLoader
Loads stuff for Discord.

Currently loads:
* Zerthox ClearVision
* Zerebos RadialStatus
* Some custom styles

(PS. Don't have those guys permission. Sorry, guys! You still own all the permissions and rights. When you want it removed, you got it done.)

# Variables!
To be honest, I've created and tested so many of them, I'm prolly forgetting some or adding wrong ones.
Do keep in mind, these go into "Custom CSS" section in BetterDiscord. Also, between :root {}

> --main-color: rgba(x,x,x,x);

This color paints most of your discord. This is core part of ClearVision, and I take no credit for it!

> --hover-color: rgba();

This is ClearVision's hover!

> --voiceColor: rgba();

Changes to color of voice indicator when speaking.

## The italic text
For us, we use it for _actions_, but you can use it for anything else.
To construct the variable, you start with `--i`, and follow up with these:

> -f: "Font here";

The usable fonts are: "Caveat", "Bad Script", "Sacramento", "Satisfy", "Shadows Into Light", "Dancing Script", "Crafty Girls", "Over the Rainbow", "Lakky Reddy" and "Mr Bedfort".
If you fork it, you can always just add your own fonts to it (into STBL, and using @import).

> -gf: "":

This is "generic family". It's not exactly required, but you can read up [here](https://www.w3schools.com/cssref/pr_font_font-family.asp).

> -size: "";

Self-explanatory. The size of the text.

> -pad: "";

If you run into problems with fonts behaving differently, you can fix it through this... hopefully.  :pray:

> -color: rgba(x,x,x,x);

It honestly doesn't matter what you use it here, be it hsl(a), rgb(a), hex or whatever. Text has currently no animations to it, thus, nothing to worry about.

## More useless stuff?
> --Roundificator: N px;

An addition from Yuks. Rounds out image corners.

## More or less deprecated, but still there...
> --z-background: url();

Allows the addition of background, if you don't like transparency or default. This was achieved by butchering some of ClearVision's perfect code. Rest in bits.

> --z-effects: filters;

This further allows you to change the background through [CSS filters](https://developer.mozilla.org/en-US/docs/Web/CSS/filter).

> --z-shadow: inset box-shadow;

And even more...
Either way, this utilizes [box shadow](https://www.w3schools.com/cssref/css3_pr_box-shadow.asp) inset, to create a vignette. This was used when transparency wasn't a thing, to make the backgrounds blend in better. 

### Remnants from Dev branch

As we used bold for spoilers, now that we have proper spoilers, it became useless, so i'm bringing it back as a secondary "italic". I've split this into two segments: **un** and **bText**.
If you read the italic segment, you know how to use these too. Do keep in mind, there is currently no padding for them.

# Warning!

If you use it on big servers, you are so gonna get slapped with higher CPU, due to animations. This is **_NOT_** to be used on big servers. This is just for me and SO.
