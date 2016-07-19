# taskname

Task description.

taskname can be run with Python using [gbdxtools](https://github.com/DigitalGlobe/gbdxtools) or through the [GBDX Web Application](https://gbdx.geobigdata.io/materials/).  

### Table of Contents
 * [Quickstart](#quickstart) - Get started!
 * [Inputs](#inputs) - Required and optional task inputs.
 * [Outputs](#outputs) - Task outputs and output structure.
 * [Advanced](#advanced) - Additional information for advanced users.
 * [Issues](#issues) - Current or past known issues.
 * [Background](#background) - Background information.
 * [Contact](#contact) - Contact information.

### Quickstart

Quick start example.

```python
# Quickstart example for taskname.  

from gbdxtools import Interface
gbdx = Interface()
raster = 's3://gbd-customer-data/PathToImage/image.tif'
taskname = gbdx.Task('taskname', raster=raster)

workflow = gbdx.Workflow([taskname])  
workflow.savedata(taskname.outputs.data, location='taskname')
workflow.execute()

print workflow.id
print workflow.status
```

### Inputs

The following table lists all taskname inputs.
Mandatory (optional) settings are listed as Required = True (Required = False).


Name            |   Required       |   Default      |  Valid Values  |   Description
----------------|:----------------:|----------------|----------------|----------------                       

### Outputs

The following table lists all (task name) outputs.

Name            |   Required       |   Default      |  Valid Values  |   Description
----------------|:----------------:|----------------|----------------|----------------                       


**Output structure**

Explain output structure via example.


### Advanced
Include example(s) with complicated parameter settings and/or example(s) where
taskname is used as part of a workflow involving other GBDX tasks.


### Issues
List known past/current issues with taskname (e.g., version x does not ingest vrt files).


### Background
For background on the development and implementation of taskname see [here](Insert link here).


### Contact
List contact information for technical support.