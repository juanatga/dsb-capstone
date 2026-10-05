<h1>
  <span class="prefix">Data Science: Capstone</span>
  <span class="headline">Part 4: Findings + Technical Report</span>
</h1>

## Goal

Present your analysis in a Jupyter Notebook so another data scientist can follow your choices and understand what you found. Explain the question, the data, your method, how you checked its results, and the limits of your conclusions.

Your audience is **technical stakeholders**: people who need to understand or review the technical work. Aim for **reproducible results**, so another person can follow your documented steps and obtain the same results with the same data and setup. This report can become part of your **portfolio**, a collection of work you can show to employers or collaborators.

Use the [DSB Data Science Framework](../README.md#ga-terminology-and-the-data-science-lifecycle) to organize the report.

## Suggested notebook outline

1. **Executive summary:** A brief overview for a reader who needs the main points. State the question, the main result, how you measured performance, and the most important limits.
2. **Question and data:** Describe the goal, the audience, the data source, and your **variables of interest** (the columns relevant to your question). State what one row represents.
3. **Data preparation and exploration:** Summarize the checks and analysis from Part 3. Explain how you handled unusual values and missing information. **Data imputation** means filling in missing values; if you used it, explain the method.
4. **Model selection and implementation:** Explain which model or statistical method you chose and why (selection). Describe how you built and ran it (implementation) so another person could repeat the steps.
5. **Evaluation:** Explain how you tested the method. Name the **metric** (performance measure) you used, what data you tested it on, and how the result compares with a simple reference method (a **baseline**). Include relevant results, such as the number or size of errors, and explain what they mean for your question.
6. **Prediction, inference, and limitations:** Describe any predictions (estimates for new cases) and inferences (conclusions drawn from the analysis). Explain what the results suggest and what they do not establish. A model result alone does not prove that one thing caused another.
7. **Sources and appendix:** Link to data and external code or libraries, and explain how you used them.

Label each section and each chart clearly. Add short comments to code where they explain an important choice or help another person repeat your work.

---

## IMPORTANT: Check before sharing your work

> **Your report must use only suitable public or synthetic data. Do not include proprietary, private, unauthorized, or sensitive personal data in files, notebook outputs, charts, screenshots, or links.** Check all materials before uploading to GitHub or submitting. Follow the [full data requirements](../README.md#important-no-proprietary-private-or-sensitive-personal-data).

---

## Deliverables: what to submit

- A complete Jupyter Notebook technical report.
- A technical appendix with links and explanations for external libraries or code you used.
- A copy of your suitable public or synthetic dataset, or a link to its public source. Record the source and terms that allow its use and sharing.
- Host your notebook and other shareable materials in your public GitHub repository, as required for this part.

### Bonus: optional extensions

- Describe **deployment** (making your model available to users) and how you would validate its performance over time (check whether it still works well). **Production** means operating the method as part of a real service or workflow.
- Write a tutorial of at least 1,000 words explaining your approach to someone who is new to data science. Link to it in your notebook.

## Suggested prompts

- Can another person follow how I prepared the data and reached my result?
- Did I explain why I chose this method and measure?
- Did I test the method on data that was not used to fit it?
- What kinds of errors does the method make, and who could be affected?
- Do my conclusions stay within what the data and test results support?

## Useful resources

- [How to report statistics to technical audiences](https://www.bates.edu/biology/files/2010/06/How-to-Write-Guide-v10-2014.pdf)
- [Data science employers value research reports](https://sentiance.com/data-scientist)

## Evaluation

Your work will be evaluated using the [Part 4 rubric](./ds-capstone-part-04-rubric.md). Read it before you submit.
