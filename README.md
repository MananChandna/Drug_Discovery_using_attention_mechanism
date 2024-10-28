![image](https://github.com/user-attachments/assets/2bed15c4-e9c1-4e04-9413-65400af005ad)

</head>
<body>
    <h1>Drug Discovery using Attention Mechanism</h1>

  <p><strong>Description:</strong><br>
        This project leverages advanced machine learning techniques to aid in drug discovery. By using an LSTM encoder-decoder model with an attention mechanism, the model generates a primary drug formula for a given disease. The entire pipeline has been streamlined and automated using Docker and Jenkins to ensure seamless deployment.
    </p>

  <h2>Project Structure</h2>
    <ul>
        <li><strong>Model Architecture:</strong> Uses an LSTM-based encoder-decoder model with an attention mechanism for focused sequence generation.</li>
        <li><strong>Deployment:</strong> Deployed via Docker for containerized, portable model execution.</li>
        <li><strong>Automation:</strong> Jenkins is integrated for continuous integration and delivery (CI/CD) to simplify updates and maintenance.</li>
    </ul>
    <h2>Key Features</h2>
    <ul>
        <li>Automated pipeline for drug formula generation given a disease as input.</li>
        <li>Attention mechanism enhances model focus, improving relevance and accuracy of generated formulas.</li>
        <li>Streamlined deployment with Docker for easy replication and scaling.</li>
        <li>CI/CD setup using Jenkins to automate the training and deployment process.</li>
    </ul>
    <h2>Installation</h2>
    <p>To set up and run this project on your machine, follow these steps:</p>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/yourusername/Drug_Discovery_Attention_Mechanism.git</code></pre>
                <li>Navigate to the project directory:</li>
        <pre><code>cd Drug_Discovery_Attention_Mechanism</code></pre>
        
  <li>Build the Docker container:</li>
        <pre><code>docker build -t drug_discovery_model .</code></pre>
              <li>Run the Docker container:</li>
        <pre><code>docker run -p 8000:8000 drug_discovery_model</code></pre>
        
  <li>Access the model’s endpoint:</li>
        <pre><code>http://localhost:8000/predict</code></pre>
    </ol>

  <h2>Usage</h2>
    <p>To use the model, send a POST request to the endpoint with the disease name as input. The model will return the generated primary drug formula.</p>
    <h2>Contact</h2>
    <p>If any help is needed, reach me out on <a href="https://www.linkedin.com/in/manan-chandna-697588257/" target="_blank">LinkedIn</a>.</p>

</body>
</html>
