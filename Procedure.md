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