# AdvancedCSSHW\

## CSS Portfolio Site HW
This is my portfolio page for my current projects as a developer. All projects have a placeholder image and currently link to my assignment repository on GitHub, as I progress I hope to add real deployed projects that I can link to.
My goal was to have a well made HTML and CSS based portfolio page with responsive features and subtle rollover effects on all projects.

### The Nav Bar section
* The nav element layout was dealt with using flexbox, with the "display-align:space-between" feature. The links were made with a ul object, then changed to "display:inline" and styled.

### The Main section
* The Main section contains Sections for each thing. Each section is set to flexbox and contains a 'title' div and a 'content' div. The 'title' div is set to a fixed width.
* The 'work' content div is also a flexbox so that the images can wrap as the page resizes. I have two types of images labeled "wide-image" and "image" so that they can behave differently for the widths.
* For the hover effect on the project divs I decided to use css image filter to decrease the img opacity to 30%. However, I also wanted the .label objects to change from gray to purple when rolled over.
* I used the :hover pseudo class to add this feature so that when you hover the img the opacity returns to 100%. Then I added the same to the .label object to add the purple hover effect. But, I did realize that it worked a bit strangely since the opacity changes when scrolling over the img but the purple color only changed when hovering the text. This is not exactly how I wanted it.
* I decided that the img and .label objects had to get wrapped in a parent div. Then the hover effect had to be attached to the div wrapper, but then use the decendant operator ">" to effect the objects in the div.
* In order to allow the images to link, I had to change the parent "divs" to become parent "a" tags.

### Issues
* Once I had the page looking good as a responsive webpage. I had some issues making the code work in mobile devices. 
* I had to work on setting the header and nav to fixed heights, rather than % so that the contents don't scale too small at really small screen sizes.
* I found it better to set the body padding to a fixed px value as well, so that it doesn't scale strangely as the window size changes.

### Screenshots
https://drive.google.com/file/d/12U5Dh5sza1GsrWVT4CaK0TtcO1xREwdb/view?usp=sharing

### Link to deployed project
https://joshtdesign.github.io/AdvancedCSSHW/

### Thanks for reading ;)