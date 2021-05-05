# Eigen values of k-Toeplitz tridagonal matrices
  This code provides a method to compute the eigen values of k-toeplitz matrix with less computational effort and more accuracy.Diagonal,upper diagonal and lower diagonal chains are given as input here.
  Our aim is to find eigen values of tridiagonal k-Toeplitz matrices .First, we reduce the
characteristic equations of such matrices of increasing dimensions into a three-term polynomial
recurrence relation with a k th order coefficient polynomial. We establish existence of a limiting
spectrum, nature of its convergence, and a continuous support along with at most 2k distinct
points containing the limiting spectra. The k curves traced due to recurrence conditions on the
k th order coefficient polynomial converge tightly with the limiting eigenvalue distribution for
dimensions significantly larger than k. The coefficients of this polynomial also establish the
necessary and sufficient conditions for any two tridiagonal k-Toeplitz matrices of same period k,
to have the same limiting spectrum.We need to show the existence and nature of convergence
to a limiting set of roots for polynomials in a three-term recurrence of the form pn+1(z) =
Qk(z)pn(z) + γpn−1(z) as n →∞, where the coefficient Qk(z) is a kth degree polynomial, and z,γ ∈
C. We extend these results to relations for numerically approximating roots of such polynomials
for any given n. General solutions for the evaluation are motivated by large computational
efforts and errors in the iterative numerical methods. Later, we apply this solution to the
eigenvalue problems represented by tridiagonal matrices with a periodicity k in its entries,
providing a more accurate numerical method for evaluation of spectra of chains and a
reduction in computational effort from O(n2) to O(n).
