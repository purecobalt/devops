Devops
======
> Development operations resources


Website pre-launch checklist
----------------------------

*Note: set up your own launch checklist by copying the raw markdown of this list and pasting it into a new issue.*

### Search engine visibility
- [ ] Allow search engines to index site via `robots.txt` (in WordPress, just deselect the “Discourage search engines” button)
- [ ] Set up Google Webmaster Tools for the site (use `ranking@purecobalt.com`) and submit the XML sitemap when the site goes live
- [ ] Configure if necessary and enable Google Analytics on launch
- [ ] Confirm meta description is configured for home page
- [ ] Set up a useful `404` page

### Content
- [ ] Check favicon
- [ ] Run [W3C Link Checker](http://validator.w3.org/checklink) to validate links
- [ ] Use [W3C Validator](http://validator.w3.org) (not to make the site validate, just to check for issues you might not have realized existed)
- [ ] Print media query in styles; add super simple print styles (hide unnecessary elements like nav menus and such, bump font size, consider inlining link hrefs, etc.)

### Apache / MySQL / PHP sites
- [ ] Configure `.htaccess` `301` redirects if necessary
- [ ] Confirm that host has PHP `>= 5.3` and Apache `mod_rewrite` enabled
