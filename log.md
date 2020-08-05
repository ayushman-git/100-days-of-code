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

### Day 9: July 29, 2020

**Today's Progress**: Started with Introduction to Web Dev on FrontendMasters. Learned about IDs use and revised other tags and practices.

**Thoughts:** I started a new course today on FrontendMasters. I revised the tags and their semantic values that I learned in the LinkedIn course. I didn't find much new things to learn as most of the things were introduced in the LinkedIn course or I already knew. But I liked the structure and depth of this course. I learned something new today about HTML IDs. IDs name can only be used once in the whole website, meaning including all the pages under a domain. They are not that useful today because it undermines the usability of elements. But there is one instance that I found it to be useful and that is giving IDs to different sections of the page and loading to that section by using ```www.example.com/index.html#id-name```. It will directly open that section of the page. 

In my weather map I adjusted the loaction of the weather icon in main module.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/IntroToWebDev-L/commit/c8d5bb582c2d0d11024860cea58995548a2c88ad) & [2](https://github.com/ayushman-git/weather-app/commit/c3645cbbc718df9aab42ab5ad2458d3451e7a9f6)


### Day 10: July 30, 2020

**Today's Progress**: Learned about selectors, specificity, pseudo classes, display, box-sizing, flexbox. In JS template literals data type, difference between equality operaters, objects. Fixed sunrise/sunset module in weather app.

**Thoughts:** I think today I learned a lot of things. Under CSS section of the course, I learned about specificity which determines which ruleset will be applied. So, more specific the selector, more priority would be given to it. If multiple selectors have same specificity then one in the last will be considered. So this is the specificity order **tag > class > multiple classes > ID > !important**. We should avoid using !important in the most there can be other solutions which will make the CSS easy for others to read. Learned about selectors and pseudo classes. If we call .a .b then it will select all .b classes under .a. But if we use .a > .b then it will pick the immediate child of .a which has .b class. There's pseudo classes which determines the state of the element, like :hover. There's also :first-child, last-child and nth-child(n) which selects the child components and we can use nth-child to select in increment. Learned about display property in CSS, (block, inline, inline-block). There's a box-sizing property which determines what to include while giving dimension to the element. By default its content-box which don't include padding and applies dimension properties to the content then there's border-box which includes padding as well thus applying padding will not move the border (inside padding). Also learned basics about flexbox, how to align items, strech etc.

In my JS course, learned about template literals, equality opeartor. === compare the value without changing them, == compares the value after implicitly changing them. So 5 === "5" is false but 5 == "5" is true. Learned about objects.

In my weather-app I finally fixed the time calculaltor sunrise and sunset. So if we give it an UTC time it will convert it to the actual time of that timezone.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/IntroToWebDev-L/commit/1cf8f9da279930e112bd923f91ae06f056a81c89) & [2](https://github.com/ayushman-git/weather-app/commit/33cbd11f8717653a6c51b3b0d689e96eb8028389)

### Day 11: July 31, 2020

**Today's Progress**: Continued js course, learned about DOM, event listener and other basics.

**Thoughts:** Today I learned the difference between built-in property and function, arrays and how to access each element without a for loop. I also learned about context, this mostly refers to the object where its called from. Now have a better understanding of forEach and other array methods. Also about event Listener, they take two arguments, one the event type and one an anonymous callback function. A callback function is a function which is being passed in as argument in other function. There's event delegation, so if an event occurs and child is not able to handle that event the that event will be passed to the immediate parent of that child and this will continue untill the event is reached to the root element then its vanishes. This is also called bubbling. We can stop bubbling with stopPropogation method.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/IntroToWebDev-L/commit/19f76ba582db0635ca8af4c72ce80f53f690dab5)

### Day 12: August 1, 2020

**Today's Progress**: Studied further about NaN, new, boolean, falseys and truthys etc.

**Thoughts:** I started the new JS course on Frontend Masters. I learned a lot things that I didn't knew before. One being NaN and what it actually means. Then when to use the new keyword. If we want to create a new object then we should use new and if we want coercion then don't use new keyword. Learned new terminologies such as undeclared, undefined, functions expressions. I also learned about the Boolean() conversion which can also be performed using !!.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/fem-node-js-L/commit/b1f04336a852dd03ed8c3297d9458ad8888f91b5)

### Day 13: August 2, 2020

**Today's Progress**: Learned about IIFEs, let, explicit let block, scope and closure, class, difference between reference and value, dot and brackets. In my weather app I add last observation time and changed loading technique.

**Thoughts:** Today I learned a lot of new elements of JS, I learned  about IIFEs - which stands for Immediatly Invoked Function Expression, which are function expressions which gets immediately invoked after declerataion. It can be used to prevent changing the values of global scope. But we can do same with let keyword. We can use {} anywhere to define a let variable only available for that block - like {let aNamme = "A"}. Now have a better understanding of closures. So whenever any function is created it has a sense of its environment, so it don't dispose the values which can be further used and it can access its parent's var without even invoking the parent function. Also learned a little about prototypes - these are used for inheritence but same can be done with class which is much easy to understand. Class can be used to create several instance of a prticular group of data. '.' operater is always used with objects. There's two ways to store a var, one is reference( for non-primitive ) and one is value ( for primitive ). Values stored in objects are actually pointers that reference to the value. Obj -> name -> "Ayushman", but primitive values directly have the value in that variable. sameName -> "Ayushman". '.' notation coerce the variable intro string except when its starting with digits or dash.

In my weather app I added the last observation time, which I added using the dateSplit function. I also removed the previous loading method so now it looks like its loading faster than before.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/fem-node-js-L/commit/a17b618b0d7d083cce1fd07002a4107e294346e5) & [2](https://github.com/ayushman-git/weather-app/commit/83b6a8de643dcfef74c8c744aad66271664cea4f)

### Day 14: August 3, 2020

**Today's Progress**: Learned about destructuring arrays and objects. Looping arrays and objects, populating arrays and objects with variables. Also looked into forEach. 

**Thoughts:** There were  lot of variations of destructuring arrays and objects. I also learned when to use . and [] and also how to loop throw arrays and objects. Looked a little into spread operator. For looping I used forEach, for and for in. I think now I've a better understanding of how to access arrays and objects values. There was also how to populate an array or objects using functions and variables.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/fem-node-js-L/commit/2d2ee72e3883bf14a61a47e303f8a66b54e0509f)

### Day 15: August 4, 2020

**Today's Progress**: Learned about forEach, map, filter and data projection.

**Thoughts:** I am still finding new ways to create arrays, objects and access their elements. forEach don't return any value its just used to iterate through each elements. map can be used to create new array from an existing data structure as it returns an array. Filter can be used to have a condition for each elements in an array and if they return true they will be added to the new array, so it also returns an array. With these techniques I tried to access different types of data and come up with new data structure.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/fem-node-js-L/commit/74229bd0264a963ac94ff772a728f5920b143c55)

### Day 16: August 5, 2020

**Today's Progress**: Learned about argumemnts keyword, spread operator, default parameters and little about scoping.

**Thoughts:** Today I found new tools to handle functions and data structures. Arguments keyword can be used to access the list of all the arguments passed in the function. But the list is actually an array-like objects so we can't use most of the array properties and functions. We can convert it into an array with Arra.from(). Then there's spread operater (...), it is used to access the additional values. We can also assign default valeus to parameters if they are not sent as arguments. Then a little about scoping.

**Link to work:** [weather-app](https://weathertestapp.netlify.app/) & [repo](https://github.com/ayushman-git/weather-app)

**Commit link** [1](https://github.com/ayushman-git/fem-node-js-L/commit/74229bd0264a963ac94ff772a728f5920b143c55)
