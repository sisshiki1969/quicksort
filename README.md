### quicksort

Calculating -------------------------------------
                      3.2.0-dev   3.2.0-dev --yjit   3.2.0-dev --mjit 
          quick_sort   123.457k             2.952k           116.279k i/s -       1.000 times in 0.000008s 0.000339s 0.000009s

Comparison:
                       quick_sort
           3.2.0-dev:    123456.8 i/s 
    3.2.0-dev --mjit:    116279.1 i/s - 1.06x  slower
    3.2.0-dev --yjit:      2951.6 i/s - 41.83x  slower
