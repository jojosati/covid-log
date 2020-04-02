COVID log
---

## Resource
- [AngularJS 1.7](https://angularjs.org/)
- [BootStrap 3.4.1](https://getbootstrap.com/docs/3.4/)
- [Serving static files in Node.js sample for Google App Engine](https://github.com/GoogleCloudPlatform/nodejs-docs-samples/tree/master/appengine/static-files)

## Description
Just deploy to App Engine Standard Environment,
beware of cost if serve large amount of people.

When A person input their temperature and cough level,
this app will generate an url path embedded with those values and send request to host.

App Engine as a host will keep request log in Stackdriver, 
ready to export to other destinations to do analysis.

note:
Test UI by open file `public/index.html` with your browser.

more: 
https://cloud.google.com/logging/docs/export/configure_export_v2




