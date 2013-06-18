Read me
============

Scrapy template for online store.

If you have any question, please contant to @Anfernee Chang
  - Gtalk: innovotech.hr@gmail.com
  - Skype: anfernee-chang


### Product Database Schema

- Please refer to [Product Database Schema v3.3](https://docs.google.com/file/d/0BwBtbldsfq-3a0dEdEs3MFVpam8/edit)
- We define the product item in the items.py, please follow it.

### Notes

- Please add node's XPath in the spider class variable **_xpaths_** dict. We will use these information to check your spider.
- Please raises ValueError if the page have no data for the XPath to any **Required Fields**.
