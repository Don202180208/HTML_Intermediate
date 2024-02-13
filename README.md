# HTML Intermediate Part I

## Module Overview

**Names:** Don Angel Lou Salvatierra, Mark Ryan Gabuco  
**Year and Block:** BSIT 3 block 1

### Learning Outcomes

After completing this module, we were able to:

#### Lesson 1: Forms
- Build interactive forms using `<form>` and various input elements like text fields, checkboxes, radio buttons, and submit buttons.
- Create HTML forms using the `<form>` element.
- Incorporate various input elements, such as text fields, checkboxes, radio buttons, and submit buttons, within forms.
- Understand and implement form attributes like `action` and `method`.
- Apply form validation techniques to ensure data integrity.
- Develop interactive and user-friendly web forms following best practices.

#### Lesson 2: Tables
- Create structured tables using `<table>`, `<tr>`, `<td>`, and `<th>` tags to display tabular data.
- Construct well-structured HTML tables using the `<table>`, `<tr>`, `<td>`, and `<th>` elements.
- Define table headers for improved data comprehension.
- Populate tables with rows and cells to organize and display tabular data effectively.

### Lesson 1: Forms

Below is the fundamental structure of an HTML form:

```html
<!DOCTYPE html>
<html>
<head>
<title>Sample Form</title>
</head>
<body>
<h1>Sample Form</h1>

<form action="#" method="post">

<label for="input1">Label for Input 1:</label>
<input type="text" id="input1" name="input1">
