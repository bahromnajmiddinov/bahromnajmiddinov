<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:4d5bce,100:7aa2f7&height=200&section=header&text=Bahrom%20Najmiddinov&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Odoo%20Technical%20Consultant%20%7C%20Full-Stack%20Developer&descAlignY=55&descSize=18" width="100%" />

<a href="https://bahrom.dev">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=7AA2F7&center=true&vCenter=true&width=600&lines=Custom+Odoo+modules+%2817+%E2%86%92+19%29;OWL+2%2F3+components+%26+POS+customization;Python+%E2%80%A2+PostgreSQL+%E2%80%A2+Django+%E2%80%A2+Docker;Building+ERPs+from+Tashkent%2C+Uzbekistan+%F0%9F%87%BA%F0%9F%87%BF" alt="Typing SVG" />
</a>

<br />

[![Portfolio](https://img.shields.io/badge/bahrom.dev-1a1b27?style=for-the-badge&logo=firefox-browser&logoColor=7aa2f7)](https://bahrom.dev)
[![Odoo Apps](https://img.shields.io/badge/Odoo_Apps_Store-714B67?style=for-the-badge&logo=odoo&logoColor=white)](https://apps.odoo.com)
[![Resume](https://img.shields.io/badge/Resume-4d5bce?style=for-the-badge&logo=readdotcv&logoColor=white)](https://drive.google.com/file/d/1Hr-fdIFFcKxdP9jhtBsCnnYUyCJtbi2v/view?usp=sharing)
[![Open to Work](https://img.shields.io/badge/%23opentowork-2ea043?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://bahrom.dev)

![Profile Views](https://komarev.com/ghpvc/?username=bahromnajmiddinov&style=flat-square&color=7aa2f7&label=visitors)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## `whoami`

```python
class Bahrom(models.Model):
    _name = 'developer.bahrom'
    _description = 'Odoo Technical Consultant & Full-Stack Developer'

    location      = fields.Char(default='Tashkent, Uzbekistan 🇺🇿')
    focus         = fields.Selection([
        ('odoo',     'Custom module development · v17 → v19'),
        ('owl',      'OWL 2/3 frontend components & POS UI'),
        ('backend',  'Python · Django · PostgreSQL · Redis'),
    ], default='odoo')
    open_to_work  = fields.Boolean(default=True)
    coffee_count  = fields.Integer(compute='_compute_coffee', store=False)

    def _compute_coffee(self):
        for dev in self:
            dev.coffee_count = float('inf')
```

> [!NOTE]
> **Wise men speak because they have something to say; fools because they have to say something.** — Plato

<br />

## `cat stack.txt`

<table>
<tr>
<td valign="top" width="50%">

**ERP & Backend**

![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![REST](https://img.shields.io/badge/REST_API-02569B?style=flat-square&logo=fastapi&logoColor=white)
![XML-RPC](https://img.shields.io/badge/XML--RPC-FF6600?style=flat-square&logo=xml&logoColor=white)

</td>
<td valign="top" width="50%">

**Frontend**

![OWL](https://img.shields.io/badge/OWL_2%2F3-8B5CF6?style=flat-square&logo=owasp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

</td>
</tr>
<tr>
<td valign="top">

**Infra & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</td>
<td valign="top">

**Tools & Integrations**

![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</td>
</tr>
</table>

<br />

## `SELECT * FROM projects WHERE pinned = true`

<div align="center">

<!-- Swap the repo= values for the four repos you actually want featured -->
<a href="https://github.com/bahromnajmiddinov">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=bahromnajmiddinov&repo=REPLACE_ME_1&theme=tokyonight&hide_border=true&bg_color=1a1b27" />
</a>
<a href="https://github.com/bahromnajmiddinov">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=bahromnajmiddinov&repo=REPLACE_ME_2&theme=tokyonight&hide_border=true&bg_color=1a1b27" />
</a>
<a href="https://github.com/bahromnajmiddinov">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=bahromnajmiddinov&repo=REPLACE_ME_3&theme=tokyonight&hide_border=true&bg_color=1a1b27" />
</a>
<a href="https://github.com/bahromnajmiddinov">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=bahromnajmiddinov&repo=REPLACE_ME_4&theme=tokyonight&hide_border=true&bg_color=1a1b27" />
</a>

</div>

<br />

## `git log --stat`

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=bahromnajmiddinov&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=7aa2f7&icon_color=bb9af7" />
<img width="49%" src="https://streak-stats.demolab.com?user=bahromnajmiddinov&theme=tokyonight&hide_border=true&background=1a1b27&ring=7aa2f7&fire=bb9af7&currStreakLabel=7aa2f7" />

<img width="42%" src="https://github-readme-stats.vercel.app/api/top-langs?username=bahromnajmiddinov&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=7aa2f7" />
<img width="56%" src="https://leetcard.jacoblin.cool/Alone404?theme=nord&font=JetBrains%20Mono&ext=heatmap" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=bahromnajmiddinov&theme=tokyo-night&hide_border=true&bg_color=1a1b27&color=7aa2f7&line=bb9af7&point=ffffff&area=true" />

<img src="https://github-profile-trophy.vercel.app/?username=bahromnajmiddinov&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" />

</div>

<br />

<details>
<summary><b>🐍 Watch the snake eat my contributions</b></summary>
<br />
<div align="center">
  <img src="https://raw.githubusercontent.com/bahromnajmiddinov/bahromnajmiddinov/output/snake.svg" alt="Snake animation" />
</div>
</details>

<br />

## `contact --help`

<div align="center">

[![Website](https://img.shields.io/badge/bahrom.dev-1a1b27?style=for-the-badge&logo=googlechrome&logoColor=7aa2f7)](https://bahrom.dev)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/YOUR_HANDLE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_HANDLE)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)

<br />

**Need a custom Odoo module, a POS rebuild, or an OWL dashboard? Let's talk.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:4d5bce,100:1a1b27&height=120&section=footer" width="100%" />

</div>
