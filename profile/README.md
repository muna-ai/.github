![Muna logo](https://raw.githubusercontent.com/muna-ai/.github/main/banner.png)

Run AI models anywhere:
```ts
import { Muna } from "muna"

// 💥 Create your Muna client
const muna = new Muna({ accessKey: "..." });

// 🔥 Run an AI model
const prediction = await muna.predictions.create({
  tag: "@fxn/greeting",
  inputs: { name: "Peter" }
});

// 🚀 Use the results
console.log(prediction.results[0])
```

We provide client libraries for the following frameworks:

- **[Muna for Python](https://github.com/muna-ai/muna-py)**
- **[Muna for JavaScript](https://github.com/muna-ai/muna-js)**
- **[Muna for Swift](https://github.com/muna-ai/muna-swift)**
- **[Muna for Android](https://central.sonatype.com/artifact/ai.muna/muna)**
- **[Muna for React Native](https://www.npmjs.com/package/@fxn/expo)**. *Coming soon*.
- **[Muna for Unity Engine](https://github.com/muna-ai/muna-unity)**
- **[Muna CLI](https://github.com/muna-ai/muna-py)**

A few useful links:

- [Join our Slack community](https://muna.ai/slack).
- [Check out our docs](https://docs.muna.ai).
- Learn more about us [on our blog](https://blog.muna.ai).
- Reach out to us at [hi@muna.ai](mailto:hi@muna.ai).

Muna is a product of [NatML Inc](https://github.com/natmlx).
