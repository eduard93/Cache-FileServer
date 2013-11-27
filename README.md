Cache-FileServer
================

Seed for sharing files via uid with InterSystems Cache.<br>

Install.<br>
1. Create new namespace (eg. fileserver) with new database.<br>
2. Import files (via git or download zip-archive).<br>
3. Create new web-application "/fileserver", with dispatch class: Fileserver.Broker<br>

If installation has been completed successfully, then your server will be available at: http://[server ip]:[server port]/fileserver/files<br>
Test info at:  http://[server ip]:[server port]/fileserver/test<br>
