




<!-- Anchor for the "back to top" links -->
<a id="readme-top"></a>

<!-- Project logo -->
<br />
<div align="center">
  <a href="#">
    (Insert a fancy logo here)
  </a>
  <h1>DoomerPublish</h1>
  <p>Contributing</p>
</div>

## Prerequisites
This is a list of prerequisites that must be met in order to properly install this project.
### Console application
The console application runs on .NET
- Requires a .NET SDK of atleast version 7.
- Requires Visual Studio 2022 or higher.

## Installation
1. Clone the repository: `git clone https://github.com/Devishing/DoomerPublish.git`
	- If you want to clone just the dev repository: `git clone -b dev --single-branch https://github.com/Devishing/DoomerPublish.git`.
2. Follow the instructions on setting up the project template found in `template/README.md`.
	- In order to import the tool in the template, it is also possible to `publish` the console application using the available publish template. This template is configured to place the tool in the template's `script/` folder.

### Other information.
- The API startup project should be set to `DoomerPublishTool`.
- The launch parameters have been configured with pre-defined arguments to test the tool in various ways.

## DOs and DON'Ts
Please do:
- **DO** follow the coding style of the project.
- **DO** commit changes often to keep the list of changes organized.
- **DO** commit with somewhat informative messages to make possible debugging easier.
- **DO** ensure your project runs in both DEBUG and RELEASE mode.

Please do not:
- **DON'T** make PRs for style changes unless you're hindered by it.
- **DON'T** create big pull requests unless you intended to refactor part of the application.
- **DON'T** commit code that you didn't write.
- **DON'T** submit PRs of broken code and/or code that breaks part of the application.

<p align="right">(<a href="#readme-top">back to top</a>)</p>