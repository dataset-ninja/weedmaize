Dataset **WeedMaize** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvOTY5X1dlZWRNYWl6ZS93ZWVkbWFpemUtRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAidm1sUGdtTFJzOUgvTTJzeGlsclR6NG02TTJuWDFjTnlJMW1BcDBnZ1Jybz0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22weedmaize-DatasetNinja.tar%22)

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

- [train_set.zip (3.1 Gb)](https://zenodo.org/record/5106795/files/train_set.zip?download=1)
- [test_set (1.6 Gb)](https://zenodo.org/record/5106795/files/test_set.zip?download=1)
- [validation_set (0.9 Gb)](https://zenodo.org/record/5106795/files/validation_set.zip?download=1)
