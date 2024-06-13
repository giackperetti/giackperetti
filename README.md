# 👨🏼‍💻 Giacomo Peretti

```go
package main

import "fmt"

type SoftwareEngineer struct {
    FullName        string
    Role            string
    SpokenLanguages []string
}

func (se *SoftwareEngineer) sayHi() {
    fmt.Println("Thanks for dropping by, hope you'll find something interesting here. :)")
}

func main() {
    me := SoftwareEngineer{
        FullName:        "Giacomo Peretti",
        Role:            "Computer Science Student",
        SpokenLanguages: []string{"it_IT", "en_US"},
    }

    me.sayHi()
}
```

---

### 🧰 Languages and Tools

[![My Skills](https://skillicons.dev/icons?i=py,java,go,c,cpp,bash,html,css,js,linux,neovim,vscode&theme=dark&perline=3)](https://skillicons.dev)

#

<details close>
    <summary>📊 Stats</summary>
    <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=giackperetti&show_icons=true&count_private=true&theme=gruvbox&include_all_commits=true&hide_border=true" />
</details>
