FROM nginx
COPY code /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
COPY ngnix.conf /etc/nginx/nginx.conf
COPY expense.conf /etc/nginx/default.d/expense.conf
