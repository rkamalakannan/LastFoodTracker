# Active Context: Billa Store Locator Mobile App

## Current State

**Project Status**: ✅ Mobile app created with React Native + Expo

The project is a React Native mobile app built with Expo SDK 56 that helps users find Billa stores with last-day expiring offers (30% off stickers in physical stores).

## Recently Completed

- [x] Created React Native project with Expo (mobile/billa-app)
- [x] Added react-native-maps for map display
- [x] Added expo-location for user location
- [x] Built store locator screen with interactive map
- [x] Added mock Billa store data for Austria (Vienna, Graz, Linz, Salzburg, Innsbruck)
- [x] Implemented distance calculation and sorting by proximity
- [x] Added visual indicators for stores with expiring offers (30% off badge)
- [x] Fixed TypeScript errors and passed typecheck
- [x] Web export builds successfully
- [x] Initialized git repository and committed changes

## Current Structure

| File/Directory | Purpose | Status |
|----------------|---------|--------|
| `mobile/billa-app/src/app/index.tsx` | Main store locator screen with map | ✅ Complete |
| `mobile/billa-app/src/data/stores.ts` | Mock store data & distance logic | ✅ Complete |
| `mobile/billa-app/src/constants/theme.ts` | Theme colors, spacing, fonts | ✅ Complete |
| `mobile/billa-app/src/app/_layout.tsx` | Stack navigation layout | ✅ Complete |
| `mobile/billa-app/package.json` | Dependencies & scripts | ✅ Complete |

## Key Features Implemented

1. **Map View**: Interactive map showing nearby Billa stores with markers
2. **User Location**: Gets current location via expo-location (with fallback to Vienna)
3. **Store List**: Scrollable list of stores sorted by distance
4. **Expiring Offers Badge**: Red "30% Off Today" badge on stores with expiring offers
5. **Store Details**: Shows store name, address, and distance from user
6. **Map Interaction**: Tap store in list to center map on that store

## Tech Stack

- **Framework**: React Native with Expo SDK 56
- **Routing**: Expo Router (Stack navigation)
- **Maps**: react-native-maps with Google Maps provider
- **Location**: expo-location
- **Language**: TypeScript (strict mode)
- **Styling**: StyleSheet with themed colors
- **Package Manager**: bun

## Session History

| Date | Changes |
|------|---------|
| 2026-06-04 | Created mobile app with store locator feature |

## Next Steps (Future Enhancements)

- [ ] Add real Billa store API integration
- [ ] Add user submissions for expiring offers
- [ ] Add push notifications for nearby expiring offers
- [ ] Add product-level detail (which specific products have 30% off)
- [ ] Add offline support with cached store data
- [ ] Add search/filter functionality