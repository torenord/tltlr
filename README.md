# Find gcd duration

## State space search for gcd duration

**Warning: State space must be finite.**

```
(find gcd of tick durations from <initState> .)
```

## Model check using user specified tick duration

**Warning: In continuous semantics, `phi` must not contain action predicates.**

### Pointwise

```
(mc-tltlr <initState> |=p <phi> using tick duration <tickDuration> .)
```

### Continuous

```
(mc-tltlr <initState> |=c <phi> using tick duration <tickDuration> .)
```
