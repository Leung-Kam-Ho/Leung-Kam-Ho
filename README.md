```python
class Male:
    def __init__(self):
        self.name = "LEUNG Kam HO"
        self.school = "HKPOLYU"
        self.bachelor = "Electronics and Information Engineering"
        self.interests = ["VLA", "AI", "Machine Learning", "Robotics", "Automation"]
        self.languages = ["Python", "Swift", "C++"]
        self.status = "Playing with Robotics Arm"
    
    def code(self):
        return "print('What's Up!')"
    
    def learn(self):
        return "How not to get hit by robotics arm?"
    
    def __str__(self):
        return f"{self.name} | {self.bachelor} @ {self.school}"

me = Male()
print(me)  # LEUNG Kam HO | Electronics and Information Engineering @ HKPOLYU
```
