## Alternatives
There are a few alternatives to Jenkins and GitHub Actions.
1. All-in-One platforms (integrated with Git Hosting):
- GitLab CI/CD which has a single .gitlab-ci.yml file for configuration. It is either SaaS or Self-Hosted.
- Bitbucket Pipelines which is SaaS (cloud-only), which has a bitbucket-pipelines.yml configuration file. It is a good choice if the team and project is already heavily invested in the Atlassian ecosystem (Jira, Confluence, Bitbucket).
- Azure DevOps Pipelines, which is an extremely mature platform. Integrates well with Azure cloud services. A good choice for Enterprises using Azure.

2. Standalone SaaS Platforms, which are third-party services that you connect to your Git repository:
- CircleCI is known for performance, caching, and dev productivity features. Startups and tech-forward companies seem to favor it.
- Travis CI was an open-source pioneer for CI systems, and remains a simple and straightforward option for OS projects or teams looking for easy-to-configure CI systems.

3. Self-Hosted and Hybrid Solutions:
These tools give full control over your build environment, which is crucial for security, compliance, or specialized hardware needs.

- TeamCity, known for being primarily UI-driven making it easy to visualize complex build pipelines and dependencies. Known for reliability and support for Java and .NET ecosystems.
- Buildkite is a hybrid model which offers a managed UI and the security/flexibility of running builds on your own hardware (source code never leaves the network). Ideal for companies with strict security requirements or those needing to run builds on custom hardware (mobile, game development, ML)

## Build Tools

In a MERN stack using JavaScript or TypeScript, there are a few standard tools for taking care of certain tasks:
- Linting: ESLint. The standard JavaScript linter. Detects syntax and style issues, enfroces rules.
- Testing: 
1. Unit Testing - Jest
2. End-to-End Testing - Playwright
- Building: 
1. Frontend(React): Vite/Webpack. Bundlers for building production-ready React apps.
2. Backend(Node/Express): tes/esbuild/Babel. Used to transpile TypeScript or modern JS for Node.
3. Environment Management: dotenv. Loads environment variables for both dev and build time.
4. Task Running/Scripts: npm scripts/pnpm/yarn. Orchestra builds and tests.