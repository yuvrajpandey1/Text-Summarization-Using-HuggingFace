
# Text Summarization

We are going to Summarization text from Youtube url or any other Website url.Providing HuggingFace api as a mandatory input to process further and to validate URL using validators.


## Important Libraries Used

 - [Document loaders](https://python.langchain.com/v0.1/docs/modules/data_connection/document_loaders/)
 - [Prompt Template](https://python.langchain.com/v0.1/docs/integrations/llms/deepinfra/#create-a-prompt-template)
 - [YouTube transcripts](https://python.langchain.com/docs/integrations/document_loaders/youtube_transcript/)
  - [UnstructuredURLLoader](https://python.langchain.com/api_reference/community/document_loaders/langchain_community.document_loaders.url.UnstructuredURLLoader.html#unstructuredurlloader)

- [Huggingface Endpoints](https://python.langchain.com/docs/integrations/llms/huggingface_endpoint/)





## Plateform or Providers

 - [Hugging Face x LangChain](https://huggingface.co/blog/langchain)
 - [Streamlit](https://docs.streamlit.io/)

## Model

 - LLM - mistral/Mistral-7B-Instruct-v0.3


# Documentation 

[HuggingFace](https://huggingface.co/)

Hugging Face is an AI platform and supporting community. The community uses Hugging Face to do the following:


* Implement machine learning models.
* Share and discover machine learning models. 
* Fine-tune models.
* Develop business applications.
* Evaluate ML models.


[Benefits of using Hugging Face](https://www.techtarget.com/whatis/definition/Hugging-Face#:~:text=Hugging%20Face%20is%20an%20AI,learning%20models%20to%20the%20platform.)

* Accessibility. Hugging Face helps users bypass restrictive compute and skill requirements typical of AI development. The fact that Hugging Face provides pre-trained models, fine-tuning scripts and APIs for deployment makes the process of creating LLMs easier.

* Integration. Hugging Face helps users integrate multiple ML frameworks. For example, the Transformer library integrates with other ML frameworks such as PyTorch and TensorFlow.

* Community. Hugging Face provides access to a vast community, continuously updated models, and documentation and tutorials.

* Cost-effective. Hugging Face provides cost-effective and scalable solutions for businesses. Building large ML models from scratch can be expensive, and using Hugging Face's hosted models saves money.



## Installation

Install below libraries

```bash
  pip install langchain
  pip install langchain_community
  pip install streamlit
  pip install langchain_huggingface
  pip install numexpr
  pip install validators
  pip install youtube_transcript_api

```
    
## Tech Stack

**Client:** Python, LangChain PromptTemplate, HuggingFaceEndpoint

**Server:** Streamlit, LangChain


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

`HUGGINGFACE_API_KEY`

