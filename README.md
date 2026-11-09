# 🎯 Excel Skills — Business Data Analytics Job Simulation

A practical SwiftSkale training companion for the **Forage Academy Excel Skills Job Simulation**, developed for the **SS-BA-BTC8 Business Data Analytics Bootcamp**.

Learn to inspect account-sales records, highlight data-quality issues, evaluate growth, and explain business findings through a guided Excel project.

## 🌐 Open the practical guide

**[🚀 Open the interactive training guide](https://enochsage.github.io/excel-skills-account-sales-guide/)**

[View or download the HTML source](Practical-Guide-Exploring-FA-Account-Sales-Data%20in%20Excel.html)

Use the live link above to run the guide in your browser through GitHub Pages. For offline use, open the HTML source link, choose **Download raw file**, and double-click the downloaded file. The guide is self-contained and works offline.

**[Start the Forage simulation](https://www.theforage.com/simulations/forage/sponsored-content-excel-skills-jf8r)** · **[Read the project brief](Forage_Excel_Skills_Job_Simulation_Project_Brief.pdf)**

## Project overview

| Item | Details |
| --- | --- |
| Project | Excel Skills — Business Data Analytics Job Simulation |
| Training context | SwiftSkale Business Data Analytics Bootcamp, SS-BA-BTC8 |
| Platform | Forage Academy |
| Full simulation duration | 6–7 hours, self-paced |
| Difficulty | Intermediate, with accessible explanations of foundational concepts |
| Original project deadline | Thursday, 5 November 2026 — retained as the historical cohort deadline |
| Relevant roles | Data Analyst, Business Analyst, BI Analyst, Reporting Analyst, Operations Analyst and Junior Data Analyst |

The simulation develops practical Excel skills through workplace-style analysis. Participants prepare data, identify patterns, automate repetitive workflows, create visual reports and communicate recommendations.

## 📚 What you will learn

| Learning area | Practical capability |
| --- | --- |
| Data cleaning and preparation | Identify incomplete fields, inconsistent information and calculation problems before reporting. |
| Exploratory data analysis | Inspect data types, compare annual sales and investigate unusual values. |
| Excel automation and macros | Develop repeatable workflows through the broader simulation. |
| Data visualization and dashboards | Present business metrics clearly through charts and organized reporting. |
| Business insights and recommendations | Translate observations into specific actions while explaining data limitations. |

## Scope of this repository

The HTML guide focuses on **Task 1: Prepare and Explore Business Data**, using the supplied account-sales workbook. It is a worked practical companion, not a claim that all simulation tasks have been completed.

The project brief describes four broader learning areas:

1. **Data preparation and exploration:** review business datasets, identify missing values and errors, and use shortcuts and conditional formatting.
2. **Data analysis and automation:** investigate performance and streamline repeated work using Excel techniques and macros.
3. **Data visualization and dashboard development:** create clear charts and a professional dashboard.
4. **Business insights and recommendations:** interpret results and propose evidence-based improvements.

Detailed worked solutions for later platform tasks are outside this guide’s current scope. Its Power Query quiz is supporting practice, not an additional requirement for the six-rule exercise.

## The practical business question

> Your sales manager needs to review 40 customer accounts. How can you highlight missing information, calculation problems, cross-selling opportunities and sales performance without changing the original data?

The dataset contains **40 accounts**, with headers in **A1:M1** and data in **A2:M41** on the **Account Sales Data** worksheet.

### Data dictionary

| Columns | Fields | Meaning |
| --- | --- | --- |
| A | Account ID | Identifier for each customer account. |
| B | Account Name | Business name used for reporting and follow-up. |
| C | Account Type | Customer segment, such as Retail or Enterprise. |
| D | Region | Geographic grouping. |
| E–F | Product 1 / Product 2 | Yes/No product status; a blank means unknown. |
| G–L | 2016–2021 Unit Sales | Annual sales volumes, not revenue or profit. |
| M | 5 YR CAGR | Compound annual growth rate from 2016 to 2021; the supplied formula returns error text when unavailable. |

### Six required conditional-formatting rules

| Business purpose | Range | Appearance | Expected count |
| --- | --- | --- | ---: |
| Flag calculation problems | A2:M41 | Purple fill, white text | 2 |
| Locate missing information | A2:M41 | Yellow fill | 5 |
| Identify Product 2 = No | F2:F41 | Orange fill | 16 |
| Identify CAGR ≥100% | M2:M41 | Green fill | 3 |
| Identify negative CAGR | M2:M41 | Red fill, white text | 7 |
| Identify top 10% of 2021 sales | L2:L41 | Blue fill | 4 |

These counts refer to highlighted cells, not mutually exclusive customer groups. The top four 2021 volumes are **1,450, 1,180, 980 and 820 units**.

### Important analytical distinctions

- **Missing is not zero:** a blank means unknown; zero is a recorded numerical value.
- **Unknown is not No:** an empty Product 2 field must not be treated as a confirmed cross-selling opportunity.
- **Unavailable CAGR is not 0%:** a zero starting value makes CAGR undefined.
- **Growth is not volume:** a small account can grow quickly while remaining smaller than an established account.
- **Volume is not profit:** profitability requires price and cost information.
- **Top 10% is not Top 10 Items:** with this dataset, the correct rule selects four accounts.

## Guide features

- Question-first lessons with titled, step-by-step solution implementations.
- A data dictionary, comparison tables and workflow infographics.
- All **34 supplied task and quiz screenshots**, including clearly labelled troubleshooting examples.
- SwiftSkale and Forage Academy branding, with the Excel Skills overview image at the top.
- **View Solution** buttons that reveal answers and reasoning.
- Six original business-focused matching scenarios and 15 supporting quiz questions.
- Interactive CAGR calculator and blank-cell rule demonstration.
- Formula-copy buttons with a manual-copy fallback.
- Searchable screenshots with click-to-enlarge viewing.
- Seven practical completion checks, saved in the current browser when local storage is available.
- Embedded downloads of the original workbook and project brief.
- Responsive desktop/mobile layout and browser printing.

## Recommended learning workflow

1. Open the guide in a modern browser.
2. Download the source workbook from the guide’s **Project files** section.
3. Save a separate working copy in Excel.
4. Read the practical question before applying each rule.
5. Follow the implementation steps and explain the formula in your own words.
6. Use **View Solution** to compare your result with the expected cells and counts.
7. Complete the matching scenarios and supporting quiz.
8. Verify all rules in **Conditional Formatting → Manage Rules → This Worksheet**.
9. Save the workbook and write a short findings summary with recommended follow-up.
10. Continue the remaining tasks on Forage according to your trainer’s instructions.

The HTML guide does not edit your workbook, submit assignments or issue certificates. Browser checklist progress is a personal practice aid.

## Expected practical deliverables

| Deliverable | Completion evidence |
| --- | --- |
| Formatted Excel workbook | Six correctly configured rules, with original source values preserved. |
| Validation evidence | Correct ranges, expected counts and readable results. |
| Business summary | Clear findings, limitations and recommended investigation. |
| Full simulation completion | Complete the platform requirements separately to obtain the Forage certificate. |

## 🏆 Certification opportunity

According to the supplied project brief, successful completion of the full Forage Excel Skills Job Simulation provides a certificate of completion that participants can include on their **CV, LinkedIn profile and professional portfolio**. Completing this local guide alone does not qualify as completion of the full simulation.

## Files and technical requirements

| File | Purpose |
| --- | --- |
| `Practical-Guide-Exploring-FA-Account-Sales-Data in Excel.html` | Complete offline training guide, including embedded images and source downloads. |
| `index.html` | Browser entry point that opens the training guide when hosted. |
| `Forage_Excel_Skills_Job_Simulation_Project_Brief.pdf` | Supplied SwiftSkale project brief. |
| `README.md` | Project overview, learning outcomes and usage instructions. |

No installation or build step is required. Use a modern browser for the guide and Microsoft Excel to complete the workbook exercise. The platform link requires internet access. Local progress belongs to the current browser and is not synchronized between devices.

## Validation performed

The guide was checked in a browser for solution reveals, practice feedback, CAGR calculations including a zero starting value, checklist persistence, screenshot filtering, image enlargement, image loading and internal navigation. Desktop and mobile layouts were reviewed with no detected horizontal page overflow.

## 📄 License

Original guide code and documentation are released under the [MIT License](LICENSE). You may use, adapt and redistribute those original components under its terms. Embedded third-party screenshots, datasets, artwork and trademarks are excluded; see [Third-party notices](THIRD_PARTY_NOTICES.md).

## Sources and attribution

- Supplied SwiftSkale **Forage Excel Skills Job Simulation Project Brief**.
- Supplied **Account Sales Data for Analysis.xlsx**, worksheet **Account Sales Data!A1:M41**.
- Task screenshots and training discussion supplied for this project.
- SwiftSkale logo supplied by the trainer; Forage Academy branding appears in the supplied simulation artwork.
- Original practice scenarios and explanatory guide content developed for this training companion.

Third-party logos, screenshots and simulation materials remain attributable to their respective owners. Their inclusion identifies the learning context and does not imply that this repository is an official Forage product.

Build the skill, not just the spreadsheet: verify your results and practise explaining the decisions behind them.
