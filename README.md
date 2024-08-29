import hashlib

def hashGenerator(data):
result = hashlib.sha256(data.encode)
return result.hexdigest()

def __init__(self,data,hash,prev_hash)
    self.data=data
    self.hash=hash
    self.prev_hash=prev_hash

class block:
    def __init__(self):
hashLast=hashGenerator('gen_last')
hashStart=hashGenerator('gen-hash')

genesisBlock('gen-data', hashStart,hashLast)
self.chain[genesis]

self.add.Block(self,data):
 prev_hashLast.chain[-1].hash
 hash=hashGenerator(data+prev_hash)
 block=block(data,hash,prev_hash)
 self.chain.append(block)

bc =Blackchain()
bc.add.block('1')
bc.add.block('2')
bc.add.block('3')

for block in bc.chain:
print(block.__dict__)


    

