# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge]
  - [Screenshot]
  - [Links]
  - [My process]
  - [Built with]
  - [What I learned]
  - [Continued development]
  - [Useful resources]
  - [Author]
  - [Acknowledgments]



### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Refer to the screenshots folder.

### Links

- Solution URL: https://github.com/The4thDimension/Card-component
- Live Site URL: https://the4thdimension.github.io/Card-component/

## My process

The idea was to design the card-thingy for the mobile screens. There wasn't much difference except for some simple attributes like width, height, etc. Following the semantics, the basic 
structure of the card was obvious. There weren't any pirticular header or footer mentioned, except for those inside the card. The card would supposedly go inside the main part of the 
page, considering there would be headers and footers apart from this in any normal web page. Inside the main, there would be a head part, inside which went the large photo, the main part,
inside which went the middle texts and the tail part, inside which went the footer of the design. The whole page would be part of the main section, and the card would be a div of class
container inside the main section, which would make it easy to position the card with varying screen sizes, and also to give different background color for both. Every element inside the 
container has equal padding which defines the distance from the border to the content(from the left side in pirticular). The first real challenge was to position the text exactly at the 
center of the icon. I changed the position to relative and used flexbox for this, after a bit of research. I know this is not the actual way, but it seems to work and I'm not sure what
the actual way is. Similarly I aligned the photo given below. The rest of the design was pretty obvious and easy. The next real challenge occured when I started giving hover effects.
As per the design, I had to give some neon-ish shade to the texts and the image on hover, which was easy. But to bring the eye icon to the center of the logo on hover was a bit challenging.
I brought the icon to the center by putting it inside a span and changing it's position to absolute, but I was not able to hide it. I tried display none, visibility hidden, opacity 0, 
but for some unknown reason, none of it would work. It would hide the image, but I was not able to bring it back on hover. Finally, I changed the logo's position to relative, which didn't
do much damage to my design and I used the z-index to make it work, which worked surprisingly. Finally, I put the given favicon and voila, here's the card design.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media Queries
- Mobile-first workflow


### What I learned

-> I was able to recap on flexbox and media queries
-> The challenges I faced in between ensured that I kept on checking out basic css like hover, box-shadow, etc.

### Continued development

I am not very good using flexbox. However, I plan to work on it and have a better implementation of it in the proper way, in the next project.

### Useful resources

- https://www.w3schools.com/
- https://stackoverflow.com/


## Author

- Github - https://github.com/The4thDimension
- Frontend Mentor - https://www.frontendmentor.io/profile/The4thDimension
- linkedin - https://www.linkedin.com/in/pmaheshiyer/


## Acknowledgments

Cheers to all the software developers aiding wannabe developers like myself to grow and be better.