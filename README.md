# 24kcsplus's DN42 Network

## Basic Information 基本信息

- ASN: `AS4242421347`

- DN42 IPv4: `172.23.205.96/27`

- DN42 IPv6: `fd12:7000:d0::/48`

### Contact 联系方式

Want peer or any other situation? Feel free to contact me! 想要 Peer 或是其他任何情况？欢迎随时联系我

I prefer email, so please contact me with email if you can. 我更倾向于使用邮箱，所以请先使用邮箱与我联系。 

- Telegram: 

  [@lbwnb_24k](https://t.me/lbwnb_24k)

- Email: 

  <script type="text/javascript"><!--/* Generated by www.email-encoder.com */
  for(var btcmvq=      ["aQ","Pg","bA","Mg","YQ","aQ","bw","YQ","YQ","NA","ZA","Ig","cw","bA","YQ","bQ","bw","bA","ZQ","cw","PA","bw","PA","bA","bQ","Ig","Zw","cg","NA","bQ","bQ","dQ","IA","Ig","Zg","Zw","cw","Og","YQ","Yw","dQ","Mg","cw","Ig","cA","PQ","cA","YQ","bA","Lg","dQ","bQ","aQ","Yw","cw","dA","PQ","Yw","Lg","Yw","aw","bQ","Yw","aQ","Lw","Mg","aA","bA","Pg","QA","Lg","QA","cA","cw","bQ","bw","IA","QA","aw","aQ","NA","aw","Zw","bA","Yw"],ditlqw=[54,84,68,41,53,29,79,74,10,63,38,40,24,12,1,59,33,30,5,45,0,58,81,22,73,35,51,4,17,27,52,48,36,60,6,72,70,15,83,32,23,16,20,8,46,7,21,28,55,56,69,9,37,19,49,13,39,65,77,44,64,34,78,11,82,62,3,76,61,71,31,50,67,66,80,14,2,25,43,75,42,18,26,47,57],wlwjbi=new Array,i=0;i<ditlqw.length;i++)wlwjbi[ditlqw[i]]=btcmvq[i];for(var i=0;i<wlwjbi.length;i++)document.write(atob(wlwjbi[i]+"=="));
  // --></script><noscript>Please enable JavaScript to see the email address (<a href="https://www.email-encoder.com/enablejs/" target="_blank" rel="noopener noreferrer">How-to</a>).</noscript>

## Requirements 要求

- For now, I only accept tunnel connections using WireGuard. My WireGuard AllowedIPs are as follow. 目前，我只接受使用 WireGuard 的隧道连接。我的 WireGuard AllowedIPs 如下。

  ```
  AllowedIPs = 10.0.0.0/8, 172.20.0.0/14, 172.31.0.0/16, fd00::/8, fe80::/64
  ```
  
- My network only accepts routes that are registered in DN42. 我的网络只允许接收在 DN42 中注册过的路由。

- Contact information in the registry must always be up to date and admins must respond when contacted. 在注册处的联系信息必须是有效的，且管理员在需要的时候可以联系得到。

- I do not accept to peer my mainland China's node with overseas servers. 我不接受中国大陆地区的跨境 Peer。

## Peeeing requests for manual peering 人工对等互联请求

If you want to peer with me, please send the information as follows. 如果你想要与我 Peer，请发送以下信息。

- The node you want to peer. 你想要对等互联的节点。

- Your WireGuard public key. 你的 WireGuard 公钥。

- The WireGuard endpoint for me to connect. Let me know if it's dynamic or you don't have one. 我要连接到的 WireGuard 对端。如果你的公网地址是动态的或者你没有公网地址，记得告诉我。

- The location of your node.(Accurate to city, only peer with mainland China's node). 你节点的位置（精确到城市，只在与中国大陆节点 Peer 时需要）。

- Your ASN. 你的 ASN。

- Your DN42 IP address(es). 你的 DN42 IP 地址。

- The session(s) to use: IPv6 + IPv4, IPv6 only, or IPv4 only. 要使用的会话：IPv6 + IPv4，仅 IPv6，或仅 IPv4。

E.g.:
```
Node: HKG
Public key: xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
Endpoint: your.domain.tld:21347
ASN: 4242421347
Sessions: IPv6 + IPv4
DN42 IPv6: fe80::1347
DN42 IPv4: None
```

事例：
```
节点: WGS
公钥: xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
对端: 你的域名.tld:21347
位置：海南海口
手机：13700000000
ASN: 4242421347
会话: IPv6 + IPv4
DN42 IPv6: fe80::1347
DN42 IPv4: 无
```

## Nodes 节点

### 预计上线 (Coming s∞n)

#### ITY | San Giustino, Umbria, Italy 意大利温布利亚大区圣朱斯蒂诺 | Catserver

#### HKG | Hong Kong, China 中国香港 | AWS 亚马逊云

Modified from [DN42-Info](https://github.com/Potat0000/DN42-Info)

修改自[DN42-Info](https://github.com/Potat0000/DN42-Info)
