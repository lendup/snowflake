# Snowflake

Snowflake is Medium's tool for planning and supporting our engineers' career development. You can read more
about how we use this tool in our [growth framework documentation](https://medium.com/s/engineering-growth-framework).
Our growth tool is hosted [publicly](https://snowflake.medium.com).

![The Lannisters send their regards](https://i.imgur.com/e9DYLBr.png)

## Contributions

You are free to use, change and build on this work to make it useful for your organisation. We will happily consider
unencumbered code contributions to improve functionality, but as this is the actual tool we use within Medium, acceptance is likely to be intentional, and deliberate. Meaning, slow. As such, you may prefer to fork the codebase for your own needs. We will not accept any contributions that modify the text of the application (but, thank you in advance for pointing out any typos).

## Installation

Get yarn if you don’t have it already:

`npm install -g yarn`

Install dependencies:

`yarn`

### Running the dev server

`yarn dev`

### Building

`yarn export`

This will put a static version of the site in `out/`.

## Running with Cubicle Backend:

Run `yarn dev` to host static files on localhost:3000. Then run Cubicle on localhost:8080. For expedited development, 1. we hardcoded snowflake to make requests to localhost:8080, and 2. we made a change to Cubicle to accept requests from any origin. This is hacky and we should fix this issue.

## Future work

* Load initial data from a file, to improve flexibility.
* Add restricted job title selection and validation.
* Consider moving this tool to Cubicle completely - see the `Running with Cubicle Backend` section.

