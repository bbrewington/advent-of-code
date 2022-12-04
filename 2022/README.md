# Advent of Code 2022

https://adventofcode.com/2022

I'm going to try to knock out these problems with 3 different "languages": dbt, Python, and R (each with their respective folder in 2022/src)

Will be capturing the actual problem descriptions & text files in the 2022/docs folder - that way they're importable into the different code paths

Assumption of the src/ folder is that earlier days' solutions can be extended in later days...will see how this plays out :)

---

## Python

### How to run solutions

```text
python 2022/src/aoc2022_python/solutions.py
```

This will print output like:

```text
Day 1 test(s) passed! Answer: 68802
Day 2 test(s) failed, need to fix
```

### Learnings & References

#### Packaging & Modules

It's a bit overkill since could just script out the solutions, but looking to get better at this stuff!

- inital package structure setup: https://iq-inc.com/importerror-attempted-relative-import/
  - This tutorial proved pretty helpful for getting [src/aoc2022_python](src/aoc2022_python) set up as a Python package (that always takes forever, and I usually start by trying to relative import then end up going this route at the end)

#### Object-Oriented Programming

More to come on this!

#### Iteration

Somewhat experienced w/ this, but adding this section to give credit to references I used

- day_01: Locate indices of a given element in a list (in this example, the '\n' values) - https://stackoverflow.com/a/9542768/4718936