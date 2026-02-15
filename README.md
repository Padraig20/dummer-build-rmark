# Finding good priors for building DUMMER profiles (RNA)

Benchmarking different RNA priors for dummer-build via RMARK.

I do not own the RMARK benchmark. Please refer to the original publication introducing Infernal: *Infernal 1.1: 100-fold faster RNA homology searches*

Interesting things to note (mostly for myself):

- RMARK gives us HMMER profiles. We can directly check how well DUMEMR works with those.
- We should probably keep separate test families?
- How exactly do we define a true positive? Exact match? Partial match?

<img width="748" height="359" alt="image" src="https://github.com/user-attachments/assets/5e5ce56b-f16a-49ae-870d-f42a3e2321a8" />
