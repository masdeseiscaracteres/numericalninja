To generate the HTML:

```
pelican content
pelican content -s publishconf.py (for deployment)
```

To view it:

```
cd output
python -m pelican.server
```
and visit http://localhost:8000