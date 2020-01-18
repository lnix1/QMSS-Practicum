# QMSS-Practicum

Under the app.R file is the code for a shiny app that takes in consumer complaint data from the Consumer Financial Protection Bureau, cleans the dataset with some reformatting, and outputs a simple app for data vizualization. The main goal in creating the app was to offer a tool through which individuals could diagnose the seasonality of the complaint data after subsetting for a specific company(ies), product category(ies), and a time frame. 

While the app is fully dynamic to adapt to the companies and products contained in the data set that is input, the CFPB API required authorized access which I did not have, meaning the dataset must be downloaded beforehand and then referenced by the code for the app. To improve on the app, one would need to obtain access to the CFPB data in a more dynamic way with proper authroization throught the API.
