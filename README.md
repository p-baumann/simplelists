# Simplelists

Use HTML-like commands to create `itemize` and `enumerate` lists in LaTeX.

Open `itemize` list environments with `\ul` and close them with `\Ul`:
```latex
\ul 
\li First item
\li Second item
\Ul
```

There are also combined commands `\uli` and `\Uli` to open/close a list and display the first/last item:
```latex
\uli First item
\li Second item
\Uli Third item

```
The empty line at the end is required.

For an `enumerate`list, use `\ol` etc.:
```latex
\oli First item
\Oli Second item

```
The above example would look like this:
1. First item
2. Second item

For more examples, have a look at [simplelists-example.tex](simplelists-example.tex) and the resulting [pdf](simplelists-example.pdf). 

## Usage
Copy [simplelists.sty](simplelists.sty) into the folder of your LaTeX document and add
```latex
\usepackage{simplelists)
```

## (In)Compatibilities with other packages
It seems to work with the **enumitem** package: optional arguments to `\ul` are passed to **enumitem**.

## Issues
Probably many. Use at your own risk! I take no responsibility if it eats your dissertation (it probably won't though).


