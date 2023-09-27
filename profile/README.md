# Function

![function logo](https://raw.githubusercontent.com/fxnai/.github/main/logo_wide.png)

[![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscord.com%2Fapi%2Finvites%2Fy5vwgXkz2f%3Fwith_counts%3Dtrue&query=%24.approximate_member_count&logo=discord&logoColor=white&label=Function%20community)](https://fxn.ai/community)

Run AI prediction functions (a.k.a. "predictors") on mobile, web, and in the cloud--all from a `predict` function in a Jupyter Notebook. [Go from this](https://github.com/fxnai/fxn/blob/main/examples/stable-diffusion.ipynb):
```py
pipeline = DiffusionPipeline.from_pretrained("runwayml/stable-diffusion-v1-5", torch_dtype=float16)

def predict (prompt: str):
    # Generate an image using Stable Diffusion
    return pipeline(prompt).images[0]
```

To this:

![prediction](https://raw.githubusercontent.com/fxnai/.github/main/predict.gif)

If you don't have your own predictor, or don't know how to create one, you can use any of the [available predictors on Function](https://fxn.ai/explore). You can make predictions using our client libraries:

- **[Function for Python](https://github.com/fxnai/fxn)**. Make predictions in your Python, FastAPI, Flask, and Django apps.
- **[Function for JavaScript](https://github.com/fxnai/fxnjs)**. Make predictions in your web, Node.js, Next.js, and React apps.
- **[Function for Unity3D](https://github.com/fxnai/fxn3d)**. Make predictions in your Unity apps and games.
- **[Function for CLI](https://github.com/fxnai/fxn)**. Make predictions in the command line.
- **[Function for Slack](https://api.fxn.ai/slack/install)**. Make predictions in your Slack conversations with the `/predict` slash command.
- **[Function for Discord](https://fxn.ai/discord)**. Make predictions in your Discord server with the `/predict` slash command.

We have clients for iOS (Swift) and Android (Java/Kotlin) coming soon! A few useful links:

- [Join our Discord community](https://fxn.ai/community).
- [Check out our docs](https://docs.fxn.ai).
- Learn more about us [on our blog](https://blog.fxn.ai).
- Reach out to us at [hi@fxn.ai](mailto:hi@fxn.ai).

Function is a product of [NatML Inc](https://github.com/natmlx).
