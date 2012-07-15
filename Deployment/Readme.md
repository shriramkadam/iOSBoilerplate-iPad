# iOS Boilerplate iPad Deployment Directory

The Deployment directory will be used by a continuous integration server to build the application. 

This directory will hold the following things. 

## Delivery HTML

The Delivery HTML directory will contain the build HTML files for the project. When the CI server builds the project, these files will be copied and put on the extranet server to be used to allow the user to download the OTA files.


## Provisioning

The Provisioning directory will hold the development provisioning profiles for the project. 

## Signing Identities

The Signing Identities will hold the application signing identities used by the application. 
This will be a .p12 file.

## xcode_export.properties

The project's export properties. 