### Hi there, I’m [Asif Mehmood](https://www.linkedin.com/in/asifmehmood1997/) 👋

## I'm an AI Engineer | ML Developer | LLM Practitioner | RAG Builder 🚀

- 🔭 I’m currently working on end-to-end **LLM applications** & **RAG pipelines** for enterprise workflows.
- 🌱 Constantly learning about **agentic workflows**, **prompt engineering**, **retrieval pipelines**, and **fine-tuning**.
- 👯 I love collaborating with other AI enthusiasts, researchers, and product builders.
- 🧠 Past projects include **AI chat agents**, **document intelligence tools**, **OCR pipelines**, and **NLP automation**.
- 🥅 2025 Goals: Contribute to open-source GenAI tools, grow my network, and help shape the future of applied AI.
- ⚡ Fun fact: I love exploring AGI theory and teaching AI concepts to non-technical audiences.

---

### 🌐 Connect With Me

[<img align="left" alt="LinkedIn" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg"/>](https://www.linkedin.com/in/asifmehmood1997)[<img align="left" alt="Stack Overflow" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/stackoverflow.svg"/>](https://stackoverflow.com/users/9104570/asif-mehmood)
<br />
<br />

---

### 🧠 Tech Stack & Tools

[<img align="left" alt="Python" width="26px" src="https://raw.githubusercontent.com/github/explore/master/topics/python/python.png"/>](#)
[<img align="left" alt="OpenAI" width="26px" src="https://cdn.iconscout.com/icon/free/png-256/free-openai-1524348-1290723.png"/>](#)
[<img align="left" alt="LangChain" width="26px" src="https://avatars.githubusercontent.com/u/139914147?s=280&v=4"/>](#)
[<img align="left" alt="Hugging Face" width="26px" src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg"/>](#)
[<img align="left" alt="FastAPI" width="26px" src="https://cdn.worldvectorlogo.com/logos/fastapi.svg"/>](#)
[<img align="left" alt="MongoDB" width="26px" src="https://raw.githubusercontent.com/github/explore/master/topics/mongodb/mongodb.png"/>](#)
[<img align="left" alt="SQL" width="26px" src="https://cdn-icons-png.flaticon.com/512/2772/2772128.png"/>](#)
[<img align="left" alt="Docker" width="26px" src="https://raw.githubusercontent.com/github/explore/master/topics/docker/docker.png"/>](#)
[<img align="left" alt="Git" width="26px" src="https://raw.githubusercontent.com/github/explore/master/topics/git/git.png"/>](#)
[<img align="left" alt="Linux" width="26px" src="https://raw.githubusercontent.com/github/explore/master/topics/linux/linux.png"/>](#)
[<img align="left" alt="AWS" width="26px" src="https://raw.githubusercontent.com/github/explore/master/topics/aws/aws.png"/>](#)
[<img align="left" alt="OCR" width="26px" src="https://cdn-icons-png.flaticon.com/512/2917/2917993.png"/>](#)

<br />
<br />

---

### 🚀 Featured Projects

<!-- PROJECTS:START -->
- [🔍 RAG-as-a-Service Platform](https://github.com/yourusername/rag-platform) – Modular retrieval-augmented generation system with multi-vector support.
- [🤖 Conversational AI with Tools & Memory](https://github.com/yourusername/tool-augmented-agent) – LangChain-powered chatbot with custom tools and state.
- [🧾 OCR-Powered Form Understanding](https://github.com/yourusername/doc-ai-suite) – Document parsing + classification + summary pipeline.
- [🧠 Fine-Tuned LLM for Niche Domain](https://github.com/yourusername/custom-llm) – QLoRA + PEFT on domain-specific corpus.
- [📈 Referral Management System for SNFs](https://github.com/yourusername/snfs-referral-ai) – Summarization + keyword analytics + VOB automation.
<!-- PROJECTS:END -->

---

### 🧠 Open Source Contributions

I've contributed to the [LangChain](https://github.com/langchain-ai/langchain) and [LangChain Community](https://github.com/langchain-ai/langchain-community) repositories, focusing on improvements to tools, utilities, and core features.

#### 🔗 Notable Merged Pull Requests

- [langchain-ai/langchain-community#83](https://github.com/langchain-ai/langchain-community/pull/83)  
  **🔢 Added AWS Bedrock Claude 4 series model cost tracking**  
  Enhanced `bedrock_anthropic_callback.py` to include token pricing data for the following Claude 4 models:
  - `anthropic.claude-sonnet-4-20250514-v1:0`
  - `anthropic.claude-opus-4-20250514-v1:0`  
  Pricing based on AWS Bedrock documentation.  
  Reference: [AWS Bedrock Pricing](https://aws.amazon.com/bedrock/pricing)  
  Related Issue: [#82](https://github.com/langchain-ai/langchain-community/issues/82)

- [langchain-ai/langchain-community#50](https://github.com/langchain-ai/langchain-community/pull/50)  
  **🔍 Added support for `additional_search_client_options` in Azure Search (async)**  
  Extended the Azure Search **async vectorstore client** to accept `additional_search_client_options`, aligning its behavior with the sync client.  
  Previously, the async client ignored this parameter and defaulted to an empty dictionary.  
  Related Issue: [#42](https://github.com/langchain-ai/langchain-community/issues/42)

- [langchain-ai/langchain#31177](https://github.com/langchain-ai/langchain/pull/31177)  
  **📚 Fixed outdated import paths and corrected documentation typo**  
  Updated the import path of `DoctranPropertyExtractor` from `document_loaders` to `document_transformers` to match recent package refactoring.  
  Also fixed a minor typo across docs for clarity and correctness.

- [langchain-ai/langchain#31107](https://github.com/langchain-ai/langchain/pull/31107)  
  **⚙️ Replaced deprecated `.dict()` calls with `.model_dump()` for Pydantic v2 compatibility**  
  Updated multiple modules to replace deprecated `.dict()` usage with `.model_dump()` to align with **Pydantic v2+ guidelines** and suppress `PydanticDeprecatedSince20` warnings.  
  This change prepares the codebase for Pydantic v3 with no impact on functional logic.  
  Related Issue: [#31103](https://github.com/langchain-ai/langchain/issues/31103)

- [langchain-ai/langchain-community#27](https://github.com/langchain-ai/langchain-community/pull/27)  
  **💰 Added token usage & cost tracking for OpenAI embedding models in `OpenAICallbackHandler`**  
  Enhanced `get_openai_callback()` to include **embedding model calls** in usage and cost reporting, improving observability and enabling complete cost tracking across all OpenAI model types.  
  This change aligns LangChain's callback utilities with real-world production monitoring needs.  
  Related Issue: [#25888](https://github.com/langchain-ai/langchain/issues/25888)


#### 🛠️ Ongoing Contributions
- Actively contributing additional improvements to LangChain and related projects.  


---

### 🎬 YouTube | Articles | Interviews

<!-- CONTENT:START -->
- [🔍 RAG Explained Simply for Non-Techs](https://your-blog-link.com/rag-simply-explained)
- [🤖 Behind-the-Scenes of Building AI Agents](https://your-blog-link.com/building-agents)
- [📹 How to Use LangChain with OpenAI](https://youtube.com/your-video)
<!-- CONTENT:END -->

---

### 📊 GitHub Stats

<img align="left" alt="Asif's GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=AsifMehmood97&show_icons=true&hide_border=true&theme=radical&count_private=true" />
