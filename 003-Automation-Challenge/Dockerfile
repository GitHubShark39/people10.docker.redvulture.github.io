#
# Nginx Dockerfile
# Automation Challenge
# spec file and rpm used as well as the framework
#
# https://github.com/dockerfile/nginx
# http://localhost
#

# Pull base image.
FROM dockerfile/ubuntu

# Install Nginx.
RUN \
  add-apt-repository -y ppa:nginx/stable && \
  apt-get update && \
  apt-get install -y nginx && \
  rm -rf /var/lib/apt/lists/* && \
  echo "\ndaemon off;" >> /etc/nginx/nginx.conf && \
  chown -R www-mysite:www-mysite /var/lib/nginx \
  cp automation /etc/ \
  chown -R www-mysite:www-mysite /var/automation \
  

# Define mountable directories.
VOLUME ["/etc/nginx/sites-enabled", "/etc/nginx/certs", "/etc/nginx/conf.d", "/var/log/nginx", "/var/www/html"]

# Define working directory.
WORKDIR /etc/nginx
WORKDIR /etc/automation

# Define default command.
CMD ["nginx"]
CMD ["automation"]

# Expose ports.
EXPOSE 80
EXPOSE 443
