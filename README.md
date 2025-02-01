# gluing_data

Contains results of computations performed with the code in https://github.com/ndwrobotics/gluing_utilities. All results are stored as python/SageMath objects in [pickle](https://docs.python.org/3/library/pickle.html) files.

## output_3

Contains a file for each genus 2 curve identified as potentially gluable along 3-torsion with a list of potentially gluable elliptic curves. Note that for some genus 2 curves, the aforementioned list may be empty.

## output

Similar to output_3, but for $\ell$-torsion for prime $\ell > 3$.

## gluings

Contains Dixmier-Ohno or Shioda invariants of gluings along 3-, 5-, and 7-torsion. Also contains explicit equations for some 3-gluings.

## errors

Contains error information about failed gluings attempts. Note that if a pair of curves appears in this directory, it may still also have a successful gluing in the gluings directory from a later computation.