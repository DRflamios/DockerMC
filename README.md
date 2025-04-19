# MC Server Docker

Here is a very simple docker-compose file you can use to host a Minecraft Java Server.
it use the [itzg/minecraft-server](https://hub.docker.com/r/itzg/minecraft-server) docker image.

## Tips for non-tech users

if you are not a technical user, here is some tips to host a server using this docker-compose:

- Use Linux if you host it on a server like a VPS. Linux is free and open-source, and often used for servers.
I recommend using Debian or debian-based distro like Ubuntu Server. It is free and easy to use.
- Protect your server with a firewall like ufw. if you only host a minecraft server, you will need to open ports 25565, 25575 (for rcon) and 22 for SSH.
- Make sure you do not allocate more RAM that you have on your server.

## Contact

if you have questions, security reports, or issues, feel free to open a GitHub issue.