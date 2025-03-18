## Hi there 你终于来了👋 

🎄 **Visitor Count 来访人次**  

[![Moe Counter](https://count.getloli.com/@saprz?name=saprz&theme=booru-lewd&padding=7&offset=0&align=center&scale=1&pixelated=1&darkmode=auto)](https://github.com/saprz)
  
🍕 **Who am I 我是谁**
```python
class Draina:
    def __init__(self):
        self.name = "Draina"
        self.version = "v1.0"
        self.language = "zh-CN"
        self.encoded_email = None
        self.school = "XJU(XinJiang University)"
        self.major = "Information Security"
        self.capabilities = [
            "Watching Anime",
            "Taking Long Naps",
            "Eating Delicious Food",
            "Playing Games"
        ]

    def set_email(self, encoded_email):
        decoded_email = base64.b64decode(encoded_email).decode('utf-8')
        self.email = decoded_email

    def introduce(self):
        intro = f"Hello, I am {self.name}, version {self.version}."
        intro += "\nI am capable of performing the following tasks:"
        for capability in self.capabilities:
            intro += f"\n- {capability}"
        if hasattr(self, 'email') and self.email:
            intro += f"\nMy email is: {self.email}"
        intro += f"\nI study at {self.school} since 2020, majoring in {self.major}."
        return intro

saprz = Draina()
encoded_email = "ZHJhaW5hQHFxLmNvbQo="
saprz.set_email(encoded_email)
print(saprz.introduce())
```

  
📕 &nbsp;**Latest Blog Posts 最近的博客**
<!-- BLOG-POST-LIST:START -->
- [文件转十六进制出现转义字符直接通过ASCII码逐字符展开的问题与修复 - Draina](https://www.cnblogs.com/Draina/p/18740372)
- [python实现排列组合--itertools - Draina](https://www.cnblogs.com/Draina/p/18668558)
- [B@se-还原错误字母表转码的base64编码 - Draina](https://www.cnblogs.com/Draina/p/18668219)
- [rot-偏移，ascii，md5爆破 - Draina](https://www.cnblogs.com/Draina/p/18667858)
- [这是base-还原数字查正确码表再解码 - Draina](https://www.cnblogs.com/Draina/p/18662261)
<!-- BLOG-POST-LIST:END -->
✨ ​**Github Stats 我的状态**  
  
<a href="https://github.com/saprz">
  <picture>
    <!-- 暗色模式 -->
    <source 
      srcset="https://github-readme-stats.vercel.app/api?username=saprz&theme=neon&card_width=300"
      media="(prefers-color-scheme: dark)"
    />
    <!-- 亮色模式 -->
    <source
      srcset="https://github-readme-stats.vercel.app/api?username=saprz&theme=buefy&card_width=300"
      media="(prefers-color-scheme: light)"
    />
    <img 
      height=200 
      align="center" 
      src="https://github-readme-stats.vercel.app/api?username=saprz&theme=buefy&card_width=300"
    />
  </picture>
</a>
<a href="https://github.com/saprz">
  <picture>
    <source 
      srcset="https://github-readme-stats.vercel.app/api/top-langs?username=saprz&layout=donut&theme=neon&langs_count=8&card_width=300"
      media="(prefers-color-scheme: dark)"
    />
    <source
      srcset="https://github-readme-stats.vercel.app/api/top-langs?username=saprz&layout=donut&theme=buefy&langs_count=8&card_width=300"
      media="(prefers-color-scheme: light)"
    />
    <img 
      height=200 
      align="center" 
      src="https://github-readme-stats.vercel.app/api/top-langs?username=saprz&layout=donut&theme=buefy&langs_count=8&card_width=300"
    />
  </picture>
</a>




