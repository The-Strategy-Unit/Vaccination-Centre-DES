# Vaccination Centre DES  [<img src="https://www.strategyunitwm.nhs.uk/themes/custom/ie_bootstrap/logo.svg" title="The Strategy Unit" alt="The Strategy Unit Logo" align="right" height="80"/>](https://www.strategyunitwm.nhs.uk/)
Modelling of Discrete Event Simulation (DES) for vaccination centres

This repository is for creating DES model of COVID-19 vaccination centres. The model was initially built by Wolverhampton ICS but was then developed into a more generic model by the Strategy Unit Team. 

## Repository structure
### Model. 
SU VacCentre DES 2021-01-29.cfg file can be dowloaded and edited. If you want to run the model on your computer you will need to have JaamSim installed. Click [here](https://jaamsim.com/downloads.html) to choose the appropriate version of the JaamSim program to download and install. Detailed instructions can be found in the [JaamSim manual](https://jaamsim.com/docs/JaamSim%20User%20Manual%202021-01.pdf). Please ensure that you have an appropriate version of Java and your graphics drivers are up to date.

Once JaamSim is installed you can open your model and unpdate input parameters. For full instructions please go to the Instuctions file. 

### Instructions
Instructions cover how to open JaamSim model, change inputs, run the model and where to find results. If you want to know about JaamSim and how to use it, please have a look at the [manual](https://jaamsim.com/docs/JaamSim%20User%20Manual%202021-01.pdf). 

### Excel Output
This excel template has been provided to help with formatting and processing the results, it produces a chart and a table from the model output. Once model has finished running, it will save a .dat file to the same folder as you have the model configuration file with the same name as the .cfg. Open the .dat file in excel. Copy the contents into the "Paste ,Dat file here" worksheet. The "Outputs Table and Chart" will update automatically. 

The table, below the chart, shows a summary of results for the outputted metrics from 200 runs. This includes the average (mean), 95% confidence interval of the average, the minimum, maximum median and interquartile range for each metric. The listed metrics are not exhaustive and it is possible to further adapt the output list within JaamSim. 

It is possible to change which metrics appear in the chart, to do this enter a 1 in column N next to the indicators you want to include. 


## Next Steps
We welcome discussion and ideas on developing this model and would be interested to hear if others find it useful. Please get in touch 
