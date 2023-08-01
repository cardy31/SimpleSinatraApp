# Simple Sinatra App
Here is how to run this on a basic Ubuntu/Debian server (I run it on a Raspberry Pi).

1. Install Dependencies
```bash
apt-get install nginx
apt-get install ruby
gem install sinatra
gem install puma
```
2. Copy `nginx.conf` to `/etc/nginx/nginx.conf`
3. Restart Nginx with `systemctl restart nginx`
4. Run `rackup &` in the same folder as your app

The app should now be served via HTTP.
