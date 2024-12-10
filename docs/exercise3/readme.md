# Setup your computer

In this exercise you will find a chatbot that uses large language models implemented in Python in `gui.ipynb`. It is rude and ma not be very helpful. You can modify its behaviour by changing its prompt. Furthermore, there `chatbot_explained.ipynb` which demonstrates how the chat works under the hood. 

For executing the code in this folder, it is recommended to install [mini-conda](https://docs.anaconda.com/miniconda/) and setup an environment for Python programming as explained on [this page](https://scads.github.io/generative-ai-notebooks/00_setup/readme.html). In very short this requires creating a new conda environment using this command:

```
conda env create -f https://raw.githubusercontent.com/ScaDS/generative-ai-notebooks/main/docs/00_setup/environment-cpu.yml
```

You can then also execute the code in Python Juptyer notebooks. If you want to open the chat-interface in the browser without the Jupyter environment, you can use [voila](https://github.com/voila-dashboards/voila):

```
voila gui.ipynb
```

## See also

* [Tutorials on Retrieval Augmented Generation](https://scads.github.io/generative-ai-notebooks/60_rag/readme.html)
* [Chatting with PDFs](https://scads.github.io/generative-ai-notebooks/63_chat_with_docs/readme.html)
