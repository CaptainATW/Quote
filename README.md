<img
    align="right" alt="title" width="200px"
    src="https://github.com/CaptainATW/Quote/blob/fefc5123ca6df6da60a54e9a142e277267e19bba/logo.png"
/>

# Quote, an assessment utility tool.

Quote is simple. Highlight a question, copy it, and the **answer will show up on the bottom of your screen**.
Use it however you want, whether it be a studying assistant, an alternative to google, or to use on quizes/tests.

## Installation

To install Quote, please go to the [releases page](https://github.com/CaptainATW/Quote/releases), or build it yourself from source.
**You will need an OPENAI API key if you want to utilize GPT-4 Turbo**

### Building with Gradle

- `git clone` the project, this can be achieved by installing [git][git], then running

```bash
git clone https://github.com/CaptainATW/Quote.git
git submodule update --init --recursive
```

- **UN*X**

```bash
cd CaptainATW && chmod +x ./gradlew && ./gradlew agent
```

- **Windows**

```cmd
cd CaptainATW && .\gradlew.bat agent
```

## Contributing

We welcome contributions from anyone interested in improving Quote. If you find a bug or have an idea for a new
feature, feel free to submit a pull request.

---
