![title](https://github.com/user-attachments/assets/8a57303f-5b9f-4ec3-bb64-136c3dc4cd13)

## **🌎 SDGs (Sustainable Development Goals) Contributed by This App**

### **✅Goal 11: Sustainable Cities and Communities**

- Encourages local residents to voluntarily clean up litter and maintain urban/natural spaces
- Records location-based cleanup activities and visualizes them on a map → promotes community engagement

### **✅Goal 12: Responsible Consumption and Production**

- Raises user awareness of the severity and environmental impact of waste
- Optional **recycling education feature** (e.g., categorize plastics, cans, glass, etc.)

### **✅Goal 13: Climate Action**

- Ecosystem preservation through environmental cleanup → indirect reduction of greenhouse gas emissions
- Uses LLM-generated messages to link user actions to climate change impacts

### **✅Goal 14: Life Below Water**

- Coastal trash removal → directly contributes to marine life protection
- Messages like “Thanks to you, a sea turtle was saved!” align with this goal

### **✅Goal 15: Life on Land**

- Cleans up mountains, valleys, forests → protects wildlife habitats
- Highlights individual actions that contribute to ecosystem conservation

### **🎯Problem Awareness**

1. *Illegal dumping in natural environments* (beaches, mountains, valleys, etc.) is a serious issue  
2. Many cleanup efforts exist but **lack sustained motivation**  
3. **Gamification** boosts participation among volunteers

---

### **🧩Core Features**

### **1. 🎥Photo Analysis & Scoring (AI Vision)**

- Users upload **after-cleanup photos**
- AI analyzes how much trash was removed
- Assigns scores based on cleanup level (e.g., grades like A–F or 0–100 points)
- **Difficulty adjustment**: considers environment type such as beach or mountain

> ✅ Technologies: Image Segmentation (YOLOv8 + SAM), Optical Flow, Change Detection

---

### **2. 🧠LLM-based Encouragement Feedback Generation**

- Generates **natural language feedback** based on scores
- Example output:

<aside>
💡

Congratulations! You cleaned about 3kg of plastic from the beach. Thanks to you, a sea turtle’s life was saved! 💙

</aside>

- Simulated environmental impact messages also provided
    - “If this trash hadn't been removed, it would’ve taken 5 years to decompose.”

> ✅ Technologies: Gemini API prompt customization using a trash impact database

---

### **3. 🗺️ Location-Based Activity Visualization**

- Logs cleanup activities based on user GPS location
- **Aggregates cleanup scores by region**
    - Neighborhood/regional leaderboards
- Personal dashboard showing total trash cleaned, number of participations, etc.

> ✅ Technologies: GPS integration,FusedLocationProviderClient

---

### **🎮(Expected)Additional Game Elements**

- **Level-up system**: Users level up based on trash amount/score
- **Title system**: Earn badges like “Valley Spirit,” “Sea Guardian”
- **Team system**: Join guilds or parties to plan cleanup missions or compete in team scores
- **Ranking system**: Compete with others based on personal scores
- **Daily quests**: “Collect only plastics today!”, “Clean more than 3kg of trash”
- **Friend invite/co-op mode**: Tackle cleanup challenges with friends
- **Reward system**: Earn souvenirs, donation points, or connect with environmental organizations

---
### Feature
![poster1](https://github.com/user-attachments/assets/8db3929a-a285-4235-a329-94b31b33bb6d)
![poster2](https://github.com/user-attachments/assets/ad02900b-858f-49e3-8922-70481c3d1467)


