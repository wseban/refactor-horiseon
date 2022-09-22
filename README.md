# Refactoring Code

## Site Picture
![Site](./assets/images/horiseon-pic.png)

## Technologies Used
- HTML - Builds the basic struction and content of the site.  The original had many unspecified divisions within the code which I replaced with semantic HTML.
- CSS - Builds upon a basic HTML structure by styling the page.  Includes changes such as colors of text, background and positioning of all items on the page.
- Git - Git is what I used to work on my personal computer and pushing my work to GitHub.
- GitHub - A cloud based repository that holds my saved code reserved for resetting my personal computeror deployment.

## Description

The purpose of refactoring the code for Horiseon was to add semantic HTML into the website, as well as, improve the logical workflow of the webpage code.  The end result improved the accessibility standards for anyone with disabilities who need assistive technology to access the webpage.

## Installation

NA

## Usage

Assistive technology will now be able to specify each section of the webpage more effectively and accurately.  Furthermore, if you open the code within a code reader you will notice detailed elements and attributes pertaining to divisions within the webpage.  All this was accomplished without changing any functionality to the webpage; as per clients request.

## Code Snippets
Before:
```html
<body>
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
    <div class="hero"></div>
```
After:    
```html
    <body>
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
    <figure class="hero"></figure>
```


## Credits

NA

## License
Please refer to the LICENSE in the Repo.


