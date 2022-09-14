This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, install the required dependencies for this project.

#### System Requirements:
- GIT
- Node v14 or higher
- NPM or Yarn (Yarn is preferred)

After the system requirements are installed, clone this project.

Then, run the project installation:
```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the home page by modifying `pages/index.js`. The page will hot-reload as you edit the file.

The [PokéApi](https://pokeapi.co/) can be accessed through a local API route [http://localhost:3000/api/pokemon](http://localhost:3000/api/pokemon). Requests to this route will proxy the same endpoint from the public API. For example: [http://localhost:3000/api/pokemon/bulbasaur](http://localhost:3000/api/pokemon/bulbasaur) will return the results from [https://pokeapi.co/api/v2/pokemon/bulbasaur](https://pokeapi.co/api/v2/pokemon/bulbasaur).

## Assigment

Use the PokéApi via the proxy endpoint ([http://localhost:3000/api/pokemon](http://localhost:3000/api/pokemon)) to build a Pokédex (list of Pokémon).

The design of the Pokédex is up to you, but the Pokédex should initially show a list of at least 20 Pokémon names.

Each Pokémon should be selectable, and when selected, the Pokédex should display the following attributes for the selected Pokémon:
- Name
- Height
- Weight
- Types (name)
- Abilities (name)

Example data using [bulbasaur](https://pokeapi.co/api/v2/pokemon/bulbasaur):
- Name: bulbasaur
- Height: 7
- Weight: 69
- Types: grass, poison
- Abilities: overgrow, chlorophyll
# HelloAliceRuthTakeHome
