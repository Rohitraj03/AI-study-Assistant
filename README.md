# 📚 AI Study Assistant

A powerful, personalized learning platform powered by multiple specialized AI agents. Get custom learning roadmaps, practice quizzes, AI tutoring, and RAG-powered document Q&A to supercharge your studies!

## 🌟 Features

### 🎯 Personalized Learning Analysis
- **Student Profiling**: AI analyzes your knowledge level, goals, and learning style
- **Gap Analysis**: Identifies what you need to learn and prerequisite knowledge
- **Custom Recommendations**: Tailored approach based on your unique needs

### 🗺️ Smart Learning Roadmaps
- **Structured Learning Paths**: Break down complex topics into manageable phases
- **Time-Optimized**: Plans adapted to your available study time
- **Milestone Tracking**: Clear checkpoints to measure progress
- **Flexible Scheduling**: Adjust pace based on your schedule

### 📝 Dynamic Quiz Generation
- **Adaptive Difficulty**: Questions matched to your knowledge level
- **Multiple Question Types**: MCQ, True/False, Short Answer, Problem-Solving
- **Detailed Explanations**: Learn from both correct and incorrect answers
- **Custom Focus Areas**: Target specific topics you want to practice

### 🤖 AI Tutor
- **24/7 Availability**: Get help whenever you need it
- **Personalized Explanations**: Adapted to your learning style
- **Step-by-Step Guidance**: Break down complex concepts
- **Real-World Examples**: Understand through practical applications

### 📄 RAG-Powered Document Q&A
- **Upload Study Materials**: PDFs, textbooks, lecture notes
- **Intelligent Search**: Find relevant information instantly
- **Context-Aware Answers**: Get answers grounded in your materials
- **Source Citations**: Know where information comes from

### 🔍 Resource Finder
- **Curated Resources**: AI finds the best learning materials
- **Quality Filtered**: Only high-quality, relevant resources
- **Learning Style Matched**: Resources suited to how you learn best




### "No API key found" or API errors
**Solution:**
1. Ensure `.env` file exists in the project root
2. Verify your API key is correctly formatted:
   - Groq keys start with `gsk_`
   - OpenAI keys start with `sk-`
3. Check that the key is valid and active
4. For OpenAI: Ensure you have credits in your account

### "Failed to load document" (RAG feature)
**Solution:**
- Ensure PDF is not password-protected
- Check file is not corrupted
- Try converting to text format first
- Verify file size is reasonable (< 50MB recommended)

### "Agent not responding" or timeout errors
**Solution:**
- Check your internet connection
- Verify API key is valid and active
- Try switching to a different model in the app settings
- For Groq: Check [status.groq.com](https://status.groq.com)
- For OpenAI: Check [status.openai.com](https://status.openai.com)



## 🚀 Future Enhancements

- [ ] Progress tracking and analytics
- [ ] Spaced repetition scheduling
- [ ] Collaborative study groups
- [ ] Integration with learning platforms (Coursera, Udemy, etc.)
- [ ] Mobile app version
- [ ] Voice interaction for auditory learners
- [ ] Gamification and achievements
- [ ] Export to Anki flashcards



## 💬 Support

For issues, questions, or suggestions:
1. Check the troubleshooting section above
2. Review the configuration in `prompts.yaml`
3. Ensure all dependencies are correctly installed

---

**Happy Learning! 📚✨**

*Remember: The best way to learn is to start. Let AI agents guide your journey!*
