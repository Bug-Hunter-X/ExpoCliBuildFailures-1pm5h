# Expo CLI Build Failure with metro-resolver

This repository demonstrates a bug encountered while building an Expo app using the Expo CLI. The bug manifests as inconsistent build failures, with vague error messages related to the `metro-resolver` package. Standard troubleshooting steps like cleaning the cache and reinstalling dependencies did not resolve the issue.

## Reproduction Steps

1. Clone this repository.
2. Run `yarn install` or `npm install`.
3. Try building the app using `expo start`.
4. Observe the inconsistent build failures.

## Potential Causes

* Possible issues with the `metro-resolver` package configuration.
* Conflicts between dependencies.
* Underlying issues with the Expo CLI or Node.js environment. 

## Solution (see bugSolution.js)
 The solution involved carefully reviewing and restructuring the project's dependencies, ensuring they are compatible and resolving version conflicts.  A detailed solution is given in the `bugSolution.js` file.