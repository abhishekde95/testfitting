# testfitting

I am testing how a quadratic model and linear model can be fit when the error is in the radial direction.
I attempt to fit the model in the polar space rather than in the cartesian space. I log transform the error to make the error distribution closer to normal.
Then I use Tukey-Bisquare robust regression to fit the model. I use this method because it is resistant to outliers.
