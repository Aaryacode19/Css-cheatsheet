# CSS-Cheatsheet

```markdown
## CSS Syntax
```css
selector {
    property: value;
}
```

## CSS Selectors

- **Element Selector**: Selects all elements of a given type.
  ```css
  p {
      color: blue;
  }
  ```

- **Class Selector**: Selects all elements with a given class.
  ```css
  .classname {
      color: green;
  }
  ```

- **ID Selector**: Selects a single element with a given ID.
  ```css
  #idname {
      color: red;
  }
  ```

## CSS Properties

### Text

- **Color**: Sets the color of the text.
  ```css
  p {
      color: blue;
  }
  ```

- **Font Size**: Sets the size of the text.
  ```css
  p {
      font-size: 16px;
  }
  ```

- **Text Align**: Sets the alignment of the text.
  ```css
  p {
      text-align: center;
  }
  ```

### Background

- **Background Color**: Sets the background color of an element.
  ```css
  div {
      background-color: yellow;
  }
  ```

- **Background Image**: Sets the background image of an element.
  ```css
  div {
      background-image: url('image.jpg');
  }
  ```

### Box Model

- **Width and Height**: Sets the width and height of an element.
  ```css
  div {
      width: 100px;
      height: 100px;
  }
  ```

- **Padding**: Sets the padding inside an element.
  ```css
  div {
      padding: 10px;
  }
  ```

- **Margin**: Sets the margin outside an element.
  ```css
  div {
      margin: 20px;
  }
  ```

- **Border**: Sets the border around an element.
  ```css
  div {
      border: 1px solid black;
  }
  ```

### Display

- **Block**: The element is displayed as a block element.
  ```css
  div {
      display: block;
  }
  ```

- **Inline**: The element is displayed as an inline element.
  ```css
  span {
      display: inline;
  }
  ```

- **None**: The element is not displayed.
  ```css
  div {
      display: none;
  }
  ```

## CSS Positioning

- **Static**: The default positioning of an element.
  ```css
  div {
      position: static;
  }
  ```

- **Relative**: The element is positioned relative to its normal position.
  ```css
  div {
      position: relative;
      top: 10px;
      left: 20px;
  }
  ```

- **Absolute**: The element is positioned absolutely to its first positioned (not static) ancestor element.
  ```css
  div {
      position: absolute;
      top: 30px;
      left: 40px;
  }
  ```

- **Fixed**: The element is positioned relative to the browser window.
  ```css
  div {
      position: fixed;
      top: 50px;
      left: 60px;
  }
  ```

- **Sticky**: The element is positioned based on the user's scroll position.
  ```css
  div {
      position: sticky;
      top: 0;
  }
  ```

## CSS Flexbox

- **Display Flex**: The element becomes a flex container.
  ```css
  .container {
      display: flex;
  }
  ```

- **Justify Content**: Aligns flex items along the main axis.
  ```css
  .container {
      justify-content: center;
  }
  ```

- **Align Items**: Aligns flex items along the cross axis.
  ```css
  .container {
      align-items: center;
  }
  ```

- **Flex Direction**: Specifies the direction of the flex items.
  ```css
  .container {
      flex-direction: row;
  }
  ```

## CSS Grid

- **Display Grid**: The element becomes a grid container.
  ```css
  .container {
      display: grid;
  }
  ```

- **Grid Template Columns**: Defines the columns of the grid.
  ```css
  .container {
      grid-template-columns: repeat(3, 1fr);
  }
  ```

- **Grid Template Rows**: Defines the rows of the grid.
  ```css
  .container {
      grid-template-rows: repeat(2, 100px);
  }
  ```

- **Grid Gap**: Sets the gap between grid items.
  ```css
  .container {
      grid-gap: 10px;
  }
  ```


## CSS Reference Link

For a comprehensive reference on CSS properties, selectors, and usage examples, visit the **[Mozilla Developer Network (MDN) CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)**.
```
