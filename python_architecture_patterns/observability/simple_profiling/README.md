# Profiling tools

## 1. cProfile

- C extension of CPython
- instruction: `python -m cProfile [-o output_file] [-s sort_order] (-m module | myscript.py)`

## 2. line_profiler (used with @profile annotation)

- install by `pip install line_profiler`
- run by `kernprof -l -v test.py`

