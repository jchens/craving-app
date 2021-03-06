# Craving
Find a food truck, calm a craving.

[Final report of our design process](http://web.stanford.edu/class/cs147/projects/ArtsCulture/Craving/reports/final.pdf)

[Experience the hi-fi prototype here](https://expo.io/@jchens/Craving)

## Imagine this
It’s lunch time. You just got out of a late class and you’re starving. But you’re sick of Coupa, you’re out of meal plan dollars – it’s not going well. So where do you go?

### Enter, food trucks.

Food trucks, serving good, cheap, and convenient food, are perfect for on-the-go college students and working young adults. But due to their changing schedules and locations, they’re sometimes hard to find. But, there isn’t an existing food truck finder app. So we decided to build one, redesigning the food discovery process to focus on connecting consumers to food trucks they love.

- Find & track trucks near you
- Read reviews that aren’t just a wall of text
- Be rewarded with discounts

![Craving Features](https://github.com/jchens/craving-app/blob/master/App/Images/mockup.png "Craving Features")



## Installation Instructions

Download the .zip from our website, and navigate to the folder containing the project:
```
npm install react-native-maps --save

npm install --save react-native-elements@beta

npm install yarn add react-native-typography

npm install --save react-native-modal-datetime-picker

npm install --save react-navigation

npm install --save react-native-snap-carousel

npm i -S react-native-multiple-tags

npm install --save react-native-progress-bar-animated

npm install --save react-native-onboarding-swiper

npm install --save react-native-tag-autocomplete

npm install react-native-popup-menu --save

expo start
```
Afterwards, scan the QR code with your phone (and install Expo if needed) to see our prototype!

## Operating Instructions
No special operating instructions.

## Implementation Limitations
- The prototype does not contain concepts of user accounts
  - Onboarding happens every time you launch the prototype
- All of the data in the app is hard-coded (dates, locations, profiles, etc.) 
  - Search on the map is hard-coded
- Changes in state do not persist across different views
  - I.e. following/unfollowing a truck does not persist, setting a reminder does not persist
  - Users can go through the flow of adding a review, but the review data is not saved anywhere and the screen does not update to include the user’s review
- Users can add duplicate tags to a review; there is no edge case handling
- We envisioned many animated transitions (between screens, when overlays pop up, etc) that were not implemented


## 3rd Party Components used

Used `npm install react-native-maps --save` to use [the Google Maps API](https://github.com/react-native-community/react-native-maps).

Used `npm install --save react-native-elements@beta` to use [React Native Elements](https://react-native-training.github.io/react-native-elements/docs/getting_started.html).

Used `npm install yarn add react-native-typography` to use [React Native typography](https://github.com/hectahertz/react-native-typography).

Used `npm install --save react-native-modal-datetime-picker` to [pick a date & time](https://github.com/mmazzarolo/react-native-modal-datetime-picker).

Used `npm install --save react-native-modal-datetime-picker` to [implement the bottom navbar](https://github.com/react-navigation/react-navigation).

Used `npm install --save react-native-snap-carousel` to [implement the photo carousel](https://www.npmjs.com/package/react-native-snap-carousel).

Used `npm i -S react-native-multiple-tags` to [implement the review tags](https://github.com/caleb-tolu/react-native-multiple-tags).

Used `npm install --save react-native-progress-bar-animated` to [implement the progress nar](https://www.npmjs.com/package/react-native-progress-bar-animated).

Used `npm install --save react-native-onboarding-swiper` to [implement the onboarding swiper](https://www.npmjs.com/package/react-native-onboarding-swiper/v/0.10.0).

Used `npm install --save react-native-tag-autocomplete` to [implement the tag system](https://github.com/JoeRoddy/react-native-tag-autocomplete).

Used `npm install react-native-popup-menu --save` to [implement the popup](https://github.com/instea/react-native-popup-menu/blob/HEAD/doc/examples.md).

Allow usage of location from instructions [here](https://stackoverflow.com/questions/48157185/info-plist-file-for-react-native-ios-app-using-expo-sdk?noredirect=1&lq=1).

