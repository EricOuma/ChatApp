https://medium.com/swlh/lets-write-a-chat-app-in-python-f6783a9ac170

We will be using TCP sockets for this purpose, and therefore we use AF_INET and SOCK_STREAM flags. We use them over UDP sockets because they’re more telephonic, where the recipient has to approve the incoming connection before communication begins, and UDP sockets are more post-mail sort of thing (anyone can send a mail to any recipient whose address s/he knows), so they don’t really require an establishment of connection before communication can happen. Clearly, TCP suit more to our purpose than UDP sockets, therefore we use them. You can know more about sockets https://en.wikipedia.org/wiki/Network_socket.

