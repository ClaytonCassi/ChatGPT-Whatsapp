<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
    <h1>ChatGPT-WhatsApp</h1>
    <p>This repository contains the ChatGPT-WhatsApp project, an application that integrates the OpenAI ChatGPT API with the WhatsApp messaging service, allowing users to interact with the language model directly through the messaging app.</p>
less
Copy code
<h2>Prerequisites</h2>
<ul>
    <li>Javascript</li>
    <li>Twilio account and access to the WhatsApp sandbox with credentials</li>
    <li>Whatsapp business</li>
    <li>OpenAI API key</li>
</ul>



<h2>Configuration</h2>
<ol>
    <li>Rename the <code>.env.example</code> file to <code>.env</code> and fill in the environment variable values with your Twilio and OpenAI credentials.</li>
    <li>Ensure the phone number is properly configured in the Twilio sandbox and connected to the WhatsApp application.</li>
</ol>

<h2>Execution</h2>
<ol>
    <li>npm i.</li>
    <li>change env.local 
TWILIO_ACCOUNT_SID=YOUR_ACCOUNT_SID
TWILIO_AUTH_TOKEN=YOUR_ACCONT_TOKEN
OPENAI_API_KEY='YOUR_API_KEY'
</li>
    <li> npm run dev <li/>
</ol>

<h2>Contributing</h2>
<p>Contributions are welcome! Feel free to open an issue or submit a pull request.</p>

<h2>License</h2>
<p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.</p>
</body>
</html>
