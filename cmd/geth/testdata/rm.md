geth init --datadir ./party testdata/genesis.json 

./geth account new

0x34A5A39ed28A9905310165F08464ef3AD0b970dc

./grams-geth --datadir /home/panda/.grams --networkid 1773 --port 30308 --http --http.port 9718 --authrpc.port 8668 --http.api personal,eth,net,web3,admin,txpool,debug --cache=8000 --maxpeers 100 --syncmode full --miner.etherbase 0x34A5A39ed28A9905310165F08464ef3AD0b970dc --unlock 0x34A5A39ed28A9905310165F08464ef3AD0b970dc --password /home/panda/.elh/.elh-pw --nat any --allow-insecure-unlock --nodiscover --snapshot=false

./gram-geth attach /path/to/data/dir/geth.ipc

admin.addPeer("enode://...")

"enode://8904d18d98034bf36cc8aed2ff33fd5a59e92bcd549d5f865792ea2864170b5a88acdde54d799148071137b7ab2b9c544d82ad7354ac053fffb242e5124b3d1c@172.104.194.36:30303"

"enode://1918351925bd05be23486fe60fc4635f3a25abb424645f725848dd158985d61f608a8ba5042eb959cc59f71c5e5200e088220839fbacbdb794867f773c902aee@65.109.52.145:60606"

"enode://988c12a97ac6139a3509835ea45735f91c426ba0cb3deb69274a99c345b2e6f74189584658e47fd7d46df30f20d88c65f67f915488ca9dd5f405cd97828166a2@172.104.5.209:60606"

"enode://6434d99e663f9f37f8b3f4f0588b263c1e661b71c3d5f778d2929f3fd9ad6cccb0995ce64de0f39a55fecc1c4b2b8fd138e5541c3b9be9dffd53617c36ec92a9@5.9.151.50:60606"

"enode://7efcbba8460fdb84b1d3f148bd67d78ab5e0471f0e12d4eb572f211a0c21007eeb99ebdbb29644807c359cb999d219403d19df1c4531bb6899941d079b10c033@51.161.131.90:60606"

admin.peers <<< to show peers list






//nohup ./geth --networkid 1773  --port 30303 --http --http.port 8545 --http.addr 0.0.0.0 --http.api personal,eth,net,admin --http.corsdomain '*' --http.vhosts '*' --allow-insecure-unlock  --syncmode full --ws --ws.addr 0.0.0.0    --datadir ./party --nodiscover --mine --miner.etherbase 0x3604db9Dc197dbbcc0dbE93c469c5b7fB0B6a7e3 &

--bootnodes

172.104.194.36:30303

"enode://8904d18d98034bf36cc8aed2ff33fd5a59e92bcd549d5f865792ea2864170b5a88acdde54d799148071137b7ab2b9c544d82ad7354ac053fffb242e5124b3d1c@172.104.194.36:30303"

"enode://1918351925bd05be23486fe60fc4635f3a25abb424645f725848dd158985d61f608a8ba5042eb959cc59f71c5e5200e088220839fbacbdb794867f773c902aee@65.109.52.145:60606"

"enode://988c12a97ac6139a3509835ea45735f91c426ba0cb3deb69274a99c345b2e6f74189584658e47fd7d46df30f20d88c65f67f915488ca9dd5f405cd97828166a2@172.104.5.209:60606"

"enode://6434d99e663f9f37f8b3f4f0588b263c1e661b71c3d5f778d2929f3fd9ad6cccb0995ce64de0f39a55fecc1c4b2b8fd138e5541c3b9be9dffd53617c36ec92a9@5.9.151.50:60606"

"enode://7efcbba8460fdb84b1d3f148bd67d78ab5e0471f0e12d4eb572f211a0c21007eeb99ebdbb29644807c359cb999d219403d19df1c4531bb6899941d079b10c033@51.161.131.90:60606"
