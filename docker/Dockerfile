FROM node:latest
RUN npm config set registry https://registry.npm.taobao.org
RUN npm install -g cnpm --registry=https://registry.npm.taobao.org
WORKDIR /app
RUN cnpm install hexo-cli -g
EXPOSE 4000
CMD ["hexo", "server"]
