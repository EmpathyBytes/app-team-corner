## Onboarding Resources

### General Resources:
[React Native Documentation](https://reactnative.dev/docs/getting-started)\
[React Native Navigation Guide](https://reactnavigation.org/docs/getting-started/)\
[React Native Animated](https://reactnative.dev/docs/animated)\
[React Native Firebase](https://rnfirebase.io/)\
[React Three Fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)

### Installation
1. Install [Node.js](https://nodejs.org/en/) - you need to download it from the link.
    - Or run ```brew install node``` if you’re using Homebrew
2. That really should be it to run React Native/Expo projects. This website lists the requirements for Expo - [https://docs.expo.dev/get-started/create-a-project/](https://docs.expo.dev/get-started/create-a-project/) - feel free to double check if you need to install any other tools.

### React Native
#### Onboarding Deliverable (for everyone)
As a little refresher for returning members, and an introduction for new members, everyone will be turning this little practice app in at the end of the semester as part of your deliverables.
This tutorial offers a simple and beginner-friendly walkthrough the basics of React Native development. Please watch and follow along with the video. There are extra resources below. Particularly recommend first watching the JavaScript introduction video.\
[React Native Tutorial: Learn Basics in 45 minutes](https://www.youtube.com/watch?v=Zawba2eABsU)

#### JavaScript, React, and React Native Tutorials
Little introduction to React and a reminder of JavaScript:\
[All The JavaScript You Need To Know For React](https://www.youtube.com/watch?v=m55PTVUrlnA)
- This is optional if you want to dive right into React. Fair warning, if it’s your first time with React, it will probably be confusing without watching this video.\

**[Build and Deploy a React Native App | 2023 React Native Course Tutorial for Beginners](https://www.youtube.com/watch?v=mJ3bGvy0WAY&t=887s)**\
**[React Native Tutorial for Beginners - Build a React Native App](https://www.youtube.com/watch?v=0-S5a0eXPoc&t=334s)**\
- Expo tutorials. Both are good

**[The Complete React Native Course: from Zero to Hero](https://www.youtube.com/watch?v=ANdSdIlgsEw&list=PL8kfZyp--gEXs4YsSLtB3KqDtdOFHMjWZ)**
- Okay, so I know it looks horrible because it’s a 6 hour long video...BUT you only need to start at 43:15, and you only need to watch certain sections.
	Sections to watch after 43:15 (it’s only about an hour):
  - Using the State Hook
  - Styles & Stylesheet
  - Responsive UI with Flexbox
  - List, ScrollView, and Refresh Control
  - Button, Touchables & Pressable
  - Image & ImageBackground
  - Custom Components & Props
- THAT’S ALL YOU NEED FOR NOW. We can refer to the video if there is anything we need to know in the future.

### Cloning and running our application!
**Current app:** [https://github.com/EmpathyBytes/empathy-bytes-react-native-app-23-24](https://github.com/EmpathyBytes/empathy-bytes-react-native-app-23-24) (go to branch installation-fix)
1. Feel free to clone it and look through! 
2. Install Node.js if you don’t have it already. Validate the installation using npm -v https://nodejs.org/en/download/package-manager
3. Run the command ```npm install``` after cloning the repository since we need to install dependencies. It is highly recommended to run ```npm install``` every time you pull or clone from a remote repository since dependencies can change or update over time.
4. In order to run it, you need Expo requirements: [https://docs.expo.dev/get-started/installation/](https://docs.expo.dev/get-started/installation/)
5. Install Expo Go on your phone! https://docs.expo.dev/get-started/expo-go/
6. Once you have everything installed, you can type ```npm start``` or ```npx expo start``` in the terminal in the root folder to run the application. Try not to do this in git bash as it may not load correctly. Additionally, make sure you’re connected to wifi (not data).
    - If you get a config error about not having the “expo” module, type ```npm install expo``` and try “npm start”/ “npx expo start” again.\
    - A QR code should pop up like above and you can scan it with Expo Go on your phone to pull up the application!
7. Voilà, now you should see a beautiful app. If you need any help, please don’t hesitate to reach out!

### Firebase (Backend) (potentially redo)
**React Native + Firebase:** https://rnfirebase.io/ \
**FirebaseJS SDK installation (it’s probably the best choice for Expo Go):** https://docs.expo.dev/guides/using-firebase/#using-firebase-js-sdk \
**Great video to help you connect Firebase with React Native:** https://www.youtube.com/watch?v=TwxdOFcEah4

#### Integrating 3D Models
**React Three Fiber:** https://docs.pmnd.rs/react-three-fiber/getting-started/introduction 

### Animated (Frontend)
**React Native’s built-in animation library:** https://reactnative.dev/docs/animated
**Introductory article:** https://eveningkid.medium.com/the-basics-of-react-native-animations-fb00a8ccc178
