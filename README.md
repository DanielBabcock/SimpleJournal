# Simple Journal

May contain items such as: Today I Learned (TIL), Fails, Wins, Helps, Snippets, Questions I had || Answers found, Topics of Curiosity, and more.

## Table of contents 2019

- [July](#july)
- [August](#august)

## July

- TIL/still Confused: Javascript Hoisting [Article: Understanding Hoisting in Javascrip](https://scotch.io/tutorials/understanding-hoisting-in-javascript "Understanding Hoisting in Javascript")
- TIL: about Block Scope vs Function Scope, [here's an article about it.](https://medium.com/@josephcardillo/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe "The Difference Between Function and Block Scope in JavaScript")
- TIL: ES6 things. I was rejecting a pull request and decided to spend some time leanring more about the why's of let vs var. Found this little article by my favourite code blogger Tania Rascia,[ES6 Syntax and Feature Overview
  ](https://www.taniarascia.com/es6-syntax-and-feature-overview/ "ES6 Syntax and Feature Overview
").

## August

- TIL: Inspect previous commit. `git log` , find the commit you wish to checkout and copy its hash, `git checkout <commit hash>`

## Table of contents 2023

- [January](#jan)

## January

- TIL: Px vs REM [Article: Why designers should move from px to rem ](https://uxdesign.cc/why-designers-should-move-from-px-to-rem-and-how-to-do-that-in-figma-c0ea23e07a15 "Why designers should move from px to rem ") : "we are in the dark about users browser preset choices, so using rem will serve zoom and root font-size change and make everyone happy."
- TIL: for Hubspot form embeds on external sites you can remove CSS styling coming from Hubspot by adding "css" to remove basic styling and "cssRequired" to remove styling from required items to the embed code. Example:
  <code>
  portalId: "6060861",                            formId: "218dced7-2147-4cd5-aff6-b8e424b2d531",                            css: '',                            onFormSubmitted: function($form) {                                setTimeout(function() {                                    window.location.href = "https://www.ministrybrands.com/unleash-2023/thank-you/";                                }, 500);                            }  });
  </code>
  https://community.hubspot.com/t5/CMS-Development/Custom-Form-Style/td-p/5707

## March

- Snippet: for switching content based on URL in PHP Wordpress Templates. Saves writing multiple templates often times, primary example is a Landing Page and it's coresponding Thank You page or just multiple pages with very similar content and small diffs.
  <pre>
  <code>
  <?php if ( is_page('thank-you') ) { ?>
  
  
  <?php } else { ?>
  
  
  <?php } ?>
  </code>
  </pre>
