## 1 - Explore the "hold_out_validation" notebook

```
Q2. What are the cyan and red curves in those plots ? Why are they
different ?
```

- Cyan is the training results
- Red is the test results

```
Q3. What happens with the training and test errors (MSE) when the 2 sets overlap significantly ?
```

The MSE (Mean Square Error) increase drastically

```
Q4. Why does the red curves sometimes indicate a higher error than the
cyan ones ?
```

Depending on the data picked on the train data set and on the test data set

```
Q5. What is the boxplot summarizing the validation errors of the preceding experiments showing ?
```

It's shows a better view on the MSE in function of the spread of the datas.

We can see that with the smallest spread (0.4) the median is the best but can have more error then 0.5.

## 2 -  Explore the “cross_validation” notebook

```
Q2. What is the difference between hold-out and cross-validation ? What is
the new parameter that has to be defined for cross-validation ?
```

- `K = 5` dataset is split in K parts. k-1 parts are used during training and the remaining part is used for testing the generalization capabilities of the mode

```
Q3. Observe the boxplots summarizing the validation errors obtained using
the cross-validation method and compare them with those obtained by hold-out validation.
```

This method has the advantage of giving more consistent results than hold-out validation.

