# Function

![function logo](https://raw.githubusercontent.com/fxnai/.github/main/logo_wide.png)

[![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscord.com%2Fapi%2Finvites%2Fy5vwgXkz2f%3Fwith_counts%3Dtrue&query=%24.approximate_member_count&logo=discord&logoColor=white&label=Function%20community)](https://fxn.ai/community)
[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/fxnai)](https://twitter.com/fxnai)

Run Python functions (a.k.a. "predictors") locally on Android, iOS, macOS, Linux, in the browser, and Windows--with full GPU acceleration and zero dependencies:
```ts
import { Function } from "fxnjs"

// 💥 Create your Function client
const fxn = new Function({ accessKey: "..." });

// 🔥 Run predictions on-device
const prediction = await fxn.predictions.create({
  tag: "@fxn/greeting",
  inputs: { name: "Peter" }
});

// 🚀 Use the results
console.log(prediction.results[0])
```

> [!TIP]
> [Join our waitlist](https://fxn.ai/waitlist) to bring your custom Python functions and run them on-device across Android, iOS, macOS, Linux, web, and Windows.
> 
You can make on-device predictions using our client libraries:

- **[Function for Python](https://github.com/fxnai/fxn)**. Make predictions in your Python, FastAPI, Flask, and Django apps.
- **[Function for JavaScript](https://github.com/fxnai/fxnjs)**. Make predictions in your web, Node.js, Next.js, and React apps.
- **[Function for Android](https://central.sonatype.com/artifact/ai.fxn/fxn)**. Make predictions in your Kotlin and Java Android apps. *Coming soon*.
- **Function for iOS**. Make predictions in your iOS, iPadOS, and macOS Catalyst apps. *Coming soon*.
- **[Function for React Native](https://www.npmjs.com/package/react-native-fxn)**. Make predictions in your React Native apps for iOS and Android. *Coming soon*.
- **[Function for Unity Engine](https://github.com/fxnai/fxn3d)**. Make predictions in your Unity apps and games.
- **[Function CLI](https://github.com/fxnai/fxn)**. Make predictions in the command line.

A few useful links:

- [Join our Discord community](https://discord.gg/fxn).
- [Check out our docs](https://docs.fxn.ai).
- Learn more about us [on our blog](https://blog.fxn.ai).
- Reach out to us at [hi@fxn.ai](mailto:hi@fxn.ai).

Function is a product of [NatML Inc](https://github.com/natmlx).
