# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    I'm using Excel. 

    > Who is your intended audience? 
    I am also using Ontario apple production by variety (https://data.ontario.ca/dataset/ontario-apple-production-by-variety/resource/3f2e894b-46f2-44b8-9520-6869a7560b00), specifically the 2005 data, so the intended audience would be the same to be buyers and retailers. 
    
    > What information or message are you trying to convey with your visualization? 
    I am trying to show ontario apple production (lbs) by variety in 2005. 

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Similarly, I considered the visualization from three main perspectives. From an aesthetic perspective, I aimed to create a clean and intentional layout in which the title, chart elements, labels, and legend are clearly presented. Rather than using another bar chart, I chose a pie chart to emphasize how each apple variety contributes to total production. From a substantive perspective, I ensured that the subject and purpose of the visualization are easy to understand and that the chart connects the data to the real-world distribution of apple production across varieties. From a perceptual perspective, I focused on making the visualization easy to interpret by organizing the categories clearly. However, I also noticed several limitations. The bar chart does not communicate the values as precisely as the original table, especially when many categories are included. Using different colours for each category also adds visual complexity without necessarily improving clarity. Although a pie chart can show each variety’s share of total production, the large number of apple varieties creates too many small slices, making the chart difficult to read and compare. Excel also provides limited flexibility for improving the arrangement of labels and categories. Therefore, because of the number of categories in this dataset, neither the bar chart nor the pie chart can present every value with the same clarity as the original table.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    The original data is in excel and the figure is also created in excel. And similarly, if a non-reproducible tool had been used, it would be difficulty to verify how data was processed to create the visualization. This will introduce errors and inconsistencies. 
    
    > How did you ensure that your data visualization is accessible?  
    I improved the accessibility of the Excel pie chart by giving it a clear and descriptive title and by including a legend that identifies each apple variety. The chart uses distinct colours to separate the categories, and white borders between the slices help make each section more visible. I also kept the background simple so that the chart elements remain easy to see. However, as I mentioned above the large number of apple varieties makes some slices very small and difficult to compare. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    It is the same dataset, so growers and agricultural organizations could use the information to understand which apple varieties account for the largest portions of production in 2005. Distributors and retailers may use it to understand the relative availability of different varieties.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Similarly, I included apple variety and marketed production because the variables directly support the purpose of comparing the relative production of different apple varieties. I excluded transaction price, grower price, transaction value, grower value, and marketing costs. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Using excel is easy without the need to clean data, but to improve accessibility further, I tried to  add data labels showing the percentage for each major variety, however, it doesn't help, so I removed it. 


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-16`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * Two distinct data visualizations (for example, PNGs, PDFs, or screenshots)
        * Two Markdown files answering all questions for each visualization (including a link to your dataset in both files)
        * One Python file contains the complete code and visualization, and another file (with or without code) contains the visualization.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
