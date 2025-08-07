## 🚀 Deployment Guide: Writer Cloud

Follow these steps to deploy your application.

---

### 1. Navigate to Your Project Directory

Open your terminal and go to the folder where your `main.py` and `.wf/` files are located.

```bash
cd path/to/your/project
```

---

### 2. Deploy to Writer Cloud

Run the deployment command:

```bash
writer cloud deploy .
```

---

### 3. Enter API Key

When prompted:

```
Enter your API key:
```

Paste in your Writer API key and press **Enter**.

API Key: RcgXn8MTQEsfprz3ntggHO2ixo8p87bA

---

### 4. Confirm Overwrite (if prompted)

If this application was previously deployed, you’ll see:

```
This app already exists. Do you want to overwrite? (y/N)
```

Type `y` and press **Enter** to confirm.

---

### 5. Wait for Deployment

Writer will begin uploading files and building the application.  
You may see:

```
Deployment status timeout
```

This is normal — the app is still deploying in the background.

⏳ **Wait about 15–20 minutes**, and your app will become available at the deployment URL shown in the log, e.g.:

```
https://zt7y7q61.ai.writer.build
```

---

### ✅ Done!

Once deployed, you can access and test your app at the provided URL.  
If you make further edits, repeat the same steps to redeploy and overwrite the existing app.


