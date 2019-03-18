curl http://localhost:8888/v1/chain/get_info

{"server_version":"ea08cfd3","chain_id":"cf057bbfb72640471fd910bcb67639c22df9f92470936cddc1ade0e2f2e7dc4f",
"head_block_num":348,"last_irreversible_block_num":347,"last_irreversible_block_id":"0000015b27ac0a2b3797aacb3fe754634c1dfa262ece4773945c386b0c81f15f",
"head_block_id":"0000015cd0b3dd316c9385b3a7bb1b66f5bf92a5fe54945d4da9fe5b6248805f",
"head_block_time":"2019-03-17T15:16:46.000","head_block_producer":"eosio","virtual_block_cpu_limit":282806,
"virtual_block_net_limit":1483594,"block_cpu_limit":199900,"block_net_limit":1048576,"server_version_string":"v1.5.0"}



cleos --url https://jungle2.cryptolions.io:443 get info
{
  "server_version": "686f0deb",
  "chain_id": "e70aaab8997e1dfce58fbfac80cbbb8fecec7b99cf982a9444273cbc64c41473",
  "head_block_num": 18893680,
  "last_irreversible_block_num": 18893352,
  "last_irreversible_block_id": "01204a28892ac2b17daa7db344e23c37c643831297593357746401aa1e58418f",
  "head_block_id": "01204b709b11de03e0f141bf8ddc6d1125cfa384f6f8a7f4c7b58ab2bbc67b5e",
  "head_block_time": "2019-03-17T21:41:59.000",
  "head_block_producer": "jungleswedem",
  "virtual_block_cpu_limit": 200000000,
  "virtual_block_net_limit": 524288000,
  "block_cpu_limit": 199349,
  "block_net_limit": 523984,
  "server_version_string": "v1.7.0"
}



cleos --url https://jungle2.cryptolions.io:443 system listproducers
Producer      Producer key                                              Url                                                         Scaled votes
lioninjungle  EOS5g7gVXGeQVCTNW7U3gxeBJuvzvkmbCLioNqTUPYLjQXFGfQXfo     https://cryptolions.io                                      0,1588
alohaeostest  EOS7r5MsqVU5x9N95crSXbELK48MasNT1Daq9FQsW97wRJDM595wb     https://www.alohaeos.com/                                   0,0376
mosquitometa  EOS5YB3npnbWxVZqXUi7tVHLoPwjq67WRHaNELEkgqQyYrPALZjiq     https://eosmetal.io                                         0,0369
ohtigertiger  EOS7tigERwXDRuHsok212UDToxFS1joUhAxzvDUhRof8NjuvwtoHX     https://cryptolions.io                                      0,0367
eosphereiobp  EOS7TTJ2LsMPbCPsRJSxL2PhhHBqg8xNfV3MtBcx7gzYxH27YGSHh     https://eosphere.io                                         0,0365
junglesweden  EOS79e4HpvQ1y1HdzRSqE1gCKhdN9kFGjjUU2nKG7xjiVCakt5WSs     http://zverige.com/kingkong/                                0,0362
eosdacserval  EOS5CJJEKDms9UTS7XBv8rb33BENRpnpSGsQkAe6bCfpjHHCKQTgH     https://eosdac.io                                           0,0361
eos42panther  EOS8hPoDfJWxAHSkBkYH8fhkcjAz7a3yQ85W3L8RgwBw5aBt92vDQ     https://eos42.io/                                           0,0361
junglemorpho  EOS796kTMQF9sTjFz6cRftBXpxfH4aRSkSt9XSUV9hRxyxFkVgA2y     https://eoscostarica.io                                     0,0361
tokenika4tst  EOS6wkp1PpqQUgEA6UtgW21Zo3o1XcQeLXzcLLgKcPJhTz2aSF6fz     https://tokenika.io/                                        0,0361
eosbarcelona  EOS8N1MhQpFQR3YABzVp4woPBywQnS5BunJtHv8jxtNQGrGEiTBhD     https://eos.barcelona                                       0,0361
eosnationftw  EOS8YhQPU6agWNfXYswnyM5fLaLecoriyD1H5Ckr3R95Z38eWZ9qg     https://bp.eosnation.io                                     0,0361
eoscafeloons  EOS6XgXr6zGhyk6p2rSHrizUYCnhHCMjz3NuvBFGRATLUueBFC2tv     https://eoscafeblock.com                                    0,0361
atticlabjbpn  EOS5hVMcN6UVWtrNCxdp5HJwsz4USULmdfNA22UDyjRNdprXEiAP6     https://AtticLab.Net                                        0,0361
blockchained  EOS6VG88TsufLFhHYJscqXYQWFWgDCHUBYtvk6eXvpxEuYV9MUKGk     https://eos.blckchnd.com                                    0,0357
eosiodetroit  EOS5KoSVp3ktJ6BZ8G5gdAg19BwtUrmJDbAZ73KYip3uqrjnhSQby     http://eosdetroit.io                                        0,0357
jungleswedem  EOS79e4HpvQ1y1HdzRSqE1gCKhdN9kFGjjUU2nKG7xjiVCakt5WSs     http://zverige.com/kingkong/                                0,0356
ysignnodeacc  EOS7J7Wj23H7GPhR5kqy56GP3Nc6BZZPd1WXnVBARgyJ1h2HNzmPD     https://ysign.io                                            0,0350
gnuargentina  EOS84gipb2XWGZfVmm1jrYnTVNeS45Pq5pk3VN9Yk8wAyHGDKUJG2     https://eosargentina.io                                     0,0349
eosamsterdam  EOS65kKLaG5gqjHqqa6accj96Qsf2BcP4h9tqw423u9HbywpMhMBJ     https://eosamsterdam.net/                                   0,0325




cleos --url https://jungle2.cryptolions.io:443 get account vordynsk1212
created: 2019-03-17T21:29:42.000
permissions: 
     owner     1:    1 EOS7yznJmLRJU2q7sCpfAqSVt8SqSHHJEkuo7tiuGEmeW2xSxUz4F
        active     1:    1 EOS7yznJmLRJU2q7sCpfAqSVt8SqSHHJEkuo7tiuGEmeW2xSxUz4F
memory: 
     quota:     5.343 KiB    used:     3.365 KiB  

net bandwidth: 
     staked:          1.0000 EOS           (total stake delegated from account to self)
     delegated:       0.0000 EOS           (total staked delegated to account from others)
     used:                 0 bytes
     available:        133.3 KiB  
     limit:            133.3 KiB  

cpu bandwidth:
     staked:          1.0000 EOS           (total stake delegated from account to self)
     delegated:       0.0000 EOS           (total staked delegated to account from others)
     used:                 0 us   
     available:        48.81 ms   
     limit:            48.81 ms   

EOS balances: 
     liquid:          100.0000 EOS
     staked:            2.0000 EOS
     unstaking:         0.0000 EOS
     total:           102.0000 EOS

producers:     <not voted>


cleos wallet create_key

Created new private key with a public key of: "EOS7yz***********************meW2xSxUz4F"

top 21 BP here:
https://eosauthority.com/producers_rank










formula for the vote decay:
https://www.eoscanada.com/en/how-is-your-vote-strength-calculated-on-eos

What is the language of writing smart contracts for EOS?
C++

What is Stake?
Used in two ways: 1) Your total EOS token holding is referred to as your stake. 2) Synonym for delegate.
delegate:
Tokens on the EOS network can have two states, delegated and undelegated.
When a token is delegated, it provides an allocation of network resources for an account.
You can delegate resources towards your own account, or to another account, using your tokens. (also known as stake)

What is a Vote decay?
In order to maintain maximum voting influence each voter will have to re-assert their vote every week.
Voting influence decays with a half-life of 1 year for those who do not keep their votes up to date.

Who are Block Producers?
Block Producers are teams around the world who create the blocks that make up the EOS blockchain.
They are elected by the EOS token holders. 21 Block Producers create blocks, while a list of Standby Block Producers
Another name that is commonly used is Supernode.

What is dapps?
This is a short-hand for the term decentralized application or distributed application.
A dApp is any application which operates on a decentralized network.
The purest form of a dApp is one which is deployed to the network and then operates without any central parties.

Permission EOS? What are the standard ones?
As EOSIO operates with an account structure - a new feature amongst blockchains - a user can assign a unique permission
structure to their account to delegate authority over different functions.
For example, this can be used to increase security around more sensitive actions, such as transferring tokens,
while not being as worried about securing a private key that can only be used to interact with a specific on-chain game.

What is proxy accounts?
The term proxy can be used in two distinct definitions:

1. A user is registered as a proxy by calling the `regproxy` action, and can now have other users voting weight delegated along with their vote.

2. The actual act of delegating your vote towards another account. If a user does not want, or have the available time,
to research which Block Producers should receive their vote (but still wants to participate in voting),
they can proxy their vote strength towards another account. 
