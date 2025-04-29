
# 📘 Key Learnings: FAQ Chatbot for Fitness App

## ✅ What Worked:
- Providing limited scope made answers more accurate
- Using fallback instructions prevented hallucinations

## ⚠️ What Didn’t Work:
- Without scope, the model tried to "make up" answers
- Short prompts missed tone guidance

## 💡 Final Takeaways:
- For chatbot tasks, **role + rules + scope + fallback** = solid results
- Clear prompt structure is critical

## 🧭 Next Steps:
- Try few-shot prompt for custom responses
- Test on multiple LLMs (Claude, GPT-4)
- Add user intent detection
