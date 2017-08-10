# Any size

### If (face[x] || face[y])

    ?x!y{...}

Found by: @TehPers  
Significance: There's no builtin way to do `if (x || y)`
Example: `?6!7{%0}` -> if notepad or input buffer is truthy, print the 0th face sum
