## Allowed URLs

Allowed URLs lets admins restrict which external URLs can be used in pages.

* Project Lead: [Raphael Jakse](https://github.com/raphj)
* [Documentation](https://store.xwiki.com/xwiki/bin/view/Extension/AllowedURLs)
* Communication: [Forum and mailing list](http://dev.xwiki.org/xwiki/bin/view/Community/MailingLists), [chat](http://dev.xwiki.org/xwiki/bin/view/Community/IRC)
* [Development Practices](http://dev.xwiki.org)
* License: LGPL 2.1+
* Minimal XWiki version supported: XWiki 15.10
* Translations: N/A
* Sonar Dashboard: N/A
* Continuous Integration Status: [![Build Status](http://ci.xwikisas.com/view/All/job/xwikisas/job/allowedurls/job/master/badge/icon)](https://ci.xwikisas.com/view/All/job/xwikisas/job/allowedurls/job/main/)

# Release

```
mvn release:prepare -Pintegration-tests -DskipTests -Darguments="-N"
mvn release:perform -Pintegration-tests -DskipTests -Darguments="-DskipTests"
```
