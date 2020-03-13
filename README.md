# COVID Alert

- `/app` - Expo React Native App for end-users
- `/dashboard` - Create React App with Firebase cloud functions for an API and admin dashboard
- `/designs` - All the related design files
- `/package` - A small NPM package with two functions. One is for turning GPS coordinates into a sector, row, and column. The other is for turning a row and column into a 0/1 tensor.

## Getting `app` to work

The dashboard and package directories mostly speak for themselves. To get the app to run, run the following lines:

1. `yarn install`
2. `react-native link`
3. `node_modules/.bin/rn-nodeify —hack —install` <-- The hack, here's an issue for whoever wants to fix this
4. If you want to install ios, run `cd ios && pod install && cd ../`
5. iOS: `yarn ios` / Android: `yarn android`

## Acknowledgements

Many people have worked on this application within the OpenMined community, many of which do not show up in the commit history. Here's a brief list (in alphabetical order):

- Amel Sellami
- Andrew Trask
- Bennett Farkas
- Héricles Emanuel
- Jose Corbacho
- Maddie Shang
- Patrick Cason
- Théo Ryffel
- Thiago Costa Porto
- Vova Manannikov
