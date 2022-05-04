# API-Docs

To automate the generation of FAN Courier shipping labels, we put at your disposal the SelfAWB API that can be integrated into your website or custom application. 
Using this solution you can: calculate the price of the expedition, generate shipping labels (AWB), print the AWB, track the delivery status and more. 

You can use the data below for testing only:
- ClientID : 7032158
- Username : clienttest
- Password : testing

This is a public test account that can be uset to test the API or to access the SelfAWB application.

Regarding the general workflow for API integration, this is:
1. AWB generation using the import_awb_integrat.php script and the csv file model_awb.csv file
2. AWB printing using view_awb_integrat_pdf.php
3. create the pick-up order using the script comanda_curier_integrat.php
4. tarif.php can be used to estimate the transport cost.

If you have any questions do not hesitate to contact us at asistenta.it@fancourier.ro . 
