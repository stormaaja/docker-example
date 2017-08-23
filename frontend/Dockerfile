# assumes that you've ran `npm install` & `npm run build` before building this

FROM nginx
# Override default config
COPY ./nginx.conf /etc/nginx/nginx.conf
# Copy React ./dist & index.prod.html to nginx root
COPY ./dist /usr/share/nginx/html 
COPY ./index.prod.html /usr/share/nginx/html/index.html
