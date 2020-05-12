# View at https://sylviapap.com

# Credits

Ethereal by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


>This is Ethereal, my latest, greatest, and quite possibly most unique template for HTML5 UP.
>Since releasing Parallelism 3-4 years ago (!!!), I've been dying to do another side-scrolling
>template with more in the way of flexibility/customization potential. The result is this template,
>Ethereal, which combines a robust side-scrolling framework of my own creation (with various
>"scroll-assist" features like drag/momentum scrolling, keyboard shortcuts, etc.) with a unique
>look and feel, a lightbox gallery, tons of customization options, and, of course, full
>responsiveness. Hope you dig it :)

AJ
aj@lkn.io | @ajlkn

Browsers deal with side-scrolling pages differently to vertically-oriented ones in
that they require elements (or at the very least, the top-most wrapper element) to
have a defined (fixed) width. This leads to a number of limitations (eg. the page
won't automatically grow/shrink in the same way a vertically-oriented one will), so
Ethereal does two things to work around this:

- The entire page is made up of "panel" elements, each of which can be assigned an
	optional "size" modifier (satisfying the fixed width requirement).

- For panels that don't use a size modifier, individual containing elements *inside*
	them (eg. a column) can be assigned a "span" modifier to give those a fixed width
	instead (also satisfying the fixed width requirement).

Another fun quirk of side-scrolling pages is how to actually implement horizontal
scrolling *without* resorting to using the horizontal scrollbar.
Ethereal does this in FOUR (!) ways:

- Dragging: Users can simply click and drag the page left or right to scroll it around.
	This works exactly as you'd expect, and even has a nice "post-scroll momentum" effect.

- Scroll Wheel: Ethereal modifies* the scroll wheel's behavior to translate vertical
	scrolling into horizontal scrolling, allowing the user to use either the scroll wheel
	or trackpad to scroll the page (the latter of which retains the ability to horziontally
	scroll as normal, so nothing changes there).

	* Special thanks to @miorel + @pieterv of Facebook for `normalizeWheel()` :)

- Scroll Zones: Users can hover the mouse cursor on the left or right edges of the page
	to automatically scroll in either direction.

- Keyboard Shortcuts: Finally, users can simply use the left/right arrows, page up/down,
	home/end, and the spacebar to scroll the page.

Note that these scroll-assist features can be turned off (and in some
cases customized). See `assets/js/main.js`

# Additional Credits

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		normalizeWheel (@miorel + @pieterv of Facebook)
		Responsive Tools (github.com/ajlkn/responsive-tools)