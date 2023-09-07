FROM node:16 as build

WORKDIR /app

COPY . .

EXPOSE 3000

CMD ["serve", "dist", "--host=0.0.0.0"]
