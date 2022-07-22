FROM node:10.24.1-alpine3.11

WORKDIR /app
COPY . .

RUN apk add --no-cache git make python3 gcc g++

# ENV PORT 80
EXPOSE 8080:8080
RUN npm install
CMD ["npm", "run", "start:production"]