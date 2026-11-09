# Attia Inayat

AI Engineer | BS Artificial Intelligence, COMSATS University Islamabad, Lahore

[LinkedIn](https://linkedin.com/in/attia-inayat) · [Email](mailto:attia.inayat23@gmail.com) · [WhatsApp](https://wa.me/923209176066) · [CV](./Attia_Inayat_CV.pdf)

## About

I'm a final-year AI student (CGPA 3.66). My final year project turns multi-view images of Minecraft builds into 3D structures. Outside university I've built a RAG chatbot that answers from your documents and a voice agent that takes restaurant orders over the phone, and I've done freelance work for clients in Canada, the UK and Spain.

I'm currently training Stage 2 of my FYP and looking for an AI engineer role, internship or freelance work, mainly in LLM applications, voice agents or computer vision.

## Projects

### Blocksmith: 2D images to 3D Minecraft builds (team FYP)
A two-stage model that takes images of a build and produces a `.schem` file you can load in Minecraft.
- Scraped Minecraft build websites for schematics, images and metadata, and built a dataset of 2,052 builds, each paired with its 3D voxel grid.
- Loaded each build in Minecraft, set up its camera views by hand and validated the image and voxel pairs.
- Currently training Stage 2, a DINOv2-based image encoder that connects to a frozen VQ-VAE decoder.

Built with PyTorch, VQ-VAE and DINOv2.

### [Restaurant Voice Ordering Agent](https://github.com/AttiaInayat/Restaurant-Voice-Agent)
A phone agent that answers questions, recommends menu items and takes orders, built for a restaurant client.
- Uses function calls to capture the order, delivery address and preferences.
- Logs orders and reservations to Airtable through Make.com webhooks.
- Deployed on Vapi and delivered to the client's representative.

Built with Vapi, Retell AI, Make.com and Airtable.

### [Document Q&A Chatbot with RAG](https://github.com/AttiaInayat/langchain_course/tree/main/ai_chatbot_project)
Ask questions about your own documents and get answers pulled from the source text.
- Splits documents into chunks, creates embeddings and retrieves the closest passages with FAISS.
- FastAPI backend with a Streamlit interface.

Built with LangChain, FAISS, FastAPI and Streamlit.

## Skills

- **Programming:** Python, C++, Java, SQL
- **AI and ML:** Machine Learning, Deep Learning, NLP, Computer Vision, Transfer Learning
- **Generative AI:** RAG, LangChain, LangGraph, FAISS
- **Frameworks and libraries:** PyTorch, TensorFlow, Scikit-Learn, NumPy, Pandas, Matplotlib
- **Chatbot, voice AI and automation:** Vapi, Retell AI, Tidio, Make.com, Airtable, Webhooks
- **Backend and databases:** FastAPI, Node.js, Express.js, MongoDB, SQLAlchemy, Alembic
- **Tools:** Docker, Docker Compose, Git

## Contact

Email: attia.inayat23@gmail.com
LinkedIn: [linkedin.com/in/attia-inayat](https://linkedin.com/in/attia-inayat)
