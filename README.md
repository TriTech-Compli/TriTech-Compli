TriTech Compli Ltd.
===================

Corporate website

Run web server for development:

    docker run --rm -it --name website -p 8000:8000 -v ${HOME}/Workspace/TriTech-Compli.github.io:/var/www/html php:8.1-cli-alpine php -S 0.0.0.0:8000 -t /var/www/html
