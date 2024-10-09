# nginx-docker
How to Set Up a Node.js Project and Configure Nginx as a Reverse Proxy Server using Docker 

## Getting Start
1. Create .env file in app folder
2. Copy necessary variable in [.env.example](app%2F.env.example) file to .env
3. Build Project `docker-compose build`
4. Run Project `docker-compose up -d`
5. Access cms: http://localhost/cms/

## You can now edit the nginx/nginx.conf file to test any Nginx configuration changes
## After making changes use `docker-compose stop` and `docker-compose start` to apply the updated nginx.conf settings.
