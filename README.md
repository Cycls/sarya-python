<p align="center">
<img style="height: 75px;" src="https://www.sarya.com/img/logo.svg" alt="logo" />
<!-- <img style="height: 75px;" src="https://www.sarya.com/img/sarya.svg" alt="sarya" /> -->
</p>


<p align="center">
<b>Sarya - Generative UI for your AI</b>
<br/><br/>
Design, publish, and share customer facing AI apps with Sarya ⚡️
</p>

<p align="center">
<a href="https://sarya.com/docs" target="_blank"> Docs </a>
|
<a href="https://sarya.com" target="_blank"> Homepage </a>
|
<a href="https://platform.sarya.com" target="_blank"> Platform </a>
</p>

```bash
pip install sarya
```

## Example

```python
from sarya import Sarya, UI

sarya = Sarya("SECRET")

@sarya.name("@my-app")
def ai():
    return UI.Text("Hello World!")

sarya.run()
```


## Features
- **100% control over your code**: Maintain your app logic and data on your infrastructure.
- **Bring Your Own LLM**: Flexibility in LLMs, use OpenAI or any open source alternative.
- **Generative UI**: Quickly build powerful UIs that integrate seamlessly with your AI logic.
- **Instant sharing**: Instantly share your customer-facing AI app.
- **Data & analytics**: Measure app's performance. Use data to finetune AI for better results.
- **Cross-platform**: Sarya currently is web-based. Mobile support for iOS and Android is underway.
- **Multimodal I/O**: Starting with text input, and expanding to voice, image, and video data inputs.




