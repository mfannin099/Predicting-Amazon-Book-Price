# Machine Learning (Amazon Best Selling Books)

Creating and tuning machine learning model to predict price of books.
Dataset was gotten from Kaggle and consisted of 550 rows of the top 50 best selling books from 2009 to 2019.

Exploratory analysis was conducted to familiarize myself with the dataset.

---
![](/eda.jpg)

---

![](/price_of_books.jpg)

---

## Making the Model

First, I made the the "Genre" column a 0 (Non fiction) or a 1 (fiction) so this column could be included. I tried to predict the cost of a book using the number of reviews, the rating of the book, the year it was relased, and its genre.

The first attempt was using Logistic Regression

---

![](/original_predictions.jpg)

---

After reading more about predictive models I created a voting classifer and also made a new column called ID which a value assigned to each author which helped improve the model.

---

![](/final_predictions.jpg)

---

I improved the model from being 11.82% accurate to 53.64% accurate with a mean squared error of (4.73) meaning on average my model is off by almost 4 dollars and 75 cents. 

### Limitations 

I was working with a small dataset of 550 rows, and also trying to predict price by using 5 columns (orginally 4) this could help explain why my model is not the most accurate. However, I am happy about the improvement in predictions. 
