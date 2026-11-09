# data-analysis-ai-assignment1
IMF UK Report Analysis Using LLM
About the Project
This project analyses the IMF United Kingdom 2026 Article IV Consultation Report using Python and Large Language Models (LLMs). The main aim is to extract important economic information from the report and present it in a simple and clear way.
What the Project Does
- Reads and cleans the IMF report PDF.
- Divides the text into smaller chunks for analysis.
- Uses Google Gemini to prepare summaries and extract economic indicators.
- Identifies seven financial stability themes, along with key strengths and risks.
- Uses FAISS and sentence-transformers to find relevant information from the report.
- Compares single-query and multi-query RAG results.
- Creates four charts to show economic trends and findings.
Tools Used
Python, Google Colab, Google Gemini API, Pandas, Matplotlib, pypdf, FAISS, sentence-transformers and tiktoken.
How to Run
1. Open UK_IMF_Analysis.ipynb in Google Colab.
2. Run the installation cells for the required Python libraries.
3. Upload the IMF UK 2026 Article IV report PDF when asked.
4. Enter your Gemini API key when prompted.
5. Run the remaining cells in order to generate the analysis, JSON files and charts.
Conclusion
This project shows how LLMs and RAG can help analyse a long financial report and present useful findings through charts. Checking the extracted information with the original report is important for getting reliable results.
