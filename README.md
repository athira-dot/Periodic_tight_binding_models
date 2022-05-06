
<h2> Eigen values of k-Toeplitz tridagonal matrices</h2>


<p align="justify">

This code provides a method to compute the eigen values of k-toeplitz matrix with less computational effort and more accuracy.Eigen values of the k-toeplitz matrix is approximated using the chebyshev polynomial of second kind.Diagonal,upper diagonal and lower diagonal chains of the k-toeplitz matrix are given as the inputs in the code.
First, we reduce the characteristic equations of such matrices of increasing dimensions into a three-term polynomial recurrence relation with a k th order coefficient polynomial. We establish existence of a limiting spectrum, nature of its convergence, and a continuous support along with at most 2k distinct points containing the limiting spectra. The k curves traced due to recurrence conditions on the k th order coefficient polynomial converge tightly with the limiting eigenvalue distribution for dimensions significantly larger than k. The coefficients of this polynomial also establish the necessary and sufficient conditions for any two tridiagonal k-Toeplitz matrices of same period k,to have the same limiting spectrum.We need to show the existence and nature of convergence to a limiting set of roots for polynomials in a three-term recurrence of the form pn+1(z) = Qk(z)pn(z) + γpn−1(z) as n →∞, where the coefficient Qk(z) is a kth degree polynomial, and z,γ ∈C. We extend these results to relations for numerically approximating roots of such polynomialsfor any given n. General solutions for the evaluation are motivated by large computational efforts and errors in the iterative numerical methods. Later, we apply this solution to the eigenvalue problems represented by tridiagonal matrices with a periodicity k in its entries, providing a more accurate numerical method for evaluation of spectra of chains and a
reduction in computational effort from O(n^2) to O(n).
Here diag_entries.txt,upper_diag.txt,lower_diag.txt are the 1 D arrays which should be given as input.
</p>


<h2>Periodic tight binding models</h2>

<p align="justify">
  Periodic tight binding hamiltonian with free-free boundary conditions are k-toeplitz matrices.Energy eigen values of such periodic tight binding models can be found out with more accurately and less computational effort by chebyshev polynomial approximation.Here,We are able to provide the energy eigen spectrum for periodic tight binding model with free-free boundary condition.
</p>



Figure of One dimensional free-free lattice(Di-atomic lattice)

![chain_free_free](https://user-images.githubusercontent.com/75409178/167105574-7e83bdf3-33fc-4382-95c3-d1da323b2ac4.png)

Figure of Two dimensional free-free lattice(both the chains are Di-atomic)

![free_free_lattice](https://user-images.githubusercontent.com/75409178/167107020-85028363-3298-4976-90c7-6b1ed13a58c2.png)





Base paper: [Base_paper.pdf](https://github.com/athira-dot/Periodic_tight_binding_models/files/8638889/Base_paper.pdf)
