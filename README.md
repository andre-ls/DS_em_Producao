# DS_em_Producao

On this Repository, a Machine Learning project of Sales Forecast is proposed. This project was created as a participation on the Online Course "DS em Produção" by Meigarom Lopes. 

The involved task consists of forecasting the total Sales of 6 weeks of 1115 stores of the Rossmann Company, which is one of the largest drug store chains on operation in Europe. The data used on this project was obtained on Kaggle [here](https://www.kaggle.com/c/rossmann-store-sales/overview).

---
## Files Organization 

The files on the repository are organized on some folders as below:

* Data: This folder stores all the data used through the work. Keep in mind that, because of some restrictions of file's size on Github, only the original data was uploaded, but as the code is executed new files, containing processed data, are created.

* Model: This folder just contains the Machine Learning selected to be used on this project.

* Notebooks: This folder contains the code responsible for all the steps related to generating the Machine Learning model, from the initial Cleaning of Data until the Model Selection and Tuning.

* Parameter: On this folder, some operators, mainly scalers, are stored to be used on the API's of the model to process new incoming data.

* Rossmann-Sales and Rossmann-Telegram: These two last folders contains some files responsible for creating two aplications on Heroku used to deploy the model. The first one is responsible for calling the model to make predictions, and the second one makes an interconnection between the Rossmann Sales App and a Telegram Bot, where the predictions can be acessed by the target users of the project.




 
