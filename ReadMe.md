# Hello There 👋

![License](https://img.shields.io/github/license/1nj3ct0rrr/1nj3ct0rrr.svg)
![Follow](https://img.shields.io/github/followers/1nj3ct0rrr.svg?style=social&label=Follow&maxAge=2592000)


```python
#!/usr/bin/python3
# -*- coding: utf-8 -*-

class Me:
    def __init__(self):
        self.nick_name = "1nj3ct0r"
        self.name = "Hesam Tavakoli"
        self.role = "Scriptwriter, Hacker and Geek"
        self.location = "Tehran, Tehran, Islamic Republic of Iran"
        
        self.website = "https://1nj3ct0rrr.github.io/"
        
        self.knowledge_base = [
            "AI",
            "Crypto",
            "Database",
            "Web Site",
            "Web Apps",
            "Security",
            "Data Science",
            "Computer Engireeng",
            "Mobile Programming",
            "And ..."
        ]
        
        self.knowledge_base.insert(0, "Full Stack Developer")
        
    def sayHi(self):
        print(
            """Hello my friend, thanks for dropping by!
            This is {nick_name} (My real name is {name}), I live in {location}. I work as a {role}.
            I have wide interests, but most of them are {knowledge_base}.
            You can find out more about me on my personal website: {website}""".format(
                name = self.name,
                location = self.location,
                role = self.role,
                knowledge_base = ", ".join(self.knowledge_base[1:]),
                website = self.website
            )
        )

me = Me()
me.sayHi()
```

## Technologies and Tools 🛠️

## GitHub Stats 📊
