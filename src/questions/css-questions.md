# CSS Questions

### 1. Flexbox vs CSS Grid
>
##### Short Answer:
>
> CSS Grid Layout is a two-dimensional system while flex is one dimension.
>
> CSS Grid’s approach is layout-first while Flexbox’ approach is content-first.
>
> Grid --> Complex | Flex --> Simple
>
> Grid --> Overlap elements
>
##### Complete Answer:
>
> [Link to answer 1](https://blog.logrocket.com/flexbox-vs-css-grid/)
>
> [Link to answer 2](https://medium.com/youstart-labs/beginners-guide-to-choose-between-css-grid-and-flexbox-783005dd2412)

<br />

### 2. Absolute vs Fixed
>
##### Short Answer:
>
> Static is the default position for all elements. Z-index does not work with statical elements.
>
> Relative, relative to itself and will appear on top (z-index). And limits the scope of absolute position for their childs.
>
> Absolute are removed drom the flow of the elements page. It is not affected by other elements and it doesn't affect other elements. Limit flexibility of the site.
>
> Fixed position is relative to the viewport or the browser window itself. the viewport doesn't change when you scroll.
>
> Sticky will just sit there like static elements but as you scroll past it the element will behave as fixed. if the parent element has room (extra height)
>
##### Complete Answer:
>
> [Link to answer 1](https://css-tricks.com/absolute-relative-fixed-positioining-how-do-they-differ/)

<br />

### 3. CSS Preprocessor
>
##### Short Answer:
>
> CSS Preprocessors are tools that extend the functionality of vanilla CSS by adding a wide variety of logical syntax such as you might see in a normal programming >language.
>
> One of the biggest drawbacks is that debugging takes longer. Since debugging is already harder than programming, this can be a true disadvantage.
>
> It can also be time-consuming to compile, and performance may be compromised. Extra-tooling, Performance.
>
##### Complete Answer:
>
> [Link to answer 1](https://adamsilver.io/articles/the-disadvantages-of-css-preprocessors/)
>
> [Link to answer 2](https://medium.com/@sedwardscode/css-preprocessors-what-why-how-7bc5a7a564de)
>
> [Link to answer 3](https://raygun.com/blog/10-reasons-css-preprocessor/)


<br />

### 4. What is BEM?
>
##### Short Answer:
>
> The Block, Element, Modifier methodology. Naming convention for HTML and CSS.
>
> In this CSS methodology a block is a top-level abstraction of a new component, for example a button: .btn { }. This block should be thought of as a parent.
>
> Child items, or elements, can be placed inside and these are denoted by two underscores following the name of the block like .btn__price { }
>
> Finally, modifiers can manipulate the block so that we can theme or style that particular component without inflicting changes on a completely unrelated module. 
> This is done by appending two hyphens to the name of the block just like btn--orange.
>
##### Complete Answer:
>
> [Link to answer 1](https://css-tricks.com/bem-101/#:~:text=The%20Block%2C%20Element%2C%20Modifier%20methodology,CSS%20in%20a%20given%20project.)
>



