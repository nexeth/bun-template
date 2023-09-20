# @nexeth/bun-template

<p align="center">
  <a href="https://bun.sh"><img src="https://user-images.githubusercontent.com/709451/182802334-d9c42afe-f35d-4a7b-86ea-9985f73f20c3.png" alt="Logo" height=170></a>
</p>


Welcome to the Bun project template repository! This template provides a starting point for creating new projects using [bun](https://bun.sh/). With bun, you can quickly build modern JavaScript and TypeScript applications.

## Features

- **Bun Ready:** This template is preconfigured with Bun, a fast and simple framework for building web applications.

- **ESLint Integration:** Ensure code quality with ESLint, including TypeScript support and a pre-configured set of rules.

- **Test Coverage:** Run tests with coverage reports to ensure your application is well-tested.

## Getting Started

### Install bun

If you haven't already, install bun. Follow the directions [here](https://github.com/oven-sh/bun)

### Create a new project

To create a new project using this template, follow these steps:

1. Click the "Use this template" button at the top of the repository to create a new repository based on this template.

2. Clone your newly created repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-new-project.git
   cd your-new-project
   ```

Install project dependencies:

```bash
bun install
```

Start building your Bun project by modifying the index.ts file and adding your application code.

### Linting

To lint your code:
```
bun lint
```

### Tesing

To run tests:
```
bun test
```


## Directory Structure
The project template follows a typical directory structure for Bun projects:

- `index.ts`: The entry point for your application.
src/: Directory for your application source code.
tests/: Directory for your tests.
- `.eslintrc.cjs`: ESLint configuration file.
- `package.json`: Project configuration, including scripts and dependencies.
- `/modules`: Contains the modules you are creating
- `/types`: Contains TypeScript types that are shared across your repository
- `/test`: Contains tests for the modules you have created


## Contributing
If you have suggestions, bug reports, or would like to contribute to this project template, please open an issue or submit a pull request on the GitHub repository.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

