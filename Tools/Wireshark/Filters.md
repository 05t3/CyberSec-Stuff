# Wireshark Filters

If you want to filter traffic for a specific IP address.

`ip.addr == 10.10.10.10`

You can also specify certain protocals to filter, for example:

`http`

![image](https://user-images.githubusercontent.com/58165365/145465963-7e3a8ab1-68a5-490d-b487-31c7cb7278f0.png)

In relation to the above, we can also specify a domain name to narrow down the search. i.e

`http contains tryhackme.css`

![image](https://user-images.githubusercontent.com/58165365/145466585-cc23f46d-b6c3-41d1-a4cb-c19b2ec77ed8.png)

You can also specify specific HTTP methods you want to filter. i.e

`http.request.method == GET`

![image](https://user-images.githubusercontent.com/58165365/145689759-c7289923-d37f-4bc7-9a3f-92b57d2e6d95.png)

`http.request.method == POST`

![image](https://user-images.githubusercontent.com/58165365/145689777-5587c824-a8b9-4bf6-97a9-ade6eaf2939b.png)


`tcp.port == 3389`

![image](https://user-images.githubusercontent.com/58165365/145468457-d7e55164-9132-4d1d-aad2-d911800811ff.png)


`not tcp.port == 3389`

![image](https://user-images.githubusercontent.com/58165365/145469124-6f6c2f88-ad70-452f-ab25-4f3fd7d82f3a.png)

If you want to filter DNS packets

`udp.port == 53` or `udp`

![image](https://user-images.githubusercontent.com/58165365/145690707-e53c1d53-4d11-4ea1-bb11-b2e56e8207bf.png)

![image](https://user-images.githubusercontent.com/58165365/145690723-0d0111dc-b37c-41e4-9f52-72af47dbad29.png)

If you want to filter FTP packets

`tcp.port == 21` or `ftp`

