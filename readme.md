## Building

The document can be compiled using either `latexmk` (with a standard
LaTeX distribution such as **TeX Live** and **MiKTeX**) or **Tectonic**.

### TeX Live / MiKTeX
Compile the document with:

```bash
latexmk -pdf main.tex
```

To remove auxiliary files generated during compilation:

```bash
latexmk -c
```

### Tectonic
Compile the document with:

```bash
tectonic -o build main.tex
```

### Compiled Document
In both cases, the compiled PDF document will be generated in the `build/` subfolder of the source file:

```bash
build/main.pdf
```

---

This work is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a> 
<a href="https://creativecommons.org/licenses/by/4.0/">
  <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" height="14" alt="CC">
  <img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" height="14" alt="BY">
</a>