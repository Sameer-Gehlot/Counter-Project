# Counter Project
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Counter App — README</title>
  <style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial; line-height:1.6; color:#0b1220; background:#f7fafc; padding:32px; }
    .card { background:#fff; border-radius:10px; padding:24px; max-width:900px; margin:0 auto; box-shadow:0 6px 20px rgba(2,6,23,0.06); }
    h1,h2 { color:#0f1720; margin:0 0 12px 0; }
    h1 { font-size:28px; }
    h2 { font-size:20px; margin-top:18px; }
    p { margin:8px 0; }
    ul { margin:8px 0 8px 20px; }
    code { background:#eef2ff; padding:2px 6px; border-radius:6px; font-family:monospace; }
    .images { display:flex; gap:12px; flex-wrap:wrap; margin-top:12px; }
    .images img { width:320px; max-width:100%; border-radius:8px; box-shadow:0 6px 18px rgba(2,6,23,0.08); }
    .note { background:#fff8e6; padding:10px; border-left:4px solid #f6c85f; margin:14px 0; border-radius:6px; }
    .small { color:#475569; font-size:14px; }
  </style>
</head>
<body>
  <div class="card">
    <h1>Counter App — README</h1>

    <h2>📌 Project Overview</h2>
    <p>This is a simple <strong>Counter App</strong> built to understand the basics of the <strong>DOM (Document Object Model)</strong> in JavaScript. The goal of this project was to practice updating values in real time, handling events, and controlling HTML elements using JavaScript.</p>

    <h2>📚 What I Learned Today</h2>
    <ul>
      <li><strong>What the DOM is</strong> and how the browser represents a webpage</li>
      <li><strong>Selecting elements</strong> using <code>getElementById()</code> and <code>querySelector()</code></li>
      <li><strong>Changing HTML content</strong> using <code>textContent</code></li>
      <li><strong>Changing CSS styles</strong> using <code>element.style.property</code></li>
      <li><strong>Event Listeners</strong> to run functions on button clicks</li>
      <li><strong>Basic logic building</strong> for increasing and decreasing values</li>
    </ul>

    <p class="small">These concepts helped me understand the four main pillars of the DOM: Selecting Elements, Changing HTML, Changing CSS, and Event Listeners.</p>

    <h2>🔢 Counter App (Short Description)</h2>
    <p>In this project:</p>
    <ul>
      <li>A heading displays the current number (default = 0)</li>
      <li>There are two buttons → <strong>Increase</strong> and <strong>Decrease</strong></li>
      <li>Clicking the buttons increases or decreases the count</li>
      <li>JavaScript updates the UI through DOM manipulation</li>
    </ul>

    <h2>🖼 Screenshots</h2>
    <p>Place your images named <code>snap1.png</code> and <code>snap2.png</code> inside a folder called <code>screenshots</code> (at repo root). Example:</p>
    <pre class="small"><code>counter-project/
├─ index.html
├─ style.css
├─ script.js
└─ screenshots/
   ├─ snap1.png
   └─ snap2.png
</code></pre>

    <div class="images">
      <img src="screenshots/snap1.png" alt="Screenshot 1 (snap1.png)" />
      <img src="screenshots/snap2.png" alt="Screenshot 2 (snap2.png)" />
    </div>

    <h2>💬 My Experience</h2>
    <p>This project is simple, but it helped me understand how the DOM actually works. I learned how to use event listeners, update values, and control webpage elements with JavaScript. It’s a solid and important step in my web development journey.</p>

    <div class="note">
      <strong>Note:</strong> If you paste this HTML inside <code>README.md</code>, GitHub will render the HTML. Make sure your <code>screenshots/</code> folder exists and images are named correctly.
    </div>

    <p class="small">If you want a shorter version, a more professional recruiter-friendly version, or the plain Markdown version, tell me and I'll prepare it.</p>
  </div>
</body>
</html>
