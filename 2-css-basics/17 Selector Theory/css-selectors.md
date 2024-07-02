# Theory of Selectors in CSS

**CSS selectors** are patterns used to select the elements you want to style. Understanding how selectors work is fundamental to applying styles efficiently and effectively. Here's a detailed overview:

## Basic Selectors

1. **Type Selector**:

   - Selects all elements of a given type.
   - Example: `p` selects all `<p>` elements.

   ```css
   p {
     color: blue;
   }
   ```

2. **Class Selector**:

   - Selects all elements with a specific class attribute.
   - Denoted by a dot (`.`) followed by the class name.
   - Example: `.classname` selects all elements with `class="classname"`.

   ```css
   .classname {
     font-size: 18px;
   }
   ```

3. **ID Selector**:

   - Selects a single element with a specific ID attribute.
   - Denoted by a hash (`#`) followed by the ID name.
   - Example: `#idname` selects the element with `id="idname"`.

   ```css
   #idname {
     background-color: yellow;
   }
   ```

4. **Universal Selector**:

   - Selects all elements on the page.
   - Denoted by an asterisk (`*`).
   - Example: `*` selects every element.

   ```css
   * {
     margin: 0;
     padding: 0;
   }
   ```

## Attribute Selectors

1. **Basic Attribute Selector**:

   - Selects elements with a specific attribute.
   - Example: `[type="text"]` selects all `<input>` elements with `type="text"`.

   ```css
   input[type="text"] {
     border: 1px solid black;
   }
   ```

2. **Attribute Selector with Value**:

   - `[attribute=value]` selects elements with the specified attribute value.

   ```css
   a[target="_blank"] {
     color: red;
   }
   ```

3. **Attribute Selector with Multiple Values**:

   - `[attribute~=value]` selects elements with an attribute containing a space-separated list of words, one of which is the specified value.

   ```css
   [class~="example"] {
     border: 1px solid blue;
   }
   ```

4. **Attribute Selector with Beginning Value**:

   - `[attribute|=value]` selects elements with an attribute value that begins with the specified value.

   ```css
   [lang|="en"] {
     color: green;
   }
   ```

### Summary

- **Selectors** are used to target HTML elements for styling.
- **Type, class, ID, and universal selectors** provide basic element selection.
- **Attribute selectors** allow for more specific targeting based on element attributes.

Understanding and effectively using CSS selectors is essential for creating well-structured and maintainable stylesheets.
