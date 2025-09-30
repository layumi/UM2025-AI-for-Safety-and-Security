# 🖥️ Lab Manual: Natural Language Analysis with Large Language Models

## 🎯 Objectives
- Learn how to use large language models (LLMs) for **summarization**, **sentiment analysis**, and **interrogation simulation**.  
- Practice **prompt engineering** instead of programming.  
- Understand the **potential benefits and risks** of using AI in law enforcement and public opinion monitoring.  

---

## 🔧 Preparation
1. Each group should have access to a computer with internet connection.  
2. Use any available LLM platform:  
    - [Deepseek](https://www.deepseek.com/)
    - [Tongyi](https://www.tongyi.com/)
    - [Doubao](https://www.doubao.com/chat/)
3. Copy the provided **case texts (in Chinese)** to be used as inputs.  

---

## 📝 Tasks

### Task 1: Summarizing a Police Report

**Case Text (Chinese):**

2023年8月15日晚上9点，李某报警称其停放在小区地下车库的电动车被盗。李某表示，当天晚上7点左右还看到车停在原处，价值约3500元。监控显示一名身穿黑色外套的男子在8点45分进入车库，之后李某的电动车不见踪影。

**Prompt Template (English):**
> Please summarize the following police report. Extract the key information in bullet points, including:  
> - Time  
> - Location  
> - People involved  
> - Incident details  
> - Property loss  

**Reflection Questions:**
- If you remove “extract time and location,” does the model still capture them?  
- Are there any errors or missing details in the summary?  

---

### Task 2: Sentiment Analysis of Social Media Posts

**Case Text (Chinese):**
1. 太离谱了！居然发生这种事，真的让人愤怒。

2. 虽然情况不太好，但我相信很快会有解决办法。

3. 哈哈哈，看到这个新闻笑死我了。

4. 我觉得挺无语的，怎么会有人做出这种决定？

5. 太好了！终于等到官方回应，点赞！


**Prompt Template (English):**
> Analyze the sentiment of the following 5 social media comments. Classify each as **positive, negative, or neutral**, and provide one sentence explaining the overall public opinion.  

**Reflection Questions:**
- Does the model’s classification match your personal judgment?  
- How would the results change if you used English translations instead of Chinese text?  

---

### Task 3: Interrogation Simulation

**Case Background (Chinese):**

嫌疑人王某在超市盗窃多件化妆品，总价值约2000元。他在被抓获后承认盗窃事实，但拒绝说明作案动机。


**Prompt Template (English):**
```
1. You are an interrogator. The suspect has admitted theft but refuses to explain the motive. Please generate **3 follow-up questions** that could help reveal the hidden motive.  
```

```
2.  Based on the suspect’s background and statements, what information might he still be **hiding**?  
```

**Reflection Questions:**
- Are the AI-generated questions logical and useful?  
- If you slightly change the wording of the prompt, how does the model’s response change?  

---

## 📊 Lab Report Requirements
Each student should have a short report (1–2 pages) including:  
1. Screenshots of prompts and outputs for each task.  
2. A summary of what types of prompts worked best.  
3. Critical reflection: What problems or risks did you observe in AI-generated results?  

---

## ⚠️ Notes
- **Privacy:** All case texts are fictional. Do not use real personal data.  
- **Critical Thinking:** Treat AI outputs as suggestions, not absolute truth.  
- **Exploration:** Feel free to try different prompts or different LLMs and compare the results.  


