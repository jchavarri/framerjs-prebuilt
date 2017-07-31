# framerjs-prebuilt

Prebuilt versions of FramerJS. 

This project is forked from [jchavarri/framerjs-prebuilt](https://github.com/jchavarri/framerjs-prebuilt) which appears to have gone quiet for the time being. Keeping it up to date here. If you notice it's behind, please send a pull request!

## How to Update
1. You're going to need a Mac
2. Make sure you have the latest Node and NPM
3. Fork [FramerJS](https://github.com/koenbok/Framer)
4. Run `make dist` to build the latest version
5. Copy `version.coffee`, `framer.js`, and `framer.js.map` into your branch in the [framerjs-prebuilt](https://github.com/joetheday/framerjs-prebuilt) repository
6. Each commit message points to the Framer commit used for that version. (If you still have questions, see previous commit messages).
7. Send a pull request
