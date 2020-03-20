![](./images/hello.jpg)


    Connect to the server via RDP.

    Open %plesk_dir%admin\conf\panel.ini file (create it if it doesn't exist) and add the below directive to it.

    [php]
    curlCertificatesUrl="http://curl.haxx.se/ca/cacert.pem"

    Download the cacert.pem file from the main curl website http://curl.haxx.se/ca/cacert.pem.

    Place the downloaded cacert.pem file into the directory set as curl.cainfo in %plesk_dir%admin\conf\php.ini.

![](./images/Jun-Vu.jpg)


    
