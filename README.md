# npm-versioning
## Steps
1. Add `preid` to `npm version` command
   ```bash
    npm version [premajor | preminor | prepatch | prerelease] --preid=pre
    ```
2. Publish the prerelease package
    ```bash
     npm publish --tag pre
     ```
## Reference
1. (Best practice for creating modern npm package)[https://snyk.io/blog/best-practices-create-modern-npm-package/]
2. (Stackoverflow: How to publish a package on npm)[https://stackoverflow.com/questions/50846170/how-to-generate-npm-release-candidate-version]
3. (npm version)[https://docs.npmjs.com/cli/version]
4. (npm publish)[https://docs.npmjs.com/cli/publish]
