# rep_aus_invoice
FrontAccounting Australian Tax Invoice

I have created an extension module to provide an Australian Tax Invoice.

The ATO (Australian Tax Office) is rather flexible about the layout of invoices but there are several mandatory elements that must be complied with to be legal. Their guidelines can be found here https://www.ato.gov.au/Business/GST/Issuing-tax-invoices/?anchor=Requirementsoftaxinvoices#Requirementsoftaxinvoices

I have used the Module facility to override the standard invoice (rep109) to make FA generate compliant invoices. A number of the other reports have also been modified to be consistent (but not a legal requirement). As this is using Modules, the changes can be switched on or off simply by enabling or disabling the extension.

