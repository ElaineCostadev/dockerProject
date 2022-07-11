FROM node:14-alpine AS todofrontend
WORKDIR /app
ADD node_modules.tar.gz .
ADD env .
COPY . .
CMD ["npm", "start"]
EXPOSE 3000
