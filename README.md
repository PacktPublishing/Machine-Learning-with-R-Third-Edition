# Machine Learning with R - Third Edition
This is the code repository for Machine Learning with R - Third Edition, published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.

## About the Book
Machine learning, at its core, is concerned with transforming data into actionable knowledge. R offers a powerful set of machine learning methods to quickly and easily gain insight from your data.

Machine Learning with R, Third Edition provides a hands-on, readable guide to applying machine learning to real-world problems. Whether you are an experienced R user or new to the language, Brett Lantz teaches you everything you need to uncover key insights, make new predictions, and visualize your findings.

This new 3rd edition updates the classic R data science book with newer and better libraries, advice on ethical and bias issues in machine learning, and an introduction to deep learning. Find powerful new insights in your data; discover machine learning with R.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

The code will look like the following:
```
wbcd_test_pred <- knn(train = wbcd_train, test = wbcd_test, cl = wbcd_train_labels, k=1)
CrossTable(x = wbcd_test_labels, y = wbcd_test_pred, prop.chisq=FALSE)
```

## Software Requirements

* R 3.5.x

* RStudio 1.1.x

## Related Products

* [Mastering Machine Learning with R - Third Edition](https://prod.packtpub.com/in/big-data-and-business-intelligence/mastering-machine-learning-r-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789618006)

* [Python Machine Learning - Second Edition](https://prod.packtpub.com/in/big-data-and-business-intelligence/python-machine-learning-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787125933)

* [Architects of Intelligence](https://prod.packtpub.com/in/big-data-and-business-intelligence/architects-intelligence?utm_source=github&utm_medium=repository&utm_campaign=9781789954531)
