<p align="center">
<a href="https://grzegorz-jodlowski.github.io/creative-agency/"><img src="logo1.jpg" title="logo" alt="pharmaceutical mortar with a pistol"></a>
</p>


# <p align="center">⚡ Creative agency</p>
<p align="center">Project for learning advanced CSS</p>


</br>

## Table of Contents

- [What's this project about?](#about)
- [Technologies used](#technologies)
- [What I learned?](#what)
- [Interesting code snippet](#interesting)
- [GitHub Pages](#gitHub)

</br>

## <a name="about"></a>What's this project about?

Responsive website for a creative agency with drop-down menu, services, portfolio and contact sections.

</br>

## <a name="technologies"></a>Technologies used
- HTML
- CSS (with Flexbox)
- SCSS

</br>

## <a name="what"></a>What I learned?

- create layouts in a modern way,
- write advanced CSS and SCSS,
- use pseudoclasses and pseudoselectors,
- create a multi-level menu,
- set elements on the page using a flexbox,
- add responsiveness to website (using media queries),
- check the appearance of the page on different screens (e.g. <a href="http://responsiv.eu/">Responsive View</a>)
- create animation using CSS,
- find an interesting hover effects  (e.g. <a href="https://tympanus.net/Development/HoverEffectIdeas/">Hover Effect Ideas</a>),
- use the chrome inspector in an advanced way,
- insert fancy social media icons into footer,

</br>

## <a name="interesting"></a>Interesting code snippet (for me of course 😉)
- hiding social media names with icon visibility (for better accessibility)

```html
<ul>
  <li>
    <a href="#"><i class="fab fa-facebook-f"></i>Facebook</a>
  </li>
  <li>
    <a href="#"><i class="fab fa-instagram"></i>Instagram</a>
  </li>
  <li>
    <a href="#"><i class="fab fa-behance"></i>Behance</a>
  </li>
</ul>
```
```css
.page-footer ul {
  list-style-type: none;
}

.page-footer ul li {
  display: inline-block;
  font-size: 0;
}

.page-footer ul li i {
  background: #ff5252;
  border-radius: 50%;
  color: #ffffff;
  font-size: 30px;
  height: 60px;
  line-height: 60px;
  transition: all 1s;
  width: 60px;
}
```


</br>

## <a name="gitHub"></a>GitHub Pages
<a href="https://grzegorz-jodlowski.github.io/creative-agency/">Sample portfolio</a>

</br>
</br>

  *project implemented as part of the 9-month [Web Developer Plus](https://kodilla.com/pl/bootcamp/webdeveloper/?type=wdp&editionId=309) course organized by [Kodilla](https://drive.google.com/file/d/1AZGDMtjhsHbrtXhRSIlRKKc3RCxQk6YY/view?usp=sharing)
