# Mission 7 — How Computers Communicate

## 1. Task / objective

The objective was to understand basic network concepts, check network connectivity and DNS lookup using Terminal, and explain what happens when a website is opened.

## 2. Work completed

- Explained LAN, MAN, WAN, DNS, router, protocol, packet switching and client-server.
- Tested connectivity to `example.com` using ping.
- Used nslookup to find the IP addresses of `example.com`.
- Wrote the steps involved in opening a website.

## 3. Commands / tools used

| Command / tool | Purpose |
|---|---|
| `ping -c 4 example.com` | Tests connectivity by sending four packets. |
| `nslookup example.com` | Looks up the IP addresses associated with a domain name. |
| Terminal | Used to run the network commands. |

## 4. My understanding

- LAN covers a small area, MAN covers a city or large campus, and WAN covers large geographical areas.
- DNS translates domain names into IP addresses.
- A router connects networks and forwards data.
- Protocols are rules used for communication.
- Packet switching divides data into smaller packets.
- In a client-server model, the client requests a service and the server provides it.

### What I observed

The ping test transmitted 4 packets and received all 4, with 0% packet loss. The average response time was 8.879 ms.

The DNS lookup for `example.com` returned these IP addresses:

- 104.20.23.154
- 172.66.147.243

The DNS server used was 8.8.8.8.

A connectivity test helps check whether a destination can be reached. A DNS lookup displays the IP address associated with a domain name. DNS helps the browser locate a website using its domain name.

## 5. What happens when you open a website?

1. The user enters a website name in the browser.
2. The browser acts as a client and requests the website.
3. DNS finds the IP address associated with the domain name.
4. The request travels through the network and router.
5. The server receives and processes the request using network protocols.
6. The server sends the requested data back in packets.
7. The browser receives the response and displays the website.

## 6. Difficulties faced

No major difficulties.

## 7. How I resolved them

Not applicable.

## 8. Evidence / files

- `network-concepts.txt` — Explanations of the eight network concepts.
- `README.md` — Mission documentation and network observations.

## 9. Commit details

To be added after committing and pushing this mission.
