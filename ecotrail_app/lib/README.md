# EcoTrail — Static UI (Week 14 Activity)

A two-screen non-interactive Flutter mobile UI for **EcoTrail**, a local hiking and trail-discovery application.

## Screens Included
1. `HomeScreen`: Trail discovery dashboard with greeting header, avatar status badge (`Stack`/`Positioned`), featured peak banner with gradient overlay, and three equal-width difficulty cards (`Row` + `Expanded`).
2. `DetailScreen`: Trail details view for *Mt. Pulag Summit Trail* featuring a full-bleed hero image with overlaid action icons and difficulty pill, an overlapping rounded content sheet, key route metrics, and a primary call-to-action button.

## How to Preview Both Screens
Open `lib/main.dart` and toggle the `showHomeScreen` boolean inside `EcoTrailApp.build` (line 12):
- **Screen 1 (`HomeScreen`)**: Set `const bool showHomeScreen = true;` and run the app.
- **Screen 2 (`DetailScreen`)**: Set `const bool showHomeScreen = false;` and run the app.