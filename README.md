## Monthly Rain Fall Bangladesh 

### Dataset 
URL : https://www.kaggle.com/emonreza/65-years-of-weather-data-bangladesh-preprocessed

### Correlation matrix 
![correlation](https://user-images.githubusercontent.com/41207912/135913066-3e75188e-55af-4105-8baa-58b43d22d7b6.png)

### Relational Plot
![pairplot](https://user-images.githubusercontent.com/41207912/135913078-546c4c63-b961-4fd5-8408-1218bf15246d.png)

From relational plot it seems ['Cloud Coverage','Min Temp', 'Bright Sunshine'  ] are positively or negetavily correlated [Close to -1 or 1] 
<br>
<br> NB: Rainfall is ignored as Rainlevel is a quantized version of Rainlevel.

### Applied SVM, DT,KNN,NB 
The accuracy of the SVM is: 0.6493 <br>
The accuracy of the DT is: 0.5612 <br>
The accuracy of the KNN is: 0.5979 <br>
The accuracy of the NB is: 0.5821 <br>
