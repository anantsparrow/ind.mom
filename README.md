# ind.mom
This module integrates with .ind.mom domains with .ind.mom registry with WHMCS

Installations- 
This repository will have files for a SparrowHost registry epp client module for WHMCS.

Edit the config.php file with the appropriate data given by the registry.

Copy the folder 'fred' to 'YOUR_PATH_TO_WHMCS/modules/registrars/'

Click then on "Products / Services" => "Domain Registrars"

Enable fred module.

Prepare your certificate file by pasting the private key below the certificate to appear as the sample given... 'cert.pem'.

edit whois.json file under whmcs/resources/domains/dist.whois.json

{
        "extensions": ".ind.mom",
        "uri": "socket://registry.sparrowhost.in",
        "available": "No entries found"
    },
paste this at the end, and you are now ready to sell our ind.mom domains through your whmcs 
