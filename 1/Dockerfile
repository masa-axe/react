FROM node:20-alpine

WORKDIR /app

RUN npm create vite@latest my-vite-app -- --template vanilla

WORKDIR /app/my-vite-app

RUN npm install

EXPOSE 5173

CMD ["npm", "run", "dev", "--", "--host", "0.0.0.0"]
