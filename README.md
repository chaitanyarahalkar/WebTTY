# WebTTY


A Swiss Army knife that provides secure tunnels to localhost and allows you to share your terminal as a web application.

<img src="icon.png" height="200">


### What is WebTTY? 

WebTTY is a lightweight commandline utility that allows you to share applications and serivces running on localhost to the Internet. 

WebTTY is not just that! It is a bundle of many more features and thus is rightly called the Swiss Army knife.

- Terminal Mirroring: Mirror your terminal for others to see. The terminal is served in a web browser and anyone accross the globe with a generated URL can view your terminal through the web browser.

- Multi shell Spawning: A new terminal instance is spawned for every link opened in the browser. This allows multiple developers to work independently.

- File sharing for everyone: Why involve a third party drive service, when WebTTY can allow others to directly download files from your computer? WebTTY makes file sharing a breeze. It creates a HTTP Server and generates a URL, sharing it will allow others to download files <i> directly </i> from your computer. You can add a password to your file sharing URLs to protect your files from an adversary. 

- Remote SSH: Others can SSH into your machine without the hassle of port forwarding and dynamic DNS handling. WebTTY does it all for you! Share the unique link with others and you are good to go.  

- Easy web development: With WebTTY, sharing your web application running on localhost feels like a dream come true! You can share your work with your peer developers working anywhere in the world. 


### Who can use WebTTY? 

WebTTY is for everyone! Teachers can mirror their terminals for students to learn; spawn multiple shells for students to have hands-on experience even without having the required environment on their computer. Developers can work collaboratively by tunneling localhost. Machine Learning enthusiasts and data scientists can share their Jupyter Notebooks running on localhost! File sharing for everyone. From a developer to an ordinary computer user, WebTTY extends its features to all.  


### Building from Source

Building WebTTY requires you to download the Python modules mentioned in the requirements.txt. Currently it is built in Python 2, and will be ported soon to Python 3. 
Download them with - 

```bash

webtty@webtty$ pip install -r requirements.txt

```

After all the modules are installed successfully, run WebTTY with - 

```bash

webtty@webtty$ python2 run.py 

```

### How does WebTTY work?

WebTTY uses <b>Web Sockets</b> for asynchronous communication with the terminal running on your machine. It uses [HTTP Tunneling](https://en.wikipedia.org/wiki/HTTP_tunnel) to forward network packets of other services like SSH over the HTTP. WebTTY bypasses Firewall restrictions that prevents [port forwarding](https://en.wikipedia.org/wiki/Port_forwarding) for machines inside a secure network. 


### Things Yet to be Implemented 

- Freezing the Python code into a running executable, which will eliminate the need of installing the Python dependencies.
- Making the binary executable on all platforms.

### Author

 **Chaitanya Rahalkar**

* Twitter: [@chairahalkar](https://twitter.com/chairahalkar)
* Github: [@chaitanyarahalkar](https://github.com/chaitanyarahalkar)

 **Dhaval Gujar**

* Twitter: [@dhvlgjr](https://twitter.com/chairahalkar)
* Github: [@dhavalgujar](https://github.com/dhavalgujar)

#### Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/chaitanyarahalkar/WebTTY/issues).

#### Show your support

Give a ⭐️ if this project helped you!

#### License

Copyright © 2019 [Chaitanya Rahalkar](https://github.com/chaitanyarahalkar).<br />
This project is [MIT](https://github.com/chaitanyarahalkar/WebTTY/blob/master/LICENSE) licensed.





