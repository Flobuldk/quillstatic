# quillstatic

Static blog generator: markdown in, tidy HTML out

Side project, maintained when I have time.

## Getting started

```bash
pip install -r requirements.txt
```

## How to use

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Highlights

- RSS feed generation
- Index page with post list by date
- Single template, plain str.format, no Jinja
- Markdown posts with fenced code and tables

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas

## License

MIT licensed, see LICENSE.
