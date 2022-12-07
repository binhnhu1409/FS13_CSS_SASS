# :computer: A landing page - dark theme :computer:

In this project, I was trying to imitate a similar landing webpage as in this [link] (https://maido-dark.fueko.net/).
Visit my work [here]()

## Tasks haven been done (max 4)

1. Floating the HTML elements using Flexbox and Grid system
2. Implementing basic animations as shown in the [webpage](https://maido-dark.fueko.net/) (hover effect,
   active link styles, typing effect).
3. Implement codes using Github Pages.
4. Using SCSS (made use of variables, @mixin, @extend)

## Tech stacks

- CSS/SCSS (made use of grid and flexbox layout as well as transition and animation)
- HTML

## Project structure

```
.
│   package.json
│   README.md
└───src
    │   index.html
    ├───assets (contain images)
    ├───compiled
    │       style.css
    │       style.css.map
    └───styles
        │   style.scss
        │
        ├───abstract
        │       _mixins.scss
        │       _variables.scss
        │
        ├───base
        │       _animation.scss
        │       _typography.scss
        │
        └───layout
                _articles.scss
                _footer.scss
                _header.scss
                _old_posts.scss
                _pinned_posts.scss
                _subscribe.scss
```
