# Tech Enterprise Labs Documentation

This repository contains the general documentation of the Tech Enterprise Labs solution. Its the starting pointing for
new developers, reviewers and end users.

## Documentation Strategy

The documentation strategy is based on this simply rule:

> Every documentation that only relates to a component that lives inside a single repository will be placed in that 
repository under the `/doc` folder as Markdown files.

Documentation that relates to components that goes across repositories will be placed in this repository. This will 
include:

- Overview of each lab or application in the solution.
- Dependencies between components in different repositories.
- General coding decisions for the backend components.

The entire frontend is placed in its own repository, so all documentation for this component will be placed in the 
that repository.

## Repositories

| Name                                                                            | Description                                                                        |
| ------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| [tel-doc](https://github.com/sunepoulsen/tel-doc)                               | This repository                                                                    |
| [tel-core-backend](https://github.com/sunepoulsen/tel-core-backend)             | Libraries for core functionality for all backends that is written with Spring Boot |
| [tel-helloworld-backend](https://github.com/sunepoulsen/tel-helloworld-backend) | The Helloworld backend                                                             |
| [tel-monopoly-backend](https://github.com/sunepoulsen/tel-monopoly-backend)     | The Monopoly backends for the Monopoly App                                         |
