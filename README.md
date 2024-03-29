# webReaDeR backend

![logo](https://github.com/chm-dev/rdr-frontend/raw/master/public/img/icons/icon-192x192.png)

This is backend for simple "Read it later" / "Pocket" clone as Progressive WebApp.
[Frontend repository is here](https://github.com/chm-dev/rdr-frontend).

It is a [Strapi](https://strapi.io) instance with some custom modifications.

This backend provides:
* Fully functional and lovely strapi frontned for data managment
* Account managment (login / register) with JWT Authentication 
* Custom content fetcher plugin (uses external ML based api for content extraction from url)
* Customised endpoints for limiting data transfer size and caching purposes.
* Splits contents of an article and its metadata into two separate tables (proof of concept for easier scaling as scraped html contents can get big)
