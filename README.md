# ui-challange
UI code challenge.

## The task
The challenge is to achieve a responsive design as per the screens present in the assets directory. The screens are provided for 3 different resolutions. There is no need for implementing the undelying functionality.

This is a helper repo to get you started with.
Prerequisite
[Node JS](https://nodejs.org/en/). 
Steps:
```
git+https://github.com/mcmakler/ui-challange.git
cd ui-challenge
yarn
yarn serve
```
This repo uses [parceljs](https://parceljs.org/) and contains support for [SCSS](https://sass-lang.com/)
- You are free to use any framework/pre-processor.
- Use icons/assets wherever required.

## Implementation
To accomplish the challenge, use a mobile first solution. Which means write mobile styles firstly, then tablet, finally desktop.

### Breakpoints
- tablet: 768px
- desktop: 1200px

### File structure
- main.scss: the entry file
- base.scss: reset style, basic layout
- breakpoints.scss: responsive mixins
- components.scss: shared components
- mobile.scss: mobile style
- tablet.scss: tablet style
- desktop.scss: desktop style

### Third party library
Font Awesome(icon)
