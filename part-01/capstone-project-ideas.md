# Finding a Data Science Capstone Idea

You do not need access to data from your current institution to choose a strong capstone. Start with a question you care about, then look for data that can help answer it. Your inspiration can come from:

- **Your current work:** a decision, prediction, or recurring uncertainty in your field.
- **A personal interest:** a hobby, sport, subject, or question you enjoy exploring.
- **Your community:** a local service, environment, or issue that affects people around you.

The capstone is a chance to apply data science methods to a practical question. A project does not need to be adopted by an institution to be valuable.

## What makes a question a data science project?

| Project type | Main question | Example |
| --- | --- | --- |
| **Data science** | Can data help predict an outcome, classify cases, find groups, or detect unusual patterns—and how well does the method work on new data? | Can historical payment behavior help identify installment plans at risk of a missed payment? |
| **Data analytics** | What happened, and how can we describe it? | How many payments were late each month? A descriptive report can be a useful first step, but a report alone may not meet the capstone's modeling goal. |
| **Process automation** | How can a task or workflow be completed with fewer manual steps? | Can a script copy payment details into a report? Useful work, but automation alone does not test a predictive or statistical question. |

Analytics and automation can support a data science project. To make data science the central contribution, define a question that can be tested with data, build an appropriate model or statistical analysis, and evaluate the result. A model should inform a decision or understanding; it should not be presented as proof of cause or as an automatic decision-maker.

## Examples inspired by students' work

These examples build on interests students have mentioned. They do not assume that institutional data will be available. Look for public data, an approved anonymized extract, or a comparable dataset from another context.

### Weather

- **Data science question:** Can recent observations and past forecast errors improve short-term temperature or rainfall forecasts for a location?
- **Not this alone:** What was the average rainfall by month last year? That describes past data but does not test a model.
- **Possible data and approach:** Weather observations and historical forecasts; compare a time-series or regression model with a simple baseline.

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

These are starting points for Montenegro or the wider Balkan region. A student can study a place they care about even if the available data comes from another country or a broader regional source. First check coverage, language, date range, and whether the variables needed for the question are actually present.

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

Use these prompts to turn a broad interest into a project proposal:

1. **What interests me?** Is it connected to my work, a personal interest, or my community?
2. **Who could use or care about the result?** What decision or understanding could it support?
3. **What exactly do I want to estimate or discover?** Name an outcome to predict, a category to classify, groups to explore, or unusual cases to identify.
4. **What does one row of my data represent?** For example, one match, payment, injury, day of weather, or sensor reading.
5. **Can I find data with the outcome and input variables I need?** Check source, access rules, language, time period, geographic coverage, and data quality.
6. **What simple baseline can I compare against?** A model needs a fair point of comparison.
7. **How will I measure success?** Choose a metric that reflects the cost of different errors and the needs of the audience.
8. **Can I test the model on data it did not learn from?** For time-based data, preserve the order of time when making the test split.
9. **What are the risks and limits?** Consider privacy, bias, missing data, small samples, changing conditions, and whether results generalize to the people or place of interest.

### A proposal template

> **For [audience], I want to [predict/classify/estimate/discover] [specific outcome or pattern] using [data source]. I will compare [method] with [baseline] and measure success using [metric]. The result could support [decision or understanding]. The main limits are [data, privacy, fairness, or generalization limits].**

### If you cannot access the ideal data

- Search for public data from another country, city, sport, or field that has similar variables.
- Narrow the question to match the data that is available.
- Use an approved anonymized sample if one can be provided safely.
- Use synthetic data to practice a method, while stating that synthetic results do not establish real-world performance.
- If the dataset has no outcome labels, consider an unsupervised question such as clustering or anomaly detection, and define how you will judge whether the result is useful.

Do not spend weeks building around a dataset you cannot obtain. Confirm that the data exists and can be used before committing to a project topic.
