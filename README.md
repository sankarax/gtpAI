The Guess The Price app is super simple to setup. As a preface, the fine-tuned Llama 3.1 model is stored in the personal HuggingFace repo. The fine-tuning process took around 24 hrs and is a separate mini-project.
- If you are using your own fine-tuned model make sure to change the HF username and project name first. And add the hf-secret to the Modal Secrets.
- Install modal using pip install modal.
- Create a new modal token by running "modal setup" in the terminal. Authorize the access popup in the webpage.
- Run "modal deploy -m gtpAI" to deploy the app to Modal. Setting MIN_CONTAINERS = 1 will make sure the app is always running but the costs will be drastic.
- Finally run the notebook code using Jupyter.
- Change the product and description to guess the prices for different products. The category of the product could be something like Automotive, Musical Instruments, Electronics etc.
And voila!
