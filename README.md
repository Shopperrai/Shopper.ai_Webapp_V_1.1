# Shopper.ai_Website V_1.1
<html>
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>Installation Guide</h1>
  <h2>React Client Folder</h2>
  <ol>
    <li>Make sure you have Node.js and npm (Node Package Manager) installed on your system. You can download them from <a href="https://nodejs.org/">https://nodejs.org/</a>.</li>
    <li>Open a terminal or command prompt and navigate to the root directory of the React client folder.</li>
    <li>Run the following command to install the necessary dependencies:
      <pre><code>npm install</code></pre>
    </li>
    <li>Once the installation is complete, you can start the React development server using the command:
      <pre><code>npm start</code></pre>
    </li>
    <li>The React client should be accessible in your browser at <code>http://localhost:3000</code>.</li>
  </ol>
  <h2>API Folder (Node.js)</h2>
  <ol>
    <li>Ensure that you have Node.js and npm installed on your system as mentioned earlier.</li>
    <li>Open a terminal or command prompt and navigate to the root directory of the API folder.</li>
    <li>Run the following command to install the required dependencies:
      <pre><code>npm install</code></pre>
    </li>
    <li>Next, you need to set up the necessary environment variables. Create a file named <code>.env</code> in the root directory of the API folder and define the required variables. For example:
      <pre><code>PORT=3001
DB_HOST=localhost
DB_PORT=27017
DB_NAME=mydatabase
API_SECRET=yourapisecret</code></pre>
      Adjust the values according to your needs.
    </li>
    <li>Once the dependencies are installed and the environment variables are set up, you can start the Node.js server using the command:
      <pre><code>npm start</code></pre>
    </li>
    <li>The API should now be running and ready to accept requests at the specified port.</li>
  </ol>
  <p>Please ensure that both the React client and the API server are running simultaneously to enable full functionality.</p>
  <p>For any further assistance, please refer to the documentation or consult the respective project maintainers.</p>
</body>
</html>
