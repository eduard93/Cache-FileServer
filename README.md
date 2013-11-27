Cache-FileServer
================

Seed for sharing files via uid with InterSystems Cache

Install.
1. Create new namespace (eg. fileserver) with new database,
2. Import files (via git or download zip-archive).
3. Create new web-application "/fileserver", with dispatch class: Fileserver.Broker

If installation has been completed successfully, then your server will be available at:
  http://<server ip>:<server port>/fileserver/files
Test info at:
  http://<server ip>:<server port>/fileserver/test
