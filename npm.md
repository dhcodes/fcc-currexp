# Node Modules with npm

The Node Package Manager (npm) is a command-line tool used by developers to share and control modules (or packages) of Javascript code written for use with Node.js.

When starting a new project, npm generates a <code>package.json</code> file. This file lists the package dependencies for your project. Since npm packages are regularly updated, the <code>package.json</code> file allows you to set specific version numbers for each dependency. This ensures that updates to a package don't break your project.

npm saves packages in a folder named <code>node_modules</code>. These packages can be installed in two ways:

1. globally in a root <code>node_modules</code> folder, accessible by all projects.
2. locally within a project's own <code>node_modules</code> folder, accessible only to that project.

Most developers prefer to install packages local to each project to create a separation between the dependencies of different projects.
