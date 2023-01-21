<!-- First & Last name display -->
<p align='center'>
<a href="https://github.com/nulzo"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=1&pause=1000&color=4ECDC4&center=true&vCenter=true&repeat=false&width=435&lines=Nolan+Gregory" alt="Typing SVG" /></a>
</p>

<!-- About me display -->
<p align="center">
<a href="https://github.com/nulzo"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=400&color=FFFFFF&center=true&vCenter=true&width=435&lines=Computer+Science+Student;Software+Engineering+Intern;Certified+Cool+Guy" alt="Typing SVG" /></a>
</p>

<!-- Socials -->
<p align="center">
  <a href="https://www.youtube.com/channel/UCKRgEboEIQuq-PKD8J4RvtA"><img width="32px" alt="Youtube" title="Youtube" src="https://imgur.com/3hcdxzP.png"/></a>
  &#8287;&#8287;&#8287;&#8287;&#8287;
  <a href="https://www.linkedin.com/in/nolan-gregory-cs/"><img width="32px" alt="LinkedIn" title="LinkedIn" src="https://imgur.com/TNyxVAX.png"/></a>
  &#8287;&#8287;&#8287;&#8287;&#8287;
  <a href="https://discord.gg/fPrdqh3Zfu](https://media.tenor.com/5AyrPjdvtqMAAAAC/please-say-sike-eric-andre.gif" alt="Discord" title="Discord"><img width="32px" src="https://imgur.com/1PqeK8P.png"/></a>
  &#8287;&#8287;&#8287;&#8287;&#8287;
  <a href="https://github.com/nulzo/"><img width="32px" alt="Github" title="Github" src="https://imgur.com/cF6vTtn.png"></a>
</p>

<!-- Break point -->
##
```python

class aboutMe:
    def __init__(self, name, role, languages = []):
        self.name = name
        self.role = role
        self.languages = languages
        
    def greeting(self):
        print(f"Hello!\nMy name is {self.name} and I am a {self.role}!")
        print("I am comfortable developing in: ")
        self.getLanguages()
        print("Thanks for checking out my page! Why don't you sign my \"guestbook\" while you're here? :)")
        
    def getLanguages(self):
        if len(self.languages) > 0:
            for lang in self.languages:
                print(f"\t>> {lang}")
        else:
            print("\t>> No languages?!")
        
if __name__ == "__main__":
  me = aboutMe("Nolan", "Software Engineer", ["Python", "Java", "C#", "C", "JS"])
  me.greeting()
```

<!--
**nulzo/nulzo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
