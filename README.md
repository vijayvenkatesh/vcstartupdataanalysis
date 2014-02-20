This project is my attempt at applying data processing, data munging and science to freely available VC/Startup data.

My source is the Crunchbase API and data export - available at http://info.crunchbase.com/about/crunchbase-data-exports/

Directory structure as follows
data            - Where the initial data exports, dumps are to be stored
iPython         - Where I do all my work
python          - Final quality code
visualizations  - Graphs, visualizations from the data

To start, clone the repo, navigate to the iPython directory and open up the notebook in a iPython viewer


Issues:
1. The data export only contains funded companies. Need to write a scraper that collects all company data.
2. The startups funding graph had some Nans - filled with mean values. Some sawtooth activity as a result. 
