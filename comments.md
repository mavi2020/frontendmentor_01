1-All page content should be contained by landmarks
<div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="https://github.com/develoba">DeveLoba</a>.
  </div>
2-every Html document must contain the <main> tag, so we can identify the main content, to fix this, wrap all the content with the main tag.
  HTML5 landmark elements are used to improve navigation experience on your site for users of assistive technology.
3-Consider using rem for font size. 
  If your web content font sizes are set in absolute units, such as pixels, the user will not be able to re-size the text or control the font size based on their needs. 
  Relative units “stretch” according to the screen size and/or user’s preferred font size, and work on a large range of devices.
4-there are two ways to add Google Fonts to your project. The first is by using <link>...</link>. Here is the full code

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
The second way is by using @import method inside your css file before any other styling, like this

@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');
Whether you want to use the first or the second method, it's really up to you. But for me, I personally like the @import method, because it's more concise.
5-
