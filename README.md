# KIE UX Sandbox
This is the Red Hat UXD team's project for JBoss BPM/BRMS design documents and user interface prototypes.

Designs and prototypes are available at [https://kiegroup.github.io/kie-uxd-sandbox/](https://kiegroup.github.io/kie-uxd-sandbox/)

## File Structure
Designs are located in subfolders under /design. Supporting graphics are located in /images folders within those folders.

HTML prototypes are located in /prototype with a folder for each separate prototype. HTML files are at the top level, with less files in /less. CSS will be generated and placed in the /css folder.

Note: The layouts and assets folders are used to style the Github Pages site.

## Design Contributions
[Get started with SourceTree](https://www.sourcetreeapp.com/)

Then refer to the excellent [instructions on Patternfly Design] for details about how to [set up SourceTree](https://github.com/patternfly/patternfly-design/wiki/Git-Setup) to get a local copy of this repository and then [make a contribution](https://github.com/patternfly/patternfly-design/wiki/Contribution-Workflow).

To [work on multiple features at once](https://github.com/patternfly/patternfly-design/wiki/Multiple-Branches), branches can be created to encompass both the design and implementation of a feature.

## Implementation Contributions
Developers should first clone the repository. Then,
- Create a copy of the `/prototype/example` directory.
- `cd` into the cloned directory.
- Run `npm install`.
- Run the server using `gulp`.
The project will automatically open in the browser, and changes will be shown immediately.
