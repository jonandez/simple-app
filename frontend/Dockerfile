FROM node:10.24.1-alpine3.11

WORKDIR /app
COPY . .

# RUN apk add --no-cache git make

# ENV PORT 80
EXPOSE 80:80
RUN npm install
RUN npm install -g serve
CMD ["npm", "run", "build:production"]
