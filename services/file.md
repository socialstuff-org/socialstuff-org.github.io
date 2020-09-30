# File Service

### Case A: Bob sends file to Alice

1. Bob selects file(s) to send
1. Bob can define custom 'best-before date (delete date)'
1. System encrypts file(s) locally
1. Bob uploads files to server
1. Server stores files
1. File service returns one UUID per uploaded file
1. Bob sends message with file UUIDs and [encryption initialization vectors](initVector.md) to server
1. Server sends text message to Alice
1. Alice receives message
1. Alice requests files from origin server via (domain.com/file/UUID)
