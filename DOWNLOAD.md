Please visit dataset [homepage](https://zenodo.org/record/5106795#.Yk_sVn9Bzmg) to download the data. 

Afterward, you have the option to download it in the universal supervisely format by utilizing the *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='WeedMaize', dst_path='~/dtools/datasets/WeedMaize.tar')
```
