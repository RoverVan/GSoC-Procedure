#May 30, 2017
RcppExportsFile Auto Update

Optimize procedure in lambda loop

#May 31, 2017
Add RcppArmadillo in 'LinkingTo' Field on DESCRIPTION File

Change Rcpp include to RcppArmadillo

RcppExports Auto Update

#June 1, 2017
	
Change the Matrix Type (Rcpp::NumericMatrix to arma:mat) && Update the matrix method offer by Armadillo

RcppExports Auto Update

#June 2, 2017
Add namespace arma

Remove all 'arma::' (By adding namespace 'arma')

Change temp var(w, z, eta)'s type from array to vector

#June 4, 2017
Use matrix & vector computation instead of for loop

#June 6, 2017
Add Makevars and link to openblas as BLAS_LIBS

#June 7, 2017
RcppExport Auto Update

Add flag_beta_converged_vec to pass beta_k computation if converged

#June 8, 2017
Rewrite Compute Process: Only calculate the updated part in COEFF LOOP

Move 'copy beta' step to the end of lambda loop

#June 10, 2017
Add 'eta_mat' to save the result of each beta_k * X.col(k)

#June 12, 2017
Weekly Meeting

#June 14, 2017
Use CXX_STD = CXX11 instead of -std=c++11 flag

#June 15, 2017
fixing travis ci

#June 25, 2017
fix openblas not found in travis ci

#June 29, 2017
add compute_grad_response_gaussian_none function declaration

temporary add funtion var to fit the new funtion pointer

optimize function for gaussian && add none censoring type optimization

add function pointer to change the function by censoring type

#July 1, 2017
add all gaussian function type in iregnet_fit.cpp (not realize all yet)

#July 2, 2017
Add right censoring gaussian function type

Add right censoring gaussian function to target_compute_grad_response

Add right censoring gaussian function in distributions_gaussian.cpp

#July 4, 2017
Ignore other distributions wiht optimization function

#July 5, 2017
New Optimization Way

#July 9, 2017
Add left censoring gaussian function type

Add left censoring gaussian function to target_compute_grad_response

Add left censoring gaussian function in distributions_gaussian.cpp

#July 10, 2017
Add interval censoring gaussian function type

#July 17, 2017
Sort Matrix X by censoring type

#July 18, 2017
Rewrite distribution.cpp

#July 19, 2017
Add new parameters in compute_grad_response function

Add new parameters && change * to &

Add sort_X_and_y() fucntion && init temp var outside distributions.cpp

Sort matrix X & y outside the loop (support right censoring type)

#July 20, 2017
Change parameter's & to const & in function compute_grad_response()

#July 21, 2017
Sort matrix X & y outside the loop (support left censoring type)

#July 23, 2017
Simplify some function in distribution.cpp

#July 24, 2017
Sort matrix X & y outside the loop (support interval censoring type)

Add interval censoring gaussian function in distributions_gaussian.cpp

#July 26, 2017
Writing Benchmark

#July 28, 2017
Writing Benchmark

#July 29, 2017
Writing Benchmark

#July 30, 2017
Writing Benchmark

#July 31, 2017
Writing Benchmark

#August 1, 2017
Fix Benchmark

#August 2, 2017
Fix Benchmark

#August 4, 2017
Logistic distribution

#August 6, 2017
Remove temp var

Add distributions_logistic.cpp

Add declare of distributions_logistic

Add select function for logistic distribution

#August 7, 2017
Add declare of distributions_logistic (Right censoring type)

Support right censoring type of logistic distribution

Add right censoring type function of logistic distribution

Add declare of distributions_logistic (Left censoring type)

Support left censoring type of logistic distribution

Add left censoring type function of logistic distribution

#August 24, 2017
Writing Benchmark

#August 26, 2017
Fix bug on travis

#August 27, 2017
Fix bug on travis (Update c++ compiler version)