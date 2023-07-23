# `code-link` Limitations

## [`link--annot.qmd`](./link--annot.qmd)

```yaml
# implicit/default 
```

- Computational code block with comment annotation (_i.e._, `# <1>`) but no actual annotation => Bad, the code block is removed (source and output).

## [`link-true--annot.qmd`](./link-true--annot.qmd)

```yaml
code-link: true
```

- Annotation in code block => Bad (_known limitation_).
- Code linking => Good.
- Computational code block with comment annotation (_i.e._, `# <1>`) but no actual annotation => Bad, the code block is removed (source and output).

## [`link-true--annot-false.qmd`](./link-true--annot-false.qmd)

```yaml
code-link: true
code-annotations: false
```

- All Good

## [`link-true--annot-none.qmd`](./link-true--annot-none.qmd)

```yaml
code-link: true
code-annotations: none
```

- Code linking => Good.
- Computational code block with comment annotation (_i.e._, `# <1>`) but no actual annotation => Bad, the code block is completely removed (source and output).

## [`link-true--annot-hover.qmd`](./link-true--annot-hover.qmd)

```yaml
code-link: true
code-annotations: hover
```

- Annotation in code block => Bad (_known limitation_).
- Code linking => Good.
- Computational code block with comment annotation (_i.e._, `# <1>`) but no actual annotation => Bad, the code block is removed (source and output).

## [`link-true--annot-select.qmd`](./link-true--annot-select.qmd)

```yaml
code-link: true
code-annotations: select
```

- Annotation in code block => Bad (_known limitation_).
- Code linking => Good.
- Computational code block with comment annotation (_i.e._, `# <1>`) but no actual annotation => Bad, the code block is removed (source and output).
