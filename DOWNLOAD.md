Dataset **Ship Detection from Aerial Images** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/R/u/2h/qd6wDRKFbuZPb3i8Y2RGXR0xkgcJwiHBbcVZN8sDKiYoyRL2hY9efp3LnnyETt03SuUACd2vfah8jFCS6XsRcr0EIUWxAmm4b0gNmbyivpR1tsqJF8gukcUjX4o5.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Ship Detection from Aerial Images', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/andrewmvd/ship-detection/download?datasetVersionNumber=1).