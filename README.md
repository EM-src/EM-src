<h1 align='center'>
  Hi there 👋
</h1>

<details><summary>📃 Resume</summary>Peek a boo!</details>

<picture> 
 <a href="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" alt="Developer">
  <img src="/assets//developer.webp" align="right" width="440" height="382">
 </a>
</picture>

 ```python
class AboutMe:
    def __init__(self):
        self.name = "Emmanouil Marketos"
        self.profession = "Technical Analyst"
        self.contact_info = {
            "Email": "marketos.manolis@gmail.com",
            "LinkedIn": "https://www.linkedin.com/in/emmanouil-marketos-37056587/",
            "GitHub": "https://github.com/EM-src"
    
    def introduce(self):
        intro = f"Hi, I'm {self.name}, a {self.profession}."
        contact_details = "\n".join([f"{key}: {value}" for key, value in self.contact_info.items()])
        return f"{intro}\n\nContact Info:\n{contact_details}"

if __name__ == "__main__":
    me = AboutMe()
    print(me.introduce())
```

<h1 align='center'>
  Tech Skills
</h1>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,sklearn,pytorch,php,html,css,mysql,lua,git,vscode,figma" />
  </a>
</p>


<!-- ![](https://komarev.com/ghpvc/?username=EM-src&color=green) -->
 
