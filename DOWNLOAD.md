Dataset **WeedMaize** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](Set 'HIDE_DATASET=False' to generate download link)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='WeedMaize', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be downloaded here:

- [train](https://zenodo.org/record/5106795/files/train_set.zip?download=1)
- [test](https://zenodo.org/record/5106795/files/test_set.zip?download=1)
- [val](https://zenodo.org/record/5106795/files/validation_set.zip?download=1)
