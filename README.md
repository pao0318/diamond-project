# Diamond Project

This project consists of a ML model which predicts the price of diamond based on its different features.

## Description

Diamond is highly valued in our society. It is seen as a sign of nobility. However, we don't know more about different features of diamond. We only know about carat, but not in depth. Hence let's discuss about the different features of diamond used in our project:

1. Carat : 1 carat is equal to 200mg. Further, 1 carat is divided into 100 division. 
2. Cut : Cut refers the way the diamond is shaped. It has a large impact of the brilliance(shining).
3. Clarity : It refers to the amount of blemishes, different types of clarity :
    1. Flawless (FL) No inclusions and no blemishes visible under 10x magnification
    2. Internally Flawless (IF) No inclusions visible under 10x magnification
     3. Very, Very Slightly Included (VVS1 and VVS2) Inclusions so slight they are difficult for a skilled grader to see under 10x magnification
    4. Very Slightly Included (VS1 and VS2) Inclusions are observed with effort under 10x magnification, but can be characterized as minor
    5. Slightly Included (SI1 and SI2) Inclusions are noticeable under 10x magnification
    6. Included (I1, I2, and I3) Inclusions are obvious under 10x magnification which may affect transparency and brilliance
In our dataset, we have only I1,IF,VS1,VS2,VVS1,VVS2,SI1 and SI2.
4. Colour : Colour actually means lack of colour in diamond. The used dataset has colours D-J (worst to best).
5. Dimensions : The lenght, width and height of diamond(x,y and z respectively).
6. Depth and table : These two are related to dimension. Depth is the ratio of z with mean of x and y.
Depth  = z/mean(x,y). Table is width of diamond relative to its widest point.

Click [here](https://www.kaggle.com/shivam2503/diamonds/download) to download the dataset and see it first.


### Dependencies

* Libraries used in project:
    1. Pandas
    2. Numpy
    3. Matplotlib
    4. Scikit-Learn
    5. Seaborn

### Installing Libraries

* The YAML file (.yml) is in the project folder, hence you can use it create the conda environment at your end.
* If any new libraries are used, please mention them and make another YAML file from your end and upload it with the project notebook.

### Executing program

Cell by cell execution in series from start to end. Please read the comments in each cell as some have information regarding when to run.


## Author

Contributor names and contact info

Ankit Oscar Xalxo  
Email : ankitoscar911@gmail.com

## Version History
* 0.1
    * Initial Release


## Acknowledgments

* [Kaggle (for dataset)](https://kaggle.com)
* [Stack Overflow](https://stackoverflow.com)
* [GIA (for information regarding diamond's features)](https://4cs.gia.edu/)