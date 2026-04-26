# llm-phishing-detection-capstone
# Evaluating LLMs for Spear Phishing Detection

This project evaluates the effectiveness of open-weight large language models (DeepSeek-R1, Llama 4 Scout, Qwen 2.5-72B) in detecting spear phishing emails.

## Summary
- Dataset: 205 emails (human + AI-generated phishing)
- Task: Phishing vs legitimate classification
- Result:
  - High phishing detection (up to 100% recall)
  - High false positive rates (42%–76%)

## Key Insight
LLMs are highly sensitive to phishing signals but struggle with precision, making them risky for real-world deployment without additional filtering.

## Files
- /paper → Capstone PDF
- /code → code/phishing_detection.py 
