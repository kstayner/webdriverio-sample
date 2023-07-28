# Webdriver.io Login Test Example

This is a sample project that demonstrates how to use Webdriver.io with JavaScript to perform a login test. The test ensures that the login functionality of a web application is working as expected.

## How to Run the Tests Locally

Before running the tests, ensure you have the following requirements installed on your system:

- Node (version >= v18.17.0)
- NPM (version >= 9.6.7)
- Chrome web browser

We recommend using [NVM](https://github.com/nvm-sh/nvm) to manage your Node.js distribution. To set up your Node environment, run the following command:

```shell
nvm use
```

### Step 1: Install Dependencies

First, you need to set up the project's dependencies. Open a terminal or command prompt and navigate to the project directory. Then, run the following command:

```shell
npm install
```

### Step 2: Install Chrome Web Browser

To run the tests successfully, you need to ensure that Chrome browser version 114 is installed on your system. If you haven't installed it yet, please download and install Chrome version 114 from the official Chrome website.

### Step 3: Run the Tests

After installing the dependencies and Chrome version 114, you can execute the test suite. In the same terminal or command prompt, run the following command:

```shell
npm run wdio
```

This will trigger the execution of the test cases using Webdriver.io, and the results will be displayed in the terminal.

Please make sure you have the necessary configuration in the "wdio.conf.js" file to specify the target web application URL and other test settings.

Feel free to customize the test cases or add more tests to suit your specific use cases.

Happy testing! 🚀