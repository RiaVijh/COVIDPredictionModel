[Delhi.xlsx](https://github.com/AKKwork/COVIDPredictionModel/files/7828031/Delhi.xlsx)
# COVIDPredictDeploy

## The Following Model is used to :
1. Predict the future COVID cases in each state in India based on previous data based on IDM Covid Modelling Library
2. Estimate the required number of AAC beds and ICU beds required for each state

## INSTRUCTIONS :
### AUTOMATION OF DATA SCRAPING:
1. Clone the repeository and save it a accessible directory
2.  Install java and set java to system path variable
3. Open command prompt/terminal and navigate to saved directory
4. Enter the following command into the command prompt/terminal : java -jar covidpredict-0.0.1-SNAPSHOT.jar "path-to-directory"
5. Most recent covid data for each state shouldd be saved as a csv in the sub-folder CovidPredictDeploy

### RUNNING THE MODEL:
1. Replace the csv file in the folder with the csv file of the state that you want to predict covidd cases for
2. Run jupyter Notebook CovidPredictionModel.ipynb after install additional requirements from requirements.txt and follow specified instructions 

