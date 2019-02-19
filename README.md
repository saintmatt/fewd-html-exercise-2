# HTML5 Exercise 2

This exercise should help solidify the basics of properly structuring HTML files, as well as including images and links in our markup.

  * Fork and clone this repo.

  * Create a new branch off of `master` and name it something relevant.

  * Switch to your new branch and build out a basic directory structure.

  * In your new `index.html` file, start by including the basic HTML file structure elements that are required for us to run our project in the browser. Refer back to HTML files in other projects we’ve set up in class if you need a reminder on what the basic structure of an HTML document should look like.

  * Create a `<header>` element in your `index.html` file and add navigation markup (refer to [this slide](http://fewd.betamore.com/slides/unit/3#p10) as an example). Add *2* links in your navigation: one that points to your homepage (`/`), and another that points to an 'About' page that we will create shortly (`about.html`). Make sure your `<header>` element is _inside_ your `<body>`.

  * Add an `images` sub-directory inside your `assets` directory.

  * Create a new HTML file in the root of your project and name it `about.html`. After you’ve created this new file, your project directory structure should look something like this: https://screencast.com/t/nLpv9Qc8ZPL

  ```
  fewd-html-exercise-2/
  │  index.html
  │  about.html    
  │
  └───assets/
      │
      └───images/
      │
      └───css/
      │     main.css
      │
      └───js/
            main.js
  ```

  * In your new `about.html` file, add some appropriate (~2-4) `meta` tags in the `<head>` section. Can’t think of which to use? This list gives you _plenty_ of options: https://gist.github.com/lancejpollard/1978404

  * Let's add some content to our `about.html` file. We’re going to add *2* sections inside of our `<body>`: one that gives a short bio about you, and another that describes why you’re interested in learning how to code. Here’s a shortened example of what I might include in the two sections in my `about.html` page:

  ```html
  <body>
    <section id="section-one">
      <h1>Zac's Bio</h1>
      <p>Hello, I'm Zac. I like trail running, watching Netlix, and building stuff for the web.</p>
    </section>
    <section id="section-two">
      <h1>Why I Code</h1>
      <p>Learning to code is becoming increasingly important, and it opens up more and more doors as technology advances. I really enjoy learning and writing HTML, CSS, and JS, otherwise known as "the languages of the web."</p>
    </section>
  </body>
  ```

  * Great! So we’ve got our content sections created. Now let’s add some images! Include *2* new images in your `about.html` page. You’ll want to begin by adding these new images to the appropriate directory (e.g. `/assets/images`), and then adding an image to each of the two `<section>` elements in your `about.html` file. Reference the [MDN docs on adding images to a webpage](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML#How_do_we_put_an_image_on_a_webpage) to help you along.

  * Finish by adding *2* links in your `about.html` page. One should be an _internal_ link that points back to your `index.html` file. The other should be an _external_ link that points to your Github profile URL **AND** opens up in a new browser tab. [Refer here](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#Absolute_versus_relative_URLs) for info on how you should be structuring these types of links. It’s up to you where the best placement for these links should be - just make sure they are visible and functional in the browser!

  * Commit your changes.

  * Push your changes.

  * Share a link to your project repo in the class Slack channel.
