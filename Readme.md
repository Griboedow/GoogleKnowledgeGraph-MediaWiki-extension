Google Knowledge Graph extension adds short descriptions for specified terms.

# Warning
The extension is provided only for education purpose. 
Using it in production is not recommended: Google provides only 100 000 requests for free. 

# Installation and configuration
To install the extension, place the folder in ./extensions and add in LocalSettings.php:

wfLoadExtension( 'GoogleKnowledgeGraph' );
$gkgApiToken = 'your-google-token';
$gkgApiLanguage = 'ru,en';


# Where to get Google API token
You can get token on:
https://console.cloud.google.com/flows/enableapi?apiid=kgsearch.googleapis.com&credential=client_key

# Usage
To use the extension add on a page tag:
<GoogleKnowledgeGraph query="Moscow">
and save the page
