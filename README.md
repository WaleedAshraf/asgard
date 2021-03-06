# Asgard
Asgard is the API and dashboard service for Payload applications.

## Installation
1. Set up the project with `git clone https://github.com/payloadpk/asgard.git && cd asgard && npm install`
2. Set up the environment variables specified in `config/index.js`, or create and add them to `config/configOverrides.js`.
3. Use forman to start with `foreman start` or `nf start`

## Structure
```
/
  config/
  lib/
  models/
  controllers/
  test/
```
1. `config`: all the configuration objects
2. `lib`: Libraries reused in the code
3. `models`: DB Schemas
4. `controllers`: All the controllers
5. `test`: Mocha tests

## Support
Please [open an issue](https://github.com/payloadpk/asgard/issues/new) for support or email `hey@payload.pk`.

## Contributing
Contributions are welcome! Please contribute using [Github Flow](https://guides.github.com/introduction/flow/):
1. Create a branch
2. Add commits
3. [Open a pull request](https://github.com/fraction/readme-boilerplate/compare/).

Please ensure your code is:

1. [JSHint](http://jshint.com/) Compliant
2. Documented with inline comments
