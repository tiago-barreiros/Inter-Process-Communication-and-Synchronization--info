# Inter-Process-Communication-and-Synchronization

Tiny Web server
Dave O'Hallaron
Carnegie Mellon University

This is the home directory for the Tiny server, a 200-line Web
server that we use in "15-213: Intro to Computer Systems" at Carnegie
Mellon University.  Tiny uses the GET method to serve static content
(text, HTML, GIF, and JPG files) out of ./ and to serve dynamic
content by running CGI programs out of ./cgi-bin. The default 
page is home.html (rather than index.html) so that we can view
the contents of the directory from a browser.

Tiny is neither secure nor complete, but it gives students an
idea of how a real Web server works. Use for instructional purposes only.

The code compiles and runs cleanly using gcc 2.95.3 
on a Linux 2.2.20 kernel.

To install Tiny:
   Type "tar xvf tiny.tar" in a clean directory. 

To run Tiny:
   Run "tiny <port>" on the server machine, 
	e.g., "tiny 8000".
   Point your browser at Tiny: 
	static content: http://<host>:8000
	dynamic content: http://<host>:8000/cgi-bin/adder?1&2

Files:
  tiny.tar		Archive of everything in this directory
  tiny.c		The Tiny server
  Makefile		Makefile for tiny.c
  home.html		Test HTML page
  godzilla.gif		Image embedded in home.html
  README		This file	
  cgi-bin/adder.c	CGI program that adds two numbers
  cgi-bin/Makefile	Makefile for adder.c

SisOps.

## Equipa de Desenvolvimento

[![Diogo Carvalho](https://avatars.githubusercontent.com/u/44882507?s=100&v=4)](https://github.com/carvalho28)| [![João Marques](https://avatars.githubusercontent.com/u/76715591?s=100&v=4)](https://github.com/vmkalima) |[![Tiago Barreiros](https://avatars.githubusercontent.com/u/78179371?s=100&v=4)](https://github.com/tiago-barreiros)
---|--------------------------------------------------------------------------------------------------------------|---
[Diogo Carvalho](https://github.com/carvalho28)| [João Marques](https://github.com/vmkalima)                                                         |[Tiago Barreiros](https://github.com/tiago-barreiros)

# Orientação

## [Prof. Doutor Paul Crocker](https://www.it.pt/Members/Index/577)

## *Sistemas Operativos* @[Universidade da Beira Interior](https://www.ubi.pt/).

<!-- 
### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>
-->

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- CONTACT -->
## Contact

<div> 
   <a href = "mailto:tiago.m.barreiros@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/tiago-barreiros/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
   <a href="https://discord.gg/537381363486031873" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a>
</div>
