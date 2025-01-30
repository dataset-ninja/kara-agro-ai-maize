Dataset **KaraAgro AI Maize** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzMzNzJfS2FyYUFncm8gQUkgTWFpemUva2FyYWFncm8tYWktbWFpemUtRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAid0xLMXd5eGxpNkx2Tmc1RjlZSG5iR0h3QnVGTUNUTjAvZWd1ZWVNeDd5az0ifQ==)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='KaraAgro AI Maize', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/CXUMDS#).