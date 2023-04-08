[![Python](https://img.shields.io/badge/-Python-464646?style=flat&logo=Python&logoColor=56C0C0&color=008080)](https://www.python.org/)
[![Practicum.Yandex](https://img.shields.io/badge/-Practicum.Yandex-464646?style=flat&logo=Practicum.Yandex&logoColor=56C0C0&color=008080)](https://practicum.yandex.ru/)
# scrapy_parser_pep
## Description
Asynchronous PEP documentation parser written in Scrapy framework. The parser generates 2 reports in .csv format in the results directory.

## Installation

To run this script on your computer, follow these steps:

1. Clone the repository using the command
```
git clone git@github.com:seregatipich/scrapy_parser_pep.git
``` 
2. Navigate to the application directory using the command
```
cd scrapy_parser_pep
``` 
3. Create virtual environment
```
python -m venv venv
```
4. Activate virtual environment
```
source venv/Scripts/activate
```
or
```
source venv/bin/activate
```
5. Install the dependencies from requirements.txt
```
pip install -r requirements.txt
```

## Usage

1. run the parser
```
scrapy crawl pep
```
### All data will be saved in two .csv files in the results directory:
```
pep_2023-04-08T07-49-08.csv
status_summary_2023-04-08_09-49-33.csv
```

## License

<<<<<<< HEAD
This project is licensed under the MIT License. You are free to use it in your projects.
=======
This project is licensed under the MIT License. You are free to use it in your projects.
>>>>>>> 53d8c783e5cb67613e1de4895c3d56f5cbff798c