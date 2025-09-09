# n8n Chatbot Widget  

A customizable, responsive **AI-powered chatbot widget** built in a single HTML file.  
This chatbot is designed to integrate with **n8n workflows** via webhook URLs, making it easy to embed automation and AI responses into any website (WordPress, static sites, or custom apps).  

# 📷 UI Previews

| Theme  | Preview |
|--------|---------|
|  Blue  | Blue Chatbot UI <img width="2560" height="1440" alt="blue2" src="https://github.com/user-attachments/assets/4073edf1-80ca-474a-b566-269148cb2326" />|
|red-dark  | red night Chatbot UI <img width="1920" height="1080" alt="redui" src="https://github.com/user-attachments/assets/8edf3d3d-9ea9-44f2-a716-03b67313795e" />|
|Green | Green  Chatbot UI <img width="2560" height="1440" alt="gree-ui1" src="https://github.com/user-attachments/assets/a4657891-bb49-48a2-af8a-f271d012bda0" />|
|  Blue-dark  | Blue night Chatbot UI <img width="2560" height="1440" alt="blue-dark" src="https://github.com/user-attachments/assets/2e99e172-8728-4c88-829c-2bdd6586db30" />|
|Purple| modern purple  Chatbot UI <img width="3280" height="1712" alt="modern" src="https://github.com/user-attachments/assets/3a5b7436-5d94-49ce-8c06-0629b89e55cf" />
|

Lightweight HTML-based AI assistant widget for WordPress. Compatible with N8N, customizable , and visual themes included.

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
-----------
## 📜 License

-This project is open-source under the MIT License.

## 🤝 Contributions

- Feel free to open issues, suggest features, or submit pull requests. Let’s build smarter web experiences together!

