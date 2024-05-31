# CSS Position

<details>
<summary>Table of content</summary>

- [What is position?](#what-is-position)
- [Available values of position](#available-values-of-position)
</details>

### What is position?

Position is an important part of HTML and CSS but it can be complicated now and then. In a HTML document, we have a natural flow of elements, everyting goes form top to bottom. The order of elements is important when you start creating your application. The more time you invest in your structure, the easier it is going to be to get your elements where you want them. 

We can of course modify this natural order if we want to, and the tool we can use in order to do so, is called `position`. `position` is a css rule _( or a css property )_ that can have multiple values that have different purposes. 

In short, the position property decides what kind of anchoring the element should have. When that is decided we can start moving it in relation to its anchoring with the help of some other css rules. They are named: `top`, `right`, `bottom` and `left`. Sounds simple! But in reality it is rarely not.

[Back to top](#css-position)

### Available values of position

**Css syntax of the property position**

```css
.some-class {
  position: "value";
  top: "value";
  right: "value";
  bottom: "value";
  left: "value";
}
```

- `static`: default-value. Noting happens to the element, it reamins in the natural flow of the document. Element is _NOT_ affected by top, right, bottom and left.
- `relative`: The element remains in the natural flow but we can move the element relative to its own position with the help of top, right, bottom and left. 
- `fixed`: This one removes the element from the natural flow of the document but fixates it relative to the viewport _( window )_. We can also move the element relative to viewport with top, right, bottom and left.
- `absolute`: The element is removed from the natural flow, but it's anchored to its nearest parent element that has `position: relative;`. If no such parent element exisits, it will default to the `body`. With the help of top, right, bottom and left, we can move this element inside its parent element.
- `sticky`: we will not handles this one during this course.

[Click here for a link to further reading](https://www.w3schools.com/css/css_positioning.asp).

