## Example of a proton-native package with native dependecies (keytar)

To reproduce issue run on windows platform

```
npm i
npm run dist
```

See https://github.com/electron-userland/electron-builder/issues/3736
for issue details.

Here is the sample app http://github.com/yrik/broken-native.
It consists of a basic app made with create-proton-app and keytar as a
dependency (npm i --save keytar). I have built it on appveyer (see conf inside)
for win x86. The result is not functional, it throws an error: `The specified procedure could not be found`
