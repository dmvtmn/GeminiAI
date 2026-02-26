![GitHub](https://img.shields.io/github/license/DataForScience/GeminiAI)
[![Twitter @data4sci](https://img.shields.io/twitter/follow/data4sci)](https://twitter.com/intent/follow?screen_name=data4sci)
![GitHub top language](https://img.shields.io/github/languages/top/DataForScience/GeminiAI)
![GitHub repo size](https://img.shields.io/github/repo-size/DataForScience/GeminiAI)
![GitHub last commit](https://img.shields.io/github/last-commit/DataForScience/GeminiAI)

[![Graphs For Science](https://img.shields.io/badge/Graphs_For_Science-Subscribe-blue)](https://graphs4sci.substack.com/)
	[![Data Science Briefing](https://img.shields.io/badge/Sunday_Briefing-Subscribe-blue)](https://data4science.ck.page/a63d4cc8d9)

# Gemini API with VertexAI for Developers

### Code and slides to accompany the online series of webinars: https://www.oreilly.com/live-events/gemini-api-with-vertexai-for-developers/0642572299484/ by Data For Science.

This webinar provides attendees with an excellent opportunity to explore Google's cutting-edge Generative AI capabilities, specifically focusing on the Gemini API within the Vertex AI framework on Google Cloud Platform. As AI development accelerates, understanding and implementing multimodal generative models have become essential for creating innovative and intelligent applications. The session will provide participants with the knowledge and hands-on skills to leverage generative AI across various modalities, including text generation for content creation and natural language processing, image synthesis for design and visual communication, video creation for automated production and immersive experiences, and audio generation for advancements in voice assistants and sound design.

The content is designed to provide developers with the necessary skills and knowledge to integrate powerful AI features into their projects. Whether building new applications or enhancing existing ones, the insights gained will enable the creation of more dynamic, interactive, and intelligent user experiences. By mastering the Gemini API within Vertex AI and the broader GCP ecosystem, developers will be positioned to harness the latest developments by one of the forefront leaders in this growing field.

## Course Structure
### 1. Gemini API and Vertex AI Fundamentals
- Generative AI
- Introduction to Gemini API
- Overview of Vertex AI

### 2. Gemini API for Text Generation
- Prompt Engineering for Text Models
- Text Generation with Gemini API
- Text Models for Information Extraction

### 3. Multimodal Applications with Gemini API
- Exploring Gemini's Image and Video Understanding Capabilities
- Hands-on: Image Captioning and Visual Question Answering
- Integrating Multimodal Inputs for Advanced Applications
- Real-world Use Cases for Multimodal Generative AI

### 4. Vertex AI and Deployment Strategies
- Advanced MLOps Practices with Vertex AI
- Model Monitoring and Explainability on Vertex AI
- Deploying Gemini-powered Applications
- Scaling and Optimization for Production Environments

### 5. End-to-End Generative AI Solutions
- Designing and Architecting Generative AI Systems
- Best Practices for Security and Data Privacy

## Setup

### 1) Install dependencies (recommended: `uv`)

1. Install `uv` (if needed):

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

2. Create an environment and install dependencies:

```bash
git clone https://github.com/DataForScience/GeminiAI.git
cd GeminiAI
uv venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
uv sync
```

### 2) Add API keys

You'll need accounts with the following services. All offer free tiers or pay-as-you-go pricing:

| Service    | Used in         | Where to get it                          |
|------------|-----------------|------------------------------------------|
| Anthropic  | All notebooks   | console.anthropic.com                    |
| Serper     | Modules 2–5     | serper.dev                               |
| VoyageAI   | Module 3 (RAG)  | dash.voyageai.com *(optional)*           |

Once you have your keys, create a `.env` file in the root of the project:

```
ANTHROPIC_API_KEY=sk-ant-...
SERPER_API_KEY=...
VOYAGE_API_KEY=...  
```

### 3) Launch notebooks

```bash
jupyter notebook
```

## Repository Structure

```
GeminiAI/
├── 1. Gemini Fundamentals.ipynb                 # Module 1: Gemini API basics
├── 2. Text Generation.ipynb                     # Module 2: Text generation
├── 3. Multimodal.ipynb                          # Module 3: Multimodal inputs
├── 4. Deployment.ipynb                          # Module 4: Deployment
├── 5. E2E Solutions.ipynb                       # Module 5: End-to-end solutions
├── slides/                                      # Slides
│   └── GeminiAI.pdf
├── data/                                        # Logos + author image assets
├── config/                                      # YAML agent/task config (Module 5)
├── d4sci.mplstyle                               # Custom matplotlib style
├── pyproject.toml                               # Dependency manifest (for `uv sync`)
├── requirements.txt                      # Alternative install path (pip/uv pip)
└── .env                                  # API keys (create this file; do not commit)
```

## Suggested learning path

- Start with **Module 1** and run the notebooks in order (1 → 5).
- If you only want the deck, open `slides/GeminiAI.pdf`.

| File                           | Topic                                   |
| --------------------------------| -----------------------------------------|
| `1. Gemini Fundamentals.ipynb` | Gemini API and Vertex AI Fundamentals   |
| `2. Text Generation.ipynb`     | Gemini API for Text Generation          |
| `3. Multimodal.ipynb`          | Multimodal Applications with Gemini API |
| `4. Deployment.ipynb`          | Vertex AI and Deployment Strategies     |
| `5. E2E Solutions.ipynb`       | End-to-End Generative AI Solutions      |

---

## Estimated API Costs
Running through all notebooks end-to-end costs roughly **$1–3** in API calls, depending on how much you re-run cells. 

---

## Questions?

Reach out at <a href="mailto:info@data4sci.com">info@data4sci.com</a> or open an issue if something isn't working.

## Author

<table border="0">
 <tr>
	<td>
	  <img src="data/bgoncalves.png" alt="Bruno Gonçalves" width="150" height="150" style="border-radius: 50%; object-fit: cover;">
	</td>
	<td>
	  <h2>Bruno Gonçalves</h2>
	  <h3>Data For Science, Inc.</h3>
	  <p>
			Web: <a href="http://www.data4sci.com/">www.data4sci.com</a><br>
			Twitter/X: <a href="https://twitter.com/bgoncalves">@bgoncalves</a><br>
			LinkedIn: <a href="https://www.linkedin.com/in/bmtgoncalves/">@bmtgoncalves</a><br>
			Email: <a href="info@data4sci.com">info@data4sci.com</a><br>
			Schedule a Call: <a href="https://data4sci.com/call">https://data4sci.com/call</a>
	  </p>
	</td>
 </tr>
</table>