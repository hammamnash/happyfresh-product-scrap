## Happyfresh Product Scrapper

A python notebook to scrap or get data from happyfresh website
Attribute can be scrapped as :
- product Category
- Product Name
- product packaging
- product price per pack
- product unit
- product price per unit

### requirements : 
- Python 3.6
- Selenium 
- Latest Chrome webdriver exe

### Pros : 
- can acquire multi and specific category and outlet

### Cons : 
- To bypass unidentified char in product name, i am using encode to utf-8 which result needing additional processing
- Price need additional processing
- Some product will have different name across another outlet
- ugly loading animation *hehe*
        
### how to use:
- clone or download this repo.
- install the dependencies using pip `pip install -r requirements.txt` or `conda install -r requirements.txt` if u use conda.
- open notebook using your favourite text editor or IDE.
- fill your target outlet's url in list `target`
- fill your target outlet category code in list `category`

This code need lot of improvement tho😅🙏

