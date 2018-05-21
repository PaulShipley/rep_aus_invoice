# rep_aus_invoice
FrontAccounting Australian Tax Invoice

I have created an extension module to provide an Australian Tax Invoice.

The ATO (Australian Tax Office) is rather flexible about the layout of invoices but there are several mandatory elements that must be complied with to be legal. Their guidelines can be found here https://www.ato.gov.au/Business/GST/Issuing-tax-invoices/?anchor=Requirementsoftaxinvoices#Requirementsoftaxinvoices

I have used the Module facility to override the standard invoice (rep109) to make FA generate compliant invoices. A number of the other reports have also been modified to be consistent (but not a legal requirement). As this is using Modules, the changes can be switched on or off simply by enabling or disabling the extension.

Refer to:
http://frontaccounting.com/punbb/viewtopic.php?id=7449

The module can be downloaded from:
https://github.com/PaulShipley/rep_aus_invoice

Install by copying to [fa root dir]/modules, then install Australian Tax Invoice extension and activating it for company(s).

Refer to:
http://frontaccounting.com/fawiki/index.php?n=Help.InstallActivateExtensions

The only visible indication that the module is working is that when an invoice is generated it will be formatted as a Tax Invoice.

