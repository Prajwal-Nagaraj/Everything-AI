## Kyutai's Moshi

In this folder, I will be exploring Kyutai's Moshi model, which is the first open-source model that enables users to interact with a language model in real-time using voice, similar to the widely popular demo from OpenAI showcasing live voice capabilities but the only difference is that moshi is fully open source. The model requires approximately 23 GB of VRAM, so unfortunately, it can only be run on the paid version of Google Colab.

But on the flip side the KyutAI team have made it very simple to run the model and it only takes one line of code to start a server that hosts the model and the GUI for interactive use. The session can also be recorded for demo purposes.

Another thing to consider for this notebook is that I will be using the tunnel feature from gradio which will setup a tunnel with a URL accessible from anywhere, but this tunnel goes through US and can add significant latency. This will not be a problem if the model is hosted locally.

The github repo for the model is here: [Kyutai-github-repo](https://github.com/kyutai-labs/moshi)
