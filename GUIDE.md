### How to use docker image

# Run on workstation
docker run -d /
&nbsp;&nbsp;--name \<container name\> /
&nbsp;&nbsp;-p 9002:9002 /
&nbsp;&nbsp;-v \<graphql file path\>:/workdir/schema.faker.graphql \
&nbsp;&nbsp;\<image url\> \
&nbsp;&nbsp;npm run start
