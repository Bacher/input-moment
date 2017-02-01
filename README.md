# input-moment
React datetime picker powered by [momentjs](http://momentjs.com).

This repository is fork of [wangzuo/input-moment](https://github.com/wangzuo/input-moment).

The design is from [dribbble](https://dribbble.com/shots/1439965-Due-Date-and-Time-Picker).

### Installation
``` sh
npm i --save awesome-react-datetime
```

**Notice:** This module requires [moment](https://www.npmjs.com/package/moment) as a [peerDependency](https://docs.npmjs.com/files/package.json#peerdependencies).

### Usage
``` javascript
<InputMoment
  moment={this.state.moment}
  onChange={this.handleChange}
  onSave={this.handleSave}
  prevMonthIcon="ion-ios-arrow-left" // default
  nextMonthIcon="ion-ios-arrow-right" // default
/>
```
Check [app.js](https://github.com/wangzuo/input-moment/blob/master/example/app.js) for a working example.

### Development
- npm install
- npm start
- http://localhost:8888

### License
ISC
