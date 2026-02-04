FROM node:25.6.0-bookworm
RUN mkdir -p /app/src
WORKDIR /app/src
COPY package.json .
RUN npm install --legacy-peer-deps
COPY . .
EXPOSE 3000
CMD ["npm","start"]
