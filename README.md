# Simple Journal

May contain items such as: Today I Learned (TIL), Fails, Wins, Helps, Snippets, Questions I had || Answers found, Topics of Curiosity, and more. It's also a place a I just put random simple things that I forget exactly how to use.

<!-- ## Table of contents -->
# Tables of Contents
- [Table of Contents 2019](#contents19)
- [Table of Contents 2023](#contents23)
- [Table of Contents 2024](#contents24)


## Table of Contents 2019 
<a id="conetnts2019"></a>

- [July](#jul19)
- [August](#aug19)


<a id="jul19"></a>
## July 

- TIL/still Confused: Javascript Hoisting [Article: Understanding Hoisting in Javascrip](https://scotch.io/tutorials/understanding-hoisting-in-javascript "Understanding Hoisting in Javascript")
- TIL: about Block Scope vs Function Scope, [here's an article about it.](https://medium.com/@josephcardillo/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe "The Difference Between Function and Block Scope in JavaScript")
- TIL: ES6 things. I was rejecting a pull request and decided to spend some time leanring more about the why's of let vs var. Found this little article by my favourite code blogger Tania Rascia,[ES6 Syntax and Feature Overview
  ](https://www.taniarascia.com/es6-syntax-and-feature-overview/ "ES6 Syntax and Feature Overview
").

## August
<a id="aug19"></a>

- TIL: Inspect previous commit. `git log` , find the commit you wish to checkout and copy its hash, `git checkout <commit hash>`


## Table of Contents 2023
<a id="conetnts2023"></a>

- [January](#jan23)
- [March](#mar23) 
- [May](#may23)
- [July](#jul23)
- [August](#aug23)
- [September](#sep23)
- [October](#oct23)  

## January #jan
<a id="jan23"></a>

- TIL: Px vs REM [Article: Why designers should move from px to rem ](https://uxdesign.cc/why-designers-should-move-from-px-to-rem-and-how-to-do-that-in-figma-c0ea23e07a15 "Why designers should move from px to rem ") : "we are in the dark about users browser preset choices, so using rem will serve zoom and root font-size change and make everyone happy."
- TIL: for Hubspot form embeds on external sites you can remove CSS styling coming from Hubspot by adding "css" to remove basic styling and "cssRequired" to remove styling from required items to the embed code. Example:
  <code>
  portalId: "",
  formId: "",
      css: '',
  </code>

## March
<a id="mar23"></a>

- Snippet: for switching content based on URL in PHP Wordpress Templates. Saves writing multiple templates often times, primary example is a Landing Page and it's coresponding Thank You page or just multiple pages with very similar content and small diffs.
  ```
  <?php if ( is_page('thank-you') ) { ?>
  
  <?php } else { ?>
  
  <?php } ?>


## May
<a id="may23"></a>

- and a further snippet url conditional content requiring further else if to your if - else. (write unique html/code in between each)

  ```
  <?php if (is_page('url')) { ?>
      
  <?php } else if (is_page('id-id')) { ?>
      
  <?php } else if (is_page('id-id')) { ?>
      
  <?php } else { ?>
      
  <?php } ?>



## July
<a id="jul23"></a>
- Was struggling with indention in lists and paragraphs specifically around using custom images in the places of bullet points with a nice amount of space between them and the first line while keeping the subsequent lines from overflowing under the list decoration images..
  ```
  <style>
    /* set all of X block elements to Y indention */
    li {
      text-indent: -17px
    }
    /* remove indention from :first-line */
    li:first-line {
      text-indent: 0
    }
    /* remove default list decoration/bullet points */
    ul {      
      list-style: none;
    }
    /* custom image in the place of list decoration/bullet points*/
    li::before {
      content: url('');
      display: inline-block;    
      margin-right: 13px;
    }
  </style>

  <li>
    Requires workarounds:
    Must search and clean up “unauthorized accounts” in chart of accounts
  </li>


- Two ways to generate Pardot Forms in Wordpress sites after downloading the plugin:
  w/ php 
  ```
  <?php echo do_shortcode('[mb_pardot handler="{URL-here}" brand="brand_asc" prospect="MQL" interest="ChMS" redirect="{URL-here}" comments_type="textarea" comments="How did you hear about us?" button_color="#6486FD"]') ?>      
    
- -  w/ html

<pre><code>
  [mb_pardot handler="{URL-here}" brand="HGS" prospect="MQL" interest="" redirect="{URL-here}" button_color="##f47a55"]      
  </code></pre>


## August
<a id="aug23"></a>

- #If IE BUGS you can use this media query to attack them without breaking things in normal browsers:
```
    @media all and (-ms-high-contrast: none), (-ms-high-contrast: active) {
      // IE10+ CSS here
    }


## September
<a id="sep23"></a>

- PHP Template place to drop content in via the admin page editor.
```
  <?php the_content(); ?>
```

## October 2023
<a id="oct23"></a>

- simple css hack to help visually debug layout issues..
```
    * { border: 1px solid red; }
```

- node
  Check version with <pre><code>node -v</code></pre>
```
    sudo npm cache clean -f 
```
  (force) clear your npm cache
```  
```
    sudo npm install -g n 
```
  install n (this might take a while)
```   
    sudo n stable 
  
  upgrade to the current stable version

If you initially installed Node.js with <a href="https://brew.sh/" target="_blank">Homebrew</a>, run:

<pre><code>brew update</code></pre>

<pre><code>brew upgrade node</code></pre>

<pre><code>npm install -g npm</code></pre>

Or as a one-liner:

<pre><code>brew update && brew upgrade node && npm install -g npm</code></pre>

A convenient way to change versions is to use n:

<pre><code>brew install n</code></pre>

To install the latest version of Node.js with n:

<pre><code>n latest</code></pre>

Or, to install the latest LTS version with n:

<pre><code>n lts</code></pre>

Alternatively, you could use nvm instead of <a href="https://github.com/tj/n" target="_blank">n</a>:

<pre><code>brew install nvm</code></pre>

To install the latest version of <a href="https://nodejs.org/en" target="_blank">Node.js</a> with <a href="https://github.com/nvm-sh/nvm" target="_blank">nvm</a>:

<pre><code>nvm install node</code></pre>

## Table of contents 2024
<a id="contents24"></a>



- [Febraury](#feb24)
<!-- - [March](#mar24) 
- [April](#apr24)
- [May](#may24)
- [June](#jun24)
- [July](#jul24)
- [August](#aug24)
- [September](#sep24)
- [October](#oct24)  
- [November](#nov24) 
- [December](#dec24) -->



<!-- <a id="mar24"></a>
<a id="apr24"></a>
<a id="may24"></a>
<a id="jun24"></a>
<a id="jul24"></a>
<a id="aug24"></a>
<a id="sep24"></a>
<a id="oct24"></a>
<a id="nov24"></a>
<a id="dec24"></a> -->


## February 
<a id="feb24"></a>

- Alt text solutions for CSS Background Images: 
- - (this is for background images that are contextual, if they are not contextual then they can be ignored, unsure if automated SEO/Accessibilty audit will spot the fix though manual testing should accept it)
- - Instead of applying a background image to a div or other block element via CSS background image apply it to the span within the div with rol= and aria-label= applied and the content inside of that span.

```
  <div>
    <span class="background-image" role="img" aria-label="place alt text here"> </span>
      all the rest of my content
  </div>


- - OR a slightly hackier way where the CSS background image is still applied to the div but will allow a screen reader to ignore the div and read the span's aria-label in liu of a normal alt tag before moving on to the content.

```
  <div class="background-image">
    <span role="img" aria-label="place alt text here"> </span>
      all the rest of my content
  </div>