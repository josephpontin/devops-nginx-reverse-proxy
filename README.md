# Nginx Reverse Proxy example

Using reverse proxy with nginx to set up a simple app.

To use:

- Clone the repository
- Run `vagrant up`
- SSH into the app VM with `vagrant ssh app`
- Go to the correct folder with `cd /home/ubuntu/app`
- Run the following commands:
  - `sudo npm install ejs express mongoose`
  - `node seeds/seed.js`
  - `node app.js`
