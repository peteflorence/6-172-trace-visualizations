## Visualizing memory traces for MIT 6.172's Project 3: Serial Dynamic Memory Allocation

This is a simple iPython notebook to help visualize the structure of a memory trace.

### Quickstart

Just run `jupyter notebook` (or `ipython notebook`) and "run all" cells in `trace_visualizations.ipynb`.

### Features

Does simple things that are surprisingly useful:

- Counts number of instances for each allocation size
- Plots these numbers of instances for each allocation size
- Plots the amount of memory used by each allocation size (#instances X allocation
amount)
- Calculates header overhead (internal fragmentation)
- Prints allocation amounts in the order in which they were freed, rather than in the
provided trace as the allocation’s pointer, which is harder to understand
- Computes what percentage of memory is for small (slabbed) vs large allocations
- Plots cdf of memory allocations by size
- Plots the ordering of allocating and freeing the large memory blocks

### Contributing

Will happily accept pull requests if you have improvements!
