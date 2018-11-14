# Faster-than-CSV

[![screenshot](https://source.unsplash.com/eH_ftJYhaTY/800x402)](https://youtu.be/QiKwnlyhKrk?t=5)

| Library                       | Speed    |
|-------------------------------|----------|
| Pandas `read_csv()`           | `20.09`  |
| NumPy `fromfile()`            | `3.88`   |
| NumPy `genfromtxt()`          |  `4.00`  |
| NumPy `loadtxt()`             |  `1.26`  |
| csv (std lib)                 |  `0.40`  |
| csv (list)                    |  `0.38`  |
| csv (map)                     |  `0.37`  |
| Faster_than_csv               |  `0.10`  |

<details>

- Benchmarks run on Docker from Dockerfile on this repo.
- Speed is IRL time to complete 10000 CSV Parsings.
- Stats as of year 2018.

</details>


# Use

```python
import faster_than_csv as csv
print(csv.csv2list("sample.csv"))  # See Docs for more info.
```


# FAQ

- Whats the idea, inspiration, reason, etc ?.

[Feel free to Fork, Clone, Download, Improve, Reimplement, Play with this Open Source. Make it 10 times faster, 10 times smaller.](http://tonsky.me/blog/disenchantment)

- This requires Cython ?.

No.

- This runs on PyPy ?.

No.

- This runs on Python2 ?.

I dunno. (Not supported)

- Developer Documentation ?.

[Yes.](https://github.com/juancarlospaco/faster-than-csv/raw/master/faster_than_csv_DOCS.zip)
(Zip because GitHub marks the Repo as being JavaScript)

- How can I Install it ?.

https://github.com/juancarlospaco/faster-than-csv/releases

If you dont understand how to install it, you can just download, extract, put the files on the same folder as your `*.py` file and you are good to go.

- How can be faster than NumPy ?.

I dunno.

- How can be faster than Pandas ?.

I dunno.
