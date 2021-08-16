FROM node:12-alpine
WORKDIR /usr/src/app/
RUN npm install -g npm@4
RUN adduser \
  --disabled-password \
  --home /usr/src/app \
  --gecos '' app \
  && chown -R app /usr/src/app
USER app