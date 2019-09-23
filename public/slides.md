
class: center middle main-title

# What Can Wesley Do?
Press "P" to enter presentation mode, and see annotations.

???
> Press "C" to open cloned view, press "P" to exit presentation mode.

I write, architect, and promote maintainable code; plan large projects; research and promote best practices; and provide and foster mentorship in front-end engineering and all of these skills.

---
class: center middle main-title


## Experience

Most Recent CMS Project [→](#3)

Web Application Experience [→](#7)

Pattern Library & Design System [→](#11)

Websites, CMS's, E-Commerce, & ERP [→](#13)

Other Skills & Projects [→](#17)

???

I've organized my experience by what I percieve to be most relevant to the job description.

If there is a topic that need not be covered at all, or further once started, then please interrupt me.


---
class: center middle main-title


# Most Recent CMS Project
Craft CMS | static files | Atomic Design

---

### Craft CMS \*

.accent[A content management system that is built to meet team needs.]

- .text-icon[+] most **user-friendly** CMS on the market
- .text-icon[+] extremely **extensibile** feature set
- .text-icon[–] **but** has _high developer learning curve_

> \* Researched and compared against other CMS's (see [research document](./images/cms-research.pdf))

### static files

.accent[A website that merely serves files, then calls APIs as necessary.]

- .text-icon[+] deployment is **simple** and **flexible**
- .text-icon[+] **fast load time** in terms of _"time to first render"_
- .text-icon[–] **but** any dynamic content _depends on JavaScript_

### Atomic Design

.accent[A design methodology to organize patterns, and a library to review them in isolation.]

- .text-icon[+] think of **user interfaces as hierarchies**
- .text-icon[+] basis of an **effective pattern library**
- .text-icon[…] can transform **design and development workflow**

???

- **Craft CMS**, [researched and compared against other CMS's](./images/cms-research), was chosen to allow a cohesive editor/designer/developer workflow:
    - Editors can manipulate and format text, and choose images.
    - Designers can edit layout and provide and manage images.
    - Developers can focus on modules and website performance.

- Deploying only **static files** allowed teams to decouple user interface, web service, and backend logic. _But, any dynamic content would not work if use has disabled JavaScript._

- **Atomic Design** gave stakeholders and contributors a common vocabulary for user interfaces.


---
class: center middle main-title


## Craft CMS & Atomic Design

- [atomic design visual](http://atomicdesign.bradfrost.com/images/content/atomic-design-process.png)
- <del>annotated admin UI</del>
| [live admin UI](https://wes-craft-cms.herokuapp.com/admin/entries)
- <del>annotated webpage</del> | [live website](https://www.vyprvpn.com)

???

The concept of atomic design was applied to the CMS, but the vocabulary of atomic design was not used.

So, I have created an [annotated screenshot](./images/craft-cms-and-atomic-design.png) that layers the two for a visual of the final result.

Also, we can log in to a [live admin interface](https://wes-craft-cms.herokuapp.com/admin/entries) to play around.


---
class: center middle main-title


## static files & APIs & deployment

![Illustration of static files affect on deployment and backend communication](https://images-na.ssl-images-amazon.com/images/G/01/img15/pet-products/small-tiles/23695_pets_vertical_store_dogs_small_tile_8._CB312176604_.jpg)
> This is supposed to be a over-simplified icon-based illustration of a decoupled website, but I did not have time.
> <br/><small>Maybe, it is a metaphor for the fun and ease of deployment, and **"fetch"**ing data from APIs.</small>

???

Static files include basic web text files (HTML, CSS, and JavaScript).

The HTML and CSS is enough to load static content. Any dynamic content is loaded by JavaScript via an API from which comes data managed by a back-end service.

The static files can independently be served from any configuration of any amount of servers.


---
class: center middle main-title


# Web Application Experience
learn → develop → architect → mentor

---

### Web Applications

#### Learn

| Dump Truck v1 | _online storage_
| -: | :-
| Sample Work | none
| Responsibility | specific user interface challenges
| Technologies | HTML, CSS, JavaScript, jQuery

| Dump Truck v2 | _online storage_
| -: | :-
| Sample Work | [features](https://www.goldenfrog.com/blog/welcome-to-dump-truck-part2-web-app), [thumbnail view](https://www.goldenfrog.com/blog/dump-truck-web-app-thumbnail-view-update)
| Responsibility | user interface
| Technologies | HTML, CSS, JavaScript, jQuery, <abbr title="lightweight JavaScript framework">JavaScriptMVC</abbr>

#### Develop

| Cyphr | _secure messaging_
| -: | :-
| Sample Work | [screenshot](https://uploads-ssl.webflow.com/5cebfb3d5d0f474f39a1cdba/5ced47499dfb42a84d8de8b4_cyphr_4.jpg) (from [product/brand showcase](https://www.goldenfrog.com/blog/welcome-to-dump-truck-part2-web-app))
| Responsibility | user interface, <abbr title="Model-View-Controller">MVC</abbr>, API calls, shared modules
| Technologies | HTML, CSS (<abbr title="Syntastically Awesome Style Sheets">SASS</abbr> + <abbr title="Scalable & Modular Architecture CSS">SMACSS</abbr> + <abbr title="Object-Oriented CSS">OOCSS</abbr>), JavaScript, jQuery, <abbr title="heavyweight JavaScript framework">Ember.js</abbr>, Promises,<br/>NPM, auto-generated documentation (<a title="JavaScript documentation via comments" href="http://docstrap.github.io/docstrap/themes/simplex/">JSDoc</a> & <abbr title="CSS documentation via comments">Styleguide.js</abbr>)

???

I began Dump Truck (online storage app) development by helping solve version 1 UX problems. I was invited to join the Software Engineering team full time to own the user interface of version 2.

I began Cyphr (secure messaging app) development on just the user interface, but later took over the entire web application. I also created reusable CSS and JavaScript modules in shared repositories.

---

### Web Applications, Cont.

#### Architect

| VyprVPN Router | _VPN service usage_
| -: | :-
| Sample Work | screenshots [#3 and #4](https://forum.goldenfrog.com/t/new-vyprvpn-router-app-now-available-for-testing/98/61) (and [#2](https://static-goldenfrog.netdna-ssl.com/images/vyprvpn/vypr-router/screenshot_2.png) and [#1](https://static-goldenfrog.netdna-ssl.com/images/vyprvpn/vypr-router/screenshot_1.png))
| Responsibility | user interface, API calls
| Technologies | HTML, CSS, JavaScript

| VyprVPN Cloud | _VPN server admin_
| -: | :-
| Sample Work | [screenshots](https://support.goldenfrog.com/hc/en-us/articles/360004446071-How-do-I-manage-my-DNS-)
| Responsibility | mentoring; user interface, <abbr title="Model-View-View-Model">MVVM</abbr>, API code, shared modules
| Technologies | HTML, CSS (<abbr title="Scalable & Modular Architecture CSS">SMACSS</abbr>), <abbr title="lightweight modern JavaScript framework">Aurelia.io</abbr>, ES6+, Python, NPM, Bash

| VyprVPN SDK | _example web app (for VPN service usage)_
| -: | :-
| Sample Work | screenshots [#1](https://www.qnap.com/images/products/Application/notes/VyprVPN_02.png), [#2](https://download.qnap.com/QPKG/img/vyprvpn_640x400_screen1.png), [#3](https://download.qnap.com/QPKG/img/vyprvpn_640x400_1.png)
| Responsibility | user interface, <abbr title="Model-View-View-Model">MVVM</abbr>, API calls, shared modules
| Technologies | HTML, CSS (<abbr title="Transform CSS with JS">PostCSS</abbr> + <abbr title="Block Element Modifier">BEM</abbr> + <abbr title="Inverted Triangle CSS">ITCSS</abbr>), <abbr title="lightweight modern JavaScript framework">Aurelia.io</abbr>, ES6+, shared modules,<br/>auto-generated documentation (<a title="JavaScript documentation via comments" href="http://docstrap.github.io/docstrap/themes/simplex/">JSDoc</a> & <abbr title="CSS documentation via comments">Styleguide.js</abbr>), NPM, Bash

???

VyprVPN (router app) was my first project as a member of the "Skunk Works" R&D team. The challenge was to limit code size (because of limited disk space on a router). So, zero libraries were used.

VyprVPN (administration interface) had limited future scope. The challenge was to find a lightweight and modern framework, minimize code architecture, and mentor an intern. I also worked on the API in Python.

Finally, there was a VyprVPN example web app bundled with an SDK package for external developers to create their own VyprVPN service application.

---

### Web Applications, Cont. (even more)

#### Mentor

| Outfox App | _desktop app interface_
| -: | :-
| Sample Work | [screenshots](https://www.cbrennand.com/work/outfox)
| Responsibility | architecture, mentoring; user interface, <abbr title="Model-View-View-Model">MVVM</abbr>, shared modules
| Technologies | HTML, CSS (<abbr title="Transform CSS with JS">PostCSS</abbr> + <abbr title="Block Element Modifier">BEM</abbr> + <abbr title="Inverted Triangle CSS">ITCSS</abbr>), <abbr title="lightweight modern JavaScript framework">Aurelia.io</abbr>, ES6+, shared modules, <abbr title="Cross-platform desktop apps with JavaScript">Electron</abbr>,<br/>3rd-party <abbr title="authentication">auth.</abbr>, NPM, Bash, auto-generated documentation (<a title="JavaScript documentation via comments" href="http://docstrap.github.io/docstrap/themes/simplex/">JSDoc</a> & <abbr title="CSS documentation via comments">KSS</abbr>)

| Outfox Service | _signup & control panel_
| -: | :-
| Sample Work | [sign up](https://www.getoutfox.com/subscribe) & [control panel](https://www.getoutfox.com/controlpanel/login)
| Responsibility | management; architecture, mentoring
| Technologies | HTML, CSS (<abbr title="Transform CSS with JS">PostCSS</abbr> + <abbr title="Block Element Modifier">BEM</abbr> + <abbr title="Inverted Triangle CSS">ITCSS</abbr>), <abbr title="lightweight modern JavaScript framework">Aurelia.io</abbr>, ES6+, shared modules, Node,<br/>3rd-party <abbr title="authentication">auth.</abbr>, NPM, auto-generated documentation (<a title="JavaScript documentation via comments" href="http://docstrap.github.io/docstrap/themes/simplex/">JSDoc</a> & <abbr title="CSS documentation via comments">KSS</abbr>)

???

Outfox (desktop app) user interface project was my transition from developer to architect; I delegated work to and mentored developers and an intern who each had different degrees of web dev experience.

Outfox (service) control panel project had me mentoring devs, who primarily worked in HTML & CSS, to build a dynamic JavaScript-heavy web application (all of whom are now full-time JavaScript developers).


---
class: center middle main-title


# Pattern Library & Design System
- Auto-generate a pattern library from stylesheet comments.
- Use existing CMS for website to build its design system.

???

A pattern library is an organized showcase of re-usable patterns, typography, iconography, and colors on a website or suite of websites.

A design system can include a content style guide, branding style guide, and pattern library; and serves as a set of standards to maintain a cohesive visual identity.

---

### Pattern Library & Design System \*

#### Pattern Library

<del>sample pattern library</del>
> (not public yet; [private host link](http://127.0.0.1:8080/developer/docs/styles/index.html))
- added structured comments (and sample HTML) to stylesheets
- used seprate template files for complex sample HTML
- organized patterns by defining hierarchy via comment

#### Design System

<del>sample design system</del>
> (incomplete)
- served dedicated CMS pages into a microsite
- bundled in the auto-generated pattern library
- used for internal or external reference

> \* Examples of design systems—**not my work**: [University of Texas](https://utsystem.edu/sites/branding/primary-colors), [Shopify](https://polaris.shopify.com/), [Salesforce](https://www.lightningdesignsystem.com/), [IMB Cloud](http://carbondesignsystem.com/)

???

Wesley, run this command in terminal **before** clicking "sample pattern library" link:
```
http-server /Users/wesleyb/Code/phm/wesleyb-craft-cms/public
```

I researched around fifteen pattern library tools. The choice considered usability, investment, maintainability, flexibility, and learning curve. For flexibility across projects and minimal investment and learning curve, I opted for solutions that rely solely on comments within stylesheets, and optional template files.

---
class: center middle main-title


# Websites, CMS's, E-Commerce, & ERP
install, develop, maintain, customize

???

I've created 18 websites; maintained, expanded, and managed 6 websites; used and customized 7 content management systems, and developed an ERP system.


---

## Recent

### Websites

- [Portfolio Website & Resume](http://wesleyb.io)
- [Marketing & Product Sign Up — _Network Optimization_](https://getoutfox.com)
- [Marketing — _Privacy & Security Software_](https://goldenfrog.com/)
- [Marketing & Product Sign Up — _VPN Service_](https://www.vyprvpn.com/our-commitment)
- [Marketing — _Data Center & Colocation Services_](https://datafoundry.com/)
- [Marketing — _Usenet Service, Brand #1_](https://giganews.com/)
- [Marketing — _Usenet Service, Brand #2_](https://usenet.net/)

### Technology
- .accent[Front-End]: HTML + CSS + JavaScript, Node + NPM
- .accent[Back-End]: Scala + Lift, Mason (Perl)
- .accent[CMS]: WordPress, Craft CMS

???

Since my recent non-CMS website work has been mostly oversight, with occasionaly JavaScript, I created a personal website to play with markdown parsing, deployment pipelines, DOM manipulation, responsive design, newer NPM features, async/await, and the latest CSS features—stage 0 through 3.

---

## Florists

### Websites
- [2013: Florist E-Commerce](https://atxflowers.com/) + [heavily-customized shopping cart](https://yi3themes.myshopify.com/admin/themes/171617873/editor#/cart)
    - Delivery customizations with comprehensive parameters:
        - require delivery date and/or time, different prices for different times, extra text
        - allow same-day delivery; activate company vacation dates; error handling
        - free delivery for pre-orders, in-store pick-up, and/or ASAP delivery charge
    - Avoided buying shipping module by implementing workaround:
        - Calculate delivery cost by automatically adding a delivery "product" after user enters zip code; the product attribute is a specific zip code.
    - Other features: shipping cost calculator, special instructions, card message
- [2013: Florist E-Commerce, Coming Soon](http://flowersarehappy.yi3artist.com/) + flexible & responsive design
- .accent[2012: Florist E-Commerce]

### Content Management Systems
- Magento, Shopify

???

I implemented three florist websites to help a friend and to learn responsive web design, another e-commerce platform, and how to achieve creative solutions to challenging customization requirements.


---

## Legacy

### Websites
- .accent[2011: Web Design Company]
    - [banner slider with stylized text](https://web.archive.org/web/20111217085913/http://www.aquim.com/#1)
    <br/>Real text in banner is available for SEO.
    - [accordian-within-accordian article navigation inside paragraphs](https://web.archive.org/web/20120102161126/http://www.aquim.com/webdesign.html)
    <br/>The content links can open within context or in a new tab.
    <br/>_The "our approach" link opens content that itself has nested content._
    - [example of experimental layout](https://codepen.io/rrenula/pen/DGrhf)
    <br/>This website is lost, but all content was within vertical accordian sections.
- .accent[2011: Portfolio Website & Resume]
    - [unique split-screen, accordian, and tabbed navigation](http://yi3artist.com)
- .accent[2010—2012: Marketing / Product Websites]
    - [6 final websites](https://web.archive.org/web/20190123082625/https://aquim.com/our-creations.html), [5 basic websites](https://web.archive.org/web/20120311134214/http://www.aquim.com/our-creations.html?paging=2&page=our-creations), [2 earlier websites](https://web.archive.org/web/20120311134214/http://www.aquim.com/our-creations.html?paging=3&page=our-creations), 1 proprietary <abbr title="Enterprise Resource Planning">ERP</abbr> system

### Content Management Systems
- Wordpress, <big>sinc.</big> CMS, Joomla, PrestaShop, Magento, TYPOlight (now called Contao)

???

For my last two years living in China, I churned out websites on whichever CMS best matched client requirements—and each with some level of customization. Also, I made a resume website with a unique layout.


---
class: center middle main-title


# Other Skills & Projects
programming | documentation | knowledge sharing | tech. prod. mgmt.

---

### Programming

- game development _(mostly incomplete)_:
<br/>.accent[TypeScript], .accent[C#], .accent[JavaScript]
- browser-based RPG _(forever refactoring)_:
<br/>.accent[PHP+MySQL], .accent[PHP+XML], .accent[CakePHP+MySQL], .accent[Ruby on Rails], .accent[Node+MongoDB], .accent[Aurelia.io+Node]

### Documentation

- technical and non-technical instruction for ~200 website components
- `README.md`'s, code comments, research, standards & practices
- mentored teammates in documentation creation and maintenance

### Knowledge Sharing

- hosted and led two "Communities of Practice" for about four years
    - Front-End Development — _I taught, led discussions, took notes, and managed._
    - Software Engineering — _I managed, led discussions, and took notes._
- maintained Front-End team wiki of 500+ documents: create, refine, delegate, organize 

### Tech. Product Mgmt.

> I don't like it, but I'm really good at it. 😔

---
class: center middle main-title


# Questions & Answers


---
class: center middle main-title


This slide intentionally left blank.


---
class: center middle main-title


# Credits

### past employers
for letting me lead their web development

### .accent[Y'all!]
.accent[for giving me your time and consideration]

### me
for presentation material

### [`gnab/remark`](https://github.com/gnab/remark)
_for a simple, in-browser, markdown-driven slideshow tool_

???

Thank you for your time and consideration, today.

---
class: custom-slide-final

