Contentreich Alfresco RFC822/EML tweaks
================

This extension makes email consumption in Alfresco Share a little easier. Further details
are at http://www.contentreich.de/von-menschen-lesbare-emails-in-alfresco-share

To install, just copy contentreich-eml-repo.jar to alfresco/WEB-INF/lib and contentreich-imap-share.jar
to share/WEB-INF/lib. Restart Server, go to page /share/page/modules/deploy and activate.

These fork provides AMP ready-to-deploy artifacts.

From Alfresco 5.2 a flag is required in `alfresco-global.properties`

```
transformer.strict.mimetype.check=false
```