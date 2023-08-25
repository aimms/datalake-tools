# datalake-tools

**Mirrored in:** https://github.com/aimms/datalake-tools

**How-to:** https://how-to.aimms.com/Articles/598/598-datalake-tools.html

**Community:** https://community.aimms.com/aimms-pro-cloud-platform-43/datalake-tools-1520

## Introduction

Every AIMMS Cloud account is by default equipped with an Azure Data Lake Storage Gen2 (ADLS). 
You can use this storage account to store all types of files that you want to integrate with your AIMMS application. 
You can also use it to store files generated based on the output of your optimizations, as to make them available to an external source.

The Data Exchange Library (https://documentation.aimms.com/dataexchange/api.html#data-lake-storage-file-systems) offers functions to easily interact with the ADLS.  

This toolkit offers you the possibility to easily create a SAS token which is needed for authentication if you want to access the ADLS from an external source. It also allows you to fetch and manage the currently known file systems ('containers') on the ADLS and the paths (folders) and files in it. 
