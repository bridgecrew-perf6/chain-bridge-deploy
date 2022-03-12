#PLGR  token 
    0x22E6f32805d2AC7F787ca72b2F0bdbCE1693573b
#MPLGR token 
    0xb7d51b050f2072C2855B21579bB61955Cb484a97


#BSC：

cb-sol-cli --url https://data-seed-prebsc-1-s1.binance.org:8545  \
--privateKey 1da17eeca743098a8b9ccf29cfd0ed6719f160df552e4ac33db23c51e66caef4 \
--gasPrice 100000000000 deploy   \
--bridge --genericHandler   \
--erc20 --genericHandler   \
--relayers="0xef83be706597Dd409e49ed488F3e23cEB98Dc495","0xec9EB2bf4497d448FB61171C54D295702C9F5cbC","0xD5f92Fd92F8c7f9391513E3019D9441aAf5b2D9E"     \
--relayerThreshold 3    \
--chainId 0


================================================================
Url:        https://data-seed-prebsc-1-s1.binance.org:8545
Deployer:   0x99e4F27C854725Fe47924987A9cd324243b6e277
Gas Limit:   8000000
Gas Price:   100000000000
Deploy Cost: 0.7318577

Options
=======
Chain Id:    0
Threshold:   3
Relayers:    0xef83be706597Dd409e49ed488F3e23cEB98Dc495,0xec9EB2bf4497d448FB61171C54D295702C9F5cbC,0xD5f92Fd92F8c7f9391513E3019D9441aAf5b2D9E
Bridge Fee:  0
Expiry:      100

Contract Addresses
================================================================
Bridge:             0x11F565667a9B3dA6CBC843624A1293AAD8534A2a
----------------------------------------------------------------
Erc20 Handler:      Not Deployed
----------------------------------------------------------------
Erc721 Handler:     Not Deployed
----------------------------------------------------------------
Generic Handler:    0x0735e079319c8160e3B4cbFa3c4aaA91Ae8A23AE
----------------------------------------------------------------
Erc20:              0x647388F61f05cf87cb5441bacAe6099D4139d2C5
----------------------------------------------------------------
Erc721:             Not Deployed
----------------------------------------------------------------
Centrifuge Asset:   Not Deployed
----------------------------------------------------------------
WETC:               Not Deployed
================================================================



部署bridge BSC合约，生成的合约地址： 0xed8ef682d4e610200879a3a58bcc50a1b970fa90

cb-sol-cli  --url https://data-seed-prebsc-1-s1.binance.org:8545  \
--privateKey 1da17eeca743098a8b9ccf29cfd0ed6719f160df552e4ac33db23c51e66caef4 \
--gasPrice 10000000000 bridge register-generic-resource \
--bridge 0x11F565667a9B3dA6CBC843624A1293AAD8534A2a \
--handler 0x0735e079319c8160e3B4cbFa3c4aaA91Ae8A23AE \
--resourceId 0x000000000000000000000000000000c76ebe4a02bbc34786d860b355f5a5ce00 \
--execute 0x02c0ab3b \
--targetContract 0xed8ef682d4e610200879a3a58bcc50a1b970fa90

output：
Registering generic resource ID 0x000000000000000000000000000000c76ebe4a02bbc34786d860b355f5a5ce00 with contract 0xed8ef682d4e610200879a3a58bcc50a1b970fa90 on handler 0x0735e079319c8160e3B4cbFa3c4aaA91Ae8A23AE
Waiting for tx: 0x1545e29093a074af5af49b404d6e4c0ec64027205861c128cf7ce08458d1367c...




#ETH：


cb-sol-cli --url https://ropsten.infura.io/v3/acb534b53d3a47b09d7886064f8e51b6  \
--privateKey 1da17eeca743098a8b9ccf29cfd0ed6719f160df552e4ac33db23c51e66caef4 \
--gasPrice 100000000000 deploy   \
--bridge --genericHandler   \
--erc20 --genericHandler   \
--relayers="0xef83be706597Dd409e49ed488F3e23cEB98Dc495","0xec9EB2bf4497d448FB61171C54D295702C9F5cbC","0xD5f92Fd92F8c7f9391513E3019D9441aAf5b2D9E"     \
--relayerThreshold 3    \
--chainId 1


    
================================================================
Url:        https://ropsten.infura.io/v3/acb534b53d3a47b09d7886064f8e51b6
Deployer:   0x99e4F27C854725Fe47924987A9cd324243b6e277
Gas Limit:   8000000
Gas Price:   100000000000
Deploy Cost: 0.7365977

Options
=======
Chain Id:    1
Threshold:   3
Relayers:    0xef83be706597Dd409e49ed488F3e23cEB98Dc495,0xec9EB2bf4497d448FB61171C54D295702C9F5cbC,0xD5f92Fd92F8c7f9391513E3019D9441aAf5b2D9E
Bridge Fee:  0
Expiry:      100

Contract Addresses
================================================================
Bridge:             0xFFfE10DA4373A12Fb14dE9d900465d65FFD3E37e
----------------------------------------------------------------
Erc20 Handler:      Not Deployed
----------------------------------------------------------------
Erc721 Handler:     Not Deployed
----------------------------------------------------------------
Generic Handler:    0x68AEFd8c6f380e34d33F41c6c6af955Df4934Df4
----------------------------------------------------------------
Erc20:              0xe3D8Bd14C8099f90191db00718d08AB11f8F538B
----------------------------------------------------------------
Erc721:             Not Deployed
----------------------------------------------------------------
Centrifuge Asset:   Not Deployed
----------------------------------------------------------------
WETC:               Not Deployed
================================================================




部署bridge ETH合约，生成的合约地址： 0x11f565667a9b3da6cbc843624a1293aad8534a2a


cb-sol-cli  --url https://ropsten.infura.io/v3/acb534b53d3a47b09d7886064f8e51b6  \
--privateKey deb3c81d1db67ec23671e3ea648348e716a09a541de54315cf5df362a02666d3 \
--gasPrice 10000000000 bridge register-generic-resource \
--bridge 0xFFfE10DA4373A12Fb14dE9d900465d65FFD3E37e \
--handler 0x68AEFd8c6f380e34d33F41c6c6af955Df4934Df4 \
--resourceId 0x000000000000000000000000000000c76ebe4a02bbc34786d860b355f5a5ce20 \
--execute 0x02c0ab3b \
--targetContract 0x11f565667a9b3da6cbc843624a1293aad8534a2a

output：
Registering generic resource ID 0x000000000000000000000000000000c76ebe4a02bbc34786d860b355f5a5ce20 with contract 0x11f565667a9b3da6cbc843624a1293aad8534a2a on handler 0x68AEFd8c6f380e34d33F41c6c6af955Df4934Df4
Waiting for tx: 0xd9708f0a299e22224e3360ec628acfd5adf62b5ea38a47cc332f89f2d46d3cd7...