

<body>
    <div class="container">
        <h2>Open Information Extraction for Text Summarization and Question Answering System</h2>
      <h2>Problem Statement</h2>
      <p>With the ever-growing amount of data available online and in various document formats, manually processing and extracting meaningful information can be time-consuming and inefficient. Organizations need a way to quickly and accurately extract relevant information from a variety of sources and present it in a concise format.</p>
        <h2>Overview</h2>
        <p>This project is designed to extract, summarize, and analyze information from diverse sources, including plain text files, PDFs, Word documents, and URLs. The system performs three core functions:</p>
        <ul>
            <li><strong>Summarization:</strong> Generates concise summaries of large text inputs.</li>
            <li><strong>Named Entity Recognition (NER):</strong> Identifies and classifies key entities such as people, organizations, and locations within the text.</li>
            <li><strong>Question Answering:</strong> Answers specific user questions based on the extracted and processed information.</li>
        </ul>
        <h2>Features</h2>
        <ul>
            <li><strong>Multi-Source Information Extraction:</strong> Handles text extraction from various file formats, including <code>.txt</code>, <code>.pdf</code>, <code>.docx</code>, and web URLs.</li>
            <li><strong>Text Summarization:</strong> Provides both extractive and abstractive summaries of the input text.</li>
            <li><strong>Named Entity Recognition (NER):</strong> Detects and categorizes named entities in the text, aiding in structuring and understanding the data.</li>
            <li><strong>Question Answering:</strong> Uses advanced NLP models to answer specific questions based on the provided text.</li>
            <li><strong>Web Interface:</strong> Simple and intuitive web interface for uploading documents and interacting with the system.</li>
        </ul>
        <h2>Technologies Used</h2>
        <ul>
            <li><strong>Programming Language:</strong> Python</li>
            <li><strong>Libraries:</strong>
                <ul>
                    <li>Text Processing: <code>NLTK</code>, <code>spaCy</code></li>
                    <li>Document Handling: <code>PyPDF2</code>, <code>python-docx</code>, <code>requests</code> for web scraping</li>
                    <li>NLP Models: <code>Transformers</code> (Hugging Face), <code>BERT</code></li>
                    <li>Web Framework: <code>Flask</code></li>
                    <li>Deep Learning: <code>TensorFlow</code>, <code>Keras</code></li>
                </ul>
            </li>
        </ul>
        <h2>Installation</h2>
        <h3>Prerequisites</h3>
        <ul>
            <li>Python 3.8+</li>
            <li>pip (Python package installer)</li>
            <li>Virtual environment (recommended)</li>
        </ul>
        <h3>Clone the Repository</h3>
        <pre><code>git clone https://github.com/tarak0506/open-information-extraction.git
cd open-information-extraction
</code></pre>
        <h3>Create and Activate a Virtual Environment</h3>
        <pre><code>python -m venv venv
source .\venv\Scripts\activate
</code></pre>
        <h3>Install Dependencies</h3>
        <pre><code>pip install -r requirements.txt</code></pre>
        <h2>Usage</h2>
        <h3>Running the Application</h3>
        <ol>
            <li><strong>Start the Web Server:</strong>
                <pre><code>python app.py</code></pre>
            </li>
            <li><strong>Access the Web Interface:</strong>
                <p>Open your browser and navigate to <code>http://127.0.0.1:5000</code>.</p>
            </li>
        </ol>
        <h3>Uploading Documents</h3>
        <ul>
            <li><strong>Upload Files:</strong> You can upload text files, PDFs, Word documents, or provide URLs for web scraping.</li>
            <li><strong>Summarization:</strong> After uploading, the system will generate a summary of the content.</li>
            <li><strong>Named Entity Recognition:</strong> The system will also display recognized entities within the text.</li>
            <li><strong>Question Answering:</strong> You can input specific questions to receive answers based on the extracted information.</li>
        </ul>
        <h3>Example</h3>
        <ul>
            <li><strong>Upload a PDF Document:</strong> The system will extract the text from the PDF, summarize it, recognize named entities, and allow you to ask questions based on the content.</li>
            <li><strong>Ask a Question:</strong> Enter a question related to the document, and the system will provide an answer.</li>
        </ul>
        <h2>Future Enhancements</h2>
        <ul>
            <li>Support for Additional Formats: Adding support for more file formats such as <code>.xlsx</code> or <code>.pptx</code>.</li>
            <li>Improved Summarization: Enhancing the summarization capabilities with more advanced models.</li>
            <li>Advanced Question Answering: Implementing domain-specific question-answering modules for specialized fields.</li>
        </ul>
<!--     <footer>
        &copy; 2023 Open Information Extraction Project
    </footer> -->
</body>

</html>
