<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PDF Insight Analyzer</title>
    <style>
        body { max-width: 800px; margin: 0 auto; padding: 20px; font-family: Arial, sans-serif; }
        .badge { display: inline-block; padding: 5px 10px; margin: 5px; border-radius: 3px; }
        .python { background: #f5f5f5; padding: 15px; border-radius: 5px; }
    </style>
</head>
<body>
    <h1>PDF Insight Analyzer 🕵️♂️</h1>

    <section id="features">
        <h2>Key Features 🌟</h2>
        <ul>
            <li><strong>Multi-PDF Analysis:</strong> Process up to 10 PDFs simultaneously (500+ pages each)</li>
            <li><strong>Instant Q&A:</strong> Natural language questions with relevance scoring</li>
            <li><strong>Privacy First:</strong> 100% client-side processing</li>
        </ul>
    </section>

    <section id="use-cases">
        <h2>Cool Use Cases 🚀</h2>
        
        <article class="use-case">
            <h3>Academic Research Accelerator 📚</h3>
            <p><strong>Scenario:</strong> "Compare findings about neural plasticity across 8 neuroscience textbooks"</p>
            <pre><code class="python">
# Upload all PDF textbooks
# Ask: "What are the different types of neural plasticity?"
# Get ranked results with context snippets
            </code></pre>
        </article>

        <article class="use-case">
            <h3>Technical Manual Explorer 🔧</h3>
            <p><strong>Scenario:</strong> "Troubleshoot error code 0xE3 in 500-page aircraft manuals"</p>
            <pre><code class="python">
1. Upload PDF manuals
2. Query: "Resolution steps for error code 0xE3"
3. Get procedure excerpts with priority scoring
            </code></pre>
        </article>
    </section>

    <section id="technical">
        <h2>Technical Highlights 🔧</h2>
        <pre><code class="python">
# Memory-optimized processing
def process_pdf(content):
    # Streams text with 1KB buffer
    # Automatic garbage collection
            
class HybridSearch:
    def __init__(self):
        self.tfidf = TfidfVectorizer()  # Broad pattern matching
        self.nn = NearestNeighbors()    # Context relationships
        </code></pre>
    </section>

    <section id="getting-started">
        <h2>Getting Started 🚀</h2>
        <ol>
            <li>Open in <a href="https://jupyter.org/try-jupyter/lab/">JupyterLite</a></li>
            <li>Upload PDFs (<kbd>Ctrl</kbd>+Click to select multiple)</li>
            <li>Ask natural language questions</li>
        </ol>
    </section>

    <section id="specs">
        <h2>Tech Specs 💻</h2>
        <table>
            <tr><th>Category</th><th>Details</th></tr>
            <tr><td>Max PDF Size</td><td>50MB per document</td></tr>
            <tr><td>Processing Speed</td><td>~100 pages/sec</td></tr>
        </table>
    </section>

    <section id="roadmap">
        <h2>Future Roadmap 🛣️</h2>
        <ul>
            <li>✔️ OCR integration for scanned PDFs</li>
            <li>❌ Neural relevance boosting</li>
            <li>❌ Collaborative analysis mode</li>
        </ul>
    </section>

    <section id="faq">
        <h2>FAQ ❓</h2>
        <dl>
            <dt>Q: How many PDFs can I analyze?</dt>
            <dd>A: Current limit is 10 PDFs simultaneously</dd>
            
            <dt>Q: Where's my data stored?</dt>
            <dd>A: Nowhere - processing happens in your browser</dd>
        </dl>
    </section>

    <footer>
        <div class="badge" style="background: blue; color: white;">Open in Browser</div>
        <div class="badge" style="background: green; color: white;">MIT License</div>
    </footer>
</body>
</html>
