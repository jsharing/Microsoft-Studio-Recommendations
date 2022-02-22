
## Microsoft Needs Recommendations For A New Movie Studio

**Author**: [Jody Haring](mailto:jodyharing@gmail.com)


## Project Overview

This project will use exploratory data analysis to generate insights for Microsoft, a 2.25 Trillion company that is looking to create a new film studio to compete with other large companies in the film industry.


### Business Problem

Microsoft has decided to create a new movie studio, and needs insight on which films do best in the global box office. Microsoft needs actionable insights to help decide what type of films to create for their new studio.

### Data Understanding

In the folder `zippedData` are movie datasets, provided by the Flatiron School, from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)
* [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset?select=movies_metadata.csv)

The final datasets used for analysis contain ##### movies from month year to month year.


### Data Analysis

The best runtime to aim for is between 150 and 165 minutes. The reason I am not recommending a runtime between 195 and 210 minutes is because only two movies are represented in this category.

+![](./images/Runtime.png)

The highest average grossing films are categorized into four genres:
- Musical
- Animation
- Adventure
- Fantasy

+![](./images/Genre.png)

The highest average grossing month to release a film is June, followed by the summer break months of May and July, with the holiday months of November and December following closely after.

+![](./images/Month_release.png)


  
### Conclusion






### Key Points

* **Your analysis should yield three concrete business recommendations.** The ultimate purpose of exploratory analysis is not just to learn about the data, but to help an organization perform better. Explicitly relate your findings to business needs by recommending actions that you think the business (Microsoft) should take.

* **Communicating about your work well is extremely important.** Your ability to provide value to an organization - or to land a job there - is directly reliant on your ability to communicate with them about what you have done and why it is valuable. Create a storyline your audience (the head of Microsoft's new movie studio) can follow by walking them through the steps of your process, highlighting the most important points and skipping over the rest.

* **Use plenty of visualizations.** Visualizations are invaluable for exploring your data and making your findings accessible to a non-technical audience. Spotlight visuals in your presentation, but only ones that relate directly to your recommendations. Simple visuals are usually best (e.g. bar charts and line graphs), and don't forget to format them well (e.g. labels, titles).

## Deliverables

There are three deliverables for this project:

* A **non-technical presentation**
* A **Jupyter Notebook**
* A **GitHub repository**

### Non-Technical Presentation

The non-technical presentation is a slide deck presenting your analysis to business stakeholders.

* ***Non-technical*** does not mean that you should avoid mentioning the technologies or techniques that you used, it means that you should explain any mentions of these technologies and avoid assuming that your audience is already familiar with them.
* ***Business stakeholders*** means that the audience for your presentation is Microsoft, not the class or teacher. Do not assume that they are already familiar with the specific business problem, but also do not explain to them what Microsoft is.

The presentation describes the project ***goals, data, methods, and results***. It must include at least ***three visualizations*** which correspond to ***three business recommendations***.

We recommend that you follow this structure, although the slide titles should be specific to your project:

1. Beginning
    * Overview
    * Business Understanding
2. Middle
    * Data Understanding
    * Data Analysis
3. End
    * Recommendations
    * Next Steps
    * Thank You
       * This slide should include a prompt for questions as well as your contact information (name and LinkedIn profile)

You will give a live presentation of your slides and submit them in PDF format on Canvas. The slides should also be present in the GitHub repository you submit with a file name of `presentation.pdf`.

The graded elements of the presentation are:

* Presentation Content
* Slide Style
* Presentation Delivery and Answers to Questions


### Jupyter Notebook

The Jupyter Notebook is a notebook that uses Python and Markdown to present your analysis to a data science audience.

* ***Python and Markdown*** means that you need to construct an integrated `.ipynb` file with Markdown (headings, paragraphs, links, lists, etc.) and Python code to create a well-organized, skim-able document.
  * The notebook kernel should be restarted and all cells run before submission, to ensure that all code is runnable in order.
  * Markdown should be used to frame the project with a clear introduction and conclusion, as well as introducing each of the required elements.
* ***Data science audience*** means that you can assume basic data science proficiency in the person reading your notebook. This differs from the non-technical presentation.

Along with the presentation, the notebook also describes the project ***goals, data, methods, and results***. It must include at least ***three visualizations*** which correspond to ***three business recommendations***.

You will submit the notebook in PDF format on Canvas as well as in `.ipynb` format in your GitHub repository.

The graded elements for the Jupyter Notebook are:

* Business Understanding
* Data Understanding
* Data Preparation
* Data Analysis
* Visualization
* Code Quality


### GitHub Repository

The GitHub repository is the cloud-hosted directory containing all of your project files as well as their version history.

This repository link will be the project link that you include on your resume, LinkedIn, etc. for prospective employers to view your work. Note that we typically recommend that 3 links are highlighted (out of 5 projects) so don't stress too much about getting this one to be perfect! There will also be time after graduation for cosmetic touch-ups.

A professional GitHub repository has:

1. `README.md`
    * A file called `README.md` at the root of the repository directory, written in Markdown; this is what is rendered when someone visits the link to your repository in the browser
    * This file contains these sections:
       * Overview
       * Business Understanding
          * Include stakeholder and key business questions
       * Data Understanding and Analysis
          * Source of data
          * Description of data
          * Three visualizations (the same visualizations presented in the slides and notebook)
       * Conclusion
          * Summary of conclusions including three relevant findings
2. Commit history
   * Progression of updates throughout the project time period, not just immediately before the deadline
   * Clear commit messages
   * Commits from all team members (if a group project)
3. Organization
   * Clear folder structure
   * Clear names of files and folders
   * Easily-located notebook and presentation linked in the README
4. Notebook(s)
   * Clearly-indicated final notebook that runs without errors
   * Exploratory/working notebooks (can contain errors, redundant code, etc.) from all team members (if a group project)
5. `.gitignore`
   * A file called `.gitignore` at the root of the repository directory instructs Git to ignore large, unnecessary, or private files
     * Because it starts with a `.`, you will need to type `ls -a` in the terminal in order to see that it is there
   * GitHub maintains a [Python .gitignore](https://github.com/github/gitignore/blob/master/Python.gitignore) that may be a useful starting point for your version of this file
   * To tell Git to ignore more files, just add a new line to `.gitignore` for each new file name
     * Consider adding `.DS_Store` if you are using a Mac computer, as well as project-specific file names
     * If you are running into an error message because you forgot to add something to `.gitignore` and it is too large to be pushed to GitHub [this blog post](https://medium.com/analytics-vidhya/tutorial-removing-large-files-from-git-78dbf4cf83a?sk=c3763d466c7f2528008c3777192dfb95)(friend link) should help you address this

You wil submit a link to the GitHub repository on Canvas.

See the [Grading](#grading) section for further explanation of how the GitHub repository will be graded.

For further reading on creating professional notebooks and `README`s, check out [this reading](https://github.com/learn-co-curriculum/dsc-repo-readability-v2-2).



### Attention to Detail

#### Exceeds Objective
70% or more of the project checklist items are complete

#### Meets Objective (Passing Bar)
60% of the project checklist items are complete

#### Approaching Objective
50% of the project checklist items are complete

#### Does Not Meet Objective
40% or fewer of the project checklist items are complete

### Data Communication

Communication is another key "soft skill". In [the same survey mentioned above](https://www.payscale.com/data-packages/job-skills), 46% of hiring managers said that recent college grads were missing this skill.

Because "communication" can encompass such a wide range of contexts and skills, we will specifically focus our Phase 1 objective on Data Communication. We define Data Communication as:

> Communicating basic data analysis results to diverse audiences via writing and live presentation

To further define some of these terms:

* By "basic data analysis" we mean that you are filtering, sorting, grouping, and/or aggregating the data in order to answer business questions. This project does not involve inferential statistics or machine learning, although descriptive statistics such as measures of central tendency are encouraged.
* By "results" we mean your ***three visualizations and recommendations***.
* By "diverse audiences" we mean that your presentation and notebook are appropriately addressing a business and data science audience, respectively.

### Authoring Jupyter Notebooks

#### Exceeds Objective
Uses Markdown and code comments to create a well-organized, skim-able document that follows all best practices

> Refer to the [repository readability reading](https://github.com/learn-co-curriculum/dsc-repo-readability-v2-2) for more tips on best practices

#### Meets Objective (Passing Bar)
Uses some Markdown to create an organized notebook, with an introduction at the top and a conclusion at the bottom

#### Approaching Objective
Uses Markdown cells to organize, but either uses only headers and does not provide any explanations or justifications, or uses only plaintext without any headers to segment out sections of the notebook


### Data Manipulation and Analysis with `pandas`

Unlike in base Python, where the Zen of Python says "There should be one-- and preferably only one --obvious way to do it", there is often more than one valid way to do something in `pandas`. However there are still more efficient and less efficient ways to use it. Specifically, the best `pandas` code is *performant* and *idiomatic*.

Performant `pandas` code utilizes methods and broadcasting rather than user-defined functions or `for` loops. For example, if you need to strip whitespace from a column containing string data, the best approach would be to use the [`pandas.Series.str.strip` method](https://pandas.pydata.org/docs/reference/api/pandas.Series.str.strip.html) rather than writing your own function or writing a loop. Or if you want to multiply everything in a column by 100, the best approach would be to use broadcasting (e.g. `df["column_name"] * 100`) instead of a function or loop. You can still write your own functions if needed, but only after checking that there isn't a built-in way to do it.

Idiomatic `pandas` code has variable names that are meaningful words or abbreviations in English, that are related to the purpose of the variables. You can still use `df` as the name of your DataFrame if there is only one main DataFrame you are working with, but as soon as you are merging multiple DataFrames or taking a subset of a DataFrame, you should use meaningful names. For example, `df2` would not be an idiomatic name, but `movies_and_reviews` could be.

#### Exceeds Objective
Uses `pandas` to prepare data and answer business questions in an idiomatic, performant way

#### Meets Objective (Passing Bar)
Successfully uses `pandas` to prepare data in order to answer business questions


