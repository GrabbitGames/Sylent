# Vexxed Browser: An Enhanced Chrome-Like Web Proxy

Vexxed Browser offers a UI reminiscent to Google's Chrome Browser, but is specifically designed to circumvent internet censorship as a web-proxy.

&nbsp;  

![Alt Text](https://github.com/jinjinjojo/jinjinjojo.github.io/blob/main/standard.gif?raw=true)

## Customization

To modify the bare server configuration of Vexxed Browser, navigate to the file `/prox/uv/uv.config.js`. Here, adjust the "bare" parameter to align with the location of your selected server. Bare server requires a node.js runtime, which is why it is externally hosted. 

This customization feature ensures that any Bare Server can be seamlessly integrated with this proxy, even locally-run ones. 

However, please note that in order for Vexxed Browser to function correctly, the vexxed-browser files must be hosted externally—it does not function in a local environment.

## Installation

Vexxed Browser operates as a fully static solution, eliminating the need for Node.js or Server-side rendering.

Put simply, to install: either fork this repository or download the vexxed-browser files from this repository, navigate to any of the services listed below, and import or transfer the files to a new project. Then, open up the created project's url, and vexxed-browser should be ready to go. 

Vexxed Browser is compatible with any static website hosting service, including platforms such as Vercel, Netlify, Glitch.com, Google Cloud, Render, Github Pages, Cloudflare Pages, and more.

## Acknowledgments

The development of Vexxed Browser has been made possible through the contributions of the following sources:

- **Ultraviolet Proxy**: [https://github.com/titaniumnetwork-dev/Ultraviolet](https://github.com/titaniumnetwork-dev/Ultraviolet).

- **Making Ultraviolet Static**: [TIW-UV-Static](https://github.com/TheTIW/UV-Static).

- **Browser Functionality**: [Rammerhead](https://github.com/binary-person/rammerhead).

- **Bare Server by TompHTTP**: [Bare-server-node](https://github.com/tomphttp/bare-server-node)

- **Google Clone**: [Google-search-clone](https://github.com/naemazam/Google-search-clone).

## Error Info

If you get a "Not Found" error, it most likely means the bare server cannot be reached. In this case, change the bare server using the instructions listed above.

---

### Official Active Links As Of 8/9/2023

[https://vexxed.vercel.app](https://vexxed.vercel.app)

[https://jinjinjojo.github.io](https://jinjinjojo.github.io)

[https://vexxed.glitch.me](https://vexxed.glitch.me)

[https://vexxed.pages.dev](https://vexxed.pages.dev)

[https://vexxed.static.app](https://vexxed.static.app)

[https://vexxed.netlify.app](https://vexxed.netlify.app)
