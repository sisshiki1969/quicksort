### quicksort

~~~sh
❯ benchmark-driver quick_sort.yaml --rbenv '3.2.0-dev; 3.2.0-dev --yjit' --repeat-count 5
Calculating -------------------------------------
                      3.2.0-dev   3.2.0-dev --yjit 
               qsort   344.208k           811.061k i/s -     30.000k times in 0.087157s 0.036989s

Comparison:
                            qsort
    3.2.0-dev --yjit:    811060.7 i/s 
           3.2.0-dev:    344208.0 i/s - 2.36x  slower
~~~
