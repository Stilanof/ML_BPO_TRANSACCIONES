## *ML_BPO_TRANSACCIONES*

As data scientists we convert data into business values that allow making decisions based on the analysis of behavior in the past, present and future of the operation. 

This project is the final work of a eight weeks journey, in which we try to design a Machine Learning product for a local company.  

## *Let's start* 🚀

![Image text](https://github.com/Stilanof/ML_BPO_TRANSACCIONES/blob/main/target.png)

We implemented a k_means model to segment each transaction at the market platform.

## *Final Clusters* 📋

##### select # of cluster based on strength
elbow_table=pd.DataFrame()

elbow_table['k'] = [1,2,3,4,5,6,7,8,9]

elbow_table['Score'] = wcss

for i in range (1, len(elbow_table)):

    elbow_table.loc[i,'Delta1'] = elbow_table.loc[i-1,'Score'] - elbow_table.loc[i,'Score']
    
for i in range (2, len(elbow_table)):

    elbow_table.loc[i,'Delta2'] = elbow_table.loc[i-1,'Delta1'] - elbow_table.loc[i,'Delta1']
    
for i in range (1, len(elbow_table)-1):

    elbow_table.loc[i,'Strength'] = elbow_table.loc[i+1,'Delta2'] - elbow_table.loc[i+1,'Delta1']
    
for i in range (1, len(elbow_table)-1):

    elbow_table.loc[i,'Relative_Strength'] = elbow_table.loc[i,'Strength'] / elbow_table.loc[i,'k']
    
elbow_table

## *Production and implementation* 🔧⚙️ Deploy 📦

![Image text](https://github.com/Stilanof/ML_BPO_TRANSACCIONES/blob/main/architecture.png)



## *Builded with* 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* 
* 
* 


## *Versions* 📌

Take a look at the process! All versions and models tested here (https://github.com/Stilanof/ML_BPO_TRANSACCIONES)

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
* etc.
