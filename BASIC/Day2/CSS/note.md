## CSS: Cascading Style Sheets  
CSS is a **style sheet language** used to make web pages more visually appealing. It is designed to separate the **content** (controlled by HTML or XML) from the **presentation** (the visual layout and style), giving developers more flexibility and control over the design of a website.

### Key Features of CSS:
- **Control over Layout**: CSS allows you to control the positioning of elements on a page.
- **Styling**: It provides options to style elements with different colors, fonts, and backgrounds.
- **Flexibility**: CSS can be applied across multiple web pages, allowing for consistent design throughout a site.
  
### Basic CSS Workflow:
1. **Select Elements**: You target HTML elements using **selectors**.
2. **Style Elements**: Apply styles such as colors, fonts, sizes, margins, etc., to these selected elements.

---

### CSS Selectors

Selectors are used to target HTML elements to apply styles. The **DOM** (Document Object Model) represents the HTML document as a tree structure, where elements can be selected and styled.

Some common CSS selectors include:

1. **Type Selector**: Selects all elements of a specific type.  
   Example:  
   ```css
   p {
     color: blue;
   }
   ```
   This selects all `<p>` elements and makes the text blue.

2. **Class Selector**: Targets elements with a specific class.  
   Example:  
   ```css
   .header {
     font-size: 24px;
   }
   ```
   This applies styles to all elements with the class "header."

3. **ID Selector**: Targets a specific element with a unique ID.  
   Example:  
   ```css
   #main-title {
     color: green;
   }
   ```
   This targets an element with the ID "main-title" and changes its color.

4. **Universal Selector**: Selects all elements on a page.  
   Example:  
   ```css
   * {
     margin: 0;
     padding: 0;
   }
   ```
   This removes the default margin and padding from all elements.

5. **Descendant Selector**: Selects elements inside other elements.  
   Example:  
   ```css
   div p {
     color: red;
   }
   ```
   This selects all `<p>` elements inside `<div>` elements and makes them red.

---

It can create beautiful, responsive, and dynamic web designs that enhance the user experience on our website.
