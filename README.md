# Google Drive Downloader
=======================

A Python script to download files from a given URL and save them to Google Drive.
"url-to-google-drive" is a Python script for Google Colab that simplifies downloading files from URLs and saving them to Google Drive.

## Table of Contents
-----------------

*   [Installation](#installation)
*   [Usage](#usage)
*   [Requirements](#requirements)
*   [Example](#example)
*   [License](#license)

## Installation
------------

This script is designed to be used in a Google Colab environment. You can simply copy and paste the code into a new Colab notebook.

## Usage
-----

### Mount Google Drive

Use the following code to mount your Google Drive to the Colab notebook:

```python
from google.colab import drive 2drive.mount('/content/drive')
```

Verify the mount by running 
```bash 
ls "/content/drive/My Drive/"
```

### Specify File Path

Specify the file path where you want to save the downloaded file:

```python
data_path = '/content/drive/My Drive/datasets'
```

### Provide URL

Provide the URL of the file you want to download:

```python
url = "https://example.com/file.zip"
```

### Call Function

Call the `save_to_drive` function with the URL and file path:

```python
save_to_drive(url, f"{data_path}/file.zip")
```

Requirements
------------

*   Google Colab environment
*   `tqdm` library (installed by default in Colab)

Contributing
------------

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

Author
------

\[@mausam-giri\]

