# Getting Started
To get started, you need to install two things: the React Native SDK, and a suitable IDE.

## Installing React Native
1. Go here: https://facebook.github.io/react-native/docs/getting-started.html
2. Click the `Building Projects with Native Code` tab.
3. Follow the instructions for your `Development OS` and _BOTH_ the `iOS` and `Android` OSes.

## Installing an IDE
Any text editor will do for the IDE, but the leading contenders seem to be: [Deco](https://www.decoide.org/) (acquired by Airbnb & open sourced), [Expo](https://expo.io/) (free easy-mode IDE), and [Nuclide](https://nuclide.io/) (what Facebook uses; it's difficult to get your head around, but very powerful).

After a few days of research, I'm opting for Nuclide.

### Installing Nuclide
1. Go here and follow the instructions: https://nuclide.io/docs/quick-start/getting-started/

## Notes
- Live/Hot Reloading only works with one simulator at a time.
- Your Android simulator needs to be running _before_ you execute `react-native run-android` - but the same is not true for `react-native run-ios` (it will start the simiulator for you).
