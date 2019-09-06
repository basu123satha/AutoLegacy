# AutoLegacy
Automation of Store SKU Price reconciliation process

1) SKU Price Set up on Legacy(AS400):
The SKU (Product) prices for stores are set on legacy (Mainframe/AS400) system by business users through legacy SKU (Product) pricing screens. Using UiPath automation, manual process of SKU price set up by navigation through legacy screens would be automated by a bulk upload process thus saving business user effort.

Note : Please refer the attached folder with name "SKUPriceSetAS400.zip". 

2) SKU Price retrieval from legacy(AS400):
Once the prices are set, legacy (Mainframe/AS400) system sends a daily feed to stores via a download process, in the evening. These prices are retrieved on the Windows server from legacy(AS400) system using automation for later reconciliation with prices at store server.

Note: Please refer the attached folder with name "ReadSKUPriceFromAS400.zip". 

3) Store SKU price reconciliation with legacy system(AS400):
Before store open, the store associate manually compares the prices of SKUs (Products) on their Windows based store servers with that of the prices send by legacy system feed. If price mismatch is found , then manually print a sign for these SKUs(override the prices to reflect AS400 prices). Using UiPath automation, reconciliation process on Windows Store server can be automated by comparing the data of SKU (Product) price between store server and legacy system thus saving the manual effort in comparison. The differences would be highlighted for signage printing of applicable SKUs(Products)

Note: Please refer the attached folder with name "StoreReconciliationAS400.zip" .


Video file can be seen on one drive of Mindtree, Anyone can see it.
