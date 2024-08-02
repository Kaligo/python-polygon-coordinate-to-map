# Python Polygon Coordinate To Map
I am using python to visualize how a polygon (not yet with multipolygon) can be visualized within this map.

## Create Virtual Environment

```bash
python -m venv env-name
```

## Activate

```bash
source env-name/bin/activateA
```

## Install shit (To env only)

```bash
pip install numpy
```

## Deactivate Env

Do this after u finish coding session or sth, or wanna fk of frm env
```bash
deactivate
```

## Install Packages
Make sure your env has all the lib inside `requirements.txt`. Usually just run this when you activate your environment already.
```bash
pip install
```

## How to use the repo (once everything is installed and env activated)?
Inside `./script.py`, change this line to your prefered polygon coordinates.
```python
...
border = "SRID=4326;POLYGON((101.3260618 0.5985796,101.3277795 0.5965827,...))"

...
```

Run this to execute
```bash
python script.py
```

You will see changes inside `./polygon_map.html`, then you can open it in your browser to see the map with the highlighted area.