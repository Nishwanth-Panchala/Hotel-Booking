# Stay Booker Pro

Stay Booker Pro is a production-ready hotel booking website built with modern web technologies. It provides a fully functional and responsive web application designed for hotel booking services. The project ensures an elegant user experience with its intuitive interface and robust performance.

## Key Features

- **Production-Ready**: Designed to meet production-level standards.
- **Modern Tech Stack**: Built using **React.js**, **Tailwind CSS**, and **MirageJS** for API mocking.
- **Skeleton Loading**: Enhances user experience with skeleton screens during data fetching.
- **Responsive Design**: Mobile-first responsive layout using Tailwind CSS.
- **Comprehensive Testing**: End-to-end test coverage using **Cypress**.
- **Continuous Integration (CI)**: Automated testing and build checks using **GitHub Actions**.
- **Pre-Commit Hooks**: Maintains code quality with Husky and ESLint.

For the backend API, check out the [Stay Booker Express API](https://github.com/Nishwanth-Panchala/Hotel-Booking.git).

---

## Table of Contents
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running the Tests](#running-the-tests)
- [Code Quality](#code-quality)
- [GitHub Workflow](#github-workflow)
- [Contributing](#contributing)
- [Future Scope](#future-scope)
- [License](#license)

---

## Getting Started

### Prerequisites
Ensure you have the following installed before starting:

- **Node.js** (v18 or higher)
- **npm** or **yarn**

### Installation

1. Clone the repository:
    ```bash
    git clone (https://github.com/Nishwanth-Panchala/Hotel-Booking.git)
    ```

2. Navigate to the project directory:
    ```bash
    cd Hotel-Booking
    ```

3. Install dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

4. Start the development server:
    ```bash
    npm start
    # or
    yarn start
    ```

The application will be available at [http://localhost:3000](http://localhost:3000).

---

## Running the Tests

Comprehensive end-to-end tests have been written using **Cypress**. To run the tests:

```bash
npm test
# or
npx cypress open
```

This will open the Cypress test runner, where you can execute specific tests or run the entire suite.

---

## Code Quality

Stay Booker Pro uses **ESLint** and **Prettier** for maintaining code quality. Ensure your code follows the defined linting standards using the following command:

```bash
npm run lint-fix
```

This command will automatically fix common linting errors. Address any remaining issues manually if required.

---

## GitHub Workflow

The project has a GitHub Actions workflow for continuous integration. The workflow includes:

1. **Build**: Ensures the app builds successfully on every push or pull request.
2. **Code Quality Check**: Runs Prettier to maintain code consistency.
3. **Run Tests**: Executes all Cypress test cases.

This automated workflow helps maintain application stability and reliability.

---

## Contributing

We welcome contributions to Stay Booker Pro! If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch with a descriptive name.
3. Commit your changes with clear messages.
4. Push your branch and create a pull request.

### Code Quality and Linting
Before submitting a pull request, ensure your code passes the linting checks using:

```bash
npm run lint-fix
```

If necessary, you can bypass linting using the `-n` flag, though this is discouraged:

```bash
git commit -m "Your commit message" -n
```

---

## Future Scope

- Backend integration using Express.js.
- Enhanced booking features and improved user experience.
- Payment gateway integration.
- User authentication and authorization.

---

## License

This project is licensed under the **MIT License**. See the LICENSE file for details.

