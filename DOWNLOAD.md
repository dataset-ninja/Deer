Dataset **Deer** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/Y/r/aH/tcjPoxRmNOx1dZ3jYjWxaIHQK1pgyWw1vZekfLZVcm7Uh3geZYmcjoAdPvooMQilijl3j18me7NZ9H9DDcYtfOGUN4MensUDVUV2VspAyYy1zibwTB3Pu07R5FC4.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Deer', dst_path='~/dtools/datasets/Deer.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/deertracker/deer-yidlt/dataset/1/download)