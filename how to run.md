# How to run

This is a static website. GitHub Pages serves `index.html` at [jul.org.au](https://jul.org.au/).

## Preview locally

```bash
./start.sh
```

Then open http://127.0.0.1:8765/

### Flags

| Flag | Meaning | Default |
| --- | --- | --- |
| `-p`, `--port PORT` | Listen port | `8765` |
| `-H`, `--host HOST` | Bind address | `127.0.0.1` |
| `-h`, `--help` | Show help | |

```bash
./start.sh --port 9000
./start.sh --host 0.0.0.0 --port 8765
```

Copy `.env.example` to `.env` if you want to set `PORT` or `HOST` without flags.

## Publish

Push to `main`. The `CNAME` file keeps the site on jul.org.au.
