FROM nginx:1.10.1

WORKDIR /etc/nginx
ADD sites ./
COPY nginx.conf nginx.conf
RUN ln -sf /etc/nginx/sites-available/jenkins /etc/nginx/sites-enabled/
RUN cat ./sites-available/jenkins