# Use_Cases_samples



## Requirements

Opening .ipynb files requires:
1. Google account
2. [Google Colaboratory][1]

[1]: https://workspace.google.com/marketplace/app/colaboratory/1014160490159?pann=ogb


## Local Installation

1.  Copy the repository link, open Command Prompt, go to the location where file will be copied and execute git clone command:

```shell
git clone https://github.com/kyriba/Use_Cases_samples.git
```

2. Import the desired .ipynb sample file into your Google Drive.

3. Open config.csv file and input your client credentials by replacing the highlighted items with your client_id and client_secret, separated by the coma. Config file should look like this:

![config](config.png)

4. Open the jupyter notebook with Google Colab.

5. In the Table of Content on the left, click on the folder logo ![files](files.png) which opens Files section, then press on the file upload icon ![upload](upload.png) and select the amended config.csv.

6. Run the application. You can run the whole application: Runtime -> Run all, or execute separated cells.

> ⚠️  _Please notice that Python is a script language and code will be executed row by row or in the order you will run the cells._

