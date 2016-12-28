# This page is under development



## Complete:
* Build the web scraper
* Scrape all band logos from metal-archives.com
    * Uses scraper.py

## Pending:
* Research / construct generative model
* Develop data cleaning scripting

## To do:
* Data cleaning
    * Determine band name screening criteria
    * Figure out handling of multiple bands with the same name
    * Image processing
        * Determine image screening criteria
            * Weird colors (including dark-on-transparency logos)
            * Weird outlines
            * Too much grayscale variation
        * Format selected images
            * Figure out how to "cut" composite images into multiple pieces
            * Fill transparency to black
            * Set to grayscale
            * Hard auto-contrast to get as close to B&W as possible
            * Discard small images
            * Center, resize to common dimensions, fill bkg with black
* Model architecture
    * Design network, establish success criteria
    * Implement network
    * Hyperparameter tuning
* Ancillary analyses
    * Band names distributions by # chars
    * How many logos per name? (distribution)