# Alejandro Manzano's webpage

Manzano is the source code for the personal website of Alejandro Manzano. Built with [Hugo](https://gohugo.io/) and using the [triple-hyde theme](https://github.com/derme302/triple-hyde) as a submodule, this repository powers a site designed to showcase Alejandro’s publications, portfolio, and more.

> Note: This project is configured in Spanish (Mexico) and tailored for a personal website, including menu items such as "Sobre mi", "Publicaciones", and "Portafolio". The configuration file (hugo.toml) contains details for social accounts and external links to Alejandro’s projects and publications.

## Installation

To get started with Manzano locally, follow these steps:

1. **Clone the Repository**

Clone the repository recursively to initialize the theme submodule:

`git clone --recurse-submodules https://github.com/LinkSake/manzano.git`

If you have already cloned the repository without submodules, initialize them with:

`git submodule update --init --recursive`

2. **Install Hugo**

If you haven’t already, install Hugo (version 0.80 or later is recommended).

3. **Run the Development Server**

Navigate into the project folder and start the Hugo server:

```
cd manzano
hugo server
```

Open your browser and visit `http://localhost:1313` to view the site.
