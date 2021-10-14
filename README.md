# plant-carousel-task

## Git access
Please fork from https://github.com/joe-mcpherson/plant-carousel-task

## Set up
Build a plant page with an image carousel

We are using Bootstrap 4.6 https://getbootstrap.com/docs/4.6/getting-started/introduction/

You can include Bootstrap styles with Node Package Manager by running
npm install 

and using a sass compiler to generate the css/plant.css from sass/plant.scss file with the 
Bootstrap css included 

OR 

if you're not sure how or don't want to use NPM then you can uncomment the cdn include of the 
Bootstrap stylesheet in index.html and just write your css directly into css/plant.css or
build from sass/plant.scss and comment out the Bootstrap include
(but this method won't allow you to overwrite things such as Bootstrap sass variables)

## The task

Primary theme colour: #0c8a59
Secondary theme colour: #014d5d

Please expand the current scaffold index.html to include a Carousel of the 
plant images in assets/images with slide navigation. 
You could use: https://getbootstrap.com/docs/4.6/components/carousel/ 

Please make the "Wordy description column" more readable by introducing a "read more" button.
Make the button the Primary theme colour.
You could use: https://getbootstrap.com/docs/4.0/components/collapse/

Make any buttons and links in the body and the header bottom border the Primary theme color

Make the footer background the Secondary theme colour links white

Check everything looks ok on mobile, tablet and desktop

With the HTML plant dimentions data table add a button below to swich between Metric and 
Imperial values (I've commented out the Imperial value column in the HTML)
feel free to add some jQuery (or vanilla JavaScript) in js/plant.js if needed

## Bonus points (get creative!)

Some ideas:

- Add some Google Fonts for the headings
- add some javascript to calculate the metric to Imperial measurements
  so any values could be in the metric columns and they are converted dynamically in js
- Add a Lightbox (or similar popup) for the Carousel
- or something else to demo your web development skills :)
