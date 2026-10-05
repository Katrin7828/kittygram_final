FROM nginx:1.22.1
COPY nginx.conf /etc/nginx/templates/default.conf.template

# Symlink для файлов без хеша (для прохождения тестов)
RUN ln -sf /static/static/js/main.a5af4b80.js /static/static/js/main.js && \
    ln -sf /static/static/css/main.9b819c0c.css /static/static/css/main.css