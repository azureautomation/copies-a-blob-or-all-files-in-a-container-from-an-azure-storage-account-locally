Copies a blob or all files in a container from an Azure storage account locally
===============================================================================

            




Copies a blob or all files in a container from an Azure storage account
to a local directory.

Args:
    local_file_path (-p) - local directory to copy files to
    storage_resource_group (-r) - resource group name where storage account is
    storage_account_name (-a) - storage account name
    storage_account_container_name (-c) - container name
    blob_name (-b) - optional name of a blob

    Copy a specific blob to a local directory
    Example 1:
            download_storage_container.py -p <local_file_path> -r <resource_group> -a <storage_account_name> -c <storage_account_container_name> -b <blob_name>

    Download all files in a container to the local directory
    Example 2:
            download_storage_container.py -p <local_file_path> -r <resource_group> -a <storage_account_name> -c <storage_account_container_name>

**






 




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
