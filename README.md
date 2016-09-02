# STReam Annotate

`stra.py arg [...]` annotates the output of running `arg...` with the name of the corresponding stream.

It works under either python 2 or 3.

#Example

    ./stra.py ls -l
    [OUT] total 64
    [OUT] -rw-r--r--@ 1 tcf  staff  1487 Sep  2 21:32 LICENSE
    [OUT] -rw-r--r--  1 tcf  staff   177 Sep  2 21:34 README.md
    [OUT] -rwxr-xr-x  1 tcf  staff  1731 Sep  2 21:23 stra.py

