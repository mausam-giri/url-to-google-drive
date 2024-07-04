# url-to-google-drive
"url-to-google-drive" is a Python script for Google Colab that simplifies downloading files from URLs and saving them to Google Drive.


Google Drive Downloader
A Python script to download files from a given URL and save them to Google Drive.

Table of Contents
Installation
Usage
Requirements
Example
License
Installation
This script is designed to be used in a Google Colab environment. You can simply copy and paste the code into a new Colab notebook.

Usage
Mount your Google Drive to the Colab notebook using the following code:
python

Verify

Open In Editor
Edit
Run
Copy code
from google.colab import drive
drive.mount('/content/drive')
Specify the file path where you want to save the downloaded file:
python

Verify

Open In Editor
Edit
Run
Copy code
data_path = '/content/drive/My Drive/datasets'
Provide the URL of the file you want to download:
python

Verify

Open In Editor
Edit
Run
Copy code
url = "https://example.com/file.zip"
Call the save_to_drive function with the URL and file path:
python

Verify

Open In Editor
Edit
Run
Copy code
save_to_drive(url, f"{data_path}/file.zip")
Requirements
Google Colab environment
tqdm library (installed by default in Colab)
Example
You can find an example usage of the script in the url_to_google_drive.ipynb file.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

Author
[@mausam-giri]

