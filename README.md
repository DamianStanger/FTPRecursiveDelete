FTP-Utilities
=============

A collection of powershell utilities to work with ftp sites


FTPRecursiveDelete.ps1
======================

Powershell to recursively delete everything from a FTP directory.

Originally developed to run against an Azure website FTP target but no reason why this cant be changed to work against any FTP target.

When running against an Azure website run with the following:
.\FTPRecursiveDelete.ps1 -ftpRoot <publishUrl> -WebsiteName <websiteName> -Username <userName> -Password <UserPwd>

Example:
.\FTPRecursiveDelete.ps1 -ftpRoot ftp://waws-prod-db1-123.ftp.azurewebsites.windows.net/site/wwwroot/ -WebsiteName MyWebsite -Username '$MyWebsite' -Password AzurePa55w0rdX3St0aagu9pn1viHyLdJGGG8vidgorXnKharMgggk1KlMxx
