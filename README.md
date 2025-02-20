# Data Project with AWS and Lake Formation

This project aims to download and process an academic dataset, uploading the file to **Amazon S3** and managing permissions using **AWS Lake Formation**.

## Requirements

- Python 3.x
- Libraries:
  - `dotenv` (for loading environment variables)
  - `boto3` (for interacting with AWS)
  - `pandas` (for data manipulation)
  - `kagglehub` (for downloading datasets)

## How to Create the `requirements.txt`

Create a file named `requirements.txt` in the root directory of your project with the following content:

```txt
python-dotenv==1.0.0
boto3==1.24.16
pandas==1.5.3
kagglehub==1.0.4
pyarrow==11.0.0
```
## Architecture Diagram
![ETL Pipeline Architecture](./images/Architecture.png)