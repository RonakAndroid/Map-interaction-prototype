# Map interaction prototype

Map interaction for a mobile app to find what’s nearby ,
made with React Native.


Check it out on Dribbble (https://dribbble.com/shots/4984844-Map-interaction-prototype)


![image](/screenshot/preview.gif)


# Installation
`npm i mindinventory/react-native-tab-bar-interaction`

Android: `react-native run-android`

iPhone: `react-native run-ios`


# Usage

```js

import TabBar from "react-native-tab-bar-interaction";
...
  render() {
      return (
          <TabBar>
            <TabBar.Item
                icon={require('./tab1.png')}
                selectedIcon={require('./tab1.png')}
                title="Tab1"
                screenBackgroundColor={{ backgroundColor: '#008080' }}
            >
              <View>
                  {/*Page Content*/}
              </View>
            </TabBar.Item>
            <TabBar.Item
                icon={require('./tab2.png')}
                selectedIcon={require('./tab1.png')}
                title="Tab2"
                screenBackgroundColor={{ backgroundColor: '#F08080' }}
            >
                <View>
                    {/*Page Content*/}
                </View>
            </TabBar.Item>
            <TabBar.Item
                icon={require('./tab3.png')}
                selectedIcon={require('./tab1.png')}
                title="Tab3"
                screenBackgroundColor={{ backgroundColor: '#485d72' }}
            >
              <View>
                  {/*Page Content*/}
              </View>
            </TabBar.Item>
          </TabBar>
      );
    }
```

## Component props

| prop | value | required/optional | description |
| --- | --- | --- | --- |
| icon | image source | required | the icon when item is not focus |
| selectedIcon | image source | required | the icon when item is focus |
| title | string | required | title of item |
| screenBackgroundColor | string | required | background color of tab |

## Dependencies

* `geolib`
* `react-native-linear-gradient`
* `react-native-maps`
* `react-native-maps-directions`


# Changelog

### Version: 1.0

  * Initial Build



# LICENSE!

Map interaction prototype is [MIT-licensed](https://github.com/Mindinventory/react-native-tabbar-interaction/blob/master/LICENSE).

# Let us know!
We’d be really happy if you send us links to your projects where you use our component. Just send an email to sales@mindinventory.com And do let us know if you have any questions or suggestion regarding our work.
