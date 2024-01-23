# Functionality

## Reference

- https://en.wikipedia.org/wiki/Lambda_calculus
- https://en.wikipedia.org/wiki/De_Bruijn_index
- https://en.wikipedia.org/wiki/Simply_typed_lambda_calculus

## Rules

- [] variable
- [] lambda abstraction (λx.M)
    - [] bound variables between λ and the punctum/dot
    - [] return body M
- [] application (M N), applying function M to an argument N where M and N are lambda terms

## Reduction operations

- [] αlpha-conversion, renaming the bound variables in the expression to avoid name collisions. (\lambda x.M[x]) -> (\lambda y.M[y])
- [] beta-reduction, replacing bound variables with with arguments in the body  ((\lambda x.M) N) -> (M[x:=N])


## Additional features

- [] De Brujin index
- [] Typing
