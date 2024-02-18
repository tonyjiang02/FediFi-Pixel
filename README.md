# AdsContainer Component Node Module

## Fedifi Pixel

This Node module provides a versatile AdsContainer component for your web applications. Easily integrate advertisements into your projects with minimal effort.

## Installation

```bash
npm install @tonyjiang02/ads-container
```

## Usage

```javascript
import AdsContainer from "@tonyjiang02/ads-container";

// Within your component render method
<AdsContainer creatorId={mastodon.social/@tonyjiang02} />;
```

## Props

- **adType** (String): Specifies the type of advertisement to display. Options include "banner", "sidebar", "popup", etc.

## Example

```jsx
import React from "react";
import AdsContainer from "@tonyjiang02/ads-container";

const App = () => {
  return (
    <div>
      <h1>Welcome to My Website</h1>
      <AdsContainer creatorId={mastodon.social/@tonyjiang02} />
    </div>
  );
};

export default App;
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
