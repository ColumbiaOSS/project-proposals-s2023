# `pynrm`

## Description
`pynrm` provides a simple yet powerful algorithm for computing a numerator relationship matrix given a pedigree.
While the traditional tabular method to compute the matrix is simple to implement, as the number of animals bred increases, the size of the matrix grows exponentially.
`pynrm` efficiently solves for the matrix values by tracing up the pedigree for only the relevant ancestors, thereby minimizing computational overhead.