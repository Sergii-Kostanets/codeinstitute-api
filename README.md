1. Create a file named `.env` in the root directory of your project.

2. Add your `API_KEY_ENV` variable to the `.env` file in the format `API_KEY_ENV=your_api_key_here`.

3. Add the `.env` file to your `.gitignore` file to ensure that it is not pushed to GitHub.

4. In your code, use a library like dotenv to read the environment variables from the `.env` file. For example, in Node.js, you can install the dotenv library using `npm install dotenv`.

5. Get `API_KEY` here: [JSHint API](https://ci-jshint.herokuapp.com/)