## CONTRIBUTING.md

We're happy you're interested in contributing to this Rust chat app! This document outlines the guidelines for submitting pull requests, code style conventions, and testing procedures.

**Getting Started**

Before diving in, ensure you have the following:

* **Rust and Cargo:** Install Rust and Cargo following the official guide: [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install)
* **Git:** Familiarize yourself with Git version control basics. 

**How to Contribute**

1. **Fork the Repository:**
    - Visit the project repository on GitHub and click "Fork." This creates your own copy of the codebase.

2. **Clone Your Fork:**
    - Open your terminal and navigate to your desired local directory.
    - Clone your forked repository using the following command, replacing `your-username` with your GitHub username:

      ```bash
      git clone [https://github.com/](https://github.com/)<your-username>/rust-chat-app.git
      ```

3. **Create a New Branch:**
    - Navigate to the cloned repository directory:

      ```bash
      cd rust-chat-app
      ```

    - Create a new branch for your specific contribution:

      ```bash
      git checkout -b your-branch-name
      ```

4. **Make Changes:**
    - Edit the relevant files according to your contribution.
    - Adhere to the code style conventions outlined below.

5. **Commit Your Changes:**
    - Stage your changes for commit using:

      ```bash
      git add .
      ```

    - Optionally, stage specific files using `git add <filename>`.

    - Commit your changes with a descriptive message:

      ```bash
      git commit -m "Your commit message here"
      ```

6. **Push Your Changes:**
    - Push your changes to your forked branch:

      ```bash
      git push origin your-branch-name
      ```

7. **Create a Pull Request:**
    - Visit your forked repository on GitHub and navigate to the "Pull requests" tab.
    - Click "New pull request" and select your branch and the main branch of the upstream repository.
    - Provide a clear and concise description of your changes in the pull request description.
    - Click "Create pull request" to submit your contribution for review.

**Code Style**

- Use consistent formatting and indentation.
- Adhere to Rust's official formatting guidelines: [https://github.com/rust-lang/rustfmt](https://github.com/rust-lang/rustfmt)
- Consider using a Rust linter like `rustfmt` or `clippy` to enforce style and identify potential issues.

**Testing**

We value well-tested code. It's recommended to:

- Write unit tests for your changes using a testing framework like `cargo test`.
- Consider adding integration tests to ensure different components work together seamlessly.
- Execute existing tests before submitting your pull request.

**Additional Notes**

* Feel free to open an issue if you encounter any problems or have questions.
* We appreciate clear and concise pull requests with well-written commit messages.
* Be respectful and professional in all communication.

**License**

This project is licensed under the MIT License. For full details, please refer to the `LICENSE` file.

**Thank you for your contributions!**
