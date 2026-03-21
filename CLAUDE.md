# augmented-reality
v0.1.0

## Rules
- Project scope: ARKit-based AR app in Swift.
- SwiftUI + RealityKit
- iOS 17+, @Observable
- xcodegen for project generation
- no emojis

## Run
```bash
xcodegen generate
xcodebuild -scheme augmented-reality -destination 'platform=iOS Simulator,name=iPhone 17 Pro'
```

## Key Files
- `Sources/App.swift` -- App entry point
- `Sources/ARViewContainer.swift` -- ARView wrapped for SwiftUI
- `Sources/PlaneDetection.swift` -- Horizontal/vertical plane detection
- `Sources/ObjectPlacement.swift` -- 3D object placement on surfaces
- `Sources/GestureHandler.swift` -- Tap, drag, pinch gestures
