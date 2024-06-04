# Module 14 Challenge: Belly Button Biodiversity Dashboard

## Background

This project aims to create an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. This dataset reveals that a small number of microbial species (operational taxonomic units or OTUs) are present in over 70% of people, while the rest are relatively rare.

## Repository Setup

1. **Create a Repository**: Create a new repository named `belly-button-challenge` on GitHub.
2. **Clone the Repository**: Clone this repository to your local machine.
3. **Copy Starter Code**: Copy the files from the `StarterCode` folder provided within the Module 14 Challenge zip file (index.html, samples.json, and the static folder) into your local repository.
4. **Push to GitHub**: Push the copied files to your GitHub repository.
5. **Deploy to GitHub Pages**: Deploy your repository to GitHub Pages.

## Files

Download the starter code from the following link: [Starter Code](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/Starter_Code.zip)

## Instructions

1. **Read Data**: Use the D3 library to read in `samples.json` from the URL [here](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json).
2. **Horizontal Bar Chart**:
    - Display the top 10 OTUs for an individual selected from the dropdown menu.
    - Use `sample_values` as the values, `otu_ids` as the labels, and `otu_labels` as the hover text.
3. **Bubble Chart**:
    - Display each sample with `otu_ids` as the x values, `sample_values` as the y values, `sample_values` for the marker size, `otu_ids` for marker colors, and `otu_labels` for text values.
4. **Metadata Panel**:
    - Display the individual's demographic information.
    - Loop through each key-value pair in the metadata JSON object and append it to the `#sample-metadata` panel.
5. **Update Plots**: Update all plots when a new sample is selected from the dropdown menu.
6. **Deploy App**: Deploy the application to a static page hosting service like GitHub Pages.

## Requirements

### Bar Chart (30 points)

- Initializes without error (10 points)
- Updates when a new sample is selected (5 points)
- Uses top 10 sample values as values (5 points)
- Uses `otu_ids` as the labels (5 points)
- Uses `otu_labels` as the tooltip (5 points)

### Bubble Chart (40 points)

- Initializes without error (10 points)
- Updates when a new sample is selected (5 points)
- Uses `otu_ids` for the x values (5 points)
- Uses `otu_ids` for marker colors (5 points)
- Uses `sample_values` for the y values (5 points)
- Uses `sample_values` for the marker size (5 points)
- Uses `otu_labels` for text values (5 points)

### Metadata and Deployment (30 points)

- Metadata initializes without error (10 points)
- Metadata updates when a new sample is selected (10 points)
- App successfully deployed to GitHub Pages (10 points)

## Submission

Submit your assignment by providing the URL of your GitHub repository for grading. Ensure your repository has regular commits and a comprehensive README.md file.

## Grading

Your assignment will be evaluated based on the criteria outlined above and graded accordingly:

- A: 90+ points
- B: 80-89 points
- C: 70-79 points
- D: 60-69 points
- F: <60 points

## References

Hulcr, J. et al. (2012). A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from [Belly Button Biodiversity](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

## Author

Kevin Ngala
---
Note: The source of any code that I did not author came from The Data Analysis Boot Camp at George Washington University. 
