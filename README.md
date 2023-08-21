![Projeto-Airbnb-Busca-de-Precos](https://socialify.git.ci/andremporto/Projeto-Airbnb-Busca-de-Precos/image?description=1&descriptionEditable=Airbnb%20Rio%20Project%20-%20Property%20Price%20Prediction%20Tool%20for%20ordinary%20people&forks=1&issues=1&language=1&name=1&owner=1&pattern=Signal&pulls=1&stargazers=1&theme=Light)

### Context

On Airbnb, anyone who has a room or property of any kind (apartment, house, chalet, inn, etc.) can offer their property to be rented per day.

You create your host profile (person who makes a property available for daily rent) and create your property advertisement.

In this advertisement, the host must describe the characteristics of the property as completely as possible, in order to help landlords/travelers to choose the best property for them (and in order to make their advertisement more attractive)

There are dozens of possible customizations to your listing, from minimum night amount, price, number of rooms, to cancellation rules, extra fee for extra guests, requirement for landlord ID verification, etc.

### Our goal

Build a price prediction model that allows an average person who owns a property to know how much they should charge for their property per day.

Or even, for the common lessor, given the property he is looking for, help to know if that property is at an attractive price (below the average for properties with the same characteristics) or not.

### What we have available, inspirations and credits

The databases were taken from the kaggle website: https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro

They are available for download below the lecture (if you pull the data directly from Kaggle you may find different results from mine, after all the databases may have been updated).

If you want another solution, we can refer to the solution by user Allan Bruno from kaggle in Notebook: https://www.kaggle.com/allanbruno/helping-regular-people-price-listings-on-airbnb

You will notice similarities between the solution we are going to develop here and his, but also some significant differences in the project construction process.

- The databases are the prices of the properties obtained and their respective characteristics in each month.
- Prices are given in reais (R$)
- We have databases from April 2018 to May 2020, with the exception of June 2018 which has no database

### Initial Expectations

- I believe that seasonality can be an important factor, since months like December tend to be very expensive in RJ
- The location of the property should make a lot of difference in the price, since in Rio de Janeiro the location can completely change the characteristics of the place (security, natural beauty, tourist attractions)
- Extras/Amenities can have a significant impact as we have many old buildings and houses in Rio de Janeiro

Let's find out how much these factors impact and if we have other not so intuitive factors that are extremely important.

## Environment

To run this project, you will need to add the following environment variables to your .env

`pathlib`

`matplotlib`

`numpy`

`pandas`

`seaborn`

`plotly`

`sklearn`

## Roadmap

- Import Libraries and Databases
- Handle Missing Values
- Check Data Types in each column
- Replace the $ and the commas
- Exploratory Analysis
- Outlier Treatment
- Outlier function definitions
- Outliaries deletion
- Handling columns of text values
- Property map view
- Encoding
- Forecast Model
- Best Model Analysis
- Best Model Adjustments and Improvements
- Best Model Final Adjustments
- Project Deployment

## Screenshots

![Screenshot 01](https://github.com/andremporto/Projeto-Airbnb-Busca-de-Precos/blob/main/images/output1.png?raw=true)

![Screenshot 02](https://github.com/andremporto/Projeto-Airbnb-Busca-de-Precos/blob/main/images/output2.png?raw=true)

![Screenshot 03](https://github.com/andremporto/Projeto-Airbnb-Busca-de-Precos/blob/main/images/output3.png?raw=true)

![Screenshot 04](https://github.com/andremporto/Projeto-Airbnb-Busca-de-Precos/blob/main/images/output4.png?raw=true)

## References

- [Kaggle databases](https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro)
- [Allan Bruno kaggle](https://www.kaggle.com/allanbruno/helping-regular-people-price-listings-on-airbnb)
- [Hashtag Treinamentos Course](https://www.hashtagtreinamentos.com/)

## Author

- [André Porto](https://www.linkedin.com/in/andremporto/)
