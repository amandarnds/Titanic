<h1 align="center"> Business Problem </h1>

<figure>
  <p align="center">
   <img src="https://user-images.githubusercontent.com/120829907/236650672-89c7d88a-7607-4b99-8003-dee0f6bc5b40.jpg" width="300" height="300">
   <figcaption style="text-align: center;">Image of <a href="https://allthatsinteresting.com/titanic-sinking-photos">Ati</a></figcaption>
</figure>

<h2> 1.  Summary </h2>
<p> 
Titanic was a British luxury liner that tragically sank on its maiden voyage in 1912. The ship, touted as "unsinkable," collided with an iceberg, leading to the deaths of over 1,500 people. The disaster prompted improvements in maritime safety, and the Titanic's story continues to captivate the world's imagination. </p> 

<h2> 2.  Description </h2>
<p> IThis experiment aims to create a model to answer the question :“what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc). </p>

<h2>3.  Data </h2>
<p>Dataset:
    <a href="https://www.kaggle.com/competitions/titanic/data">Titanic - Machine Learning from Disaster</a>
</p>
<p> This data set is from Kaggle and is part of a competition  </p>
<p> There are two datasets: train and test </p>
<p> This data set contains 10 variables where the survival is the target variable <p> 

<h2>4.  Features </h2>

 <table>
  <tr>
    <th> Variable </th>
    <th> Definition</th>
    <th> Key</th>
  </tr>
  <tr>
    <td>PassengerId</td>
    <td> Id unique for each passenger </td>
    <td> </td>
    <tr>
    <td>Name</td>
    <td> Name of each passenger</td>
    <td> </td>
    <tr>
    <td>survival</td>
    <td>survival</td>
    <td>0 = No, 1 = Yes</td>
    <tr>
    <td>pclass</td>
    <td>A proxy for socio-economic status (SES) </td>
    <td>1 = 1st (upper), 2 = 2nd (middle), 3 = 3rd(lower)</td>
    <tr>
    <td>sex</td>
    <td>Sex</td>
    <td>male or female</td>
    <tr>
    <td>Age</td>
    <td>Age</td>
    <td> in years </td>
    <tr>
    <td>sibsp</td>
    <td># of siblings / spouses aboard the Titanic</td>
    <td>The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored) </td>
    <tr>
    <td>parch</td>
    <td># of parents/children aboard the Titanic</td>
    <td>The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.</td>
    <tr>
    <td>ticket</td>
    <td>number of the ticket</td>
    <tr>
    <td>fare</td>
    <td>Passenger fare</td>
    <td>the value payed</td>
    <tr>
    <td>Cabin</td>
    <td>Cabin number</td>
    <td>number of the cabin</td>
    <tr>
    <td>embarked</td>
    <td>Port of Embarkation</td>
    <td>C = Cherbourg, Q = Queenstown, S = Southampton</td>
  </tr>
</table>
