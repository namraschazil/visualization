# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    I used matplotlib to make the visualisation in python. For the second visualisation, I used excel and the graph features in it. 

    > Who is your intended audience? 
    The intended audience for both the visualisations could be Toronto public health workers or health reform makers in healthcare institutions like hospitals, long-term care homes and retirement homes. Toronto public health works with healthcare institutions to prevent and control institutional outbreaks. The visualisation made on matplotlib could be utilised for infection prevention and control.
    
    > What information or message are you trying to convey with your visualization? 
    The first visualisation demonstrates the number of gastroenteric (eg. Nausea, vomiting, diarrhea, fever) and respiratory (eg. Cough, runny nose, sore throat, fever) infections in different outbreak settings like LTCH (long term care hospital), retirement homes, chronic care hospital, acute care hospital, psychiatric care hospital and transitional care.  The second visualisation shows a bar graph with the frequency of outbreaks in different outbreak settings also divided by the type of outbreak like respiratory, enteric and others. 
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    The design principles I considered while making both the visualisation was aesthetics, substantive and perceptual. I used colors and font which were pleasing to look at, used data appropriately to convey an honest and true message and tried to keep the visualisation simple and clear to convey the message appropriately. 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    I made the visualisation using python code and save it so they can be run again and replicated. I also set a seed value to allow for reproducibility even if the code is run multiple times.  I couldn’t save the steps I used to make the second visualisation in excel therefore the visualisation is not reproducible and hence if someone wants to replicate the same visualisation on their own, it wont be possible to do and they might succeed in making something similar but not entirely same. 
    
    > How did you ensure that your data visualization is accessible?
    I used colors and contrast that are suitable for people with color blindness and autism. The softwares I used for this purpose are webAIM and color blindness stimulator. They allowed me to select optimum colors with adequate contrast. I changed the colors for the bars in the second visualisation using the edit graph feature to allow for accessibility for color blindness.   
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    The healthcare community might be impacted by both the visualisation as it allows them to see the number of infection outbreaks and to access how to stay safe from them through prevention and control. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I excluded the addresses of the outbreak settings and the time the outbreak started and ended as it was a lot of overwhelming information that I didn’t want to show in my visualisation. I only included 2 columns: outbreak setting and the type of infections caused like respiratory, enteric and others. For the second visualisation, I also added a third column in addition to the two columns which included the total number of outbreaks. 
    > What ‘underwater labour’ contributed to your final data visualization product?
    I used resources from the Data Visualisation module and beginner youtube videos on data visualisation  to enable me to work on my visualisation constructively. 

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
