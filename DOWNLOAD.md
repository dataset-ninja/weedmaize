Dataset **WeedMaize** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/d/p/1I/IQOFyxvkuNbooLgZDdQQ89A9cZno8CuGgavToACwoiHOqhfaxa7S4f1LWjrDTfAdGXcQ3M90mpG2xpHZoeViHht1G4rLaBZMPtJq27eEhgWS5uSCSyOqziePkNlS.tar)

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
