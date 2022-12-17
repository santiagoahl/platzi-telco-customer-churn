<h1 align="center">
  <br>

  <br>
Telco Customer Churn
  <br>
</h1>

<h4 align="center">Machine Learning model to predict wether a given customer will churn. 
</h4>

<p align="center">
  <a href='https://www.kaggle.com/' target="_blank"><img alt='kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=kaggle&logoColor=37BAE8&labelColor=BEFDFF&color=37BAE8'/></a> <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='scikit-learn' src='https://img.shields.io/badge/scikit-learn-100000?style=for-the-badge&logo=scikit-learn&logoColor=FFFFFF&labelColor=FF6A00&color=1882EA'/></a> <a href='https://numpy.org/' target="_blank"><img alt='numpy' src='https://img.shields.io/badge/Numpy-100000?style=for-the-badge&logo=numpy&logoColor=0250BD&labelColor=8BBFEA&color=B1DCFF'/></a>  <a href='https://pandas.pydata.org/' target="_blank"><img alt='pandas' src='https://img.shields.io/badge/pandas-100000?style=for-the-badge&logo=pandas&logoColor=2D0090&labelColor=9D7BEA&color=D2C0FA'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a> 
</p>

![screenshot](https://miro.medium.com/max/1104/0*6hXwLKd67L__lTsg.png)

## Key Features

This machine learning model clusters a set of costumers from its personal data. This prediction is one of 3 clusters. The dataset is taken from the [Telco Customer Churn kaggle competition](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). So here are the key features of this project:

* Prediction is based (between others) on these costumers' attributes

	* `gender`
	* `tenure`
	* `MultipleLines`
	* `TotalCharges`
	* `PaymentMethod`

* The target feature is `Churn`, which tells us wheter the customer left or not the telco.

* Dimensionality reduction with **PCA**.
* Data balancing with **SMOTE**.
* Based on **Scikit-Learn** modules and functions such like:
  - `decomposition.PCA`: Dimensionality reduction.
  -  `linear_model.LogisticRegression` : Machine model classifier

* We've gotten a **80.9%** of `f1_score`.
* The confusion matrix is the following:
![screenshot](https://winter-anchovy-50e.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F434aac0d-d773-436f-a3ea-8e7f2f577be4%2FUntitled.png?id=afd281e0-70cb-4bbc-a249-151e50e4f77b&table=block&spaceId=12eea25e-0790-4a8f-aa1c-b60f93c02da2&width=640&userId=&cache=v2)
## How To Use

To clone and run this application, follow these steps

```bash
# Clone this repository
$ git clone https://github.com/santiagoahl/telco-customer-churn.git

# Go into the repository
$ cd telco-customer-churn

```

## Credits
This software uses the following open libraries and datasets:


- [Numpy](http://electron.atom.io/)
- [Matplotlib](https://nodejs.org/)
- [Seaborn](https://github.com/chjj/marked)
- [Pandas](http://showdownjs.github.io/showdown/)
- [Sci-kit Learn](http://codemirror.net/)
- [Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/download?datasetVersionNumber=1)


## License

MIT

---

> Web Site [santiagoal.super.site](https://santiagoal.super.site/) &nbsp;&middot;&nbsp;
> GitHub [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> Twitter [@sahumadaloz](https://twitter.com/sahumadaloz)
