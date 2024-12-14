

### **1. Messages**

- **What it is:** "Messages" is just the conversation history between you and the model. It includes everything that’s been said so far—what you’ve asked and what the model has answered.
  
- **How it works:** The model uses these messages to understand the conversation and give relevant, context-aware responses. So if you ask a follow-up question, the model knows what you’re talking about based on previous messages.

---

### **2. Model**

- **What it is:** "Model" refers to which version of the AI you're using, like GPT-3, GPT-4, etc.
  
- **How it works:** Different versions of the model are trained differently. Newer versions (like GPT-4) are better at understanding complex ideas and giving detailed answers, while older versions (like GPT-3) might be faster but less advanced.

---

### **3. Max Completion Tokens**

- **What it is:** "Max completion tokens" sets the limit for how long the model’s answer can be. The limit is in "tokens," which are usually words or parts of words.
  
- **How it works:** If you set a low number of tokens, the model will give shorter answers. If you set a higher number, it will be able to give longer responses. Once it hits that token limit, the answer stops.

---

### **4. n**

- **What it is:** "n" tells the model how many different responses to generate.
  
- **How it works:** If you set `n` to 3, the model will give you 3 different responses to the same question. This is helpful if you want to compare a few options before choosing one.

---

### **5. Stream**

- **What it is:** The "stream" setting decides whether the model sends the answer all at once or piece by piece as it generates it.
  
- **How it works:** If set to `true`, the model will start sending parts of its answer as soon as it begins generating them. If set to `false`, you’ll get the whole answer at once when it's done.

---

### **6. Temperature**

- **What it is:** "Temperature" controls how creative or random the model's answers are.
  
- **How it works:** A low temperature (like 0.2) means the model will give more predictable, focused answers. A high temperature (like 0.8) makes the answers more varied and creative. If you set it to 1, the model becomes more unpredictable.

---

### **7. Top_p**

- **What it is:** "Top_p" helps the model choose which words to consider when responding.
  
- **How it works:** Instead of picking from every possible word, the model will pick from the most likely words, based on the value you set for `top_p`. For example, with a `top_p` of 0.9, the model only looks at the top 90% of likely words to form a response. This helps make responses feel more natural.

---

### **8. Tools**

- **What it is:** "Tools" are external features or services the model can use to get extra information or perform tasks.
  
- **How it works:** If the model needs to do something it can't handle on its own (like looking up the weather or solving a complex math problem), it can use these tools to get the information it needs and give a more accurate answer.

