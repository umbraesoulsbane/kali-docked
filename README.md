# Dockerized project for Kali
### kali-docked

This is a skeleton project for working with Kali Linux (https://www.kali.org). 

###### Usage
Once container is up, either:
- enter the following in your terminal: `docker exec -it kali_docked /bin/bash` 
- ssh to your localhost (coming)

**Note:** This application has not been hardened or vulnerability tested and is not intended for production use.

## Folder Structure
**/srv**
- Custom configuration files to be copyed to container. 
- Contains Dockerfiles and logs

**/root**
- Custom code and files.
 