# API
Defintions of the iReceptor API

YAML files are compatible with the online Swagger Editor. In order to view
one of the APIs in the Swagger Editor do the following:
- Copy a raw URL for one of the YAML files
  - Navigate to one of the YAML files
  - Click on the "Raw" button to generate a "Raw" URL for the file
  - Copy the URL
- Go to the swagger editor at: http://editor.swagger.io/
- Go to th File -> Import URL menu item
- Enter the URL you got above for the YAML file.

JSON files are generated by Swagger editor.


## Development Guidelines

### Git Structure

 * This project uses the Git Flow methodology for code management and development: <https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow>.

 * This project has two master branches and corresponding develop
   branches to support ongoing V1 and V2 API work. Make sure to
   double-check your branches and merge operations so the two versions
   do not get mixed up.

 * The **v1-master** branch is the master branch for ongoing V1 API
   work, with **v1-develop** as its develop branch.

 * The **master** branch is for ongoing V2 API work, with **develop** as
   its develop branch.

 * New development and features should be done on branches that are
   cloned from the **develop** (for V2) or **v1-develop** (for V1) branch,
   and then merged into this branch when completed.

 * Releases should merge **develop** into **master** (for V2) or
   **v1-develop** into **v1-master** (for V1). Tag **master** or **v1-master**
   with the appropriate version.

