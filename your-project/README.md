<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Peanut Publishing: Business Intelligence Report for a New Publishing Company
*Maria João Silva*

*Data Squad 32, Ironhack Lisbon Campus, November 2019*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Datasets](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
This project intends to present a brief business intelligence report for an hypothetical publishing company that's starting business, offering insights into reader preferences to potentially outline a sale-optimisation strategy. I chose this subject because I have some knowledge of editorial practices from previous works that I have done.

<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
Is is better for the publisher to invest in new, unpublished authors or well-established authors?
What book format would be better for the publisher to invest on (audiobook, ebook, traditional book)?
What are the genres that attract most readers?
What are some of the costs that the publisher can expect to incur?

<a name="dataset"></a>

## Datasets
I crossed information from two datasets that were found on Kaggle:
1) [Goodreads' Best Books Ever](https://www.kaggle.com/meetnaren/goodreads-best-books): Data on the list of best books ever as published of Goodreads.com, with information about book characteristics.
2) [goodbooks-10k](https://www.kaggle.com/zygmunt/goodbooks-10k): I used the updated version of this dataset, which contains more detailed information about user ratings for many of the books found on the first dataset.

<a name="workflow"></a>

## Workflow
The first and lenghthier step was to clean both datasets. Initially, I had hoped to join them according to the book ISBN, but a formatting error in one of the datasets made this impossible. As a result, a large amount of books could not be easily matched across datasets and ended up being dropped. I also had to organise the book genres into broader categories so that I could extract actionable information.

The next step was to perform some exploratory data analysis on the variables that I wanted to consider. For each significant conclusion, I created a visualization that could best illustrate it with the matplotlib and seaborn libraries.

Finally, I did some research on other variables that could complement the information that I had extracted from the datasets, such as budgets from local typography companies, current practices for contracts in the editorial market and other costs associated with legal fees.

<a name="organization"></a>

## Organization
I organised my work using a Trello board, where I set deadlines and checklists for the various stages of the work.

<a name="links"></a>

## Links

[Repository](https://github.com/mjvsilva/Project-Week-4/)  
[Slides](https://www.canva.com/design/DADseRDV2dw/_2_hzR80LjhU3WICNDwcjg/view?utm_content=DADseRDV2dw&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton)  
[Trello](https://trello.com/b/utVt9RdT/project-week-4)  
