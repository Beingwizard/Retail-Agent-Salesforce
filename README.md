# 🛍️ Retail-Agent-Salesforce

Build a Retail Shopping Agent using **Salesforce Agentforce** to place online orders through an AI agent.

---

## 📌 Overview

This repository walks you through setting up a **Retail AI Agent** using **Salesforce Agentforce**.
You’ll configure an org, enable Agentforce, create your agent, add topics, attach actions, and finally test your agent by placing an order.

All steps include screenshots for easy navigation.

---

## 🚀 Getting Started

### 1️⃣ **Create Your Retail Agentforce Org**

Access the Agentforce trail orgs here:

🔗 [https://orgfarm.salesforce.com/signup](https://orgfarm.salesforce.com/signup) *(open this in **incognito** mode)*

Choose the **Retail Use Case** (first option):

<img width="1600" height="607" src="https://github.com/user-attachments/assets/1b2eb000-b06c-4ae7-b4e7-f7b691e11f9b" />

Fill in your basic details:

<img width="1600" height="1019" src="https://github.com/user-attachments/assets/abca5c13-c918-482f-98e5-4a40cedd500c" />

Use your college name as the company name (e.g., *XYZ University*):

<img width="1600" height="568" src="https://github.com/user-attachments/assets/6876b367-d914-4f9e-9ecb-afc6d4a414f6" />

Click **Get My Credentials** and complete the form:

<img width="1384" height="1596" src="https://github.com/user-attachments/assets/912aea44-930e-4099-9c1f-770aee768f68" />

Copy the login URL and log in using the provided username/password:

<img width="1322" height="1600" src="https://github.com/user-attachments/assets/7188b2f3-6208-4321-8a8d-17962a5a838b" />

Do **NOT** close the tab with the manual:

<img width="1600" height="883" src="https://github.com/user-attachments/assets/ab05047a-8055-49e2-95d2-43f04bbf15ec" />

---

## ⚙️ 2️⃣ Enable Einstein & Agentforce

Click the settings icon:

<img width="1600" height="954" src="https://github.com/user-attachments/assets/d0b4c71d-965d-4c03-9a6a-d249d936ee6f" />

Choose **Setup**:

<img width="1600" height="620" src="https://github.com/user-attachments/assets/df3e4580-af9e-4682-b12d-665790a03469" />

Search **Generative**, click **Einstein Setup**:

<img width="1600" height="798" src="https://github.com/user-attachments/assets/d6438391-f716-4912-b24d-a862ad11e763" />

Toggle ON the first Einstein switch:

<img width="1600" height="917" src="https://github.com/user-attachments/assets/6b3cb334-c935-4fcc-a8c2-cae8877ff1f5" />

Search **Agent**, then open **Agentforce Agents**:

<img width="1600" height="941" src="https://github.com/user-attachments/assets/7fcf690f-c301-4bd8-b45a-77b3db037cf5" />

Toggle ON Agentforce:

<img width="1600" height="879" src="https://github.com/user-attachments/assets/a2216af5-9567-47ea-8abb-1c7f52d0085b" />

<img width="1600" height="936" src="https://github.com/user-attachments/assets/81b08cdf-2779-443f-95e5-7321b84c78e4" />

---

## 🤖 3️⃣ Create Your Agent

Click **+ New Agent**:

<img width="1600" height="948" src="https://github.com/user-attachments/assets/84de3e7c-168b-447a-aace-bac996955ab1" />

Choose **Agentforce Service Agent**:

<img width="1600" height="962" src="https://github.com/user-attachments/assets/1219decc-6df6-4737-af61-d912f82fd9dd" />

Click **Next**:

<img width="1600" height="909" src="https://github.com/user-attachments/assets/81a4043e-8118-4758-b111-1cfdeff31864" />

You’ll see this screen:

<img width="1600" height="906" src="https://github.com/user-attachments/assets/8e5e79fb-6635-4c21-b878-0584fca8cd20" />

Remove all added items:

<img width="1600" height="905" src="https://github.com/user-attachments/assets/cc033576-8c98-4ebb-9ab6-7704eaf46003" />

Click **Next**:

<img width="1600" height="898" src="https://github.com/user-attachments/assets/4f0a40b2-3929-4608-bb20-a932308f1b86" />

Open **Exercise 2** in the manual:

<img width="1600" height="969" src="https://github.com/user-attachments/assets/5c863da7-b02b-467c-acb5-a6a27bf7fc18" />

Update fields:

* Replace **Label** with **Name**
* Copy **Description** from the manual
* Change the **Company**
* Change Agent User → pick the second **Einstein** option
* Check **Keep on record**

<img width="1600" height="909" src="https://github.com/user-attachments/assets/30b8a617-436c-4bd9-ab32-5e739e67b92a" />

If you get errors, close them:

<img width="1600" height="983" src="https://github.com/user-attachments/assets/0556a244-5d0d-4c7f-a017-8d18030fa7e9" />

Click **Create**:

<img width="1600" height="957" src="https://github.com/user-attachments/assets/7b7cd1fc-2043-45f5-afc0-96051baa0d08" />

Your screen should look like this:

<img width="1600" height="991" src="https://github.com/user-attachments/assets/349e7acc-6346-4c38-ae6e-3e9926b66631" />

---

## 🧠 4️⃣ Create a Topic

Click **New → New Topic**:

<img width="1600" height="971" src="https://github.com/user-attachments/assets/a15e5e9d-6269-4b64-aff6-3ee889ad7c40" />

Copy the prompt from manual:

<img width="1600" height="942" src="https://github.com/user-attachments/assets/db292a0e-6b3b-4454-90ca-0ea592a6d8fd" />

Paste it here:

<img width="1600" height="964" src="https://github.com/user-attachments/assets/00acf2c9-b0b1-4089-bcef-f95bd34150a0" />

You will see this screen:

<img width="1600" height="952" src="https://github.com/user-attachments/assets/ad2979ae-7771-4b05-9276-069941b65011" />

Replace the following from the table in the manual:

<img width="1600" height="1000" src="https://github.com/user-attachments/assets/2e542abe-0cf8-40e1-9d97-b4e10523a99e" />

Update:

* Topic Label → Name
* Description
* Scope
* Instruction (add one extra instruction if required)

<img width="1600" height="1002" src="https://github.com/user-attachments/assets/775afb1b-db81-452a-98f5-edc9ca54739b" />

Add missing instruction:

<img width="1600" height="1000" src="https://github.com/user-attachments/assets/23f895e4-a608-4a08-aa7d-3a41c2ec695f" />

Continue to the next screen:

<img width="1600" height="1000" src="https://github.com/user-attachments/assets/57e135bf-f97f-4a60-af9e-8d103fd33fd3" />

Add 3 actions:

* Get Customer Details
* Get Available Products
* Create Order

<img width="1600" height="258" src="https://github.com/user-attachments/assets/b5d9bdb7-7511-4d9e-957c-5071bba99b08" />

Your screen should look like this:

<img width="1600" height="848" src="https://github.com/user-attachments/assets/6e8b59b0-7b24-4477-826c-015758e33c83" />

Click **Finish**:

You will see:

<img width="1600" height="995" src="https://github.com/user-attachments/assets/0126fb6d-3d11-49a0-8c75-1001a8125282" />

---

## 🧪 5️⃣ Test Your Retail Agent

Open Q&A from manual:

<img width="1600" height="878" src="https://github.com/user-attachments/assets/24b3c9e5-61c9-4a69-afa7-647ad169ba6e" />

Paste it into:

<img width="1600" height="1000" src="https://github.com/user-attachments/assets/1d2c340c-d7c8-4160-820e-88c8348a188f" />

You should see:

<img width="1600" height="1000" src="https://github.com/user-attachments/assets/051d6730-5d91-4200-890b-9c74975bfb6b" />

Once you receive your **Order Number**, your agent is fully operational:

<img width="1600" height="973" src="https://github.com/user-attachments/assets/30f9fc10-8b43-47f7-8ca5-0c156460a2b2" />

---

## 🏅 6️⃣ Create Your Social Badge

Open **Share on your social** in the manual:

<img width="1600" height="993" src="https://github.com/user-attachments/assets/217b3dc2-05a3-43a9-a684-cf895729c98f" />

Upload & adjust your photo:

<img width="1600" height="1000" src="https://github.com/user-attachments/assets/b2f6d50a-64cf-4003-a276-9c93cfcc1ea2" />

Post on LinkedIn using:
🔗 [https://www.linkedin.com/company/salesforce/](https://www.linkedin.com/company/salesforce/)

---

## 🎉 Congratulations

You have successfully created your **Retail Shopping Agent** using Salesforce Agentforce!

---
