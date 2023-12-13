# Stage 1
FROM node:16 AS builder
WORKDIR /app
COPY package*.json .
RUN npm i --legacy-peer-deps
COPY . .
EXPOSE 3000
CMD npm start
# RUN npm run build

# # Stage2
# FROM nginx:1.25
# WORKDIR /usr/share/nginx/html
# COPY --from=builder /app/build .
