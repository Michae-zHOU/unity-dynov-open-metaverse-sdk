# Samples

This folder can be used to store example projects etc.
This folder is ignored for NPM in [.npmignore file](../.npmignore).

# Running package tests

You can store sample project here to run your packages tests on,
since Unity does not provide standalone package testing solution.

1. Create new Unity project
2. Import your package in manifest.json and mark it as testable:

```json
{
  "dependencies": {
    "com.Virtual-Dynamic-Labs.unity-dynov-open-metaverse-sdk": "https://github.com/Virtual-Dynamic-Labs/unity-dynov-open-metaverse-sdk.git"
  },
  "testables": [ "com.Virtual-Dynamic-Labs.unity-dynov-open-metaverse-sdk" ]
}
```
