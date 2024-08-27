<h1 style="text-align: center;">Todopro</h1>
<p style="text-align: center;">Todopro is a command-line tool for managing your to-do list. It allows you to add, delete, mark as done, and manage your tasks from the terminal. This document provides details on installation, usage, and key concepts related to Todopro.</p>

<h2>Quick Start - Node.js</h2>
<h3>Install:</h3>
<p>Install Todopro globally using npm:</p>
<pre><code>npm install -g todopro</code></pre>

<h3>Simple Usage:</h3>
<p>After installation, you can start using Todopro with the following commands:</p>
<pre><code>todopro add "&lt;task&gt;"</code></pre>
<pre><code>todopro rm "&lt;task&gt;"</code></pre>
<pre><code>todopro done "&lt;task&gt;"</code></pre>
<pre><code>todopro edit &lt;id&gt;</code></pre>
<pre><code>todopro ls</code></pre>
<pre><code>todopro ls p</code></pre>
<pre><code>todopro ls d</code></pre>
<pre><code>todopro reset</code></pre>
<pre><code>todopro h</code></pre>

<h2>Features</h2>
<ul>
    <li><strong>Add new tasks:</strong> Easily add tasks to your to-do list.</li>
    <li><strong>Mark tasks as done:</strong> Update the status of tasks to done.</li>
    <li><strong>Edit tasks:</strong> Modify existing tasks by their ID.</li>
    <li><strong>Remove tasks:</strong> Delete tasks from your list.</li>
    <li><strong>List tasks:</strong> View all tasks, pending tasks, or completed tasks.</li>
    <li><strong>Reset all tasks:</strong> Clear all tasks from the list.</li>
    <li><strong>Display help information:</strong> Get a list of available commands and their usage.</li>
</ul>

<h2>Key Concepts</h2>
<ul>
    <li><strong>Command-Line Interface (CLI):</strong> Learn how to create and manage a CLI tool using <code>commander</code> and other Node.js modules.</li>
    <li><strong>File System Operations:</strong> Understand how to use the <code>fs</code> module to read and write files for persistent storage of tasks.</li>
    <li><strong>User Interaction:</strong> Utilize <code>readline-sync</code> for interactive command-line input.</li>
    <li><strong>Styling Output:</strong> Use <code>chalk</code> for colored and styled console output.</li>
    <li><strong>Text Art:</strong> Incorporate <code>figlet</code> for text-based art in the CLI.</li>
</ul>

<h2>How to Explore</h2>
<p>To explore Todopro CLI tool:</p>
<ul>
    <li><strong>Install Todopro:</strong> Install the CLI globally using npm with <code>npm install -g todopro</code>.</li>
    <li><strong>Run Commands:</strong> Use commands like <code>todopro add "&lt;task&gt;"</code>, <code>todopro rm "&lt;task&gt;"</code>, <code>todopro done "&lt;task&gt;"</code>, <code>todopro edit &lt;id&gt;</code>, <code>todopro ls</code>, <code>todopro ls p</code>, <code>todopro ls d</code>, <code>todopro reset</code>, and <code>todopro h</code> to interact with the to-do list.</li>
    <li><strong>Check the Help Menu:</strong> Display help information using <code>todopro h</code> to see available commands and usage.</li>
    <li><strong>Modify the Code:</strong> Review and modify the code to add new features or improve functionality.</li>
</ul>

<h2>Author</h2>
<p style="text-align: center;">&copy; Muhammad Zafar Ul Haq</p>

<h2>Contributing</h2>
<p style="text-align: center;">Contributions are welcome! Please open an issue or submit a pull request on the <a href="https://github.com/zafar1162014/todopro">GitHub repository</a>.</p>
