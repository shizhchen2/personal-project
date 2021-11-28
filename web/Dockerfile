
FROM node:16.13.0

RUN mkdir -p /web

COPY . /web

WORKDIR /web

# RUN npm config set registry https://registry.npm.taobao.org

# RUN npm install --save next@10.0.3
# RUN npm install -g npm@8.1.4

RUN npm install

# RUN npm run build

# COPY . ./web

# ENV HOST 0.0.0.0
# ENV PORT 3000

EXPOSE 3333

CMD ["npm", "run", "dev"]