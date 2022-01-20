# ACM Research Coding Challenge (Spring 2022)

## Explanation

This was my first time working with machine learning/data science. I have used Python in the past, but not with Jupyter Notebooks. There definitely was a bit of a learning curve here for me — you might have noticed that when I went a little bit ham with the slightly excessive amount of markdown cells created and used. Oh well.

I used the following libraries:
1. `pandas` for reading the data-set.
2. `sklearn`'s `LabelEncoder`, `train_test_split`, and `StandardScaler` for converting the entries in the data-set to integers, splitting the entries for training and testing, and standardizing the data respectively.
3. `sklearn`'s `SVC` to implement the Support-Vector Machine algorithm. More specifically, my implemention uses the C-Support Vector Classification technique. This is the meat of the problem and was chosen primarily because the package works well enough for a data-set of this size, provides satisfactory results (an accuracy of 100% o_o), and it doesn't hurt that it's not math-heavy on the surface and is easy to use. It apparently isn't as efficient for larger data-sets, though.

Resources used:
- https://youtu.be/iGFdh6_FePU a good guide for learning `pandas`
- https://medium.com/analytics-vidhya/mushroom-classification-using-different-classifiers-aa338c1cd0ff some code from this guide was used to get me started on researching on choosing the algorithms for my model. Seeing all those graphs and charts was quite intimidating, if I am being honest. After referring to this guide, I found out that I needed to use `LabelEncoder` to convert the strings in the data-set to integers because almost every library used afterwards was incompatible with string data. It also exposed me to a variety of ML models. I decided to stick with SVC because of its relative performance compared to the other models as well as ease of use.
- https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html `sklearn`'s documentation for the algorithm was referred to numerous times
- https://youtu.be/7E7tl6rm7VM this guide was very helpful in fleshing out what I wanted to do. It influenced me to standardize my data with `StandardScaler`.

Overall, this challenge was quite intriguing and made me brush up on my Python, which I really appreciate! For whatever reason, I didn't hold a favorable opinion on machine learning before, but this challenge changed that and has inspired me to delve further into the topic to play around with it a lot more. I truly felt like I learned a lot after giving this challenge a try and rummaging around the Internet trying to make sense of it, and now I really want to eat a shiitake mushroom for some reason.
