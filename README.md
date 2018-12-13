# bedrock-server
Minecraft Bedrock Server - Docker


## Run

docker run -d --name=bedrock-server    -v '/root/bedrock-server/data/server.properties:/bedrock-server/server.properties'    -v '/root/bedrock-server/data/whitelist.json:/bedrock-server/whitelist.json'    -v '/root/bedrock-server/data/ops.json:/bedrock-server/ops.json'    -v '/root/bedrock-server/data/worlds:/bedrock-server/worlds'    -p 19132:19132    --restart=unless-stopped    quay.io/adamprice/bedrock-server
