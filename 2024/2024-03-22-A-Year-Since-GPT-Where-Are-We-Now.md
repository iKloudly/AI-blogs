# :zap: GPT - Where Are We Now, Since a Year and a Half Ago...?

**1. GPT is OLD TIME NEWS**
  
  * There are literally over 10 different new LLMs that are being released each day. And there are a number of them who **exceed in performance** when compared to GPT. For example, [Claude 3](https://www.anthropic.com/claude) recently released a comparison of the Claude 3 models to those of our peers on multiple benchmarks of capability, and it exceeds GPT-4 in many aspects. [(See Image)](https://www.anthropic.com/_next/image?url=https%3A%2F%2Fwww-cdn.anthropic.com%2Fimages%2F4zrzovbb%2Fwebsite%2F9ad98d612086fe52b3042f9183414669b4d2a3da-2200x1954.png&w=3840&q=75).
	
**2. ROBOTS + GPT**

  * In the past, the majority robots/humanoids required very **specific commands** that they were pre-trained with, in order to comprehend and execute a task. Now, we can simply **implement LLMs in them** so they can analyze, understand, and interpret for themselves. We'll soon be able to meet extremely human-like robots in the near future... [(See Video)](https://www.youtube.com/watch?v=Sq1QZB5baNw).
	
**3. Chain of Thoughts**
  * A very popular, rising prompt engineering technique. It's pretty much a method to command GPT to think and process thoughts in order with prompts. It's a lot easier to understand with a single [(photo)](https://www.promptingguide.ai/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcot.1933d9fe.png&w=1080&q=75). A rising start-up, [Cognition](https://www.cognition-labs.com/), recently utilized this to release [the very first AI software engineer](https://www.youtube.com/watch?v=fjHtjT7GO1c). The video showcased Devin - an AI software engineer - who can write, evaluate, execute, and debug codes.
	
  * **_Yes, there are already a several similar products, but the products at this level will bring a LOT of $$$._**
	
**4. Optimization**
  * The better the performance, the bigger the size of the LLMs. There have been several methods to compress the size, here are some of the popular ones:
  1) **"Quantization"**: the process of mapping a large set of input values to a smaller set, often used to reduce file size or bandwidth usage by **decreasing data precision**. For instance, in image processing, quantization might convert continuous color values (floats) into discrete entries from a predefined color palette, thereby simplifying the data representation.
  2) **"Pruning"**: a technique used in machine learning and neural networks to reduce the complexity of the model by **removing unnecessary parameters or connections**, which helps in reducing overfitting and improving the model's efficiency. For example, in a neural network, pruning might involve **setting the weights of less important connections** to zero, effectively removing them from the model's computation, thus simplifying the model without significantly affecting its performance.
- Thanks to a lot of these uprising optimization techniques, Samsung was able to [implement Gemini Nano/Mini into Galaxy S24 Series](https://www.androidpolice.com/samung-galaxy-s24-google-gemini-imagen-ai/), which features live-translation during calls.
	
**5. MOE (Mixture of Experts)**
  * A machine learning model that **divides a LLM into smaller, specialized sections (experts)**, each handling specific tasks, with a gating mechanism directing input to the most relevant expert, thereby enhancing efficiency and performance.
  * For example, if you see a model named ["Mixtral-8x7B"](https://huggingface.co/mistralai/Mixtral-8x7B-v0.1), it means that this model has been trained with 8 different smaller models. The smaller models used to train, are each trained with specific topics such as Math, Coding, Animation, etcs. So once an input is received, it first determines which model to use from within; therefore, it reduces a significant amount of GPU usage.
  * The main point is that there is not much of a difference in performance when doing so.
  * We'll see a lot of these models in the future.
	
**6. WE MIGHT NOT NEED GPUs AT ALL**
  * This was quite popular last month. [The Era of 1-bit LLMs: All Large Language Models are in 1.58 bits](https://arxiv.org/abs/2402.17764) is a bit insane, I think.
  * It is pretty much saying **"Even if we change ALL the existing parameters to just -1, 0, or 1, it won't really affect the performance much."**
  * What does this mean? Well, traditionally, running deep learning models primarily involves matrix multiplication operations, and since deep learning is more efficient with parallel processing, **it requires a significant amount of GPUs**. However, if you convert all parameters into three numbers (-1, 0, 1), you can change all operations to addition, making it possible to perform calculations very quickly on CPUs as well.
  * ~~Sell NVIDIA now and buy AMD!~~


## :abcd: Current Popular Large Language Models:
	
* [**Google Gemini**](https://gemini.google.com/app): It's a fine multi-model. The irony of being racist due to being over anti-racist, is quite funny. But it can access Google, and provide references very well for the responses it generates.
		
* [**GitHub Copilot**](https://github.com/features/copilot): Probably the most popular one for code assistance, as it can be easily integrated into the IDE.
  * To run them locally due to security reasons: [Mistral-7B-Code](https://huggingface.co/TheBloke/Mistral-7B-Code-16K-qlora-GGUF), [CodeLlama](https://huggingface.co/docs/transformers/model_doc/code_llama), [WizardCoder-Python-34B-V1.0](https://huggingface.co/WizardLM/WizardCoder-Python-34B-V1.0), [DeepSeek Coder](https://github.com/deepseek-ai/DeepSeek-Coder), [OpenCodeInterpreter](https://github.com/OpenCodeInterpreter/OpenCodeInterpreter), etcs. (These are all very popular coding expert models).
		
* [**Phind**](https://www.phind.com/): One of my top 3 choice. Probably not the most cool-featured ones, but it's definitely so, so, super fast. I use Phind instead of Google most of the times.
		
* [**Grok**](https://grok.x.ai/): Elon Musk's LLM that has the least restriction of censorship I believe. [~~Watch it teach how to make cocaine~~](https://media.licdn.com/dms/image/D4E22AQH7PEM2MHDLcg/feedshare-shrink_800/0/1699145769046?e=1714003200&v=beta&t=SJRovqZNnpO_Gdh2u89KuVuDvPOhmc7rdTMYEo4E6BQ).
	
	
And **THAT'S** where we are now smile


p.s. [GPT-5 release date: upcoming summer..?](https://www.yahoo.com/tech/chatgpt-could-gpt-5-upgrade-175039034.html) They've finally included a video AI model, Sora I believe. Can't wait!
