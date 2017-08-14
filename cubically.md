# Any size

### If (face[x] || face[y])

    ?x!y{...}

Found by: @TehPers  
Significance: There's no builtin way to do `if (x || y)`  
Example: `?6!7{%0}` -> if notepad or input buffer is truthy, print the 0th face sum

### Decrement notepad by 1

    *1-1/1

Found by: Kamil Drakari  
Significance: Decrements the notepad by 1 as long as the left face is nonzero

### Increment notepad by 1

    *1-1/1

Found by: MD XF (kind of)  
Significance: Increments the notepad by 1 as long as the left face is nonzero
