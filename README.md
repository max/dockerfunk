# Docker Funk

It's annoying to install development tools locally. This runs common development tools in Docker containers.

## Installation

Installation is simple. Simply clone this repository and add it to your `$PATH`:

```bash
DOCKERFUNK=path/to/dockerfunk

if [ -d "$DOCKERFUNK" ] ; then
  PATH="$PATH:$DOCKERFUNK"
fi
```
