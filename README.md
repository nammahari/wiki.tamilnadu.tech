![wiki.tamilnadu.tech logo](static/logo.svg)

> **"ஒரே இடத்தில் அனைத்து தமிழ் திறந்த மூல கணிநுட்ப வளங்களும்."**  
> *All open-source Tamil computing resources — in one place.*

---

### About

**wiki.tamilnadu.tech** is a community-driven directory that curates and organizes open-source Tamil computing tools, datasets, fonts, libraries, and utilities — everything that helps build and grow the Tamil technology ecosystem.

Built using [dirmaker](https://pypi.org/project/dirmaker) — a simple, opinionated static site generator for publishing directory websites.

**Website:** [https://wiki.tamilnadu.tech](https://wiki.tamilnadu.tech)  
**Source:** [https://github.com/FOSSUChennai/wiki.tamilnadu.tech](https://github.com/FOSSUChennai/wiki.tamilnadu.tech)  
**License:** MIT (Code), CC BY-SA 4.0 (Content)

---

### Install

To get started with **dirmaker**, install it using pip:

```bash
pip3 install dirmaker
```
### Build Locally 

You can build the site locally using the following commands:
```bash
# Inside the project directory / edit the data.yml for any changes with the content 

nvim data.yml 

# after the changes, build the site with 

dirmaker --build
```
this will update the site/ directory

#### To preview locally 
```bash
 python -m http.server --directory site
```
then open your browser at: 
```bash
# replace the port_number
http://127.0.0.1:port_number/
```
### Contribute

We welcome contributions from developers, designers, and Tamil language enthusiasts.

To add or update any project or resource:

Edit the data.yml file — add or update your project entry.

Build the site locally with:
```bash
dirmaker --build
```

Take a screenshot of the working site showing your change.

Create a Pull Request (PR) including:

- Project name

- Short description

- Screenshot showing your update

Your contribution helps expand and strengthen the Tamil open-source ecosystem ❤️

### License
Code: [MIT License](https://github.com/FOSSUChennai/wiki.tamilnadu.tech/blob/main/LICENSE)
Content: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)


Built using [dirmaker](https://pypi.org/project/dirmaker)

Maintained by the [FOSS United Chennai
 community](https://fossunited.org/c/chennai)