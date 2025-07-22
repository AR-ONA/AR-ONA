# ARONA
A programming duo group of two junior developers who are hardcore otakus. our code comments are probably written in anime references
```python
speed = speed * 0.1 # The world
```


<h3 align="center">SKILLS</h3>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,react,kotlin,js,python,dotnet,java,idea,fastapi,flutter,unity,vim&perline=6" />
  </a>
</p>

### MEMBERS
**Render**
```python
class Profile:
    def __init__(self):
        self.name = "JONGHYUN WON"
        self.age = 15
        self.profession = "Developer"
        self.education = "High School Student"
        self.skills = ["Python", "TypeScript", "C#", "Dart"]
        self.interests = ["Full-Stack", "DNN", "OS", "Game Engine"]
    
    def introduce(self):
        return (
            f"Hello! I'm {self.name}, a {self.profession} aged {self.age}. "
            f"I'm currently a {self.education} and have skills in {', '.join(self.skills)}. "
            f"I'm also interested in {', '.join(self.interests)}."
        )

profile = Profile()
print(profile.introduce())
```
**kuroka3**
```javascript
let biodata = {
  name: "?",
  age: 15,
  profession: "Developer",
  education: "High School Student",
  skills: ["HTML", "CSS", "JavaScript", "React"],
  interests: ["Programming", "Anime", "Game"],
  introduce : function() {
    return `Hello! I'm ${this.name}, a ${this.profession} aged ${this.age}. I'm currently a ${this.education} and have skills in ${this.skills.join(", ")}. I'm also interested in ${this.interests.join(", ")}.`;
  }
};

console.log(biodata.introduce());
```