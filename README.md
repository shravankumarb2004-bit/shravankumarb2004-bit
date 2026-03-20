<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Shravan%20Kumar%20B&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=✨%20Student%20•%20Math%20Animator%20•%20Open%20Source%20Lover%20✨&descAlignY=58&descSize=20" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2500&pause=800&color=00D9FF&center=true&vCenter=true&multiline=true&width=650&height=120&lines=🎓+Student+%26+Passionate+Learner;🐍+Python+%26+Manim+Enthusiast;🎬+Turning+Math+into+Beautiful+Animations;☁️+Exploring+DevOps+%26+Cloud;🌍+Open+Source+Contributor" alt="Typing SVG" />

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=shravankumarb2004-bit&style=for-the-badge&color=blueviolet&label=PROFILE+VIEWS" />
&nbsp;
<img src="https://img.shields.io/github/followers/shravankumarb2004-bit?style=for-the-badge&color=0088ff&label=FOLLOWERS" />
&nbsp;
<img src="https://img.shields.io/badge/Focus-Math%20Animations-00D9FF?style=for-the-badge" />
&nbsp;
<img src="https://img.shields.io/badge/Lives-India-ff6b35?style=for-the-badge" />

</div>

---

<img src="https://user-images.githubusercontent.com/73097531/132140038-6a35e1a4-8b4b-4a3f-b0c3-ef7ee65cd5de.gif" width="30px"> &nbsp; **About Me**
```python
class Shravan:
    name        = "Shravan Kumar B"
    username    = "shravankumarb2004-bit"
    role        = "Student & Aspiring Developer"
    passion     = ["Python", "Manim", "Math Animations", "Cloud", "Open Source"]
    currently   = "Animating math & exploring the cloud ☁️"
    learning    = ["DevOps", "AWS", "Docker", "GitHub Actions"]
    fun_fact    = "I turn equations into animations ✨"
    open_source = True
    available   = "Always open to collaborate! 🤝"

    def say_hi(self):
        print("Thanks for stopping by! Let's build something amazing 🔥")

me = Shravan()
me.say_hi()
```

---

## 🛠️ Tech Stack & Tools

<div align="center">

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

### 🎬 Creative & Animation
![Manim](https://img.shields.io/badge/Manim-Community-00D9FF?style=for-the-badge&logo=python&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)

### ☁️ DevOps & Cloud
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 🔧 Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=shravankumarb2004-bit&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=00D9FF&icon_color=00D9FF&text_color=ffffff&bg_color=0d1117&rank_icon=github" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=shravankumarb2004-bit&theme=tokyonight&hide_border=true&stroke=00D9FF&ring=00D9FF&fire=ff6b35&currStreakLabel=00D9FF&background=0d1117&sideLabels=ffffff" />

<br/><br/>

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shravankumarb2004-bit&layout=donut&theme=tokyonight&hide_border=true&title_color=00D9FF&text_color=ffffff&bg_color=0d1117" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=shravankumarb2004-bit&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=6&margin-h=6" width="100%"/>

</div>

---

## 🎬 What I Do with Manim

<div align="center">

> *"Mathematics is not about numbers, equations, or algorithms — it's about understanding."*

</div>
```python
from manim import *

class WhoIsShravan(Scene):
    def construct(self):
        # Who am I?
        title = Text("Shravan Kumar B", font_size=56, color=BLUE)
        role  = Text("Student  ·  Coder  ·  Animator", font_size=28, color=YELLOW)
        role.next_to(title, DOWN, buff=0.4)

        self.play(Write(title), run_time=2)
        self.play(FadeIn(role, shift=UP))
        self.wait(1.5)

        # What I believe
        quote = Text(
            '"Animate the world with code"',
            font_size=24, color=WHITE, slant=ITALIC
        )
        self.play(Transform(title, quote), FadeOut(role))
        self.wait(2)

        # My journey
        axes = Axes(x_range=[0, 5], y_range=[0, 5])
        curve = axes.plot(lambda x: x**0.6 * 1.5, color=TEAL)
        label = axes.get_graph_label(curve, label="growth", x_val=4)

        self.play(FadeOut(quote), Create(axes), Create(curve), Write(label))
        self.wait(2)
```

<div align="center">

🎥 **I use Manim to bring math to life — one animation at a time!**

</div>

---

## 📈 Contribution Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shravankumarb2004-bit&bg_color=0d1117&color=00D9FF&line=00D9FF&point=ff6b35&area=true&area_color=00D9FF&hide_border=true&radius=8" width="100%"/>

</div>

---

## 🌱 Currently Learning

<div align="center">

| 🔧 Skill | 📊 Progress |
|---|---|
| ☁️ AWS Cloud | `█████████░` 90% |
| 🐳 Docker & Kubernetes | `████████░░` 80% |
| 🔁 GitHub Actions / CI-CD | `███████░░░` 70% |
| 🎬 Advanced Manim | `█████████░` 90% |
| 🐧 Linux & Shell Scripting | `████████░░` 80% |

</div>

---

## 💡 Open Source Philosophy

<div align="center">
```
Every line of code shared is a lesson gifted to the world. 🌍
```

![Open Source](https://img.shields.io/badge/Open%20Source-Lover-ff6b35?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-00D9FF?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-blueviolet?style=for-the-badge)

</div>

---

## 💬 Dev Quote of the Day

<div align="center">

![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

</div>

---

## 🌐 Connect with Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-shravankumarb2004--bit-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shravankumarb2004-bit)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shravan%20Kumar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shravankumarb)
&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-shravankumarb2004%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shravankumarb2004@gmail.com)

<br/>

*"The best way to learn is to build, share, and grow together 🚀"*

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=140&section=footer&animation=twinkling&fontSize=16&text=Thanks%20for%20visiting!%20⭐%20Star%20my%20repos%20if%20you%20like%20my%20work!&fontColor=ffffff&fontAlignY=65" width="100%"/>

</div>
