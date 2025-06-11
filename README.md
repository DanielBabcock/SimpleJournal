# Simple Journal

May contain items such as: Today I Learned (TIL), Fails, Wins, Helps, Snippets, Questions I had || Answers found, Topics of Curiosity, and more. It's also a place I put random simple things that I can reference later.

<!-- ## Table of contents -->
# Tables of Contents
- [Legend](#legend).
- [Setting up a new Machine](#newMachine).
- [Table of Contents 2019](#contents19).
- [Table of Contents 2023](#contents23).
- [Table of Contents 2024](#contents24).

<a id="legend"></a>

## Legend
- bullets and sub bullets are info points
- ! = ideas
- ¿  ? = questions
- TIL = Today I Learned

<a id="newMachine"></a> 

## New Machine Setup:

### Programs to Install:
- Adobe ???
- ClenMyMac X
- Figma
- FileZilla
- Firefox, Edge, Chrome (plugins below), Brave, Opera, Firefox Focus
- Visual Studio Code (further instructions and Plugins below)
- ImageOptim
- Password Manager/s 
- Microsoft Office and/or Mac equivalents
- Teams and Slack
- Zoom
- VPN/s
- XCode
- 

### Chrome Plugins
- Password Manager 
- Pomodoro
- Axe Dev Tools
- Lighthouse
- Color Contrast Analyzer by accessibility.oit.ncsu.edu
- Browserstack and Browserstack Accessibility
- Debug CSS
- Fake Filler
- uBlock Origin
- Wapp Analyzer
- Wave Evaluation Tool
- Web Developer Checklist
- React Developer Tools
- ¿¿¿ Website SEO Checker: Free Audit & Analysis
- ¿¿¿ CSS Peeper
- 


### Install Visual Studio Code
Extensions:
- <a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode">Prettier</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag">Auto Close tags</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=Cardinal90.multi-cursor-case-preserve">Multi-Cursor Case Preserve</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens">Git Lens</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion">HTML/CSS Class auto complete</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client">PHP Intelephense</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=rifi2k.format-html-in-php">Format HTML in PHP</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=d-koppenhagen.file-tree-to-text-generator">File Tree to Text Generator</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker">Code Spell Checker</a>

### Github access token

```sh
/bin/bash -c "$(curl -fsSL https://gist.githubusercontent.com/DanielBabcock/b11e0df92ec970868f83e56dd4e00729/raw/ddb2f40807452eb61e145cf7b0234d84e5c00b8b/create-key.sh)"
```

### Install Homebrew

Run the following command in your Terminal. You will be prompted for your computer password. It will not display the characters as you type them for security reasons. <a href="https://brew.sh/">https://brew.sh/</a>

below in gist
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Once the process is complete, run the `brew` command in your terminal. If you see the output `command not found: brew` figure it out. Some stuff is commented out in the raw markup immediately below this..

<!-- ==> zsh-completions
To activate these completions, add the following to your .zshrc:
```sh
  if type brew &>/dev/null; then
    FPATH=$(brew --prefix)/share/zsh-completions:$FPATH

    autoload -Uz compinit
    compinit
  fi
```
You may also need to force rebuild `zcompdump`:
```sh
  rm -f ~/.zcompdump; compinit
```
Additionally, if you receive "zsh compinit: insecure directories" warnings when attempting
to load these completions, you may need to run these commands:
```sh
  chmod go-w '/opt/homebrew/share'
  chmod -R go-w '/opt/homebrew/share/zsh'
``` -->

### Install Modern Shell

Run the following command in your Terminal.

<!-- ```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
``` -->

```sh
/bin/bash -c "$(curl -fsSL https://gist.githubusercontent.com/DanielBabcock/55d9f18f49d5897300f9ec1eaa39596a/raw/e60e0688f5b4fbb3cf367f92d76d35eaa67d377e/configure-zsh.sh)"
```

Once complete, run the following command in your Terminal.

```sh
echo $SHELL
```

You should see either `/usr/local/bin/zsh` or `/bin/zsh` as the output of that command. If you don't, contact an instructor.

### Install Node
```sh
/bin/bash -c "$(curl -fsSL https://gist.githubusercontent.com/DanielBabcock/b721fd90ddf675274a9d4be750df6d49/raw/e6a99f919efbbd4be9eae3e7a6654f39f58b78f6/install-nvm.sh)"
```


Once the process is complete, quit your Terminal application completely, and then open it again immediately.

Run the `node -v` command in your Terminal. If you see the output `command not found: node` then contact an instructor.

### Verify Installs:
```sh
/bin/bash -c "$(curl -fsSL https://gist.githubusercontent.com/DanielBabcock/4c8ae4d61516788f491ee504f16f85e7/raw/ae02c52727848dd23b9f39f663b110dc124ae8fd/verify-installs.sh)"
```

### Project setup example
- <a href="https://gist.github.com/DanielBabcock/3d11af493ca4ac2b7e47f015c8952f52">project-setup.sh idea stolen from NSS/Coach</a>
https://gist.githubusercontent.com/DanielBabcock/3d11af493ca4ac2b7e47f015c8952f52/raw/138f3127ad0e07827268eb8278e09040fbc2bcdf/projectsetup.sh

<a id="contents19"></a>

## Table of Contents 2019 
- [July](#jul19)
- [August](#aug19)


<a id="jul19"></a>

## July 

- TIL/still Confused: Javascript Hoisting [Article: Understanding Hoisting in Javascrip](https://scotch.io/tutorials/understanding-hoisting-in-javascript "Understanding Hoisting in Javascript")
- TIL: about Block Scope vs Function Scope, [here's an article about it.](https://medium.com/@josephcardillo/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe "The Difference Between Function and Block Scope in JavaScript")
- TIL: ES6 things. I was rejecting a pull request and decided to spend some time leanring more about the why's of let vs var. Found this little article by my favourite code blogger Tania Rascia,[ES6 Syntax and Feature Overview
  ](https://www.taniarascia.com/es6-syntax-and-feature-overview/ "ES6 Syntax and Feature Overview
").

<a id="aug19"></a>

## August

- TIL: Inspect previous commit. `git log` , find the commit you wish to checkout and copy its hash, `git checkout <commit hash>`

<a id="contents23"></a>

## Table of Contents 2023

- [January](#jan23)
- [March](#mar23) 
- [May](#may23)
- [July](#jul23)
- [August](#aug23)
- [September](#sep23)
- [October](#oct23)  

<a id="jan23"></a>

## January #jan

- TIL: Px vs REM [Article: Why designers should move from px to rem ](https://uxdesign.cc/why-designers-should-move-from-px-to-rem-and-how-to-do-that-in-figma-c0ea23e07a15 "Why designers should move from px to rem ") : "we are in the dark about users browser preset choices, so using rem will serve zoom and root font-size change and make everyone happy."
- TIL: for Hubspot form embeds on external sites you can remove CSS styling coming from Hubspot by adding "css" to remove basic styling and "cssRequired" to remove styling from required items to the embed code. Example:
  <code>
  portalId: "",
  formId: "",
      css: '',
  </code>

<a id="mar23"></a>

## March

- Snippet: for switching content based on URL in PHP Wordpress Templates. Saves writing multiple templates often times, primary example is a Landing Page and it's coresponding Thank You page or just multiple pages with very similar content and small diffs.
  ```
  <?php if ( is_page('thank-you') ) { ?>
  
  <?php } else { ?>
  
  <?php } ?>


<a id="may23"></a>

## May

- and a further snippet url conditional content requiring further else if to your if - else. (write unique html/code in between each)

  ```
  <?php if (is_page('url')) { ?>
      
  <?php } else if (is_page('id-id')) { ?>
      
  <?php } else if (is_page('id-id')) { ?>
      
  <?php } else { ?>
      
  <?php } ?>


<a id="jul23"></a>

## July

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
  [brand_pardot handler="{URL-here}" brand="___" prospect="MQL" interest="" redirect="{URL-here}" button_color="##fff"]      
  </code></pre>

<a id="aug23"></a>

## August

- #If IE BUGS you can use this media query to attack them without breaking things in normal browsers:
  ```
    @media all and (-ms-high-contrast: none), (-ms-high-contrast: active) {
      // IE10+ CSS here
    }

<a id="sep23"></a>

## September

- PHP Template place to drop content in via the admin page editor.
  ```
  <?php the_content(); ?>

<a id="oct23"></a>

## October 2023

- simple css hack to help visually debug layout issues..
  ```
    * { border: 1px solid red; }


- node
  Check version with <pre><code>node -v</code></pre>
  ```
    sudo npm cache clean -f 

- -  (force) clear your npm cache
  ```
    sudo npm install -g n 
  
- -  install n (this might take a while)
  ```   
    sudo n stable 
  
- -  upgrade to the current stable version

- If you initially installed Node.js with <a href="https://brew.sh/" target="_blank">Homebrew</a>, run:

<pre><code>brew update</code></pre>

<pre><code>brew upgrade node</code></pre>

<pre><code>npm install -g npm</code></pre>

- Or as a one-liner:

<pre><code>brew update && brew upgrade node && npm install -g npm</code></pre>

- A convenient way to change versions is to use n:

<pre><code>brew install n</code></pre>

- To install the latest version of Node.js with n:

<pre><code>n latest</code></pre>

- Or, to install the latest LTS version with n:

<pre><code>n lts</code></pre>

- Alternatively, you could use nvm instead of <a href="https://github.com/tj/n" target="_blank">n</a>:

<pre><code>brew install nvm</code></pre>

- To install the latest version of <a href="https://nodejs.org/en" target="_blank">Node.js</a> with <a href="https://github.com/nvm-sh/nvm" target="_blank">nvm</a>:

<pre><code>nvm install node</code></pre>

<a id="contents24"></a>

## Table of contents 2024

- [Febraury](#feb24)
<!-- - [March](#mar24)  -->
- [April](#apr24)
<!-- - [May](#may24) -->
<!-- - [June](#jun24) -->
<!-- - [July](#jul24) -->
<!-- - [August](#aug24) -->
<!-- - [September](#sep24) -->
<!-- - [October](#oct24)   -->
<!-- - [November](#nov24)  -->
<!-- - [December](#dec24) -->

<a id="feb24"></a>
<!-- <a id="mar24"></a> -->

<!-- <a id="may24"></a> -->
<!-- <a id="jun24"></a> -->
<!-- <a id="jul24"></a> -->
<!-- <a id="aug24"></a> -->
<!-- <a id="sep24"></a> -->
<!-- <a id="oct24"></a> -->
<!-- <a id="nov24"></a> -->
<!-- <a id="dec24"></a> -->

## February 
<a id="altHacks"></a>
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


### Useful Wordpress Plugins
- - Yoast SEO
- - Wp Mail SMTP
- - Smush
- - GTM4WP
- - Busted!
- - NotificationX
- - Better Find and Replace
- - Better Search Replace
- - WP Rocket
- - Hummingbird


### Common errors for Content Producers (SEO, Performance, Accessibility):
- Title tags and Headline H1 tags:

- - Main Differences:
- - - Title Tags appear in search engines and the Web browser’s title bar
- - - H1 Headers appear within the body text of the webpage
- - - Search engines give more weight to Title Tags than H1 Headers

- - Common Best Practices:
- - - Both Title and H1 should be slightly different, not identical.
- - - Use only one Title Tag and one H1 Header per webpage (Do not use H1 for styling purposes)
- - - Include the page’s primary keyword in both tags
- - - Try to place the keyword early in both tags
- - - Use the keyword only once within each tag
- - - Keep both titles short (55 characters or less recommended, 65 char max) 

- Images:
- - Canvas Sizing: The Canvas size affects file size and processing power. Most Images do not need to over 2000px wide. For larger images such as full width banner, background, or high resolution art I usually still top them out at 2850px. 
- - File sizing: Make and effort to lower file sizes and strip metadata. There are tons of tools out there to make this easy, ImageOptim (free program), TinyPNG (browser), and Adobe Lightroom or Photoshop for a few examples. You can usually get away with even running lossy compression in the 75%-90% range for more file compression before your eyes will see the difference (experiment with this).
- - Accessibility: 
- - - Alt Tags: INCLUDE THEM! Make them Concise enough not to waste a lot of screen reader time but clear enough to translate any content relevancy. In WordPress you can add Alt tags to images as you upload them. In code you do this with and alt="description here" tag. If you can not add them directly in a case like a CSS background image [here are some hacks.](#altHacks)

- Meta Descriptions
- - Max 156 characters, 
- - must different than the Title and Heading

- Content length:
- - Min 300 words.

- ¿ Need to Learn more about Web Components with Vanilla code. ?

### After acquiring benchmark testing scores test these plugins on Group Code (DR0) Site Code (DR0-DRR) as test bed for all (DR0) broad spectrum performance tweaks:
- Wp Rocket
- Smush
- Hummingbird if not rocket
- Broken Link Checker 
- Health Check & Troubleshooting
- WP-Optimize
- GFChart (gravity forms data visuals)
- 

<a id="apr24"></a>

## April 
Animating SVGs can be done by adding a version of the below code inside the shape section (ex: line, path, circle) of an SVG.
```
<animateTransform 
       attributeName="transform" 
       dur="15s"
       type="rotate"
       from="0 50 50"
       to="360 50 50"
       repeatCount="indefinite" />
       
       
## Table of contents 2025

- [June](#jun24)

## June

Zsh Aliases 
''' 
# Example aliases
# alias zshconfig="mate ~/.zshrc"
# alias ohmyzsh="mate ~/.oh-my-zsh"

# GIT
alias g="git"
alias ga="git add"
alias gaa="git add ."
alias gb="git branch"
alias gba="git branch -a"
alias gbb="git branch -b" 
alias gc="git checkout" 
alias gcb="git checkout -b"
alias gcm="git checkout master"
alias gc-m="git commit -m"
alias gm="git merge"
alias gpsh="git push"
alias gpo="git push origin"
alias gs="git status"
alias p="git pull" 
alias po="git pull origin"
alias pom="git pull origin master"
alias openzsh="open ~/.zshrc"
alias viewzsh="cat ~/.zshrc"

# Other Dev
alias ll="ls -FGLAhp"
alias l="ls -lahp"
alias c="clear"
alias b="cd .."
alias nuke="killall node"
alias kill="killall ssh"alias ~="cd ~"
alias edit="subl"
alias find="open -a Finder ./"
alias editrc="subl ~/.zshrc"
alias sourcerc="source ~/.zshrc"
alias path="echo -e ${PATH//:/\\n}"
cd() { builtin cd "$@"; ll; }
alias sourceprofile="source ~/.zprofile"
alias editprofile="source ~/.zprofile"


# CD shortcuts ----------------
alias cdw="cd Workspace"
alias cddr="cd Workspace/DeployedResources"
alias cdp="cd Workspace/Personal"

# NPM ---------------------
alias nrd="npm run dev"
alias st="npm start"
alias i="npm install"
alias up="npm upgrade"
export PATH="/usr/local/opt/ruby/bin:$PATH"

# VSC ---------------------
alias code="/usr/local/bin/code $(pwd) 1>/dev/null 2>&1"

# Fun ---------------------
alias dadJoke="curl -H 'Accept: text/plain' https://icanhazdadjoke.com/ ; echo"export PATH="/usr/local/opt/ruby/bin:/usr/local/lib/ruby/gems/3.0.0/bin:$PATH"
export PATH="$HOME/.gem/ruby/3.0.0/bin:$PATH"

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
export PATH="$PATH:$HOME/.npm-packages/bin"
