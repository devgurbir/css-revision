# css-revision


##### how to add comments on css?

- Comments in CSS can be added by placing text inside ```/* */```. This tells CSS that these are notes and should not be rendered in the frontend.

##### Why do we use pseudo-class?

We use pseudo-classes in CSS since they let us write CSS for specific states & external factors related to elements. For example, the **:visited** pseudo-class targets elements that have been visited in terms of navigation, the **:checked** pseudo-class targets specific elements (checkboxes) that have been checked or not, and the **:hover** pseudo-class lets us target elements when we move our mouse pointer on them.

### Specificity

Specificity in CSS is a weight given to CSS declarations. This weight is determined by the number of each selector type in the matching selector. When multiple declarations have equal specificity, the last declaration in the CSS is applied to the element. 

The following list of selector types increases by specificity:

1) Type selectors e.g h1, p and pseudo-elements e.g ::before
2) Class selectors e.g .example & attribute selectors e.g ```[type="radio"]``` & pseudo-classes e.g :hover
3) ID selectors e.g #example

Universal selector i.e * , combinators (+, >, ~, " ", ||) and negation pseudo-class (:not()) have no effect on specificity. 

When the !important rule is used on a style declaration, this declaration overrides any other declarations. When two conflicting declarations with the !important rule are applied to the same element, the declaration with a greater specificity will be applied.

##### What method allows an element to be moved from its current position?

The position CSS property sets how an element is positioned in a document. The top, right, bottom, and left properties determine the final location of positioned elements.

##### what properties does flex model have?

- flex-grow
- flex-basis
- flex-shrink

#### What is the difference between flex and grids?
The major difference between Grid Layout and Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time

#### Give an example where we have to use grids and where you have to use flexbox?

A grid is suited more to layouts where we want rigid control over the layout in both rows & columns. A grid follows more of a layout in design where first the grid is laid out and then the content is placed in it.

  A flexbox is suited more to layouts where flexibility of the content is important. A good example is creating a layout where we don't know the number of children but we want them to wrap into a new line as needed.
  
####  Give an example where you cannot use flexbox, and you can only use grids?

It isn't advisable to use flexbox for creating an overall page's layout. 

#### What are combinators? give examples of how you can use them

Combinators are CSS selectors that combine other selectors in a way that gives them a useful relationship to each other and the location of content in the document. For example, we can use the descendant combinator (" ") to combine two elements such that all occurences of an element are selected if it has the other element as an ancestor.

#### What does object-fit do?

The object-fit CSS property sets how the content of a replaced element, such as an image or video should be resized to fit its container.

#### What does rotate do?

The rotate() method rotates an element clockwise or counter-clockwise

#### When working with attribute selectors, how can you select elements which contain a particular attribute value?

```
[attribute="value"]
```


#### What does @media do?

The @media rule is used in media queries to apply different styles for different media types/devices.

#### What can be used to override properties of an element

A couple of things can be used to override properties of an element. The first is using the !important rule. The second is to write a new rule after the rule with the property to be overriden with atleast the same specificity.

#### How can you select every alternate elements in a list of elements using css?

By using the css selector :nth-child() and passing an argument for our element e.g odd and even.

#### What is the ranking of selectors with respect to specificity

1) inline styles
2) IDs
3) classes & pseudo-classes
4) tagnames & pseudo-elements

### how can we apply same styles to multiple selectors?
 
By combining different selectors with a comma.






 



