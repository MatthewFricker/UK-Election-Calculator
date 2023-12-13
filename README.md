# UK-Election-Calculator

This project aims to predict the results of the next UK general election using current polls and the previous constituency results. The model works with the [Strong Transition Model](https://www.electoralcalculus.co.uk/blogs/strongmodel.html) from the website Electoral Calculus.

If you intend to use this code on your own device, you may need to replace this section:

```
os.environ["CONDA_PREFIX"] = "C:/Users/matth/miniconda3/envs/geo_env"
os.environ['GDAL_DATA'] = os.environ['CONDA_PREFIX'] + "/Library/share/gdal"
os.environ['PROJ_LIB'] = os.environ['CONDA_PREFIX'] + '/Library/share'
```
with the location of GDAL files on your own device.
