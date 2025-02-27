<h2>Theory</h2>
<p>Stored Cross-Site Scripting (XSS) is a type of security vulnerability commonly found in web applications. It occurs when an attacker injects malicious scripts, typically in the form of HTML or JavaScript, into a web application's database or storage. These scripts are then retrieved and displayed to other users who access the affected web pages. </p>
<h4>How It Works:</h4>

<li>Injection: An attacker injects malicious scripts into input fields that are stored on the server's database, such as comment sections, forums, or user profiles.</li>
<li>Storage: The injected scripts are saved alongside legitimate data entries in the database.</li>
<li>Execution: When other users view the affected pages, the malicious scripts execute in their browsers, potentially compromising their sessions, stealing cookies, or even modifying the content of the page.</li>
<h4>Prevention:</h4>

<li>Input Validation: Implement strict input validation to ensure that user-supplied data does not contain malicious scripts.</li>
<li>Output Encoding: Encode user-generated content properly before displaying it on web pages to prevent scripts from being interpreted as executable code.</li>
<li>Content Security Policy (CSP): Use CSP to specify which sources of content are allowed to be loaded, reducing the risk of executing injected scripts.</li>
