Dataset **Ship Detection from Aerial Images** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMTMyOV9TaGlwIERldGVjdGlvbiBmcm9tIEFlcmlhbCBJbWFnZXMvc2hpcC1kZXRlY3Rpb24tZnJvbS1hZXJpYWwtaW1hZ2VzLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIkZjMTc1bGN4SS9KZmhKdWVoQm8xRkJESklpK3V2YnczYmRzM2M0b1E3TGM9In0=?response-content-disposition=attachment%3B%20filename%3D%22ship-detection-from-aerial-images-DatasetNinja.tar%22)

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