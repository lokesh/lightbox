# Lightbox

This is the original Lightbox script that introduced the concept of overlaying content on top of an existing page. The script focused on images and nailed a couple of things out of the gate that helped it gain traction: 1. It was super simple to implement 2. It degraded gracefully if Javascript wasn't enabled and didn't interfere with native behavior such as opening images in new tabs.

Over time, it went on to spawn 100s of imitators and now has become a standard pattern on the web. The term _lightbox_ has also been adopted for the pattern. [Wikipedia/Lightbox_(Javascript)](https://en.wikipedia.org/wiki/Lightbox_(JavaScript))


## History

### v1

In December 2005, I began tinkering around with the idea. I was redesigning my blog and my new design introduced a different column width for the content. This caused the images in the posts to overflow, unless I resized each one of them to fit the new width. I did not want to have to do this every time I tweaked my blog design, so I began to explore alternatives to displaying images.

And quickly during this ideation phase, Lightbox was born. I replaced the full-size images in the post with thumbnails and had a click reveal the full-size images. But this time, the images would display above, being overlayed on the page, and not have to worry about the content's column width. 

I shared the script running on my blog to a couple of coworkers and they were mildly impressed. I thought I was on to something so I kept going.

### Getting the word out

Right before the new year, I emailed a few of my favorite design bloggers and shared my script with them:

> On Dec 29, 2005, Lokesh wrote:
>
> Hello,
>
> I've written a little script to help people, mainly bloggers, 
> handle large images. Its a little faux-popup effect with Javascript.
>
> It might be useful for you, or not, either way take a look:
> http://www.huddletogether.com/projects/lightbox/
>
> btw..long time fan of your work.  Keep it up.
>
> -Lokesh

---

The first email response, and also the first bug report: 

> On Dec 29, 2005, Todd Dominey wrote:

> Hey - looks cool! I think I noticed a bug though in Safari / OS X. 
> The image loads great the first time, but after closing it and 
> clicking the same thumbnail again, I get an endless progress bar.

> Todd

---

More positive feedback, and the first feature request:

> On Dec 29, 2005, Jonathan Snook wrote:

> The script looks nice! I like that the popup image fits into the window size. The only thing I would add is a way to close the overlay before the image has loaded just in case a user doesn't want to wait or if the image doesn't load at all.

> Jonathan Snook

---

One of the biggest challenges with the new pattern was noted here in the first week:

> On Dec 30, 2005:

> I wonder how many folks visiting a page running your image script will do what I did after clicking and getting this big picture that obscures everything else...click the back button and completely leave your site?

> Perhaps there is a way to cue them that they need to click on the image a second time to return to the original page.

> Good luck!


### Snowball effect

The script was shared out by a few of the people I emailed directly and started picking up traction incredibly fast thanks to del.icio.us, a social bookmarking site which was popular for discovery at the time.

> On Dec 30, 2005

> I found the Lightbox JS demo today from del.icio.us, and I just 
wanted to say how impressed I am with it. It looks good, it's easy to 
use, and it's very unobtrusive. I would like to use it in a site I am 
developing for my university's student newspaper (Case Western 
Reserve University). Is it this okay with you?

---

> On Dec 30, 2005

> I just learned of your very interesting lightbox script. I really 
like the way you are stretching the dimensionality of the web page.

---

People were already beginning to imagine how this pattern could be extended:

> On Jan 2, 2006

> Great script!!!

> It’s way much safer than a pop up and it looks pretty neat…

> I was wondering if theres a posiblity that I could load another html instead of an image???

---

For quite some time, I attempted to help everyone who emailed my with their support issues:

> On Jan 3, 2006:

> I need some help if you have a moment.  I have implemented lightbox 
on my blog and it is not working just right.  I  click on the image 
and the loading graphic comes up but  the larger image never appears.

> Any ideas?  I am on Wordpress v2

---

There were lots of support issues, but people were generally nice and I was happy to help.

> On Jan 6, 2006:

> Many thanks for this nice scipt, it's fantastic! A nice replacement
> for all annoying pop-ups.
> I was confronted with a strange bug in Firefox 1.5. But it's not your
> script, it is some incompatibility with a css syntax in my script.

---

I also received a ton of thank you emails, each one of them was a treat!

> On Jan 7, 2006:

> this is just a cliché thank you email! loved the "lightbox", really
> clean and classy. used it on a website of mine (small icon on the side
> of each photo for floating over the page, to allow for both
> traditional and floating over the page viewing):


### To be continued


I have about 10,000 emails related to Lightbox in Gmail and the history so far captures the events of the oldest 500. I hope to dig into more over time as it is a fun walk down memory lane for me. 
