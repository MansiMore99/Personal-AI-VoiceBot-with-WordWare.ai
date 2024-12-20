
If you’re new to WordWare.ai, check out my previous blogs on how to build a basic AI app using their platform. 
Once you’re familiar, you’ll realize how simple it is to get started. 

Please check out: 
- [AI App To Generate Recipes From Food Image](https://medium.com/@mansi.more943/ai-app-to-generate-recipes-from-food-image-4eafb93d2450)
- [How to Build an AI App which Turns Household Items into Craft Ideas](https://medium.com/@mansi.more943/turning-household-items-into-craft-ideas-with-ai-3dfd58010511)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### **Let’s Build a Personal VoiceBot:**

#### 1. **Sign in to Wordware.ai 🔑**
🚀 Head over to Wordware.ai and log in to get started!

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### **2. Create a New Project** 🛠️

#### **3. Create a Flow:**

Tap Create a New Flow to begin the magic, Name it, and set the input type.

#### **4. Greeting the User:**

First, I wanted my assistant to greet me and, if it’s a new user, provide a brief introduction like:


```
“Hey, I am your personal assistant. How can I help you today?”
```

For this, I used ElevenLabs’ text-to-speech API to generate the output.


<img width="1437" alt="Screenshot 2024-12-20 at 3 42 56 AM" src="https://github.com/user-attachments/assets/14787b7e-fe57-442f-ab5d-947e028af30a" />


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### **5. Taking the User’s Query**


Next, the VoiceBot takes the user’s query as an audio input.


<img width="1345" alt="Screenshot 2024-12-20 at 3 44 55 AM" src="https://github.com/user-attachments/assets/aeb2eb20-d03a-4509-829d-3b65763e5595" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------


#### **6. Web Search for Responses**


I used a web search based on the user’s query to gather relevant information. By just entering ‘/’ for commands.


<img width="1139" alt="Screenshot 2024-12-20 at 3 46 59 AM" src="https://github.com/user-attachments/assets/5e395736-7755-44f0-bfd2-475d033dd679" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### **Note:** The most important and easiest task, add ai generation ( placeholder to add LLM completion).


<img width="1456" alt="Screenshot 2024-12-20 at 3 50 51 AM" src="https://github.com/user-attachments/assets/4f31daac-1676-4b1c-a446-7672d1edfe30" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### **7. Generating a Response**

Last, the VoiceBot produces a brief summary based on the Web search results (I used Claude 3.5 LLM here), which totals 100 words at most because, come on, let AI be intelligent and precise.

<img width="787" alt="Screenshot 2024-12-20 at 3 49 09 AM" src="https://github.com/user-attachments/assets/fcf1fae8-2b94-4afe-93f3-441608807b7a" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------


And tadaaaaa….. it’s ready! 🎉

<img width="938" alt="Screenshot 2024-12-20 at 4 03 07 AM" src="https://github.com/user-attachments/assets/05a2ee9c-3bee-4100-90da-ad99fb23d905" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Currently, I am trying to improve it with the new features. So, this is a simple demo of my app, which I did in a few minutes.

Go ahead, give it a shot, and enjoy creating something awesome. I’m excited to hear how it turns out!

* **Application:**

https://app.wordware.ai/explore/apps/6a3ab4be-74e2-4ffe-8148-a7bfe0d8187a

* **Contributing:**

Do you have any project ideas in your mind? Would you be interested in contributing? I welcome your improvements and ideas.

```
Happy Coding!!! 😄 🤜🤛
```
