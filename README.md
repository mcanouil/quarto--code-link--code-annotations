# `code-link` Limitations

## [](./link-true--annot.qmd)

```yaml
code-link: true
```

- Annotation in code block => Bad (_known limitation_)
- Computational code block with comment annotation (_i.e._, `# <1>`) but no actual annotation => Bad, a the code block is removed/hidden.

## [](./link-true--annot-false.qmd)

```yaml
code-link: true
code-annotations: false
```

- All Good

## [](./link-true--annot-hover.qmd)

```yaml
code-link: true
code-annotations: hover
```

- Annotation in code block => Bad (_known limitation_)
- Computational code block with comment annotation (_i.e._, `# <1>`) but no actual annotation => Bad, a the code block is removed/hidden.

## [](./link-true--annot-none.qmd)

```yaml
code-link: true
code-annotations: none
```

- Computational code block with comment annotation (_i.e._, `# <1>`) but no actual annotation => Bad, a the code block is removed/hidden.

## [](./link-true--annot-select.qmd)

```yaml
code-link: true
code-annotations: select
```

- Annotation in code block => Bad (_known limitation_)
- Computational code block with comment annotation (_i.e._, `# <1>`) but no actual annotation => Bad, a the code block is removed/hidden.