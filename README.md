### Hi Im Rodrigo

- 🔭 I’m currently working on: Web Scraping, Data Extraction and Automation, using GCP.
- 🌱 I’m currently learning: GCP
- 👯 I’m looking to collaborate on: Open Data, Covid-19 projects
- 💬 Ask me about PM, Python. I will be happy to help.
- 📫 How to reach me: Send me a DM in [Twitter](https://twitter.com/rotorrest)
- 😄 Pronouns: He/Him
- ⚡ Fun fact: I used to be an RF engineer, but code is more fun.


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

from __future__ import annotations
import json
from dataclasses import asdict, dataclass


@dataclass
class Arsenal:
    languages: tuple[str, ...] = ("Python", "Bash", "HTML", "LaTeX", "Octave")
    Tools: tuple[str, ...] = ("GIT", "VIM", "Docker", "GCP")
    GCP: tuple[str, ...] = ("Compute Engine", "DataStore", "FireStore")
    Ongoing:   tuple[str, ...] = ("Django", "Cloud Build, Cloud Run)

    def jsonify(self):
        return json.dumps(asdict(self), indent=4)


arsenal = Arsenal()
print(arsenal.jsonify())
```
