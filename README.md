# MACHINE LEARNING ALGORITHM TO OPTIMIZE PURCHASE TRANSACTIONS

## *ML_BPO_TRANSACCIONES*

As data scientists we convert data into business values that allow making decisions based on the analysis of behavior in the past, present and future of the operation. 

This project is the final work of a eight weeks journey, in which we try to design a Machine Learning product for a local company.  

## *Let's start* 🚀

![Image text](https://github.com/Stilanof/ML_BPO_TRANSACCIONES/blob/main/target.png)

We implemented a k_means model to segment each transaction at the market platform.

## *Production* 🔧⚙️ 

![Image text](https://github.com/Stilanof/ML_BPO_TRANSACCIONES/blob/main/architecture.png)

## *Implementation* 📋

The model consists of two notebooks, “Proveindustriales_Data_Cleaned” and “Proveindustriales_Model”.

"Proveindustriales_Data_Cleaned" loads the csv file and, once the user enters the dates corresponding to the period that he wants to analyze, he proceeds with the preparation and cleaning of the data; the grouping of the categories, subcategories, suppliers and purchasing companies with the fewest occurrences under the class "Others"; correlation analysis; the normalization of the numerical variables and the transformation of the categorical variables.

"Proveindustriales_Model" takes the file generated by "Proveindustriales_Data_Cleaned" and executes the clustering algorithm, extracts the most relevant characteristics of each cluster and presents the behavior of the clusters in the Dashboard.

Procedure:

1. Upload the Excel file with all transactions to Azure Blob storage
2. Open the notebook "Proveindustriales_Data_Cleaned"
3. Establish Start Date and End Date, corresponding to the period of time that you want to analyze
4. Run the notebook "Proveindustriales_Data_Cleaned"
5. Open and run the notebook "Proveindustriales_Model"
6. Refer to the "Dashboard_Proveindustriales"

## *Builded with* 🛠️

* Azure Blob storage  
* Containers
* Databricks 


## *Versions* 📌

Take a look at the process! All versions and models tested here (https://github.com/Stilanof/ML_BPO_TRANSACCIONES)

Final presentation here (https://github.com/Stilanof/ML_BPO_TRANSACCIONES/blob/main/presentaci%C3%B3n_final.pdf)

## *Authors* ✒️

* **Anibal Munera** 
* **Luis Andrés Montoya** 
* **Mauricio Villegas** 
* **Susana Tilano** 

Thanks to everyone who teach us something along the way! 

## *Expresiones de Gratitud* 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.

