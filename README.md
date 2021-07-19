# dask-collections-webinar

Notebooks used in the Dask Collections webinar.

The recommended environment to run the notebooks can be created with
`conda`:

```
conda create -n dask-webinar python=3.9 dask distributed dask-labextension zarr
```

Just run `jupyter lab` to start up a server to run the notebooks.

The array notebook can be run without any data; the bag and dataframe
notebook is run with individual campaign contribution data which was
grabbed from the [US FEC
website](https://www.fec.gov/data/browse-data/?tab=bulk-data).
