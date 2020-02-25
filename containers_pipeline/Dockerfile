## If IMAGE_ID ist not set with build arg, default to "latest"
ARG IMAGE_ID=nginx:latest

FROM $IMAGE_ID

## Remove:
RUN rm /usr/share/nginx/html/index.html

# Insert custom index.html file
COPY index.html /usr/share/nginx/html