# Dockerized project for ZAP
### zap-docked

This is a skeleton project for working with Zap (https://www.zaproxy.org/), a web application security scanner, in a Docker environment.

## References
- https://www.zaproxy.org/docs/docker/
- https://hub.docker.com/r/bkimminich/juice-shop

**Note:** This application has not been hardened or vulnerability tested and is not intended for production use.

## Folder Structure
**/assets**
- Local/Saved Sessions 
- Local/Saved Contexts

## Usage
Launch via web browser http://localhost:8080/zap/

Includes test site OWASP Juice Shop at http://localhost:3000
You may need to hit http://192.168.99.100:3000/ first for some reason. Maybe windows specific.
