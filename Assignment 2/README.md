## What is NPM?
 -  is a package manager and a software register but it's also a place where developers can find, build and manage code packages
 - https://www.npmjs.com/

##  What is `Parcel/Webpack`? Why do we need it?
- Parcel and Webpack are bundlers that can help improve web development workflows. Both are used for JavaScript or Typescript code. They minify, clean, and make code compact so that it's easier to send or receive requests and responses from a server. 
- Webpack allows developers to define custom HMR behavior through **Hot Module Replacement** API, whereas
- Parcel handles HMR automatically without requiring any additional configuration.

- **Hot Module Replacement (HMR)** exchanges, adds, or removes modules while an application is running, without a full reload.

- https://kinsta.com/blog/rollup-vs-webpack-vs-parcel/#:~:text=Webpack%2C%20a%20widely%20recognized%20and,small%20projects%20and%20rapid%20prototypes.

## What is `.parcel-cache`
 - The .parcel-cache directory is a cache that stores intermediate build results created by the Parcel bundler.
- **dont push this folder into the github** repo when we run the project it will generated automatically.
## - What is `npx` 
- NPM is a package management that is used to **install, uninstall, and update Javascript packages** on your workstation, whereas NPX is a **package executer** that is used to directly execute Javascript packages without installing them

## - What is difference between `dependencies` vs `devDependencies`
-  dependencies are packages that are required for an application to run in production. DevDependencies are packages that are only needed for local development and testing.