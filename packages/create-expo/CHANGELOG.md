# Changelog

## Unpublished

### 🛠 Breaking changes

### 🎉 New features

- support GitHub URLs that don't have a protocol. ([#28435](https://github.com/expo/expo/pull/28435) by [@EvanBacon](https://github.com/EvanBacon))

### 🐛 Bug fixes

### 💡 Others

## 2.3.2 — 2024-04-24

_This version does not introduce any user-facing changes._

## 2.3.1 — 2024-04-22

_This version does not introduce any user-facing changes._

## 2.2.0 — 2024-04-18

### 🎉 New features

- Add support for GitHub URLs in `--template` option. ([#26554](https://github.com/expo/expo/pull/26554) by [@byCedric](https://github.com/byCedric))
- Add auto-configuration for pnpm and yarn berry. ([#27699](https://github.com/expo/expo/pull/27699) by [@byCedric](https://github.com/byCedric))

### 💡 Others

- Document basic assumptions about the templating system. ([#27071](https://github.com/expo/expo/pull/27071) by [@byCedric](https://github.com/byCedric))

## 2.1.4 - 2024-02-06

### 🐛 Bug fixes

- Rename templates post-extraction (rather than whilst extracting) via an internal "rename config", to avoid corrupting binary files ([#27212](https://github.com/expo/expo/pull/27212) by [@shirakaba](https://github.com/shirakaba))
- Mark compressed `.gz` files as binary to avoid corruption when unpacking with `create-expo --template` ([#26741](https://github.com/expo/expo/pull/26741) by [@shirakaba](https://github.com/shirakaba))

## 2.1.3 — 2023-12-12

### 💡 Others

- Replace `@expo/babel-preset-cli` with `expo-module-scripts`. ([#25424](https://github.com/expo/expo/pull/25424) by [@byCedric](https://github.com/byCedric))

## 2.1.2 — 2023-10-17

### 🐛 Bug fixes

- Upgrade `minipass@3.3.6` to use built-in types. ([#24402](https://github.com/expo/expo/pull/24402) by [@byCedric](https://github.com/byCedric))
- Pin `tar@6.1.13` to avoid `minipass` compatibility issues. ([#24402](https://github.com/expo/expo/pull/24402) by [@byCedric](https://github.com/byCedric))

## 2.1.1 — 2023-09-11

### 🎉 New features

- Detect bun package manager. ([#4752](https://github.com/expo/expo-cli/pull/4752) by [@colinhacks](https://github.com/colinhacks))

### 💡 Others

- Bump @expo/package-manager and update changelog. ([80c1f0e7](https://github.com/expo/expo-cli/commit/80c1f0e747615f58d51dfdd9b3e685480fdc4547) by [@brentvatne](https://github.com/brentvatne))

## 2.0.4 — 2023-08-25

### 🐛 Bug fixes

- Allow scoped template package names. ([#4752](https://github.com/expo/expo-cli/pull/4750) by [@takameyer](https://github.com/takameyer)

## 2.0.3 — 2023-06-07

### 💡 Others

- Update snapshots and list of forbidden template names. ([#4717](https://github.com/expo/expo-cli/pull/4717) by [@EvanBacon](https://github.com/EvanBacon))
- Cross deploy `create-expo` to `create-expo-app`. ([#4698](https://github.com/expo/expo-cli/pull/4698) by [@EvanBacon](https://github.com/EvanBacon))
