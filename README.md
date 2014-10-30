Fast primality check in Python, using the Miller-Rabin test.

Entries inferior or equal to 20000 use a hardcoded table, created with a simple Erathostenes' sieve.

Exact results for entries inferior to 3825123056546413051 are provided, thanks to the witnesses number charts provided by Pomerance, Selfridge, Wagstaff and Jaeschke.
See for more details/proofs : https://math.dartmouth.edu/~carlp/PDF/paper25.pdf

For numbers superior or equal to 3825123056546413051, we use a 6-fold verification of the Miller-Rabin test. This may result in a false positive, but it is extremely unlikely.
