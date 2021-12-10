# Wireshark Filters

If you want to filter traffic for a specific IP address.

`ip.addr == 10.10.10.10`

You can also specify certain protocals to filter, for example:

`http`

![image](https://user-images.githubusercontent.com/58165365/145465963-7e3a8ab1-68a5-490d-b487-31c7cb7278f0.png)

In relation to the above, we can also specify a domain name to narrow down the search. i.e

`http contains tryhackme.css`

![image](https://user-images.githubusercontent.com/58165365/145466585-cc23f46d-b6c3-41d1-a4cb-c19b2ec77ed8.png)



`tcp.port == 3389`

![image](https://user-images.githubusercontent.com/58165365/145468457-d7e55164-9132-4d1d-aad2-d911800811ff.png)


`not tcp.port == 3389`

![image](https://user-images.githubusercontent.com/58165365/145469124-6f6c2f88-ad70-452f-ab25-4f3fd7d82f3a.png)
