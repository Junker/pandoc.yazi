# pandoc.yazi

Plugin for [Yazi](https://github.com/sxyazi/yazi) to preview files with [pandoc](https://pandoc.org/). 

## Instalation

```bash
ya pack -a Junker/pandoc
```

## Usage:

```toml
[plugin]
prepend_previewers = [
    { mime = "application/{openxmlformats-officedocument.wordprocessingml.document}", run = "pandoc" },
]
```

Make sure you have [pandoc](https://pandoc.org/) installed, and can be found in `PATH`.
