Recently, I started studying Apache Spark and decided to apply some of its tools to the database that I used in my final paper of the MBA in Data Science, in which I developed two default prediction models from a customer base of a financial institution.

In summary, the goal of this study was to solve a classification problem whose output variable was presented in binary format, assuming a value of 0 for non default customers and 1 for default customers. Using this customer database, I used the Python scikit-learn library to develop one model using logistic regression and another model using random forest.

So, what I did was basically use the SQL and MLlib tools from Spark to create two classification models, using the same algorithms used in the final paper. Since I already have some knowledge of this database, and since the goal was to practice using Spark's machine learning tools, I decided not to delve into exploratory data analysis, feature engineering, data balancing, etc.
