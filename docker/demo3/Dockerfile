From ubuntu:16.04

run apt-get update && apt-get install -y nginx && apt-get clean && rm -rf /var/lib/apt/lists/*

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
