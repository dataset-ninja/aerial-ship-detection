Dataset **Ship Detection from Aerial Images** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/M/U/Za/TQO8YGkMxGPPPZQY5v7xBpgUYwiR0HXYtcs0cZ2jYlC3h6jgqZaQYwRhXmoQ8DDBAdWcQME7jRoBX6OPmxnZAlqBQs1WM09aty8NOb23D741ouQH8XxKLkxUZr3v.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Ship Detection from Aerial Images', dst_path='~/dtools/datasets/Ship Detection from Aerial Images.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/andrewmvd/ship-detection/download?datasetVersionNumber=1)