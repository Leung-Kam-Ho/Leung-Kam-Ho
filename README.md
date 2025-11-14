# About Me
```python
class Male:
    def __init__(self):
        self.name = "LEUNG Kam HO"
        self.school = "HKPOLYU"
        self.bachelor = "Electronics and Information Engineering"
        self.interests = ["🧠 Machine Learning", "📊 Data Analysis", "🤖 Robotics", "⚙️ Automation", "🎨 UI Design"]
        self.languages = ["🐍 Python", "🍏 Swift", "💻 C++"]
        self.status = "🔧 Playing with Robotics Arm"
        self.open_to_work = False
    
    def greetings(self):
        return "print('👋 What’s Up!')"

    def youtube(self):
        """My Youtube Channel"""
        return "▶️ https://www.youtube.com/@kamho350"

    def linkedin(self):
        """My Linkedin"""
        return "🔗 https://www.linkedin.com/in/kam-ho-leung-b848a0269/"
    
    def question(self):
        return "🤔 How not to get hit by robotics arm?"
    
    def __str__(self):
        return f"🤖 {self.name} | {self.bachelor} @ {self.school} 🎓"

me = Male()
print(me)               # 🤖 LEUNG Kam HO | Electronics and Information Engineering @ HKPOLYU 🎓
print(me.youtube())     # ▶️ https://www.youtube.com/@kamho350
print(me.linkedin())    # 🔗 https://www.linkedin.com/in/kam-ho-leung-b848a0269/

```
