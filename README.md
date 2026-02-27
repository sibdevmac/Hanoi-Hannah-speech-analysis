# 🧠 Psychological Warfare Analysis: Hanoi Hannah Speech (1970)

## 📌 Project Overview

Hanoi Hannah played a significant role in attempting to demoralize American troops during the Vietnam War through psychological broadcasting.  

This project dives deep into one of her speeches to extract measurable insights using Python-based text analysis techniques.

📎 **Speech Source:**  
https://alphahistory.com/vietnamwar/hanoi-hannah-1970/

The goal of this project is to analyze the speech using Natural Language Processing (NLP) techniques and determine whether it qualifies as psychological propaganda.

---

## 🛠 Libraries Used

- `re` (Regular Expressions) – for text cleaning
- `collections.Counter` – for word frequency analysis
- `matplotlib` – for visualization

---

## 🧹 Step 1: Text Cleaning & Word Count

The first step involved:
- Removing punctuation
- Converting text to lowercase
- Cleaning extra spaces
- Tokenizing words

Using `Counter`, word frequencies were calculated to understand dominant themes in the speech.

This helped identify repeated linguistic patterns used to influence the audience.

---

## 🎯 Step 2: Pronoun Usage (Direct Psychological Targeting)

<img width="563" height="453" alt="image" src="https://github.com/user-attachments/assets/563c9f8e-327d-413d-958b-7805bfc62e75" />


Key finding:
- The most frequent pronoun was **“you”**
- Followed by **“your”**

### Insight:
The speaker consistently addresses American soldiers directly.  
This indicates a deliberate attempt to personalize the message and psychologically target individual soldiers.

---

## ⚠ Step 3: Fear and Threat Language Analysis

<img width="567" height="483" alt="image" src="https://github.com/user-attachments/assets/4c586e83-97e3-4875-860c-17e80ffc3f6d" />

Most frequent words:
- defeat
- never

### Insight:
The repetition of words like *“defeat”* and *“never”* suggests:
- Emphasis on inevitability
- Psychological intimidation
- Attempt to create hopelessness

This reflects classic fear-amplification strategy in psychological warfare.

---

## 👨‍👩‍👧 Step 4: Family-Based Emotional Manipulation

<img width="576" height="488" alt="image" src="https://github.com/user-attachments/assets/2c8546c7-9b26-4458-8566-c2981f4aad07" />

Common words:
- loved
- homes
- parents
- children

### Insight:
The speech heavily references family connections to:
- Trigger homesickness
- Create emotional vulnerability
- Encourage desertion or refusal to fight

This reflects emotional persuasion techniques often used in wartime propaganda.

---

## 🏛 Step 5: Authority Undermining Language

<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/23df6f46-1fc6-4501-ac7e-76018c9c59fd" />

Frequent words:
- government
- imperialist
- officers

### Insight:
These words suggest:
- Delegitimization of leadership
- Framing soldiers as manipulated
- Use of ideological language (e.g., “imperialist”)

This aligns with classical communist rhetorical framing used during the Vietnam War.

---

## 📊 Step 6: Sentiment Analysis

Calculated values: Negative (8) and Positive (3)


### Insight:
The speech is heavily negatively biased.  
Negative emotional language outweighs positive framing.


## 🧮 Step 7: Propaganda Index

The **Propaganda Index** was computed as: 
Sentiment_Bias + pronoun_score + fear_score + authority_score + question_score
The result came to be 72. Since **72 >> 30**, this indicates extremely strong psychological warfare characteristics.

## 🎖 Conclusion

The analysis shows that:

- The speech was strategically constructed.
- It aimed to lower morale among American troops.
- It aligns more closely with psychological warfare (PSYOPS) than ordinary political messaging.

This project highlights how:

> Language, repetition, emotional triggers, and framing can influence morale during conflict.

It demonstrates that psychological communication strategies can be powerful tools in warfare contexts.

## Author
Sibankar Saha
