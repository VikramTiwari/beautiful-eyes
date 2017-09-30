# Beautiful Eyes

- A "Useless Hackathon" demo at Symph.
- Replace your eyes with beautiful eyes!
- Uses GCP Vision API to detect position coordinates of eyes.

## What it does

- changes photo to base64
- sends them to vision api
- gets position and slope of eyes
- overlays beautiful eyes to those positions

## Setup

- Get an API key for Vision API from developer console
- Replace it in the index.html#l10
- Serve locally using python or nodejs

``` bash
# python
python -m SimpleHTTPServer

# nodejs
http-server
```

## Usage

- Upload files from test directory
- Wait for the response from vision api and the eyes will be replaced automatically

## Credits

- [Albert Padin](https://github.com/albertpadin)
