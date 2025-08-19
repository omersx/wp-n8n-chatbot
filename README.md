# n8n Chatbot Widget  

A customizable, responsive **AI-powered chatbot widget** built in a single HTML file.  
This chatbot is designed to integrate with **n8n workflows** via webhook URLs, making it easy to embed automation and AI responses into any website (WordPress, static sites, or custom apps).  

## 🚀 Features  

- ✅ **Direct n8n integration** (via webhook URL)  
- ✅ **Markdown support** for bot messages (headings, lists, code blocks, quotes, etc.)  
- ✅ **File upload support** (images, PDFs, text, docs) → sent to n8n workflow  
- ✅ **Customizable UI** (colors, avatars, welcome message, bot name)  
- ✅ **Quick replies** dynamically provided by n8n  
- ✅ **Typing indicator & status dot** (Online / Connecting / Failed)  
- ✅ **Mobile-friendly & responsive design**  
- ✅ **Zero external dependencies** (pure HTML, CSS, JS)  

## 📦 Installation  

1. Download the chatbot file:  
   ```bash
   WP-chatbot-n8n.html
2.Add it to your WordPress site or any website:

WordPress: insert into a page/post using Code Snippets or a custom HTML block.

Static site: just drop the file and include it with <iframe> or inline.
Update the n8n webhook URL inside the file:
  ```
const chatbotConfig = {
  webhookUrl: "YOUR_N8N_WEBHOOK_URL_HERE", 
  ...
};
  ```
Example:
  ```
webhookUrl: "https://yourname.app.n8n.cloud/webhook/513107b3-xxxx"
  ```
