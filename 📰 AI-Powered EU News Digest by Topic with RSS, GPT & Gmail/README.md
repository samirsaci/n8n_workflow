*Tags: EU News, RSS, AI Classifier, Data Table, Email Digest, Automation, n8n*

### Context

Hi! I’m Samir! A Supply Chain Engineer and Data Scientist based in Paris, and founder of [LogiGreen Consulting](https://logi-green.com).

This workflow is part of my project to **automatically monitor European Union press releases, filter them with AI, and send a curated email digest every morning**.

![Workflow Overview](https://www.samirsaci.com/content/images/size/w1000/2025/11/image-4.png)

&gt; Turn raw EU press releases into a clean, topic-based newsletter — without writing a single line of backend code.

By default, the workflow filters **sustainability-related news**, but you can easily adapt the topic description (e.g. AI, trade, digital, energy) in the AI node.

📬 For business inquiries, you can find me on [LinkedIn](https://www.linkedin.com/in/samir-saci)

### Who is this template for?

This template is designed for:

- **Policy analysts and researchers** who want to track EU updates on a specific topic
- **Consultants and sustainability teams** who need a daily view of relevant announcements


### What does this workflow do?

This workflow acts as an **AI-powered EU news filter and digest generator**.


1. **Fetches the latest press releases** from the Council of the EU RSS feed every morning at 09:00  
2. **Uses an AI classifier** (OpenAI) to decide whether each article is relevant to your topic  
3. **Stores only the relevant items** in an **n8n Data Table**  
4. **Generates a formatted HTML newsletter** grouping the day’s relevant articles  
5. **Sends the digest by email** using the Gmail node  

Here’s an example of the generated email:

![Digest Example](https://www.samirsaci.com/content/images/size/w1000/2025/11/image-5.png)

### 🎥 Tutorial

A complete tutorial (with explanations of every node) is available on YouTube:

[![Tutorial + Demo](https://www.samirsaci.com/content/images/2025/11/temp-9.png)](https://youtu.be/vNavNGRqcK4)

### Next Steps

🗒️ Inside the workflow:

- Replace the Data Table reference with your own  
- Update the recipient email in the Gmail node with your credentials
- Customize the HTML digest (colors, logo, style) in the Code node  
- Adjust the schedule time if necessary  

*Submitted: 13 November 2025*