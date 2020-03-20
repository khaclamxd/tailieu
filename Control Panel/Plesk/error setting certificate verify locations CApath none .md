![](./images/JUN-VU.jpg)

    # Log in to the server via RDP.

    Open *%plesk_dir%admin\conf\panel.ini* file (create it if does not exist)

    Note: %plesk_dir% by default is **C:\Program Files (x86)\Plesk\**

    # Add below directive to panel.ini.

    [php]
    curlCertificatesUrl="http://curl.haxx.se/ca/cacert.pem

    Download the cacert.pem file from the main curl website <a href="http://curl.haxx.se/ca/cacert.pem" target="_blank">HERE</a>.

    Place downloaded cacert.pem to *%plesk_dir%Additional\PHPSettings\* directory.

    ***Wait until Daily task is executed (It is executed once a day).***
	
	![](./images/hello.jpg)

