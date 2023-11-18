## we already have

- fuzzer for serializer
- fuzzer for parser


## ideas mentioned in discussion

for individual janet functions: property-based testing with shrinking. related: metamorphic testing

fuzzing the compiler with [oracle serialization](https://lock.cmpxchg8b.com/zenbleed.html#discovery)

potential oracle:
- build compiler with different modes and run random scripts. the results from each compiler version should be same
- make individual optimizations tweakable (on/off) at run-time

