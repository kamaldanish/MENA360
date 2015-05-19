# MENA360
Generic API for Fulfillment + Delivery

Installation Guide for MENA360 ERP Magento Extension
 
Pre-Installation Steps
 
1. Disable the Cache
 
Process: System->Cache Management), selecting all caches, clicking "Disable" from the drop-down menu, and submitting the change.
 
2. Disable Compilation Mode
 
Process:  System->Tools->Compilation. If the compiler status is "Disabled", you are ready to go. If not, simply click the ‘Disable’ button on the right hand side of the screen.
 
3. Create New Order Status
Process: System-> Order Status. Click on “Create New Status” and create two Order Status with as below
A: Status Code as “processing” and Status Label as “Processing”
B: Status Code as “erp_processing” and Status Label as “Erp Processing”
And then assign both “Status”  as processing “State”

 
Installation Steps
 
1. Extract the file to your local machine.
 
2. Put the Mena_Api.xml and Mena_Openerp.xml files into the app/etc/modules/
 
3. Put the Mena directory into the app/code/local/
 
4. Put the mena_update_stock.php, openerp.php, openERPScript.sh, erp-sync.php and corder.php files into the shell/
 
ALWAYS remember to make a full database/files backup before installing any new modules!
 
The above plugin is for development machine, so if you have development Magento server so please tries to connect first with development machine.
