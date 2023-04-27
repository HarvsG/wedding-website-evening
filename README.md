# Wedding Website
A beautiful, feature rich, device friendly wedding website.  
_See [wedding.rampatra.com](http://wedding.rampatra.com/) for a demo. Use invite code `271117` to RSVP._

# Highlights
1. Slick and fully __responsive__ design.
2. __RSVP feature__ which directly uploads data to a Google sheet.
3. __Receive email alerts__ when someone RSVPs.
4. __Add to Calendar__ feature which supports four different calendars.
5. __Book Uber__ button lets guests book a cab to the venue with just a single tap.
6. A nice __Youtube video__ showing your venue.
7. __Google Map__ showing your venue's location.
8. Start and run the website __completely free__. No hosting, backend server, or database required as you can use
   [GitHub Pages](https://pages.github.com/) to host and Google sheets (with the help of Google scripts) to store RSVP
   data.

# Getting Started
1. `$ cd wedding-website` - go inside the project directory
2. `$ npm install` - install dependencies _(optional)_
3. `$ gulp` - compile sass to css, minify js, etc. _(optional)_
4. That's it, open `index.html` on your browser by just double-clicking on the file.

# Documentation
I have written a 
[blog post describing all the features of this wedding website](https://blog.rampatra.com/wedding-website) and how to
customize each of them according to your needs.

# About Me
Hello, my name is Ram. I am a Lead Software Engineer at [Mastercard R&D Labs](https://www.mastercard.com/). I enjoy making teeny tiny applications in
my leisure time and this is one of them. Now that my wedding is over, I am open-sourcing the project. Hope you like it!

Lastly, if you use a Mac then you may also love [Presentify](https://presentify.compzets.com/). Give it a whirl and let me know your thoughts.

# Contribute
Firstly, a big thanks 🙏🏻 for the overwhelming response on [HackerNews](https://news.ycombinator.com/item?id=18556787) and [Reddit](https://www.reddit.com/r/opensource/comments/a1bx4h/i_am_open_sourcing_my_wedding_website_on_my_first/). I would be more than happy for [PRs](https://help.github.com/articles/about-pull-requests/) or [sponsors](https://www.paypal.me/iamrampatra).

<a href="https://www.buymeacoffee.com/rampatra" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

_P.S. For any queries or concerns, you can reach out to me on [Twitter](https://twitter.com/ram__patra). I'll try my best to help 🙏._

TODO:
- [x] Date directly under G&A in main banner
- [x] Change colour of banner when you scroll down
- [ ] Update images with mum's bus and church
- [x] Main banner to be made a flat colour so you can see the wording? Otherwise picture with more blank space
- [x] Remove section with when and where/move down the page
- [x] In the order of the day section, can we link the addresses so they can open in google maps if needed? 
- [x] Dress to be own section rather than pop up
- [ ] Font and text colour alignment with invitation where possible
- [x] Remove dessert option from RSVP section, consider adding song suggestion?
- [x] Switch name and email in RSVP and switch invitation code and dietaries
- [x] Add will/won't be able to attend
- [x] Use correct icons for form boxes
- [x] Add section as placeholder for gifting, which will include wording and gift registry link
- [ ] Resize images only once all text in that section is finalised (otherwise we'll have to do it again)
- [ ] If you have time, then we could add some scrolling images and a count down, but these are nice to haves not essential!!
- [x] Test form submission with added fields
- [x] Link for email RSVP just in case
- [x] Add full food descriptions
- [x] Disable mandatory fields if not attending
- [x] Change pop up for not-attending
- [x] Finalise security / captcha
- [ ] Internal /external testing
- [x] Display pictures on mobile
- [x] Migrate to harveybarkshire.com
- [x] Get google maps working, remove uber link
- [ ] Home-assistant, heartbeat monitoring