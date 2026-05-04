<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Call Sentiment AI</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f4f6f8;
}

header {
    background: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
}

.container {
    width: 85%;
    margin: auto;
    padding: 20px;
}

.section {
    background: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

h2 {
    color: #333;
}

ul {
    padding-left: 20px;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
}

th, td {
    padding: 10px;
    border: 1px solid #ddd;
}

th {
    background: #4CAF50;
    color: white;
}

footer {
    text-align: center;
    padding: 15px;
    background: #333;
    color: white;
}
</style>
</head>

<body>

<header>
    <h1>Call Sentiment AI</h1>
    <p>AI-based system for analyzing customer call sentiment</p>
</header>

<div class="container">

<div class="section">
<h2>Overview</h2>
<p>
Call Sentiment AI is a web application that analyzes customer call recordings by converting speech into text and detecting sentiment. It classifies calls as positive, negative, or neutral to help understand customer feedback.
</p>
</div>

<div class="section">
<h2>Features</h2>
<ul>
<li>Upload audio files for analysis</li>
<li>Convert speech to text</li>
<li>Perform sentiment analysis</li>
<li>Display results clearly</li>
<li>Simple and responsive UI</li>
</ul>
</div>

<div class="section">
<h2>How It Works</h2>
<ol>
<li>User uploads an audio file</li>
<li>Audio is converted into text</li>
<li>Text is analyzed for sentiment</li>
<li>Result is shown (positive, negative, neutral)</li>
</ol>
</div>

<div class="section">
<h2>Technologies Used</h2>
<ul>
<li>Python</li>
<li>Streamlit</li>
<li>Whisper</li>
<li>PyTorch</li>
<li>Transformers</li>
<li>FFmpeg</li>
<li>Git & GitHub</li>
</ul>
</div>

<div class="section">
<h2>Project Structure</h2>
<table>
<tr>
<th>File/Folder</th>
<th>Description</th>
</tr>
<tr>
<td>CallSentimentAI/</td>
<td>Main project folder</td>
</tr>
<tr>
<td>app.py</td>
<td>Main Streamlit application</td>
</tr>
<tr>
<td>requirements.txt</td>
<td>Dependencies list</td>
</tr>
<tr>
<td>README.md</td>
<td>Project documentation</td>
</tr>
<tr>
<td>Other files</td>
<td>Additional resources</td>
</tr>
</table>
</div>

<div class="section">
<h2>Installation</h2>
<pre>
git clone https://github.com/your-username/CallSentimentAI.git
cd CallSentimentAI
pip install -r requirements.txt
</pre>
</div>

<div class="section">
<h2>Run Application</h2>
<pre>
streamlit run app.py
</pre>
</div>

<div class="section">
<h2>Use Case</h2>
<p>
Used for analyzing customer support calls, understanding sentiment, and improving service quality.
</p>
</div>

<div class="section">
<h2>Future Enhancements</h2>
<ul>
<li>Real-time monitoring</li>
<li>Live microphone input</li>
<li>Analytics dashboard</li>
<li>Call history tracking</li>
<li>Emotion detection</li>
</ul>
</div>

</div>

<footer>
    <p>Developed by Harshita</p>
</footer>

</body>
</html>
