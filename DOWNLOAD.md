Dataset **Deer (z7klu)** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/1/o/wr/urT4irvEgpefRx8yXdwljujZJxjSWTMYPCiIpYgenoIqNzfyv8NkfeUBDtc3lns3cms50p3fSg1slnKj0qoyHxfphnshacCZxgsNy02E136vWTR2s9zJHFpoZPOo.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Deer (z7klu)', dst_path='~/dtools/datasets/Deer (z7klu).tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/galen-marsh-vvdvx/deer-z7klu/dataset/3/download)