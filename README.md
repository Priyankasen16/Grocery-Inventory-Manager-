

<h1 align="center">🛍️ FreshMart Inventory Tracker</h1>

<p align="center">
  <em>A simple desktop app to help small grocery shops manage stock effortlessly.</em><br>
  <strong>Built with Python, Tkinter, and JSON for local, offline storage.</strong>
</p>

<hr>

<h2>✨ What this project does</h2>
<ul>
  <li>📦 Add items with expiry dates</li>
  <li>📋 View and search your entire inventory</li>
  <li>🔄 Update stock quantities anytime</li>
  <li>🗑 Remove items you no longer need</li>
  <li>⚠️ Get notified automatically when stock is low (below 10)</li>
</ul>

<p>All inventory data is saved locally in a JSON file (<code>inventory.json</code>), so you don’t need any internet connection.</p>

<hr>

<h2>🚀 Quick Start</h2>
<ol>
  <li>Make sure you have <strong>Python 3</strong> installed.</li>
  <li>Install dependencies:
    <pre>pip install tkcalendar</pre>
  </li>
  <li>Run the app:
    <pre>python inventory_app.py</pre>
  </li>
</ol>
<p>✅ The application window should open — ready to use!</p>

<hr>

<h2>🛠 Tech Stack & Tools</h2>
<table>
  <tr>
    <td>GUI</td>
    <td><code>Tkinter</code> & <code>ttk</code></td>
  </tr>
  <tr>
    <td>Date picker</td>
    <td><code>tkcalendar</code></td>
  </tr>
  <tr>
    <td>Data storage</td>
    <td>Local <code>JSON</code> file</td>
  </tr>
  <tr>
    <td>Alerts</td>
    <td><code>tkinter.messagebox</code></td>
  </tr>
</table>

<hr>

<h2>🏗 How it works</h2>
<ul>
  <li>Displays all items in a <strong>Treeview table</strong></li>
  <li>Lets you add items with categories, quantity, price, and expiry date</li>
  <li>Updates quantity via a pop-up dialog</li>
  <li>Shows warnings if items have low stock when the app starts</li>
  <li>All changes automatically save to <code>inventory.json</code></li>
</ul>

<hr>

<h2>📂 File Overview</h2>
<pre>
inventory_app.py   # Main application code
inventory.json     # Stores the inventory data
README.md          # Project documentation
</pre>

<hr>

<hr>

<h2>✏️ Want to contribute?</h2>
<ol>
  <li>Fork this repository</li>
  <li>Make your changes</li>
  <li>Open a pull request</li>
</ol>

<hr>

<h2>👤 Author</h2>
<p>Created by <strong>PRIYANKA SEN</strong> to help local businesses track inventory simply and reliably.</p>
<p>⭐ If you find this useful, give it a star or share it with others!</p>

<hr>

<h4 align="center">Together, we simplify inventory management 🧡</h4>


