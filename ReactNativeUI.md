# React Native UI – Research Notes

## What is it?
- Framework by Facebook for mobile apps (iOS + Android).  
- Uses **JavaScript + React**.  
- UI = how the app looks + user interaction.  

---

## Key Points
- Uses **native components** (Text, Button, View).  
- Layout with **Flexbox** (like CSS).  
- Styles in **JS objects** (via `StyleSheet`).  
- **Cross-platform** → mostly same code for iOS/Android.  
- Can reuse components.  

---

## Common UI Components
- **Text** → display text.  
- **View** → container.  
- **Button** → clickable button.  
- **Image** → show pictures.  
- **TextInput** → user typing.  
- **ScrollView/FlatList** → scroll + lists.  

---

## Pros
- One codebase = faster dev.  
- **Hot reload** → see changes quickly.  
- Native look & feel.  
- Lots of UI libraries (Paper, NativeBase, Elements).  

---

## Cons
- Sometimes slower than pure native apps.  
- Might need platform-specific tweaks.  
- For advanced UI → need some native knowledge.  

---

## Example Code (Minimal)

```javascript
import React from 'react';
import { Text, View, Button } from 'react-native';

export default function App() {
  return (
    <View style={{ flex: 1, justifyContent: 'center', alignItems: 'center' }}>
      <Text>Hello React Native!</Text>
      <Button title="Click Me" onPress={() => alert('Pressed!')} />
    </View>
  );
}
```

---

## References
- [React Native Official Docs](https://reactnative.dev/)  
- [Wikipedia – React Native](https://en.wikipedia.org/wiki/React_Native)  
- [Dev.to – Guide to React Native](https://dev.to/asif-estiak/a-comprehensive-guide-to-react-native-building-cross-platform-apps-with-ease-31fn)  
- [iTitans – Cross-Platform Apps with React Native](https://ititans.com/blog/cross-platform-apps-with-react-native/)  
- [Celadonsoft – Best Practices in React Native](https://celadonsoft.com/best-practices/react-native-for-cross-platform/)  