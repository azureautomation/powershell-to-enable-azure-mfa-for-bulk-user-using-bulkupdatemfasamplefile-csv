POWERSHELL TO ENABLE AZURE MFA FOR BULK USER USING BulkUpdateMFASampleFile CSV
==============================================================================

            

POWERSHELL TO ENABLE AZURE MFA FOR BULK USER USING BulkUpdateMFASampleFile CSV


This is just extension to the earlier script - [POWERSHELL TO ENABLE AZURE MULTI-FACTOR AUTHENTICATION FOR BULK USER](http://vedtechno.com/powershell-enable-azure-multi-factor-authentication-bulk-user/)


Azure provide option to update bulk user from Azure portal using [sample CSV ](https://account.activedirectory.windowsazure.com/UserManagement/BulkUpdateMfa/BulkUpdateMFASampleFile.csv)file available at https://account.activedirectory.windowsazure.com/UserManagement/BulkUpdateMfa/BulkUpdateMFASampleFile.csv
 . you just need to add user and new MFA state in the CSV itself and then upload it to azure.

![Image](https://github.com/azureautomation/powershell-to-enable-azure-mfa-for-bulk-user-using-bulkupdatemfasamplefile-csv/raw/master/img_58e0a086ed77a.png)


CSV format -

![Image](https://github.com/azureautomation/powershell-to-enable-azure-mfa-for-bulk-user-using-bulkupdatemfasamplefile-csv/raw/master/img_58e0a06b933da.png)


 


OR


if you want to use powershell to update all users in CSV then below is script to do so..


how to use script


**Set-MFA -csv -csvpath 'C:\Users\Downloads\BulkUpdateMFASampleFile.csv'**


 


**

 

**




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
