# 👨🏼‍💻 Giacomo Peretti

```python
#!/usr/bin/python
from typing import Dict, List


class SoftwareEngineer:
    def __init__(
        self,
        name: str,
        spoken_languages: List[str],
        languages: List[str],
        technologies: Dict[str, List[str]],
    ):
        self.full_name = name
        self.spoken_languages = spoken_languages
        self.languages = languages
        self.technologies = technologies

    def hi(self):
        return (
            f"Hi! I am {self.full_name}.\n"
            f"I can speak {self.spoken_languages}.\n"
            f"I can code in {self.languages}.\n"
            f"I can use the following technologies {self.technologies}.\n"
        )


def main():
    name = "Giacomo Peretti"
    spoken_languages = ["it_IT", "en_US"]
    languages = [
        "Python",
        "Java",
        "C",
        "C++",
        "Go",
        "Javascript",
        "HTML",
        "CSS",
        "Bash",
    ]
    technologies = {
        "frontend": ["SvelteJS", "TailwindCSS"],
        "backend": {
            "python": ["Flask", "Django"],
            "go": ["Echo", "Fiber"]
        },
        "databases": {
            "sql": ["SQLite", "MySQL"],
            "no_sql": ["MongoDB"]
        },
    }

    giacomo = SoftwareEngineer(name, spoken_languages, languages, technologies)
    print(giacomo.hi())


if __name__ == "__main__":
    main()
```

<details close>
    <summary>📊 Stats</summary>
    <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=giackperetti&show_icons=true&theme=gruvbox" />
</details>
