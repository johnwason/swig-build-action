# swig-build-action

Build, install, and cache swig on Debian based systems. Used to install newer versions of swig when required.

## Usage

```yaml
- uses: johnwason/swig-build-action@v1
  with:
    # Version of swig to build (default 4.0.2)
    version: 4.0.2
    # Additional cache key component (optional)
    cache-key: ''
```
