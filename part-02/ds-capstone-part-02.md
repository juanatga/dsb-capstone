<h1>
  <span class="prefix">Data Science: Capstone</span>
  <span class="headline">Part 2: Dataset + Data Collection</span>
</h1>

## Goal

Choose one idea from Part 1. Find data that can help answer your question, check whether it is suitable, make any needed changes, and explain what the data contains.

Finding and preparing data can take time. Check early that you can access and use the data. If it does not fit your question, change the data source or revise your question.

## Steps

1. Find data that includes the information needed for your question. Record where it came from, when it was collected, and any rules about using it.
2. Open and inspect the data. Check that it has the information, time period, and geographic coverage you need.
3. Create a **data dictionary**: a table that lists each column, what it means, and its type or format.
4. Make and document necessary changes, such as correcting inconsistent formats or deciding how to handle missing values.
5. Describe the data and your work in a Jupyter Notebook.

You do not need to create a database. A spreadsheet, CSV file, other data file, or database is acceptable if it fits your project and you explain how to access it.

### Example data dictionary

| Column | Meaning | Type or format |
| --- | --- | --- |
| `payment_date` | Date a payment was made | Date, YYYY-MM-DD |
| `amount_eur` | Amount paid in euros | Number, decimal |
| `paid_on_time` | Whether the payment was on time | Yes/no |

## What to submit

- The data files, or a link to data that the instructor can access.
- A Jupyter Notebook describing the source, contents, checks, and changes you made.
- A data dictionary.

Do not publish personal, confidential, or restricted data. If you cannot share the data, do not include it in a public repository. Instead, describe its source and structure, remove or protect sensitive information where permitted, and ask your instructor how they can review your work.

### Optional extensions

- Update your project goal and describe your planned methods, assumptions, and risks.
- Write a blog post of at least 500 words about your work and link to it in your notebook.

## Suggested prompts

- Does the data contain the information I need to answer my question?
- What does one row represent?
- Are any values missing, duplicated, or in unexpected formats?
- What changes did I make, and why?
- What could make the data incomplete or misleading?

## Useful resource

- [Best practices for data documentation](https://dataoneorg.github.io/Education/bestpractices/)

## Evaluation

Your work will be evaluated using the [Part 2 rubric](./ds-capstone-part-02-rubric.md). Read it before you submit.
