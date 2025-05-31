Project Reflection

--What requirements did you achieve?

Use of semantic tags for each section - image overlay - use of flexbox - put all images in a folder - back to top button - smooth scrolling - hover effects on buttons and links - footer with social media icons that link to social media pages

--Were there any requirements or goals that you were unable to achieve?
The adding music one. I mean, I found a full step-by-step post on forum.freecodecamp.org, but not having covered JavaScript yet it felt like cheating. So, I'll add it next time.

--If so, what was it that you found difficult about these tasks?
We didn't go through JavaScript yet.

--What useful external sources helped you complete the assignment?

Google searching stuff and w3schools, mdn, and stackoverflow

--What errors or bugs did you encounter while completing your assignment? How did you solve them?

1 - I made the header and the css for it, it was all good. Then did some other css and when I pushed it to github the header disappered. I asked Sam, she suggested to see documentation on z-index. Set the header z-index to 1 and it got looking better.
2 - Doing cleanup I noticed white space left on the right of the page. Googled "html space right side" and visited a stackoverflow post. Set document to overflow-x: hidden, so any horizontal overflow will not be seen.
3 - The text on the to-top-button was overriden by the button selector and even if I added a color value it did not show. I think that's what was happening. During inspect color was not reading. Anyways, fixed that by setting the text itself as an anchor link with .button-top class and color value.
4 - Initially images were zoomed in, basically displaying in their full original size. So did background-size: 100% so they'd fill only the container. Then got the images repeating in a pattern when resizing the screen, so did background-repeat: no-repeat. Don't remember what I Googled but found the answer in a stackoverflow post.

--What went really well and what could have gone better?

Well - I completed this first project. I have a better understanding of html and css and can apply them.

To Work On - I don't like how the image is keeping its full width when the screen is resized. Not sure how exactly that could be fixed.
