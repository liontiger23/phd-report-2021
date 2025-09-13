# PhD report 2021

Source markdown files located at [src](src) directory.
Result is published at [publish](publish) directory.

Source: [src/report.md](src/report.md)  
Result: [publish/report.pdf](publish/report.pdf)

## Building

Following command builds your thesis into `.pdf`:

```
make
```

> Note: also converts [src/title.doc](src/title.doc) to pdf and prepends to the resulting artifact.

## Publishing

To "publish" the final `.pdf` you can use the following command which builds and copies `src/*.pdf` into `publish/*.pdf`
which can then be committed to the repo:

```
make publish
```
