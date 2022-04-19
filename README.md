# Portfolio Page

## Purpose of This Project

The purposed of this project was to create a portfolio page where I can display my recent web development projects. Building this page is an important step towards becoming a competitive candidate for potential employers in the near future. I will be able to continually add content to this page as I complete more and more projects.

I built this simple portfolio page using primarily HTML. I utililized the Bulma.io CSS framework in combination with my own CSS stylesheet to give this page a customized design.


## Links

* Deployed Application: https://atmason90.github.io/portfolio-page/
* GitHub Repository: https://github.com/atmason90/portfolio-page 


## Site Demo

![demo gif](./assets/images/2022-04-18%2019.23.51.gif)


## Code Examples

This is an example of how to build a navbar in HTML using the Bulma.io framework. 

```html
<body class="has-navbar-fixed-top">
    
    <nav class="navbar is-fixed-top" role="navigation" aria-label="main navigation">
        <div class="navbar-brand is-flex is-justify-content-center">
            <p id="navTitle" class="is-size-2 ml-3">Andrew Mason <span id="navSpan" class="is-flex-mobile is-justify-content-center is-size-6">Full Stack Web Developer</span></p>
        </div>
        <div id="navMenu" class="navbar-menu is-active">
            <div class="navbar-start"></div>
            <div class="navbar-end is-flex is-justify-content-space-between mr-7 ml-7">
                <a class="navbar-item" href="#aboutMe">About Me</a>
                <a class="navbar-item" href="#projects">Projects</a>
                <a class="navbar-item" href="./assets/resume/andrewmason-webdev-resume.pdf" target="#">My Resume</a>
                <a class="navbar-item" href="https://www.linkedin.com/in/andrewmason0529/" target="#">LinkedIn</a>
                <a class="navbar-item" href="https://github.com/atmason90" target="#">GitHub</a>
            </div>
        </div>
    </nav>
```

This is an example of how to use Bulma tiles with proper hierarchical tiers of ancestor, parent, and child elements.

```html
<div class="tile is-ancestor mt-6 p-5">
        <div class="tile is-parent">
            <article id="aboutMe" class="tile is-child notification has-text-grey-dark">
              <div class="content">
                <p class="title is-flex is-justify-content-center">About Me</p>
                <figure class="image is-128x128 is-flex is-justify-content-center m-auto">
                    <img class="is-rounded" src="./assets/images/professionalpic.jpeg" alt="Andrew Mason headshot">
                </figure>
                <div class="content">
                    <p class="mt-5">I am a recent graduate of the UC Berkeley Extension Full Stack Coding Bootcamp (Jun 2022) that is excited and highly motivated to begin my career in web development.</p>
                    <p>My background in management consulting has made me highly proficient working with teams to create dynamic and lasting business solutions. I bring a tenacity and a desire to learn, grow and achieve into any endeavor, which makes me an asset to any organization or community I am a member of.</p>
                </div>
              </div>
            </article>
        </div>
```


## Technologies Used

* ![HTML Badge](https://img.shields.io/badge/Language-HTML-blue)
* ![CSS Badge](https://img.shields.io/badge/Language-CSS-yellow)
* ![Bulma Badge](https://img.shields.io/badge/Framework-Bulma.io-9cf)


## License

MIT License

Copyright (c) 2022 Andrew Mason

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
