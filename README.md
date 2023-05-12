[![Python 3.10](https://img.shields.io/badge/python-3.10-brightgreen.svg)](#prerequisites)  [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  [![Gitter](https://img.shields.io/gitter/room/saspy-bffs/community.svg?color=777777)](https://gitter.im/saspy-bffs/community)


# Everything is Better with Friends: Using SAS in Python Applications with SASPy and Open-Source Tooling (Beyond the Basics)


### Materials from a Half-Day Class at [PharmaSUG](https://www.pharmasug.org/) in San Francisco, California, on May 14, 2023.


Materials provided:
  - Examples and Exercises as interactive Google Colab Notebooks:
    - [Part 1](https://colab.research.google.com/drive/17YOxqi7q9CoYuvFMW2iuiAlafT9iB0Ge#offline=true&sandboxMode=true)
    - [Part 2](https://colab.research.google.com/drive/1r68eneUC72A5CL-_Tr61Fx2wXPtjvY7B#offline=true&sandboxMode=true)
    - [Part 3](https://colab.research.google.com/drive/1RGqXaXHCUkmhhrgUMwOfPlUciPiHLQ4a#offline=true&sandboxMode=true)
    - [Part 4](https://colab.research.google.com/drive/17dYgDRgh3EdgPqiFbYX70I93KCSqLRWx#offline=true&sandboxMode=true)
    
  - Solutions to all Exercises as interactive Google Colab Notebooks:
    - [Part 1](https://colab.research.google.com/drive/1FlNxrJ_yinLOQquk-Zd8Qznwjch8v1Gd#offline=true&sandboxMode=true)
    - [Part 2](https://colab.research.google.com/drive/1EhsRZlI3zYyC2HpEOrKuhI2anH7Za7f4#offline=true&sandboxMode=true)
    - [Part 3](https://colab.research.google.com/drive/1Q1iFU5sH8XFE6M569VKeg4XrOSRvfYKJ#offline=true&sandboxMode=true)
    - [Part 4](https://colab.research.google.com/drive/1PTO5ZGLK4etcWJFBjXG-uWmxRmJS4sjX#offline=true&sandboxMode=true)

  - Solutions to all Exercises as PDF files:
    - [Part 1](solutions/Solutions-Beyond_the_Basics-Part1-Everything_Is_Better_With_Friends-PharmaSUG2023.pdf)
    - [Part 2](solutions/Solutions-Beyond_the_Basics-Part2-Everything_Is_Better_With_Friends-PharmaSUG2023.pdf)
    - [Part 3](solutions/Solutions-Beyond_the_Basics-Part3-Everything_Is_Better_With_Friends-PharmaSUG2023.pdf)
    - [Part 4](solutions/Solutions-Beyond_the_Basics-Part4-Everything_Is_Better_With_Friends-PharmaSUG2023.pdf)

  - [Slides](slides/Slides-Beyond_the_Basics-Everything_Is_Better_With_Friends-PharmaSUG2023.pdf) as a PDF file


## Setup Instructions & Prerequisites

### Accounts Needed

In order to interact with code examples, accounts for the following two online services will be needed:

- Google
  - We'll be using Google accounts to run code examples in [https://colab.research.google.com/](https://colab.research.google.com/)
  - If you don't already have a Google Account, you can create one for free at [https://accounts.google.com/signup](https://accounts.google.com/signup) 

- SAS OnDemand for Academics (ODA)
  - We'll be accessing ODA accounts from Google Colab, which will require you to know the Region associated with your ODA account. (The Region for an ODA account is typically displayed in the upper-right corner after logging in.)
  - If you don't already have an ODA account, you can create one for free at [https://welcome.oda.sas.com/](https://welcome.oda.sas.com/)
  - Note: To create an ODA account, you will also need a SAS Profile account. If you don't already have a SAS Profile account, you can create one for free using the "Don't have a SAS Profile?" link on the ODA login page.

To test your setup, please follow the instructions in our [Setup Test Colab Notebook](https://colab.research.google.com/drive/1qtnXrOmAYAlulrtUPrnJ-7KfVGXEmcws#offline=true&sandboxMode=true). If desired, you can use the __File__ -> __Save a Copy in Drive__ command to save a copy of the results to your Google Drive.

All in-class examples assume the use of Google Colab and ODA, and we will not be able to provide support for any other setup. However, if you're interested in using a local SASPy environment, with Python talking to a commercial SAS installation, you're welcome to follow the setup instructions for the demo application at [https://github.com/saspy-bffs/dataset-explorer](https://github.com/saspy-bffs/dataset-explorer)


### Attendee Prerequisites

This class is designed for intermediate to advanced SAS programmers, but assumes only basic familiarity with Python syntax and `pandas` DataFrames. No knowledge of JupyterLab is assumed. (For a refresher on Python, you're welcome to look through the materials from our [Getting Started](https://colab.research.google.com/drive/1swNT4HRGNfinA6uCU29UswySwONaJHbW#offline=true&sandboxMode=true) class.)

We also recommend a relatively new computer with a broadband internet connection and a modern web browser.


## Learning Outcomes

After successfully completing this class, we will be equipped for the following:

- Using Google Colab for Python script development, including linking to SAS OnDemand for Academics to access the SAS analytical engine

- Using SAS and Python together with SASPy, include understanding the trade-offs of completing common data-science tasks in SAS and Python.

- Rectangularizing complex JSON-formatted data returned by web APIs.

- Building simple Python web applications utilizing SAS analytics.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


## Authors
* [ilankham](https://github.com/ilankham)
* [mtslaugh](https://github.com/mtslaugh)


## Disclaimer

This project is in no way affiliated with SAS Institute Inc.
