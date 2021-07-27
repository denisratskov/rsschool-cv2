Hi! My name is Denis!

My contact: denisratskov@gmail.com or +375336624300

I am an engineer and a musician by education, I wanted to change something in my life, I decided to try myself in programming, again there is no such thing, but I have already made a website for myself ..

At the moment, I know a little ntml and css, according to JS, the script learned the syntax, started with python and also planned to study testing and Kotlin for android..

Starting on Epam course - stage0. Ending course ITDVN - JS Started - 86% of sertificate. Ending course ITEA online on Html & Css - give sertificate. And others..

My English range middle a1 or a2!I gradually tighten my level!

My code

My code:

<!DOCTYPE html>
<html lang="en" moznomarginboxes>
    <head>
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <!-- Metadata -->
        <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Cardo|Montserrat:300,400,500&amp;subset=latin-ext" crossorigin="anonymous" />
        <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.0/normalize.min.css" integrity="sha256-oSrCnRYXvHG31SBifqP2PM1uje7SJUyX0nTwO2RJV54=" crossorigin="anonymous" />
        <link rel="stylesheet" type="text/css" href="https://use.fontawesome.com/releases/v5.1.0/css/all.css" integrity="sha384-lKuwvrZot6UHsBSfcMvOkWwlCMgc0TaWr+30HWe3a4ltaBwTZhyTEggF5tJv8tbt" crossorigin="anonymous" />
        <!-- Custom Styles -->
        <link rel="stylesheet" type="text/css" href="./styles.css" />
        <title>Denis Ratskov CV</title>
	<style>
		@charset "UTF-8";

* {
    min-height: 0;
    min-width: 0;
    box-sizing: border-box;
    transform-origin: 0px 0px 0px;
}

p:blank, li:blank, div:blank, section:blank {
    display: none;
}

p:empty, li:empty, div:empty, section:empty {
    display: none;
}

p:-moz-only-whitespace, li:-moz-only-whitespace, div:-moz-only-whitespace, section:-moz-only-whitespace {
    display: none;
}

/* Page Variables */

:root {
    --main-width: 74%;
    --header-height: 1.2in;
    --sidebar-width: calc(100% - var(--main-width));
}

body {
    font-size: 0.95em;
    margin: 0 auto;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -webkit-tap-highlight-color: transparent;
    text-rendering: optimizeLegibility;
    text-decoration-skip: ink;
    hyphens: auto;
}

#save > section:first-of-type {
    display: flex;
    flex-direction: row;
}

.summary {
    font-size: 105%;
}

/* Misc */

img {
    max-width: 100%;
}

p {
    margin-top: 0;
    margin-bottom: 0;
}

abbr[title] {
    text-decoration: none;
    border: none;
}

ul {
    margin: 0;
    padding: 0;
}

li {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

li + li {
    margin-top: 0.4em;
}

.fa, .fab {
    text-align: center;
    min-width: 1em;
}

li .fa, li .fab {
    margin-right: 0.3em;
}

/* Page layout */

#save > section:first-of-type > aside {
    flex-basis: var(--sidebar-width);
    padding: 0.1618in 0 0.1618in 0.1618in;
    display: flex;
    flex-direction: column;
}

#save > section:first-of-type > aside > section + section {
    margin-top: 2em;
}

#save > section:first-of-type > aside > section:last-child {
    margin-top: auto;
} 

#save > section:first-of-type > section {
    flex-basis: var(--main-width);
    display: flex;
    flex-direction: column;
}

#save > section:first-of-type > section > header {
    flex-basis: var(--header-height);
    flex-grow: 0;
    padding: 0.1618in;
}

#save > section:first-of-type > section > section {
    flex-grow: 1;
    padding: 0.1618in;
    padding-top: 0;
    display: flex;
    flex-direction: column;
}

#save > section:first-of-type > section > section > section + section {
    margin-top: 1em;
}

#save > section:first-of-type > section > section > section:last-child {
    margin-top: auto;
}

.references address {
    font-style: normal;
    font-weight: 300;
}

.references address:first-line {
    font-weight: 400;
}

.references address + address,
.references address + p {
    padding-top: 0.5em;
}

/* Skills */

.skills {
    font-size: 92%;
}

.skills > ul:after {
    content: '';
    display: table;
    clear: both;
}

.skills > ul > li {
    display: block;
    float: left;
    margin: 6px 6px 0 0;
}

.skills > ul > li > span {
    background-color: #f5f5f5;
    border: 1px solid rgba(45, 45, 45, 0.1618);
    border-radius: 3px;
    color: #333;
    padding: 4px 8px;
    display: inline-block;
}

/* Experience & Education */

.education ol,
.experience ol {
    margin: 0;
    padding: 0;
}

.experience ol {
    flex-wrap: wrap;
    display: flex;
    flex-direction: row;
}

.experience ol > li {
    margin: 0;
    padding: 0;
    flex-basis: 100%;
    font-weight: 300;
}

.education ol > li {
    font-weight: 300;
}

.experience ol > li + li {
    margin-top: 1em;
}

.education ol > li div,
.experience ol > li header {
    display: flex;
    flex-direction: row;
}

.experience ol > li > span,
.education ol > li p,
.experience ol > li header p {
    font-weight: 400;
}

.experience ol > li header p {
    font-size: 110%;
}

.education ol > li div > *:last-child,
.experience ol > li header > *:last-child {
    margin-left: auto;
}

.experience ol > li ul {
    padding-top: 0.5em;
}

.experience ol > li ul li {
    list-style-type: circle;
    margin-left: 1.618em;
}

/* Paper CSS:  */

@page { margin: 0 }
body { margin: 0 }
.sheet {
  margin: 0;
  overflow: hidden;
  position: relative;
  box-sizing: border-box;
  page-break-after: always;
}

/** Paper sizes **/
body.A3               .sheet { width: 297mm; height: 419mm }
body.A3.landscape     .sheet { width: 420mm; height: 296mm }
body.A4               .sheet { width: 210mm; height: 296mm }
body.A4.landscape     .sheet { width: 297mm; height: 209mm }
body.A5               .sheet { width: 148mm; height: 209mm }
body.A5.landscape     .sheet { width: 210mm; height: 147mm }
body.letter           .sheet { width: 216mm; height: 279mm }
body.letter.landscape .sheet { width: 280mm; height: 215mm }
body.legal            .sheet { width: 216mm; height: 356mm }
body.legal.landscape  .sheet { width: 357mm; height: 215mm }

/** Padding area **/
.sheet.padding-10mm { padding: 10mm }
.sheet.padding-15mm { padding: 15mm }
.sheet.padding-20mm { padding: 20mm }
.sheet.padding-25mm { padding: 25mm }

/** For screen preview **/
@media screen {
  body { background-color: rgb(83, 86, 89); /*#e0e0e0*/ }
  .sheet {
    background: white;
    box-shadow: 0 .5mm 2mm rgba(0,0,0,.5);
    margin: 5mm auto;
  }
}

/** Fix for Chrome issue #273306 **/
@media print {
  body.A3.landscape          { width: 420mm }
  body.A3, body.A4.landscape { width: 297mm }
  body.A4, body.A5.landscape { width: 210mm }
  body.A5                    { width: 148mm }
  body.letter, body.legal    { width: 216mm }
  body.letter.landscape      { width: 280mm }
  body.legal.landscape       { width: 357mm }
}

html {
    padding: 2.4em;
}

.sheet {
    border: 1px solid black;
}

#save > section:first-of-type > aside {
    background-color: #f5f5f5;
}

#save > section:first-of-type aside .skills > ul > li > span {
    background-color: white;
}

button, a[role="button"] {
    user-select: none;
}

#document-controls {
    position: fixed;
    right: 0;
    top: 0;
    margin-top: 0.5em;
    margin-right: 0.5em;
    display: flex;
    flex-direction: column;
}

#document-controls button + button,
#document-controls button + a[role="button"],
#document-controls a[role="button"] + a[role="button"],
#document-controls a[role="button"] + button {
    margin-top: 0.5em;
}

#github-link {
    display: block;
    position: fixed;
    left: 0;
    top: 0;
    margin-top: 0.5em;
    margin-left: 0.5em;
    text-decoration: none;
    color: black;
}

/* Source https://www.bestcssbuttongenerator.com/#/36 */

button, a[role="button"] {
	box-shadow:inset 0px 1px 0px 0px white;
	background:linear-gradient(to bottom, #ededed 5%, #dfdfdf 100%);
	background-color:#ededed;
	border-radius:6px;
	border:1px solid #dcdcdc;
	display:inline-block;
	cursor:pointer;
	color:#777777;
	font-size:15px;
	font-weight:bold;
	padding:6px 24px;
	text-decoration:none;
	text-shadow:0px 1px 0px white;
}

button:hover, button:active,
a[role="button"]:hover, a[role="button"]:active {
	background:linear-gradient(to bottom, #dfdfdf 5%, #ededed 100%);
	background-color:#dfdfdf;
}

button:active, a[role="button"]:active {
	position:relative;
	top:1px;
}

	</style>
    </head>
    <body class="letter">
        <section id="save">
            <section class="sheet">
                <aside>
                    <a href="https://rs.school/js/">
                        <img src="https://github.com/denisratskov/rsschool-cv/blob/gh-pages/dImWmNTua70.jpg?raw=true" alt="rs.school"> 
                    </a>
                    <section class="contact">
                        <h6>Contact</h6>
                        <ul>
                            <li>
                                <p><i class="fa fa-map-marker-alt" title="Location"></i> BY, Minsk</p>
                            </li>
                            <li>
                                <p><i class="fa fa-phone" title="Cell phone"></i> <a href="tel:+375336624300">+375336624300</a></p>
                            </li>
                            <li>
                                <p><i class="fa fa-envelope" title="Email"></i> <a href="mailto:denisratskov@gmail.com">denisratskov@gmail.com</a></p>
                            </li>
                            <li>
                                <p><i class="fa fa-globe-americas" title="Website"></i> <a href="https://denisratskov.tk">denisratskov.tk</a></p>
                            </li>
                            <li>
                                <p><i class="fab fa-github" title="GitHub"></i> <a href="https://github.com/denisratskov">github.com/denisratskov</a></p>
                            </li>
                        </ul>
                    </section>
                    <section class="skills">
                        <h6>Others</h6>
                        <ul>
                            <li><span>Music Producer</span></li>
                            <li><span>Energy Profession</span></li>
                            <li><span>Music Engineer</span></li>
                            <li><span>DJ</span></li>
                        </ul>
                    </section>
                    <section class="skills">
                        <h6>Technologies</h6>
                        <ul>
                            <li><span>JS</span></li>
                            <li><span>Kotlin</span></li>
                            <li><span>HTML</span></li>
                            <li><span>CSS</span></li>
                            <li><span>Ableton</span></li>
                            <li><span>Pyton</span></li>
                        </ul>
                    </section>
                    <section class="skills">
                        <h6>Web - Pages - Official</h6>
                        <ul>
                            <li><span>http://www.denisratskov.tk/</span></li>
                            <li><span>http://djratek.tilda.ws/</span></li>
                            <li><span>https://ratskov.wordpress.com/</span></li>
                            <li><span>denisratskov.wixsite.com/djratek</span></li>
                        </ul>
                    </section>
                    <section class="skills">
                        <h6>Web - Pages - Contact</h6>
                        <ul>
                            <li><span>https://vk.com/denisratskov/</span></li>
                            <li><span>https://vk.com/djratek/</span></li>
                            <li><span>https://promodj.com/djratek</span></li>
                        </ul>
                    </section>
                    <section class="references">
                    </li>                 
                    <li>
                        <a href="https://github.com/denisratskov">
                            <img width="40" height="40" src="https://avatars.githubusercontent.com/u/86842448?s=400&v=4" alt="github"> 
                        </a>
                    </li>

                    </section>
                </aside>
                <section>
                    <header class="name" aria-label="Denis Ratskov">
                        <a href="https://denisratskov.tk">
                            <svg width="257px" height="35px" viewBox="0 0 257 35" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                                <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" font-family="Montserrat-Regular, Montserrat" font-size="48" font-weight="normal">
                                    <g id="Letter" transform="translate(-54.000000, -140.000000)" fill="#484848">
                                        <text id="DENIS-RATSKOV">
                                            <tspan x="54.728" y="174">RATSKOV</tspan>
                                        </text>
                                    </g>
                                </g>
                            </svg>
                        </a>
                        <h6>Front-end and Android Engineer</h6>
                        <hr />
                    </header>
                    <section>
                        <section class="summary">
                            <h6>Summary</h6>
                            <p>
                                Hi! My name is Denis! I am an engineer and a musician by education, I wanted to change something in my life, I decided to try myself in programming, but I have already made a website for myself .. At the moment, I know a little ntml and css, according to JS, the script learned the syntax, started with python and also planned to study testing and Kotlin for android.. 
                            </p>
                        </section>
                        <section class="experience">
                            <h6>Experience</h6>
                            <ol>
                                <li>
                                    <header>
                                        <p class="sanserif">Start Software Engineer</p>
                                        <time>2021 – Present</time>
                                    </header>
                                    <ul>
                                        <li>Starting on Epam course - stage0</li>
                                        <li>Ending course ITDVN - JS Started - 86% of sertificate</li>
                                        <li>Ending course ITEA online on Html & Css - give sertificate</li>
                                    </ul>
                                </li>
                                <li>
                                    <header>
                                        <p class="sanserif">Languages 1</p>
                                        <time>Past - Present</time>
                                    </header>
                                    <span>English</span>
                                    <ul>
                                        <li>A1+</li>
                                        <li>pull up to A2</li>
                                    </ul>
                                </li>
                                <li>
                                    <header>
                                        <p class="sanserif">Languages 2</p>
                                        <time>Past - Present</time>
                                    </header>
                                    <span>Russian</span>
                                    <ul>
                                        <li>Main Language</li>
                                        <li>Very Goog</li>
                                        <li>native Belarusian and understanding of Ukrainian</li>
                                    </ul>
                                </li>
                                <li>
                                    <header>
                                        <p class="sanserif">Technical Skills</p>
                                        <time>Past - Present</time>
                                    </header>
                                    <ul>
                                        <li>HTML, CSS</li>
                                        <li>JavaScript</li>
                                        <li>Git, VScode</li>
                                        <li>Tilda, Wordpress</li>
                                        <li>Windows Software</li>
                                        <li>Pyton</li>
                                        <li>Kotlin</li>
                                        <li>Android Software</li>
                                        <li>QA Testing</li>  
                                    <ul>
                                </li>
                                <li>
                                    <header>
                                            alert("Ура")
                                    <ul>
                                </li>
                            </ol>

                        </section>
                        <section class="education">
                            <footer>
                                    <a href="https://rs.school/js/">
                                        <img width="100" height="40" src="https://rs.school/images/rs_school_js.svg" alt="rs.school"> 
                                    </a>
                                    <footer1>
                                    <time>2021</time>
                                    </footer1>
                            </footer>
                        </section>
                    </section>
                </section>
            </section>
        </section>

        </main>
    
        <!-- Script -->
        <script type="text/javascript" src="./index.js"></script>
    </body> -->
</html>




