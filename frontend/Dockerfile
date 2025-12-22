FROM nginx:stable-alpine
COPY index.html /usr/share/nginx/html/index.html
# Proxy API calls to /api/* to backend via ALB path or configure nginx if needed.
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
