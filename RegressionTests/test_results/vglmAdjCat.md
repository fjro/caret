Adjacent Categories Probability Model for Ordinal Data (`vglmAdjCat`)
===== 

There are regression tests to compare model results between different versions of `caret` and the individual packages. These test evaluate whether consistent results can be obtained. The code used to generate the objects that are compared can be found [here](https://github.com/topepo/caret/blob/master/RegressionTests/Code/vglmAdjCat.R).
A [history of commits](https://github.com/topepo/caret/commits/master/models/files/vglmAdjCat.R) for the model code is also available

Testing Information:
---------

Old:

 * x86_64-apple-darwin13.4.0 (64-bit)
 * R Under development (unstable) (2016-10-26 r71594)
 * `caret` (6.0-71), `VGAM` (1.0-2)
 * tested on 2016-10-31 at 06:49


New:

 * x86_64-apple-darwin13.4.0 (64-bit)
 * R Under development (unstable) (2016-10-26 r71594)
 * `caret` (6.0-72), `VGAM` (1.0-2)
 * tested on 2016-10-31 at 00:16


Results:
---------

**Test Case**: `class_cv_form`

Object class(es): `train` and `train.formula`

Model Configuration:

 * Formula method
 * Resampling: Cross-Validated (3 fold)
 * Grid search
 * Pre-processing: centered (15), scaled (15)  
 * 1 tuning parameter combination was evaluated


Execution times: (old) 1.05s (new) 1.27s

Test Results:

 * _Equal results for Accuracy_
 * _Equal results for Kappa_

**Test Case**: `class_cv_model`

Object class(es): `train`

Model Configuration:

 * Non-formula method
 * Resampling: Cross-Validated (3 fold)
 * Grid search
 * Pre-processing: centered (15), scaled (15)  
 * 1 tuning parameter combination was evaluated


Execution times: (old) 1.93s (new) 2.17s

Test Results:

 * _Equal results for Accuracy_
 * _Equal results for Kappa_

**Test Case**: `class_cv_weight`

Object class(es): `train`

Model Configuration:

 * Non-formula method
 * Resampling: Cross-Validated (3 fold)
 * Grid search
 * Pre-processing: centered (15), scaled (15)  
 * 1 tuning parameter combination was evaluated


Execution times: (old) 1.09s (new) 1.17s

Test Results:

 * _Equal results for Accuracy_
 * _Equal results for Kappa_

**Test Case**: `class_imp`

Object class(es): `varImp.train`

 * _Equal results_

**Test Case**: `class_loo_model`

Object class(es): `train`

Model Configuration:

 * Non-formula method
 * Resampling: Leave-One-Out Cross-Validation
 * Grid search
 * Pre-processing: centered (15), scaled (15)  
 * 1 tuning parameter combination was evaluated


Execution times: (old) 10.89s (new) 10.9s

Test Results:

 * _Equal results for Accuracy_
 * _Equal results for Kappa_

**Test Case**: `class_loo_weight`

Object class(es): `train`

Model Configuration:

 * Non-formula method
 * Resampling: Leave-One-Out Cross-Validation
 * Grid search
 * Pre-processing: centered (15), scaled (15)  
 * 1 tuning parameter combination was evaluated


Execution times: (old) 9.08s (new) 9.49s

Test Results:

 * _Equal results for Accuracy_
 * _Equal results for Kappa_

**Test Case**: `class_none_model`

Object class(es): `train`

Model Configuration:

 * Non-formula method
 * Resampling: None
 * Grid search
 * Pre-processing: centered (15), scaled (15)  
 * 0 tuning parameter combinations were evaluated


Execution times: (old) 0.58s (new) 0.63s

Test Results:

 * _Equal results for Accuracy_
 * _Equal results for Kappa_

**Test Case**: `class_none_pred`

Object class(es): `ordered` and `factor`

 * _Equal results_

**Test Case**: `class_none_prob`

Object class(es): `data.frame`

 * _Equal results_

**Test Case**: `class_pred`

Object class(es): `ordered` and `factor`

 * _Equal results_

**Test Case**: `class_pred_form`

Object class(es): `ordered` and `factor`

 * _Equal results_

**Test Case**: `class_predictors1`

Object class(es): `character`

 * _Equal results_

**Test Case**: `class_prob`

Object class(es): `data.frame`

 * _Equal results_

**Test Case**: `class_prob_form`

Object class(es): `data.frame`

 * _Equal results_

**Test Case**: `levels`

Object class(es): `character`

 * _Equal results_

