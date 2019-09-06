---
topic: Sample
languages:
  - Python 
products:
  - Azure
---

# Sample Solution that uses OCR of Computer Vision
This python code is a quickstart that show how to use OCR of Computer Vision API for local and remote images

## Prerequisites
- [Python 3.7.4+](https://www.python.org/)
- [An Azure Subscription Key](https://portal.azure.com/#home)
- [An Azure Computer Vision instance](https://azure.microsoft.com/en-us/try/cognitive-services/?api=computer-vision)

## Setup
1. Clone or download this sample repository
2. Open your console (CLI) on cloned folder
3. On console, execute this command to install required libraries for python: 
```pip install -r requirements.txt```

## Running the sample
1. Run the sample using a local image `atoms.png`:
```python ocr-local.py```
2. Run the sample using a [this](https://upload.wikimedia.org/wikipedia/commons/thumb/a/af/Atomist_quote_from_Democritus.png/338px-Atomist_quote_from_Democritus.png) remote image:
```python ocr-remote.py```

## Documentation
* [Azure Computer Vision](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/)
* [Quickstart: Extract printed text (OCR) using the Computer Vision REST API and Python](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/quickstarts/python-print-text)
* [Sample Solution that uses the Computer Vision SDK](https://github.com/Azure-Samples/cognitive-services-dotnet-sdk-samples/tree/master/samples/ComputerVision)