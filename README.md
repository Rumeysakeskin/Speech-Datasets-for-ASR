# Download Free Audio Data for (Automatic Speech Recognition) ASR

This repo contains some of the common publically available audio data that you can download for ASR or other speech activities.

 Source | Link | Size (Hours) |
 ------- | ------- | ------- | 
[Mozilla](https://commonvoice.mozilla.org/) |  [Common Voice 10.0-tr](https://commonvoice.mozilla.org/en/datasets) | 79 |
[Mozilla](https://commonvoice.mozilla.org/) |  [Common Voice 10.0-en](https://commonvoice.mozilla.org/en/datasets) | 3050 |
[Voxforge](http://www.repository.voxforge1.org/downloads/) | [Voxforge-en-16kHz](http://www.repository.voxforge1.org/downloads/en/Trunk/Audio/Main/16kHz_16bit/) | 130 |
[Voxforge](http://www.repository.voxforge1.org/downloads/) | [Voxforge-tr-16kHz](http://www.repository.voxforge1.org/downloads/tr/Trunk/Audio/Main/16kHz_16bit/) | 3 |

### Download Speech Data for Other Languages 

You can download and create `manifest.jsonl` for different languages supported by the dataset.   

- In the following script `common_voice_dataset.ipynb` change the version and language to you wish to download from [Mozilla](https://commonvoice.mozilla.org/en/datasets).
```python
version = 'cv-corpus-8.0-2022-01-19'
language = 'cv-corpus-8.0-2022-01-19-en'
```

- In the following script `voxforge_dataset.ipynb` change the language to you wish to download from [Voxforge](http://www.repository.voxforge1.org/downloads/).
```python
VOXFORGE_URL_16kHz = 'http://www.repository.voxforge1.org/downloads/en/Trunk/Audio/Main/16kHz_16bit/'
```
 
 
Reference Github Link: [ASR-Audio-Data-Links](https://github.com/robmsmt/ASR-Audio-Data-Links)


