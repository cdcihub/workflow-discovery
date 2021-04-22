# Workflow Publishing and Discovery with KG: Old-School Astronomer Guide

## Purpose of this note

We want to demostrate on contrete and scientifically-useful working examples how an astronomer, who might indeed have relatively little interest to look in the code, can leverage ODA Knowledge Base together with other valuable resources (especially Renku) to collaborate on workflows and build web-based data analysis, ready for consumption by our robots:

## Developing the workflow

### Ontology


### Workflow inputs

For our purposes, the most important relation

```python
name_input = "Mrk 421" # name of the object; if empty coordinates are used http://odahub.io/ontology/sources/mrk421
radius_input = 3.0 # arcmin
```

They can be see for example with 
```bash
$ nbinspect final.ipynb
"name_input": {
        "comment": " name of the object; if empty coordinates are used",
        "default_value": "Mrk 421",
        "name": "name_input",
        "owl_type": "http://www.w3.org/2001/XMLSchema#str",
        "python_type": "<class 'str'>",
        "value": "Mrk 421"
    },
...
"radius_input": {
        "comment": " arcmin",
        "default_value": 3.0,
        "name": "radius_input",
        "owl_type": "http://www.w3.org/2001/XMLSchema#float",
        "python_type": "<class 'float'>",
        "value": 3.0
    }
```
Will IVOA vocabulaires, and references therein https://www.ivoa.net/rdf/index.html. One should pay particular attention the developments used in variety of tables managed by CDS-Strasbourg, where much of the needed terms for astrophysical entities can be found (one can start [here](https://www.ivoa.net/documents/UCD1+/)).
It is true that

Should 

### Other Domain-specific knowledge




## From Workflow to Web-Based Data Analysis

We want to 

## Reasoning engines

## 

workflow
