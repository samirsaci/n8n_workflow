_Tags: Supply Chain Management, Logistics, Transportation_

### Context

Hey! I'm Samir, a **Supply Chain Engineer and Data Scientist from Paris** founder of
[LogiGreen Consulting](https://www.logi-green.com/)

We design tools to help **small and medium businesses** in **improving their logistics processes** using data analytics and **automation**.

&gt; Let's use N8N to make supply chains **more efficient and sustainable Supply Chains!**

📬 For business inquiries, you can add me on [Here](https://www.linkedin.com/in/samir-saci)

### Who is this template for?

This workflow template is designed for **logistics operations** that cannot rely on a **Transportation Management System** to **record proofs of deliveries**.

![Example of Logistic Operations](https://www.samirsaci.com/content/images/size/w1000/2025/03/image-19.png)

### What is a delivery confirmation?

This workflow uses a **Telegram bot** to automatically notify **logistics teams** by email when a **shipment is delivered**.

![Example of Delivery Notice](https://www.samirsaci.com/content/images/2025/03/image-7.png)

Drivers (equipped with their smartphones) can **record their arrival** with all the necessary information for accurate distribution planning.

### How do we notify the delivery?

Let us imagine a truck driver arriving at the destination; he can contact the bot to be guided on how to record the delivery.

![Screens of Telegram Discussion](https://www.samirsaci.com/content/images/size/w1000/2025/03/image-6.png)

0. **User Guide**: the first bot's message is a brief explanation of the process
1. **Record Shipment Number**: the bot asks the driver to share the shipment number and record it
2. **Collect GPS Location**: the bot asks the driver to share its GPS location and record them
3. **Picture of the Shipment**: the bot asks for a picture of the shipment and saves it in Google Drive
4. **Send Confirmation**: after data collection, the bot proposes to send a confirmation to the logistics management team

An email is then automatically sent by the N8N workflow including all the information recorded by the flow and a picture of the shipment.

![Example of Notification via Email](https://www.samirsaci.com/content/images/2025/03/image-5.png)

### Prerequisite

This workflow does not require any additional paying subscription.

- A **Google Drive Account** with a folder including a Google Sheet
- API Credentials: **Google Drive API**, **Google Sheets API** and **Gmail API**
- A Telegram Bot with its API token from BotFather
- A Google sheet to store the shipment records with these five columns prepared: **shipmentNumber, recordTime, gpsLattitude, gpsLongitude, cargoPicture, deliveryTime**

### Next Steps

Follow the **sticky notes** to set up the parameters inside each node and get ready to improve your logistics operations!

I have detailed the steps in a **short tutorial** 👇
[![image.png](https://www.samirsaci.com/content/images/2025/04/Telegram-Shipment-Tracking.png)](https://youtu.be/9NS4RYaOwJ8)
🎥 [Check My Tutorial](https://youtu.be/9NS4RYaOwJ8)

🚀 Interested in applications of N8N for Logistics & Supply Chain Management? Let's connect on [Linkedin](www.linkedin.com/in/samir-saci)

### Notes

- This workflow can be adapted to add more functionalities. I explain how in the video.
- The bot can handle multiple drivers at the same time.
- If you want to learn more about the original tool designed with Python: 🚚 [Blog Article about Telegram Shipment Tracking Bot](https://www.samirsaci.com/build-a-shipment-tracking-tool-using-a-telegram-bot/)

_This workflow has been created with N8N 1.82.1_
_Submitted: March 17th, 2025_
