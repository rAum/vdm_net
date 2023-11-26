# Code documentation

```{hint}

  To add your code use sphinx tool in project root directory:

    $ sphinx-apidoc -o docs/api/ src/vdm_net

  and add reference from any page which is reachable from the index page.
```

```python
    import vdm_net
```

```{toctree}
---
maxdepth: 4
---
api/modules
```