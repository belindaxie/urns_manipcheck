# Experiment 1

- 2 (dependency: independent, sequential) x 3 (number of informants: 3, 5, 7) between-subjects design
- To run through the experiment, open the index.html file in your browser
    + By default, you will be randomly assigned to one dependency and number-of-informants condition
    + If you want to run through one condition in particular;
        + Specify the dependency condition on l. 61 of the index.html file (uncomment this line) - change the text string to 'i' (independent), 'sq' (sequential)
        + Specify the distribution condition on l. 44 of the index.html file (uncomment this line) - change the text string to '3-1' (3 informants), '5-1' (5 informants) or '7-1' (7 informants)

### Other information about the other files required to run this experiment
A minimal template for running experiments through the browser using jsPsych and Google App Engine. Intended to work in conjunction with MTurk and adhere to UNSW ethics guidelines. Notes:

- In the app.yaml file, edit the project ID
- If there are additional folders add those in app.yaml
- Each jsPsych trial type needs to be added
- The welcome.js file has various standard fields to fill out
- importData.R is a simple R script that downloads the data from GAE and organises it into a tidy CSV file
