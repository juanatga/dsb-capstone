# Finding a Data Science Capstone Idea

---

## IMPORTANT: Use public or synthetic data only

> **Do not use proprietary or confidential records, private data from another person or organization, data obtained without authorization, or sensitive personal data.** This applies to collecting, analyzing, uploading, and submitting data.
>
> Choose a public dataset whose terms allow your planned use and sharing, or synthetic data (made-up records that do not expose real people’s information). Access to a file or removal of names does not make private data acceptable.
>
> **Unsure? Ask your instructor before obtaining or using the data. Describe the source without sending the data.** Read the [full data requirements](../README.md#important-no-proprietary-private-or-sensitive-personal-data).

---

You do not need data from your current institution. Start with a question you care about, then look for data that can help answer it. Your idea can come from:

- **Your current work:** a decision, prediction, or recurring uncertainty in your field.
- **A personal interest:** a hobby, sport, subject, or question you enjoy exploring.
- **Your community:** a local service, environment, or issue that affects people around you.

Your project is a chance to use data to answer a practical question. It can be valuable even if an organization does not put the result into use.

## Start here

1. Write down an interest or problem you care about.
2. Turn it into a question that data could help answer.
3. Decide who might use or care about the answer.
4. Look for data that contains the information you need.
5. Check that you can access and use the data before choosing the idea.

If the data is not available, narrow or change the question, or look for similar data from another place or field.

## What makes a question a data science project?

| Project type | Main question | Example |
| --- | --- | --- |
| **Data science** | Can data help predict a result, sort cases into categories, find groups, or flag unusual cases? How well does the method work on data it has not seen before? | Can past payment information help identify payment plans at higher risk of a missed payment? |
| **Data analytics** | What happened, and how can we describe it? | How many payments were late each month? A report like this is a useful first step, but by itself it may not meet the capstone's goal of testing a method. |
| **Process automation** | How can a task be done with fewer manual steps? | Can a script copy payment details into a report? This can be useful, but automation alone does not test a question about patterns or predictions in data. |

Analytics and automation can be part of a data science project. The main contribution should be a question you can test with data, a suitable method, and an evaluation of its results. A model is a method that finds patterns in data or makes estimates. Use its result to support a decision or understanding; it does not prove that one thing caused another, and it should not make important decisions without human review.

## Examples inspired by students' work

These examples build on interests students have mentioned. You do not need data from an institution. Look for public data that meets the project’s data requirements, synthetic data, or suitable public data from another setting.

### Weather

- **Data science question:** Can recent observations and past forecast errors improve short-term temperature or rainfall forecasts for a location?
- **Not this alone:** What was the average rainfall by month last year? That describes past data but does not test a model.
- **Possible data and approach:** Weather observations and past forecasts; compare a forecasting method with a simple baseline (a basic result that a more complex method should improve on).

### Occupational safety

- **Data science question:** Which incident and workplace characteristics are associated with more severe injuries?
- **Not this alone:** How many workplace injuries were reported in each sector?
- **Possible data and approach:** Anonymized injury records or a public comparable dataset; classify severity and evaluate missed severe cases as well as false alerts.

### Tax repayment

- **Data science question:** Which installment plans are at higher risk of a missed payment?
- **Not this alone:** How much debt was repaid each quarter?
- **Possible data and approach:** Historical payment schedules and outcomes, if available; compare classification models with a baseline and explain limits.

### Public procurement

- **Data science question:** Which tenders or bids have prices or patterns that differ from comparable cases enough to merit review?
- **Not this alone:** Which ministry issued the most tenders?
- **Possible data and approach:** Public tender and bid records where available; use anomaly detection or estimate a typical price range. A flag is a prompt for review, not evidence of wrongdoing.

### Water management

- **Data science question:** Can weather and previous measurements help forecast river flow or water-quality indicators?
- **Not this alone:** Which water-quality measure was highest last summer?
- **Possible data and approach:** Water measurements and weather records; use time-series forecasting or regression and report uncertainty.

### Seismology

- **Data science question:** Can signal features distinguish recorded earthquake events from background noise?
- **Not this alone:** How many earthquakes were recorded by magnitude?
- **Possible data and approach:** Labeled seismic waveforms or a public seismic catalogue; test classification or event-detection methods. Do not frame the project as predicting exactly when an earthquake will occur.

## Examples from community and personal interests

These are starting points for Montenegro or the wider Balkan region. You can study a place you care about even if the available data comes from another country or a wider region. First check which places and dates the data covers, what language it uses, and whether it contains the information your question needs.

### Community: seasonal tourism

- **Data science question:** Can calendar, weather, and past visitor or accommodation counts help forecast tourism demand for a coastal or mountain destination?
- **Not this alone:** Which month has the most visitors?
- **Possible data and approach:** Look for public tourism or accommodation time series, weather history, and holiday calendars. If local figures are unavailable, use another destination or a broader public dataset to demonstrate and evaluate the method. Compare forecasts against a seasonal baseline.

### Community: air quality or heat

- **Data science question:** Can weather and recent sensor readings predict when a neighborhood or town is more likely to experience high particulate pollution or extreme heat?
- **Not this alone:** Which town had the highest average temperature last year?
- **Possible data and approach:** Explore public air-quality observations, weather records, and gridded climate data. Check whether monitoring stations are close enough to support a local claim; otherwise frame the project at the scale the data supports. Evaluate false alerts and missed high-pollution or heat periods.

### Personal interest: football

- **Data science question:** Can past team performance and match context improve predictions of goals or match outcomes in a chosen league?
- **Not this alone:** Which team scored the most goals last season?
- **Possible data and approach:** Historical match results and team statistics from a public source. Use classification or goal-count regression, compare with a simple baseline, and evaluate on later matches rather than randomly mixing past and future games.

Data availability will vary by country, city, sport, and language. Try international sources and comparable datasets as well as local portals. A project can still be relevant to a local community if it transparently explains that the model was tested on data from elsewhere and needs local validation. Never imply that a result applies to Montenegro or a specific community unless the data supports that claim.

## Questions to shape your idea

Use these prompts to turn a broad interest into a project proposal. An **outcome** is the result you want to predict or explain; **input variables** are the pieces of information you will use to do that.

1. **What interests me?** Is it connected to my work, a personal interest, or my community?
2. **Who could use or care about the result?** What decision or understanding could it support?
3. **What exactly do I want to estimate or discover?** Name an outcome to predict, a category to classify, groups to explore, or unusual cases to identify.
4. **What does one row of my data represent?** For example, one match, payment, injury, day of weather, or sensor reading.
5. **Can I find data with the outcome and input variables I need?** Check source, access rules, language, time period, geographic coverage, and data quality.
6. **What simple baseline can I compare against?** A baseline is a simple result or method to beat. It shows whether a more complex method adds value.
7. **What are my success metrics?** Choose measures that reflect the cost of different errors and the needs of the audience.
8. **Can I test the model on data it did not learn from?** For time-based data, preserve the order of time when making the test split.
9. **What are the risks and limits?** Consider privacy, bias, missing data, small samples, changing conditions, and whether results generalize to the people or place of interest.

### A proposal template

Use this template to prepare your **pitch** (a brief explanation of your idea). In Part 1, you will share your ideas in a **lightning talk** (a short, focused presentation).

> **For [audience], I want to [predict a result / sort cases into categories / estimate a value / find a pattern] using [data source]. I will compare [method] with [simple baseline] and measure success using [success measure]. The result could support [decision or understanding]. The main limits are [data, privacy, fairness, or whether the result applies in other settings].**

### If you cannot access the ideal data

- Search for public data from another country, city, sport, or field that has similar variables.
- Narrow the question to match the data that is available.
- Choose another public dataset whose terms allow your planned use and sharing and that contains no sensitive personal data.
- Use synthetic data to practice a method, while stating that synthetic results do not establish real-world performance.
- If the dataset does not say which outcome happened, you may still look for groups of similar cases (clustering) or unusual cases (anomaly detection). Decide how you will judge whether those results are useful.

Do not spend weeks building around a dataset you cannot obtain. Confirm that the data exists and can be used before committing to a project topic.
