# Expo CLI Version Mismatch and Dependency Conflicts

This repository demonstrates a common issue encountered when using the Expo CLI: version mismatches between the CLI itself and the project's dependencies.  The problem manifests as unpredictable errors during build or start processes.  The `expoBug.js` file showcases a scenario where a dependency conflict occurs, while `expoBugSolution.js` provides the solution.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Attempt to run the project using `expo start`.  You should encounter an error.
4. Apply the solution demonstrated in `expoBugSolution.js`.  Verify that the project now runs successfully.

## Solution

The solution usually involves carefully examining and aligning the versions of your Expo CLI, React Native, and other related libraries using `package.json` and `package-lock.json` (or `yarn.lock`).  This might involve upgrading, downgrading, or cleaning the cache.