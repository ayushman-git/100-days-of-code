# 100 Days Of Code - Log

### Day 1: July 21, 2020

**Today's Progress**: Completed Async...Await module on codecademy and made weather-app responsive to bigger screen size.

**Thoughts:** I think now I've a better understanding of asynchronous programming in javascript. I now understand how promise system works and how to consume a promimse. I also worked on my weather-app and made some changes. I changed each module so that their content will appear vertically centered.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

### Day 2: July 22, 2020

**Today's Progress**: Completed AJAX and HTTP request module on codecademy and fixed text overflow in small modules in weather-app.

**Thoughts:** Learned how to make HTTP request (GET and POST) as per pre-ECMA-2015 standard. Now able to make boiler-plate codes for GET and POST method using XHR object. Fixed a bug which makes a big text overflow in weather-app small modules.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

[**Commit link**](https://github.com/ayushman-git/weather-app/commit/ec6cc79c241f3f5f2d29aa04466a3ef2098e5b41)

### Day 3: July 23, 2020

**Today's Progress**: Used async and await with fetch and try...catch to access data. Added clouds animation on weather-app. 

**Thoughts:** Learned how to use async functions to fetch data with GET method. I found it's much simpler than XHR and normal fetch to use async and fetch together to access data. Figured out how to try and catch while using fetch. Added clouds animations on the background for cloudy day.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

[**Commit link**](https://github.com/ayushman-git/weather-app/commit/67fbd606432b50c45cc2d85d9d5d9734430afe0e)

### Day 4: July 24, 2020

**Today's Progress**: Used async and await with fetch and try...catch to access data with POST method. Added rain animation on weather-app. 

**Thoughts:** Learned how to use async functions to fetch data with POST method. I used Datamuse and Rebrandly API to practice GET and POST method with this new technique. I also added a rain animation for the background on my weather-app with the help of jQuery.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

[**Commit link**](https://github.com/ayushman-git/weather-app/commit/ee859ada335c46541d30799153744f4d4788939c)

### Day 5: July 25, 2020

**Today's Progress**: Started LinkedIn HTML essential course. Added snow animation on weather-app.

**Thoughts:** Today I started LinkedIn HTML essential course. I learned new text formatting tags ```<q>``` and ```<blockquote>``` and a new list type (description list) though its not a very useful tag. Learned about semantic values of tags, for eg. ```<h1>``` tag will have more semantive value than ```<h2>```. It could be useful in accessibility of the page. So we should always follow semantic rules of html - meaning the most dominant heading should always be displayed using```<h1>```, the next most prominent heading should be usingn ```<h2>``` and so on (we can change their size and appearance with css). Learned about ```<time>``` tag and its ```datetime``` attribute. While declaring a time we should use time tag and use datetime attribute so that we can use that date in js. Learned a little about ARIA accessibility attributes - ```aria-label``` and ```aria-remove``` to add meaning or remove the semantic meaning from a tag which might have been changed because of using un-semantic methods. Also added snow effect on weather-app with SCSS.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/linkedin-w3school/commit/9bd60cd6146a91f490776e7fa28177e3fdebbb75) & [2](https://github.com/ayushman-git/weather-app/commit/3763859a575599a7ec4bc435fc0749dbd5b8272c)

### Day 6: July 26, 2020

**Today's Progress**: Learned about links, their path, absolute URL and relative URL, srcset. Trimmed the code for background-animation in weather-app.

**Thoughts:** I continued the LinkedIn HTML course and learned about links, URL types likes relative and absolute. Learned about image tags. If there's a lot of content and images and user scrolls down, if the images are not loaded up yet and <img> tag don't have width and height attribute or its dimensions are not defined in css the scroll will go down as soon as browser loads up the images. So if we want to maintain scroll position we give dimensions to the image. Also discovered srcset attribute, but can't make it work in my example.I will take another look on it. I tried making weather-app resposive for smaller screens using media queries, but I can't make a newer grid. I may try flexbox for smaller screens. I have to look into SASS tutorial to complete the night animation. I trimmed the code for animations into a single div and instead of changing the display to ```inline-block``` now I am calling the function.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/linkedin-w3school/commit/9bd60cd6146a91f490776e7fa28177e3fdebbb75) & [2](https://github.com/ayushman-git/weather-app/commit/cb42cfbe92e5e784b15a34b3e9a3eddce2f0f6c0)

### Day 7: July 27, 2020

**Today's Progress**: Learned about responsive images, audio, video and its captions (WebVTT) also to embed videos from other streaming platform. Made stars in weather-app flicker and glow.

**Thoughts:** In my linkedIn course I learned further about resposive images. Using ```<srcset>``` and ```<sizes>``` to load same image but with different resolutions to be rendered on HTML according to user's network speed and screen size. I also used ```picture tag``` to use completely different images with different aspect ratios, so that different images are downloaded for different screen sizes. Used audio tag with ```<source>``` tag to use multiple audio formats and broswer will pick the one it can understand from top. In ```<video>``` tag I learned about ```<track>``` tag which is used to put different captions and subtitles for the video. Track tag takes a ```.vtt``` (which stands for Web Visual Text Track).

In my weather-app, I used SASS function to make stars flicker. I used SASS function to create different rulesets for all 200 stars ids and assign them random values of animation-delay and animation-duration. So each star looks different from each other. I also added box-shadow with random values of blur to make them glow.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/linkedin-w3school/commit/fd8dad905a20a9b01ab239f196b5e17b49a76fe2) & [2](https://github.com/ayushman-git/weather-app/commit/ba897e9b4d46a706d10edabdf0e2e6d89bc8d34b)

### Day 8: July 28, 2020

**Today's Progress**: Completed LinkedIn course, learned about semantic tags, form elements, tables. Made star in weather-app move.

**Thoughts:** Today I fianlly completed the HTML essential course on LinkedIn. I learned about semantic tags, like ```<main>```, ```<section>```, ```<article>```, ```<footer>```, ```<aside>``` and their semantic values. Main is used only once per page to display the main content. Section is used to divide different sections of the page, article is used to define a content that could be useful for viewer like blog post, cards etc, footer is used to display additional information, aside is used to used elements on the side like ads and navbar etc. We can nest these elements for better representation of the semantic values. Learned about different form and input types. Learned about fieldset, it should be used to bundle checkboxes, radio buttons etc, label is used for labeling a input field. There are different types of input fields, like password, email, date, color, file etc. Also learned about table elements, th tr td etc their attributes like colspan, rowspan to determine how much rows or columns they would occupy.

In my weather app I made stars move randomly. They look random but I divided them into three types of movement animations and applied different transforms to them combined with that, I applied random animation delay and animation time.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/linkedin-w3school/commit/8fc5bfd67c274cf29cf2defe7e00f317e0b33fc2) & [2](https://github.com/ayushman-git/weather-app/commit/884bc45c144d321a7f6538627df1eb3ba4a02a4e)

