# Basic Typescript Template

## Development Modules
- `@types/node`
- `typescript`
- `ts-node`
- `gts` *handle project linting*
- `nodemon` *watch files and restart on changes*

run `npm install` to install all listed modules

## Commands
### Development
- ### `npm run dev`
  start `app.ts` with `ts-node` (without precompiling)

- ### `npm run lint`
  lint project with [gts](https://github.com/google/gts)

- ### `npm run fix`
  automatically solve liniting problems if possible

- ### `npm run clean`
  clear build files

- ### `nodemon`
  lint project and start `app.ts` with automatic restart on file changes



### Production
- ### `npm run prod`
  compile and run for production

- ### `npm run compile` and `npm run start`
  to manually compile and start for production
