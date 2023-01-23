# Adapting-Specifications-for-Reactive-Controllers
Specifications used in the evaluation of the paper 'Adapting Specifications for Reactive Controllers'

ideal_specifications - contains the original, ideal specifications, representing the true environment assumptions.

mutated_specificaitons - contains the mutated specifications, created by performing strengthening patterns on the ideal specifications.

violation_files - contains the violating traces generated for each mutated specification. For each specification there are up to 10 unique violating traces.

fixed_specifications - contains the fixed specifications that resulted from applying our algorithm to the mutated specifications and their corresponding violating traces, one at a time.


File names that contain 'patterned' have had expressions of the form G(a -> F(b)) replaced with pRespondsToS(a,b), a Spectra pattern.
