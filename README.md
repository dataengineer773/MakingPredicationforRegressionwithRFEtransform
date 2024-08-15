RFE For Regression, at first frommake_regression() function we use to create  a syntethic regression problem with 1,000 examples and 10 input features, five of wich are important and five of which are redundant
at the second steps  fromscikit-learn libraray make the MAE negative so that it is maximized instead of minimized, this means that negative MAE values closer to zero are better and a perefct model has a MAE of 0
at the third the Pipeline is fit on all available data,then th epredict() function can be called to make prediction on new data
