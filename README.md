# Navigation with URL

A small JavaScript single-page site that switches between Home, About, Services, and Contact views using URL hash navigation.

## Requirements

- Node.js and npm
- `live-server` installed globally to use the `npm run serve` script

Install the project dependencies:

```sh
npm install
```

Install the server command if it is not already available:

```sh
npm install --global live-server
```

## Run the project

In one terminal, compile Sass and keep the CSS updated while editing:

```sh
npm run compile
```

In another terminal, serve the project:

```sh
npm run serve
```

Open the local URL printed by `live-server`. The navigation links update the URL hash (`#home`, `#about`, `#services`, or `#contact`), and the matching page module is rendered inside the main content area.

## Project structure

```text
app/       Application startup and hash-change routing
css/       Compiled stylesheet served by the page
images/    Image assets
model/     Page selection and rendering
pages/     Home, About, Services, and Contact content
scss/      Sass source files
index.html Application entry point
```

The compiled stylesheet is kept in `css/` because `index.html` loads it directly. Run `npm run compile` after changing the Sass sources.


## Project Link
https://in-info-web4.luddy.indianapolis.iu.edu/~ccucuiet/N315/nav-homework/