# HSTS Site Extension

This extension adds the `Strict-Transport-Security` header to any requests over https.  
Currently it sets the following value for the header `max-age=31536000 ; includeSubDomains` 
making it valid for a year including subdomains.

Read more about the hsts header 
## Build

Run the build.cmd not forgetting to add a version ex. `build.cmd 0.0.1` for instance.
This creates a nuget package in the artifacts folder, that you can add to your own nuget feed.

## Installation

### Gallery install

Go the kudu (SCM) site and go the `Site Extensions` section.    
Your gallery should now show the HstsSettings extension.  

