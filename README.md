# Firestore Security Rules and Indexes Extension

# Firestore Security Rules and Indexes

Syntax highlighting, code completions and hover help for new [Firestore security rules](https://cloud.google.com/firestore/docs/reference/security/) and [index definitions](https://cloud.google.com/firestore/docs/reference/rest/v1beta1/projects.databases.indexes).  Name files with the extension `.rule` or `.rules` to activate.  The priority for [additional rules language features](https://code.visualstudio.com/docs/extensionAPI/language-support) in roughly the order I'll get to them, if ever, is &hellip;

-  [x] Syntax Highlighting
-  [x] [Code Completions](#code-completions)
-  [x] [Hover Definitions](#hover-definitions)
-  [ ] Snippets
-  [ ] Signature Helpers
-  [ ] Incremental Formatting
-  [ ] Rule validation (moonshot)

### Rules

![rules completions](./images/rules-completions.gif)

![rules hovers](./images/rules-hovers.gif)

### Index Definitions

![index completions](./images/index-completions.gif)

![index hovers](./images/index-hovers.gif)

# Building and Packaging

To build and package this extension into a `.vsix` file:

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Compile TypeScript:**
   ```bash
   npm run compile
   ```

3. **Package the extension:**
   ```bash
   npm run package
   ```

This will create a `.vsix` file in the project root that can be installed in VS Code using:
```bash
code --install-extension vsfire-*.vsix
```

# Status

See the [repository milestones](https://github.com/toba/vsfire/milestones) for issues I expect to resolve in coming releases.
