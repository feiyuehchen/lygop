# Lygo: Crosslinguistic Evaluation for Lyrics Generation


This is a open-source project converting multi-language lyrics into IPA phonemes. 



## Usage

### Setup
```python
conda create -n lygop python=3.11
conda activate lygo
git clone https://github.com/feiyuehchen/lygo
cd lygo
pip install -r requirements.txt
```

### Download Dataset
You could directly download the dataset from kaggle (https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information/data) or run the following command line:
```

mkdir ../dataset
cd ../dataset
#!/bin/bash
curl -L -o ./genius-song-lyrics-with-language-information.zip\
    https://www.kaggle.com/api/v1/datasets/download/carlosgdcj/genius-song-lyrics-with-language-information
unzip genius-song-lyrics-with-language-information.zip 

```

The defult data structure is set as 

```
|- lygo
|- dataset
    |- song_lyrics.csv
```

