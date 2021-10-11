# plant-carousel-task

## Git access
Please fork from https://github.com/joe-mcpherson/plant-carousel-task

## Set up
Build a plant page with an image carousel

We are using Bootstrap 4.6 https://getbootstrap.com/docs/4.6/getting-started/introduction/

You can include Bootstrap styles with Node Package Manager by running
npm install 

and using a sass complier to generate the css/plant.css from sass/plant.scss file with the 
Bootstrap css included 

OR 

if you're not sure how or don't want to use NPM then you can uncomment the cdn include of the 
Bootstrap stylesheet in index.html and just write your css directly into css/plant.css or
build from sass/plant.scss and comment out the Bootsrap include
(but this method won't allow you to overwrite things such as Bootstrap sass variables)

## The task

Please expand thecurrent shell index.html to include a Carousel of the 
plant images in assets/images with slide navigation. 
You could use: https://getbootstrap.com/docs/4.6/components/carousel/ 

Please make the "Wordy description column" more readable by introducing a "read more" button.
Make the button the Primary theme colour.
You could use: https://getbootstrap.com/docs/4.0/components/collapse/

Primary theme colour: #0c8a59
Secondary theme colour: #014d5d

Make the links in the body and the header bottom border the Primary theme color

Make the footer background the Secondary theme colour links white

Check everything looks ok on mobile, tablet and desktop

## Bonus points (get creative!)

Some ideas:

- Add some Google Fonts for the headings
- You shouldn't need any JavaScript for the primary task above, but feel free to add 
  some javascript in js/plant.js to make something happen :)
- Add a Lightbox (or similar popup) for the Carousel
- or something else to demo your web development skills :)
