# Operations

Below is the list of currently implemented operations for point
processes and patterns.

## Superposition

The union or (superposition) of two point processes creates a
union process:

```@docs
union(::PointProcess, ::PointProcess)
```

## Thinning

The `thin` function implements the thinning operation for
point processes and patterns. Below are the available thinning
methods.

```@docs
thin
RandomThinning
```
