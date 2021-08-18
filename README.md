# CSS Theatre Scrolling Slideshow

## Contents
- [Background](#background)
- [Technologies](#technologies)
- [Usage](#usage)
- [Live version](#live)

<a name=background></a>
## Background

This simple slideshow was made as a mini-project to get some practice using CSS layouts and animations. I made it as a way to present thumbnails of the first 4 websites I made when learning CSS, demonstrating my progression from terrible to not-quite-as-terrible.

It is fully responsive and will scale to any size. It simply allows a selection of photos to scroll across the stage and give a little jump in the center.

I hope you like it.

![example-image](./readMePhoto.png)

<a name=technologies></a>
## Technologies

The layout and frame are created purely in HTML/CSS. The inner frame decoration has been put together by positioning div blocks to vaguely resemble the shape of stage curtains. 

The sizing of some boxes is rather arbitrary but since they are hidden by the frame overflow it is not an issue.


<a name=usage></a>
## Usage

If for any reason you wish to include this on any of your own websites it should be a straight forward copy and paste job. 

Simple include the mainContainer div and its contents in your html file

~~~
<div class="mainContainer" id="mainContainer">
~~~

And ensure script.js and style.css are linked to the HTML.

Store your own pictures in a /img folder and update the first line of the script.js file

~~~
const imageSelection = [['images/comingsoon2.png', '#'], ['images/comingsoon.jpg', '##'],
['images/comingsoon3.jpeg', '###']]
~~~

Replace image names and replace '#' with relevant hyperlinks if required. More image-link combinations can be added by extending the array.

~~~
index.html
script.js
style.css
~~~


<a name=live></a>
## Live Version
The progression of my terrible websites displayed in a live slideshow can be viewed on my [portfolio](https://sgavinmills.github.io/index.html#webHistory).