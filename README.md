<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="ui_tests Logo"/>
  <h1 align="center">ui_tests: Streamline Your UI Testing Process</h1>
  <p align="center">
    A powerful tool for conducting systematic UI tests using Cypress in a seamless manner.
    <br />
    <a href="https://empress.eco/">Visit our Website</a>
    ·
    <a href="https://grow.empress.eco/">Documentation</a>
    ·
    <a href="https://github.com/empress-eco/ui_tests/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/ui_tests/issues">Request Feature</a>
  </p>
</div>

## About ui_tests

ui_tests is a robust repository tool designed to facilitate comprehensive integration tests for UI features primarily using Cypress. This tool is specially tailored for developers aiming to seamlessly implement daily UI tests via GitHub actions.

### Key Features
- Performs seamless integration tests for UI features.
- Daily automatic test runs on GitHub Actions via cron.
- Comprehensive coverage and continuous integration for your UI tests.

### Built With
The significant framework used in the project is [Cypress](https://www.cypress.io/).

## Getting Started

### Prerequisites
Before setting up ui_tests on your local machine, ensure that you have the Framework installed and set up. If not, you can follow the instructions [here](https://Empressframework.com/docs/v13/user/en/installation) to get it done.

### Installation
To set up ui_tests on your local machine, clone the repository using the following command:

```sh
git clone https://github.com/empress-eco/ui_tests.git
```

Then, follow the steps below:

```sh
# Change directory into `Empress-bench`
cd ~/Empress-bench

# Fetch `Empress` and `Empress_ui_tests` on your `Empress-bench` installation
bench get-app Empress
bench get-app Empress_ui_tests

# Create a new site and install these apps
bench new-site Empressui.test --install-app Empress Empress_ui_tests

# Add to hosts so that the site is accessible via hostname on the browser
bench --site Empressui.test add-to-hosts

# Complete setup wizard by running this command
bench --site Empressui.test execute Empress.setup.utils.before_tests

# Run the following command to open up the Cypress runner
bench --site Empressui.test run-ui-tests Empress_ui_tests
```

### Usage
After the installation, execute the Cypress runner to conduct comprehensive UI tests on your applications.

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated. Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgements

### License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgements
Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.
```
