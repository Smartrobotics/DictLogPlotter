# DictLogPlotter
This is a plotter for simple structure such as dictionary (key & value). 

Now developing...

## todo

- [ ] add flags range_x & range_y
- [ ] add flag use_same_window

## usage
- case1 (specify key against value & scale auto range)
```
$ python3 test_plot.py --extract_keys key1 --file_name ./data/hoge.txt
```

~~- case2 (specify key & xy range)~~
```
$ python3 test_plot.py --extract_keys key2 --range_x 20:100 --range_y 0:100~~
```

- case3 (specify keys)
```
$ python3 test_plot.py --extract_keys key1 key2 --file_name ./data/hoge.txt
```

~~- case4 (specify keys, plot all graphs in same window)~~
```
$ python3 test_plot.py --extract_keys key1 key2 --use_same_window True
```

## format of log-file 

```
key11:value11, key21:value21, key31:value31, ...
key12:value12, key22:value22, key32:value32, ...
key13:value13, key23:value23, key33:value33, ...
```

## output
Show graph using value against specified key.

![Alt text](/images/sample.png)

