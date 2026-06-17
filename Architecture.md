# Architecture Diagram

## CI/CD Architecture

Developer
|
v
GitHub Repository
|
v
GitHub Webhook
|
v
Jenkins Server
|
v
Target Server
|
v
Nginx Web Server
|
+-------------------+
|                   |
v                   v
FoodHub Website    ShopEase Website

## Workflow

1. Developer pushes code to GitHub.
2. GitHub Webhook automatically triggers Jenkins Pipeline.
3. Jenkins pulls the latest source code.
4. Jenkins deploys application files to the target server.
5. Nginx serves both websites.
6. Users can access FoodHub and ShopEase through the web server.

## Components Used

* GitHub Repository
* GitHub Webhook
* Jenkins Server
* Target Server
* Nginx Web Server
* FoodHub Website
* ShopEase Website
* AWS EC2
