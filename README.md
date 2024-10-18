<h1>ChatGPT 4.0 Clone Using OpenAI API Key</h1>

<p>Welcome to the <strong>ChatGPT 4.0 Clone</strong> project! This is a web-based application built using Django, designed to replicate the functionalities of OpenAI’s GPT-4 model. The application interacts with OpenAI's GPT API, allowing users to generate human-like text responses through a simple and intuitive interface.</p>

<h2>Features</h2>

<ul>
  <li><strong>GPT-4 Powered Responses</strong>: Harness the power of OpenAI’s GPT-4 to generate meaningful and creative text responses.</li>
  <li><strong>User-Friendly Interface</strong>: A clean, responsive web interface designed using Django templates.</li>
  <li><strong>Easy API Integration</strong>: Configure the app with your OpenAI API key to get started.</li>
  <li><strong>SQLite Database</strong>: Includes basic user sessions and conversation tracking with SQLite.</li>
</ul>

<h2>File Structure</h2>

<p>The project contains the following structure:</p>

<ul>
  <li><strong>chatgpt_project/</strong>: Main project settings and configuration.</li>
  <li><strong>chat/</strong>: The core app where the chat functionalities are implemented.</li>
  <li><strong>templates/</strong>: HTML templates for the front-end.</li>
  <li><strong>db.sqlite3</strong>: The SQLite database used to store user sessions and chat logs.</li>
  <li><strong>manage.py</strong>: Django’s command-line utility for administrative tasks.</li>
</ul>

<h2>Usage</h2>

<ol>
  <li>Enter text into the chatbox and submit.</li>
  <li>The app will send your input to OpenAI’s GPT-4 API and display the AI-generated response.</li>
  <li>User sessions and conversations are tracked in the database, allowing users to pick up where they left off.</li>
</ol>

<h2>Customization</h2>

<p>You can modify the <strong>temperature</strong> and <strong>max tokens</strong> of the GPT-4 API by editing the request in the <code>chat/views.py</code> file. You can also customize the front-end by editing the HTML files in the <code>templates/</code> directory.</p>

<h2>Contributing</h2>

<p>Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to submit an issue or create a pull request.</p>

<h3>How to Contribute</h3>

<ol>
  <li>Fork the project.</li>
  <li>Create your feature branch (<code>git checkout -b feature/AmazingFeature</code>).</li>
  <li>Commit your changes (<code>git commit -m 'Add some AmazingFeature'</code>).</li>
  <li>Push to the branch (<code>git push origin feature/AmazingFeature</code>).</li>
  <li>Open a pull request.</li>
</ol>


<h2>Acknowledgments</h2>

<ul>
  <li><strong>OpenAI</strong> for providing the powerful GPT-4 API.</li>
  <li><strong>Django</strong> for being an amazing web framework.</li>
</ul>
