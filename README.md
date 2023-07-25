# DSFSG_PERMIT
This GitHub hosts the code for the permit group of the Data Science for Social Good Practicum held at Emory University

# Description
This GitHub repository serves as a resource for managing building permits in the Metro Atlanta area, facilitating the end-to-end process through various functionalities. It begins with a web scraping component that efficiently extracts relevant permit data from local government websites, converting PDF to CSV 
 - if needed - in order for information to be in a standardized format. The integrated file conversion utilities then transform these data sets into universally accessible formats, ensuring that they can be readily employed across various systems. Additionally, the repository features a robust database management tool that organizes and maintains the permit data, making it easy to access and update. In essence, this GitHub repository presents a holistic solution for the systematic collection, conversion, and management of building permit data in the Metro Atlanta area. This project helps manage the building permits for the city of Atlanta as well as the following counties: Clayton, Cobb, DeKalb, and Gwinnett

#Installation
Use the package manager [pip] to install the required Python Packages and then import the following libraries 
```bash
pip install pdfplumber
```
```python
import os
import re
import pdfplumber
import pandas as pd
```
