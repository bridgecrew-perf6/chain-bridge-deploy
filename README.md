# cross-chain-bridge

deploy contract

- [**doc**](./docs/doc.md)

generic key

    ./chainbridge accounts import --privateKey "ec7d533a64df9d7f4d5a211bb973285749fb72d331032444072dd6444e12e326"
    The chainbridge in root is compiled from https://github.com/ChainSafe/ChainBridge
      

edit config files

run docker

    docker-compose -f ./docker-compose-init.yml up -V   // Run this command when starting for the first time. When the block height is obtained, run the following command

    docker-compose -f ./docker-compose.yml up -V