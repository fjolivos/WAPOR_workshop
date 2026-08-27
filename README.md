# Designing and Implementing Factorial Surveys

This repository contains the materials for a workshop on designing and implementing factorial surveys. It covers the complete process, from the methodological foundations of factorial surveys to generating an efficient vignette design and implementing it in Qualtrics.

## Repository contents

### 1. Factorial survey foundations

The PowerPoint presentation introduces:

* The logic of factorial surveys
* Vignette dimensions and levels
* Full and fractional factorial designs
* Orthogonality and balance
* D-efficient designs
* Vignette decks
* Random assignment of respondents to decks

### 2. Generating the vignette design in R

The Google Colab notebook demonstrates how to:

* Define the vignette dimensions and levels
* Generate the complete vignette universe
* Specify the model to be estimated
* Search for D-efficient candidate designs
* Select the design with the highest D-efficiency
* Examine correlations and other design diagnostics
* Assign the selected vignettes to decks
* Convert factor combinations into readable vignette text
* Check the distribution of factor levels across decks
* Export the final design to Excel

The notebook produces two Excel files:

* **Analysis file:** one row per vignette, including deck identifiers, numeric factor levels, and vignette text.
* **Word-generation file:** one row per deck, with separate columns for the sentences included in each vignette.

The notebook runs in Google Colab, so no local installation of R is required.

## Using the Colab notebook

1. Open the notebook in Google Colab.
2. Make a copy in your own Google Drive if you want to save your changes.
3. Run the cells in order.
4. Modify the vignette dimensions, levels, model specification, and sentence templates for your own study.
5. Download the two Excel files generated at the end of the notebook.

The files created inside Colab are temporary. Download them before closing the session.

## Creating the questionnaires in Word

The step-by-step PDF guide explains how to use the Word-generation Excel file to create the questionnaire decks in Microsoft Word.

The guide covers:

* Connecting Word to the Excel output
* Adding the vignette sentences as merge fields
* Creating one questionnaire for each deck
* Checking the generated vignette text
* Saving the questionnaires as Word or PDF files

## Implementing the vignettes in Qualtrics

The Qualtrics guide explains how to:

* Create the vignette blocks
* Import or enter the vignette text
* Randomly assign respondents to one of the decks
* Present the 16 vignettes within the assigned deck
* Randomize the order of vignettes when appropriate
* Record the deck and vignette identifiers
* Test the survey before data collection

## Recommended workflow

1. Review the presentation on factorial survey foundations.
2. Open and adapt the Colab notebook.
3. Generate and download the Excel outputs.
4. Use the Word guide to create printable questionnaire decks, if needed.
5. Use the Qualtrics guide to implement random deck assignment in an online survey.
6. Pilot the questionnaire and verify that the deck and vignette identifiers are correctly recorded.

## Important considerations

The example materials are intended as a starting point. Researchers should adapt the following elements to their own research design:

* Vignette dimensions and levels
* Model specification
* Number of vignettes
* Number and size of decks
* Vignette wording
* Outcome questions
* Randomization procedure

Before beginning data collection, check the experimental design, review the wording of all vignettes, and pilot the questionnaire with participants from the target population.

## Software

The materials use:

* R
* Google Colab
* Microsoft Excel
* Microsoft Word
* Qualtrics

The required R packages are installed or loaded directly from the Colab notebook.

## Citation

If you use or adapt these materials for teaching or research, please acknowledge the repository and its author:

> Olivos, Francisco. *Designing and Implementing Factorial Surveys: Workshop Materials.*

## Author

**Francisco Olivos**
Department of Sociology and Social Policy
Lingnan University
