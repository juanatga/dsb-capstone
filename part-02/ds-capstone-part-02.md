<h1>
  <span class="prefix">Data Science: Capstone</span>
  <span class="headline">Part 2: Dataset + Data Collection</span>
</h1>

---

## IMPORTANT: Use public or synthetic data only

> **Do not use proprietary or confidential records, private data from another person or organization, data obtained without authorization, or sensitive personal data.** This applies to collecting, analyzing, uploading, and submitting data.
>
> Choose a public dataset whose terms allow your planned use and sharing, or synthetic data (made-up records that do not expose real people’s information). Access to a file or removal of names does not make private data acceptable.
>
> **Unsure? Ask your instructor before obtaining or using the data. Describe the source without sending the data.** Read the [full data requirements](../README.md#important-no-proprietary-private-or-sensitive-personal-data).

---

## Goal

Use feedback from your Part 1 **lightning talk** (your short project pitch) to choose one idea. Find data that can help answer your question, check whether it is suitable, make any needed changes, and explain what the data contains.

**Data acquisition** means finding and obtaining data. **Data munging** means changing its structure or format so you can analyze it. **Data cleaning** means checking and handling errors, duplicates, missing values, and inconsistent entries. These steps can take time. Check early that you can access and use the data. If it does not fit your question, change the data source or revise your question.

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

## Deliverables: what to submit

- The data files, or a link to data that the instructor can access.
- A Jupyter Notebook describing the source, contents, checks, and changes you made.
- A data dictionary.

Before submitting, check both the data files and notebook outputs against the data requirements above. If a dataset does not meet them, replace it with a suitable public or synthetic dataset.

### Bonus: optional extensions

- State your **specific aim** (the precise result you want to achieve) and describe your planned methods, assumptions, and risks.
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
