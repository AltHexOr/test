FROM nginx:1.0.0
    COPY --from=build-step /app/dist/ng-docker-example /usr/share/nginx/html
    EXPOSE 4200:80