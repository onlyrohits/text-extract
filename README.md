## Text Extract

This repo plays around with Amazon Textract and other AWS services to get insights from documents.


## Environment setup

```bash
$ git clone ${REPO}
$ cd text-extraction
$ pipenv install --dev
$ pipenv shell
```

Do Not Forget to setup your AWS CLI credentials locally


## Usage

```bash
$ python 01-detect-text-local.py
```
For examples that use S3 bucket, upload sample images to an S3 bucket and update variable "s3BucketName" in the example before running it.


## Python Samples

| Argument                                                    | Description                                                |
| ----------------------------------------------------------- | ---------------------------------------------------------- |
| [01-detect-text-local.py](./python/01-detect-text-local.py) | Example showing processing a document on local machine.....|
| [02-detect-text-s3.py](./python/02-detect-text-s3.py)       | Example showing processing a document in Amazon S3 bucket..|
| [03-reading-order.py](./python/03-reading-order.py)         | Example showing printing document in reading order.........|
| [04-nlp-comprehend.py](./python/04-nlp-comprehend.py)       | Example showing detecting entities and sentiment...........|
| [05-nlp-medical.py](./python/05-nlp-medical.py)             | Example showing detecting medical entities.................|
| [06-translate.py](./python/06-translate.py)                 | Example showing translation of documents...................|
| [07-search.py](./python/07-search.py)                       | Example showing document indexing in Elasticsearch.........|
| [08-forms.py](./python/08-forms.py)                         | Example showing form (key/value) processing................|
| [09-forms-redaction.py](./python/09-forms-redaction.py)     | Example showing redacting information in document..........|
| [10-tables.py](./python/10-tables.py)                       | Example showing table processing...........................|
| [11-tables-expense.py](./python/11-tables-expense.py)       | Example showing validation of table data...................|
| [12-pdf-text.py](./python/12-pdf-text.py)                   | Example showing PDF document processing....................|


## Other Resources

- [Large scale document processing with Amazon Textract - Reference Architecture](https://github.com/aws-samples/amazon-textract-serverless-large-scale-document-processing)
- [Batch processing tool](https://github.com/aws-samples/amazon-textract-textractor)
- [JSON response parser](https://github.com/aws-samples/amazon-textract-response-parser)

## License Summary

This sample code is made available under the MIT-0 license. See the LICENSE file.
