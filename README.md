# PyExcelerate

Accelerated Excel XLSX writing library for Python

* Current version: 0.1.0
* Authors: [Kevin Wang](https://github.com/kevmo314) and [Kevin Zhang](https://github.com/whitehat2k9)
* License: Simplified BSD License
* [Source repository](https://github.com/whitehat2k9/PyExcelerate)

## Description
PyExcelerate is a Python 2/3 library for writing Excel-compatible XLSX spreadsheet files, with an emphasis
on speed.

### Benchmarks
65000 rows x 1000 columns of the number 1

* PyExcelerate:
* openpyxl:
* xlsxwriter: 

## Installation

    pip install pyexcelerate

## Usage

```python
from pyexcelerate import Workbook

data = [[1, 2, 3], [4, 5, 6], [7, 8, 9]] # data is a 2D array

wb = Workbook()
wb.new_sheet("sheet name", data=data)
wb.save("output.xlsx")


```

## Support
Please use the GitHub Issue Tracker and pull request system to report bugs/issues and submit improvements/changes, respectively.
