# mst-codemod-to-0.10
A codemod to migrate to MobX-State-Tree 0.10 from previous versions

**How to run the codemod?**

The codemod is provided as npm package command line tool. It has been written using the TypeScript parser, so it will succefully support either TS or regular JavaScript source files.

To run the codemod, you need to first install it globally by `npm install -g mst-codemod-to-0.10`.
After that, the `mst-codemod-to-0.10` command will be available in your command line.

To perform the codemod, you need to call in your command line `mst-codemod-to-0.10` followed by the filename you want to codemod. A `.bak` file with the original source will be created for backup purposes, and the file you provided will be updated to the new syntax! Have fun!

PS: You could also use `npx` instead of installing the codemod globally! :)