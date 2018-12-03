---
layout: post
title: LS in Unicode [·⍼]
---

The first time I saw the [linking sigil](https://github.com/damienmaxwell/damienmaxwell.github.io/wiki/Ellis---LS---%C2%B7%E2%8D%BC), I was awestruck. My first thought was, _Holy frick, this is coolest piece of magickal tech since the [LBRP](https://en.wikipedia.org/wiki/Lesser_banishing_ritual_of_the_pentagram)!_ The immediate following thought was, _Alright, now how do I render this in Unicode so I can inject it all over the internet._ Yeah, I'm a **nerd**. Deal with it. 

So what is Unicode, and why am I so obsessed with drawing the linking sigil with it? Put simply, [Unicode](https://en.wikipedia.org/wiki/Unicode) is a standard way of rendering written text on a computer. The ultimate goal is to encode the entirety of Earth's writing systems, along with countless symbols, glyphs and emoji. Notably, Unicode also has [combining characters](https://en.wikipedia.org/wiki/Combining_character), which we will get into later. 

Which brings us back to **why?**

Because digital text is the medium of the internet. Images are cool, but they are comparatively large and unwieldy. They depend on some rendering system to convert the binary into pixels. However nearly every general computer system supports some sort of text-based shell. So in theory, anywhere you can get a shell, you can stick a linking sigil. Furthermore, since text is a string of bytes, we can use those bytes to further embed an LS in even more digital places. 

Now, we could just use the ascii "Ellis" or "LS", and I think in a lot of ways, just these written descriptors function as a "lite" sigil, but having something purely symbolic is important in sigil theory because symbols bypass the conscious filter. 

My general idea was to use a bunch of combining characters, which basically draw on top of other characters, i.e. for adding accents, along with assorted characters/symbols from the broader Unicode set (of which there are thousands), to get something "close enough" in appearance to the typical LS grapheme. Any visual differences between the grapheme and the unicode would not be an issue, by way of linking the two representations together. After all, the original LS was an arbitrary set of strokes, this would be an arbitrary set of strokes. Also, it's magick, and it works because magick. 

So here's some of the first attempts. Some/most of these likely won't render on all browsers.  

# L̷̾   L̶̷͚̾

Ok, evocative, but not visually a great hit. 

# ᛏ͢ᛊ 

Futhark is cool! Very angular. 

# ↯

Ooh, this downward lightning bolt (u21af) is a fantastic basis! Let's see what we can do with it! 

# \↯̸͢ 

The under-arrow comes in very handy. 


# ↑͢↯⃗̀

Getting occultier. 

# 🜹↯

Oh cool, a preceding character from the alchemy block makes its behavior change! 

# ⦨↯⃒̶⃗ 

The math block also mutates the behavior of the lightning bolt. 

# ⭍⃒̂͢    🜹↯̶⃒̀͢ ⃗

I can taste victory. I'm browsing a [unicode chart](https://unicode-table.com/en), looking for more interesting symbols to try to shoehorn in, and a little voice in the back of my mind is like, "Why don't you manifest the missing pieces?" An interesting thought, but that would require some crazy retrocausal crap that my metaphysical model reeeallly rebels at the idea of, so I brushed it off. The miscelaneous math symbols are looking pretty promising, when suddenly...

![237c_01](https://damienmaxwell.github.io/images/unicodal/237c_01.png)

#### Wat. 

Zoom in and enhance. 

![237c_02](https://damienmaxwell.github.io/images/unicodal/237c_02.png)

## ˙ʇɐʍ

As I'm reveling in the high weirdness that is a single character that is virtually a verbatim linking sigil, who but [Alan freaking Watts](https://www.youtube.com/watch?v=9RMHHwJ9Eqk) comes on in through the headphones. 

>  So then, let’s suppose that you were able every night to dream any dream you wanted to dream

<img alt="expanding brain" src="https://i.kinja-img.com/gawker-media/image/upload/s--eiIVX4Oq--/c_fill,fl_progressive,g_center,h_900,q_80,w_1600/yccc3f4vcwsxyj6eydy2.jpg" width="400" />

Woof. Yeah. Needless to say, I flashed back a bit. After I reconstituted my consciousness back to the present reality, I worked with some folks of the community to determine which bits and bobs could be affixed to our newfound Unicodal Elligram, as well as the portability of the other designs, and it turns out that in fact this symbol, along with a simple interpunct [·], is far and away the most compatible and best looking across browsers and environments. 

So what is this strange symbol? It's known as `Right Angle with Downward Zigzag Arrow` at codepoint [U+237C](https://unicode-table.com/en/237C/) (lol 23). It's under the [Miscellaneous Technical](https://en.wikipedia.org/wiki/Miscellaneous_Technical) block, which includes a bunch of electrical symbols, stuff used in the APL programming language, and some multimedia emoji. However, despite scouring the internet, I have not found any existing use for this symbol, nor why it ended up in this version of unicode. However, its proximity to many math/programming/scientific symbols leads me to believe that it may have been used in some early computing/networking equipment (how fitting). But seriously, this symbol is a ghost. There are a few examples of people using it for decorative purposes, but no substantiative semantic usage. 

Which, of course, means _I_ can inflect it with semantics. 

##### And upon this mark

<span style="font-family:Papyrus; font-size:23pt;">·⍼</span>

##### I unite the worlds

So how do you use this dang thing? Of course you can use it for anything you would use a standard [linking sigil](https://www.youtube.com/watch?reload=9&v=A99sTPY5bK0) for. But it's compactness and text-based nature makes it perfect for my original goal - sticking it in text. You can copy paste it, or enter in numerically depending on your OS (just google "How to enter unicode " and your OS). Stick it randomly in posts, throw it in comments in source code, and for you hackers out there, embed it in your next cross-site-scripting exploit. Speaking of injecting code, here's how you would represent it in binary:

⍼ in binary: 
`E2 8D BC 0A`

·⍼ in binary:
`C2 B7 E2 8D BC 0A`

I'll be doing more fun things with the unicodal LS in the future but I think this is a pretty good groundwork to kick things off for now. 
