# Budget Tracker

## Project Description

This project is a **Budget Tracker** created using HTML and CSS. The purpose of the project is to help users record and view their expenses in an organized way. This project builds on the Budget Tracker created in Week 1 and adds an expense table, an improved expense form, multimedia content, interactive elements, and advanced CSS selectors.

## Files in the Project

### `index.html`

The `index.html` file contains the structure and content of the Budget Tracker website.

It includes:

* A main heading and budget tracker logo.
* An Add Expense form.
* Input fields for expense name, amount, and date.
* A category dropdown with:

  * Food
  * Transport
  * Rent
  * Entertainment
  * Other
* An **Add Expense** button.
* An expense table containing sample expenses.
* A `<thead>` section for the table headings.
* A `<tbody>` section for the expense records.
* A collapsible **How to use this tracker** section using `<details>` and `<summary>`.
* A YouTube video embedded using an `<iframe>`.

## Expense Table

The expense table contains four columns:

1. Name
2. Amount
3. Category
4. Date

The table also includes five sample expense records. The HTML uses `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>` correctly.

## Add Expense Form

The form allows the user to enter information about a new expense.

The form contains:

* Expense name
* Expense amount
* Expense category
* Expense date
* Add Expense button

Each input has a matching `id` attribute so that the fields can be accessed later when JavaScript is added.

The category field uses a `<select>` dropdown instead of a normal text input.

## Multimedia

The project includes a small budget-related icon using the `<img>` element.

It also includes a budgeting tips YouTube video using an `<iframe>`.

These elements provide visual and multimedia content to make the webpage more useful and engaging.

## Interactive Features

The project includes a **How to use this tracker** section using `<details>` and `<summary>`. Users can click the summary to show or hide the instructions.

The expense table also has a hover effect. When the user moves the mouse over a table row, the background changes slightly.

The Add Expense button uses `cursor: pointer` so the mouse changes to a hand when hovering over the button.

## CSS Features

The `style.css` file controls the appearance of the Budget Tracker.

It includes:

* Table borders
* Collapsed table borders
* Cell padding
* Colored table headers
* Alternating table row colors
* Hover effects
* Form styling
* Button styling
* Input focus effects
* Responsive video styling

The project also uses advanced CSS selectors, including:

* **Descendant selector:** `.expenses-section td`
* **Direct child selector:** `.add-expense-section > form`
* **Position pseudo-class:** `tr:nth-child(even)`
* **Negation pseudo-class:** `input:not([type="submit"])`
* **Focus pseudo-class:** `input:focus`

## Technologies Used

* HTML5
* CSS3
* YouTube iframe embedding

## Future Improvements

In future weeks, JavaScript can be added to make the Budget Tracker interactive. The Add Expense button could then allow users to enter new expenses and automatically add them to the table. Other features such as calculating total expenses, editing expenses, deleting expenses, and saving data could also be added.

## Conclusion

This project demonstrates how HTML and CSS can be used to build and style a basic Budget Tracker. It includes a structured expense table, an improved form, multimedia content, interactive elements, and advanced CSS selectors.
