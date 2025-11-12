# @umituz/react-native-design-system-organisms

Organism design components for React Native - Complex UI patterns built from atoms and molecules following Material Design 3 principles.

## ✨ Features

- 🎨 **Material Design 3** - Modern, accessible UI components
- ⚛️ **Pure React Native** - No external UI library dependencies
- 🧬 **Atomic Design** - Complex patterns (organisms) built from atoms
- 🌓 **Theme Support** - Built-in light/dark mode via `@umituz/react-native-design-system-theme`
- 📱 **Responsive** - Adaptive layouts for phones and tablets
- ♿ **Accessible** - WCAG AA compliant components
- 📦 **Zero Config** - Works out of the box
- 🪶 **Lightweight** - Smaller bundle size

## 📦 Installation

```bash
npm install @umituz/react-native-design-system-organisms
```

### Peer Dependencies

```bash
npm install @umituz/react-native-design-system-atoms @umituz/react-native-design-system-theme
npm install react@18.3.1 react-native@0.76.3 react-native-safe-area-context@^5.6.2
```

## 🚀 Usage

```typescript
import {
  ScreenLayout,
  AppHeader,
  FormContainer,
} from '@umituz/react-native-design-system-organisms';

const MyScreen = () => {
  return (
    <ScreenLayout>
      <AppHeader
        title="My App"
        leftIcon="menu"
        onLeftPress={() => {}}
      />
      <FormContainer>
        {/* Form content */}
      </FormContainer>
    </ScreenLayout>
  );
};
```

## 🧩 Components

### Available Organisms

- `ScreenLayout` - Universal screen container with safe area and scrolling
- `AppHeader` - Application header with navigation and actions
- `FormContainer` - Form layout container with keyboard handling
- And more...

## 🌓 Theme Integration

This package requires `@umituz/react-native-design-system-theme` and `@umituz/react-native-design-system-atoms`:

```typescript
import { ThemeProvider } from '@umituz/react-native-design-system-theme';
import { ScreenLayout } from '@umituz/react-native-design-system-organisms';

const App = () => (
  <ThemeProvider>
    <ScreenLayout>
      {/* Your content */}
    </ScreenLayout>
  </ThemeProvider>
);
```

## 📖 Documentation

Full documentation: [Coming Soon]

## 🤝 Contributing

Contributions welcome! This is part of the universal design system used across 100+ React Native apps.

## 📄 License

MIT © Umit Uz



