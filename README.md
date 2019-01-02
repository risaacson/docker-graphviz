Docker-Graphviz
---------------

Just a simple container so you can render graphs but not install locally.

Example:
```bash
docker run -it --rm -v $(pwd):/data risaacson/graphviz:latest dot -Tsvg /data/file.dot -o /data/file.svg
```
