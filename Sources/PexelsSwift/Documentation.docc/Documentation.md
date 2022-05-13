# ``PexelsSwift``

A Swift wrapper for the Pexels.com API.

## Overview

This Swift Package is a wrapper for [Pexels API](https://www.pexels.com/api) to get access to the entire photo library of `Pexels` within your Swift app.

> It is mandatory to get an [API Key](https://www.pexels.com/api).

## Installation (SPM)

```swift
dependencies: [
.package(url: "https://github.com/lukepistrol/Pexels-Swift.git", from: "0.1.0")
],
```

## Usage

```swift
import PexelsSwift

// access the singleton instance
let pexels = PexelsSwift.shared

// set your API key
pexels.setAPIKey("YOUR_API_KEY")

// fetch images metadata
let results = await pexels.getCuratedPhotos()
```

## Topics

### Classes

- ``PexelsSwift/PexelsSwift``

### Structures

- ``PexelsSwift/PSPhoto``
- ``PexelsSwift/PSCollectionCategory``