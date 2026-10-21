# Contributing to restaurant

Thank you for contributing to **restaurant**!

## Development Workflow
1. Fork the repository on GitHub.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/restaurant.git
   cd restaurant
   ```
3. Create a descriptive feature branch:
   ```bash
   git checkout -b feature/my-feature-name
   ```
4. Install dependencies:
   ```bash
   npm install
   ```
5. Verify changes locally before submitting:
   ```bash
   npm test --if-present
   ```
6. Commit changes with clear, descriptive commit messages.
7. Open a GitHub Pull Request against `main`.

## Pull Request Guidelines
- Ensure automated CI workflows pass.
- Adhere to the project's [Code of Conduct](CODE_OF_CONDUCT.md).
- Do not check in private credentials, API keys, or large binaries.
