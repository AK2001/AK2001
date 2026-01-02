## Hi there 👋

I am a Python developer, currently working as a Machine Learning Egnineer.

I started tinkering with Python back in 2021 and since then I have worked on many interesting projects, most of them relating to data.

In my work, I mostly value efficiency and simplicity.

---

### 🔭 **I’m currently working on**:
- A mobile app which utilizes Deep Learning to perform multimodal similarity search
  - Stack: [Expo](https://github.com/expo/expo) + [Qdrant](https://github.com/qdrant/qdrant) + [FastAPI](https://github.com/fastapi/fastapi) + [Transformers](https://github.com/huggingface/transformers)
  - Goal: Allow users to quickly retrieve/search images
- [My blog ヽ༼ ◕_◕༽ﾉ](https://akelaiditis.bearblog.dev/)

</br>

### 🏗️ Portfolio in a glance...

- "Car make and model classification from Image" ([repository](https://github.com/AK2001/Car-Model-Classification-from-Image)):
  - My BSc thesis which I experimented with CNNs for the first time 🧪
 
- A similarity search system build upon a SQL database containing millions of records (no repository available :/ )
  - **Key Challenge**: Find a reliable way to sync the SQL database to the vector database
  - **My solution**: Create an automation which checks recently modified records --> process them --> adds/deletes/updates
  - **Tech Stack**: `Qdrant` (vector db), `FastAPI` (backend server), `Prefect` (workflow orchestration), `Hugging-Face` (embeddings)
 
- A data processing pipeline where given a single SQL record, it provides the closest record based on a number of criteria (no repository available :/ )
  - **Key Challenge**: Match record A with record B based on several fields. Existing pipeline (python) worked sequentially due to SQL updates
  - **My solution**: Utilize `Polars` to perform several preprocessing operations in parallel (for both number & string fields). Develop the service above for similarity search.
  - **Tech Stack**: `Prefect` (workflow orchestration), `Polars` (data handling/processing)
