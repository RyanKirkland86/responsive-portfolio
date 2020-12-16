
# Creating a Responsive Portfolio Using Bootstrap

## Project:

This is a portfolio template with responsive design elements and systems using CSS in Bootstrap. Each webpage
will change to scale according to the screen it's on, from mobile to desktop. Images adjust in relation to their surroundings, text wraps around images, the navbar changes from a hamburger icon to an expanded navbar, and elements contained within the body of the page will adjust according to the space around them.

<br>

![Image](https://github.com/RyanKirkland86/responsive-portfolio/blob/main/assets/IndexEx.jpg)
![Image](https://github.com/RyanKirkland86/responsive-portfolio/blob/main/assets/ContactEx.jpg)
![Image](https://github.com/RyanKirkland86/responsive-portfolio/blob/main/assets/PortfolioEx.jpg)

```html
<!--Added navbar from Bootstrap-->
    <nav class="navbar navbar-expand-lg navbar-dark bg-info">
        <div class="container-fluid">
<!--Set header link to the root-->
          <a class="navbar-brand" href="index.html">
              <h1>Ryan Kirkland</h1></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">           
<!--Customized buttons, making sure to keep the deadlink for current page-->
              <a class="nav-link" href="contact.html">Contact</a>
              <a class="nav-link" href="portfolio.html">Portfolio</a>
              <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">About</a>
            </div>
          </div>
        </div>
      </nav>
```

<br>

## Technologies Used:
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [BootStrap](https://getbootstrap.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

## Process:
The three webpages were created using modern HTML Semantics for accessibility. Nearly all design elements used Bootstrap components code with minimal media inquiries.

## Deployed Link:

* [Responsive Portfolio](https://ryankirkland86.github.io/responsive-portfolio/)


## Authors:
- Ryan Kirkland
- [GitHub](https://github.com/RyanKirkland86)
- [LinkedIn](https://www.linkedin.com/in/ryan-kirkland-619942200/)
- [Contributors](https://bootcamp.berkeley.edu/coding/)
- [Bootstrap](https://getbootstrap.com/)

## License:
This project is licensed under the MIT License.

## Acknowledgements:
Thank you to UCB Extension for the help with this project. And a huge thank you to the wonderful people behind Bootstrap, without whom this and many other projects could not exist.