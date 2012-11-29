gddns
===================
A Gehirn DNS API simplification client.  
It potential for Dynamic Domain Name System (DDNS).  

Function
-------------------
+ Gehirn DNS API Control
  + DNS A Record Update (Not add)

Usage
-------------------
+ Setting up to `config`  
 `token` => Gehirn DNS API Token  
 `secret` => Gehirn DNS API Secret  
 `domain` => Domain (e.x. example.com)  
 `record` => Record (e.x. abcd.example.com.)  

+ Running to gddns  (Default your global IP address) 
 `gddns`  
    + Appoint a IP address
      `gddns 123.456.78.9`

Notes
-------------------
+ Logged file to `gddns.log`  
  Logging on fatal / warning only.

+ Using gems
  + `rest-client`
  + `nokogiri`

License
-------------------
+ Please read `LICENSE`.

