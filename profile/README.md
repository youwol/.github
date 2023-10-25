# Welcome to the YouWol GitHub Group

## About Us
YouWol is an online ecosystem designed for collaboration, library and application development,
and sharing.
It places a significant emphasis on the domains of science and engineering by offering
essential tools to optimize performance.

For a broader overview of YouWol, please visit our [WebSite](https://www.youwol.com/).

At a more detailed level, YouWol transforms web browsers into a functional operating system by:
*  Enabling seamless and transparent installation of shared libraries and applications on-the-fly.
This support extends to languages that can transpile or compile to JavaScript or WebAssembly.
Additional information can be found [here](https://webpm.org).
*  Providing an initial collection of applications and libraries that replicate the familiar user
experience of a conventional operating system, including features like a desktop and file explorer.
*  Offering a development environment that streamlines and encourages contributions to the ecosystem. 
This environment is designed to make it easier for developers to participate in enhancing the platform.

## Repositories

The most foundationnal libraries:
-  [py-youwol](https://github.com/youwol/py-youwol): 
   This library includes YouWol's backend functionalities,
   its primary focus revolves around data management, authentication, authorization, and resolving dependencies.
   It also serves as a standalone Python package and replicates all of YouWol's backends on your local PC. 
-  [k8s-deployments](https://github.com/youwol/k8s-deployments):
   This library gathers the essential configurations necessary for deploying YouWol within a 
   Kubernetes cluster. It primarily addresses Kubernetes, Helm charts, Keycloak, ScyllaDB, Minio, 
   Redis, and other related aspects.
-  [cdn-client](https://github.com/youwol/cdn-client):
   A TypeScript library and HTTP client responsible for handling the dynamic installation of 
   shared libraries directly into web browsers. 
   It accomplishes this either in the main thread or within web workers.
-  [http-clients](https://github.com/youwol/http-clients):
   A collection of HTTP clients designed to interact with YouWol's backends.
-  [flux-view](https://github.com/youwol/flux-view):
   A compact library used for constructing reactive HTML content through reactive programming.
   Its objectives align with those of solutions such as React and Vue.
-  [cdn-externals](https://github.com/youwol/cdn-externals): 
   Packages available in NPM that have been ported to WebPM (the in-browser package manager of YouWol).
-  [cdn-pyodide-loader](https://github.com/youwol/cdn-pyodide-loader): 
   Extension of the cdn-client to load python packages using [Pyodide](https://pyodide.org/en/stable/)

Additionally, we've developed several noteworthy applications, including:
-  [desktop](https://github.com/youwol/platform):
   An application that emulates a desktop-like user interface, 
   running [here](https://platform.youwol.com/applications/@youwol/platform/latest).
-  [file explorer](https://github.com/youwol/explorer):
   This is YouWol's file explorer, providing file management functionalities, 
   running [here](https://platform.youwol.com/applications/@youwol/explorer/latest).
-  [low code](https://github.com/youwol/vsf-notebook):
   A low-code solution designed for orchestrating computations and visualizations directly within the web browser,
   running e.g. running [here](https://platform.youwol.com/applications/@youwol/vsf-notebook/latest?&id=NDQ5NjQyMmMtY2MzYi00ZDg5LTgzNjctMjVhZTZiMDU5ZTY0).
-  [stories](https://github.com/youwol/stories):
   A solution for creating interactive documents, relying on a drag-and-drop web-page builder
based on [grapesJS](https://grapesjs.com/), running [here](https://platform.youwol.com/applications/@youwol/stories/latest).
-  [python-playground](https://github.com/youwol/python-playground):
   An in-browser Python Integrated Development Environment (IDE) for coding and experimentation,
   running [here](https://platform.youwol.com/applications/@youwol/python-playground/latest).


## Contribution Guidelines

We welcome contributions from the community to help improve our projects. Please take a moment to review these guidelines before contributing.

### How to Contribute
-  Fork the Repository: If you want to work on a project, fork the repository to your GitHub account.
-  Clone the Repository: Clone the forked repository to your local machine using git clone.

```
git clone https://github.com/your-username/your-fork.git
```
-  Create a Branch: Create a new branch for your contribution. Use a descriptive branch name related to the issue you're addressing or the feature you're adding.

```
git checkout -b feature-branch
```
Make Changes: Make your changes to the codebase. Please follow our coding style and guidelines.

-  Commit Changes: Commit your changes with a clear and concise commit message. Use the present tense and imperative mood (e.g., "Add feature" not "Added feature").
```
git commit -m "Add feature"
```
-  Push Changes: Push your changes to your fork on GitHub.
```
git push origin feature-branch
```
-  Create a Pull Request: Go to the original repository and create a pull request. Please provide a detailed description of your changes and reference any related issues.

-  Review and Discuss: Participate in the discussion on the pull request. Address any feedback and make additional changes if necessary.

-  Merge: Once your contribution is approved, it will be merged into the main repository.

### Code of Conduct
We have a [Code of Conduct]() that we expect all contributors to follow. 
Please review our Code of Conduct before contributing.


### Reporting Issues
If you find a bug or have a suggestion for improvement, please open an issue on our issue tracker. Be sure to provide a clear and detailed description of the problem or enhancement you're suggesting.

### Licensing
By contributing to our projects, you agree that your contributions will be licensed under the same license as the project. For more details, please see our License file.

### Help and Support
If you have any questions or need assistance, feel free to contact us through email.

## Team

- **Frantz Maerten** YouWol's CEO
    - GitHub: [GitHub Profile](https://github.com/xaliphostes)
    - Email: [Email Address](fmaerten@youwol.com)

- **Guillaume Reinisch** Maintainer - frontend
    - GitHub: [GitHub Profile](https://github.com/youwol-guillaume)
    - Email: [Email Address](greinisch@youwol.com)

- **Julien Decharne** Maintainer - backend
    - GitHub: [GitHub Profile](https://github.com/youwol-jdecharne)
    - Email: [Email Address](jdecharne@youwol.com)

- **Jehad Melhad** Maintainer - frontend
    - GitHub: [GitHub Profile](https://github.com/jehadmelad)
    - Email: [Email Address](jmelad@youwol.com)

## Contact Us


- Email: [Contact Email Address](greinisch@youwol.com)
- Website: [Organization's Website](https://youwol.com)

## Social Media

- [Twitter Profile](Link to Twitter Profile)

## License

- [MIT](https://github.com/youwol/os-core/blob/main/LICENSE)

## Events and News

[Share information about upcoming events, webinars, or conferences related to your organization. Also, link to any blog posts or news articles featuring your projects.]

- [Event Title](Link to Event Details): Date and description of the event.
- [Blog Post Title](Link to Blog Post): Summary of the blog post.


![Youwol log](https://raw.githubusercontent.com/youwol/.github/main/profile/logo_name.png)

