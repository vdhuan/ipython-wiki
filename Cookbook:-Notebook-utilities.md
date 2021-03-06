Notebook utilities
==================

Here are some useful utilities which currently exist as gists, but which could benefit from being wrapped up and folded into IPython commandline tools, such as *nbconvert*.

https://gist.github.com/timo/2621679 - For each ipynb file, a kernel is started, all cells are executed in order and exceptions occuring in the cells will show up as failed tests.

https://gist.github.com/minrk/2620876 - simple example script for running notebooks and reporting exceptions. 

https://gist.github.com/minrk/2620735 - simple example script for running and testing notebooks. Each cell is submitted to the kernel, and the outputs are compared with those stored in the notebook.

https://gist.github.com/minrk/3719849 - remove all outputs from a notebook

https://gist.github.com/minrk/3836889 - *selectively* replacing code cells based on their contents. Example: cells which start off with "# Solution" get replaced with "# Solution goes here"

https://gist.github.com/minrk/3869182 - Example configuration file for using the IPython Notebook with a random password

https://gist.github.com/minrk/1935808 - Downgrade v3 .ipynb files to v2 (for use with older versions of IPython)

https://gist.github.com/fperez/e2bbc0a208e82e450f69 - Concatenate multiple notebooks into a new one.

https://github.com/davidbrai/ipythonnb-s3 - Seamlessly save and load notebook files to and from AWS S3 buckets.