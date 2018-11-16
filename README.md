# Get Python Requirements

get python requirements from a python script without installing python and pip

## Howto

run the container with your script(s) mounted in the `/requirements` folder

```txt
docker run --rm -v "/path/to/folder:/requirements" python-requirements
docker run --rm -v "/path/to/file.py:/requirements/file.py" python-requirements
```