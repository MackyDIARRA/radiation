## Local Setup


To test the application locally:

```bash
conda env create
conda activate dashboard

Radiation.ipynb
```

This will open a new browser tab at [http://localhost:8891/lab/tree/radiation/Radiation.ipynb] serving the dashboard

## Testing on Binder


An environment file is all you need to make the dashboard work with Binder:

1. Go to [mybinder.org](https://mybinder.org)
2. Put the URL of the repository
3. Then select `Url` instead of `File`
4. Put the following URL in the `URL to open (optional)` field: `/voila/render/app.ipynb`

The repository is now ready to be used on [Binder](https://mybinder.org)!

More details about Binder can be found [in the documentation](https://mybinder.readthedocs.io/en/latest/introduction.html#preparing-a-repository-for-binder).

