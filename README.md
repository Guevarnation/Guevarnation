<!--
  Drop this file in a repo named exactly like your GitHub username
  (e.g. github.com/eugenio/eugenio) so it renders on your profile.
  Then find & replace YOUR-USERNAME everywhere below.
-->

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=800&color=00ADD8&center=true&vCenter=true&width=650&lines=hey%2C+I'm+Eugenio+%F0%9F%91%8B;self-taught+full-stack+engineer;Go+%2B+TypeScript+%2B+AWS;building+things+from+Monterrey%2C+MX" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:YOUR@EMAIL.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=YOUR-USERNAME&style=for-the-badge&color=00ADD8" />
</p>

---

### `whoami`

```go
package main

import "fmt"

type Engineer struct {
	Name     string
	Age      int
	Location string
	Role     string
	Stack    []string
}

func (e Engineer) Ship(idea string) (string, error) {
	if idea == "" {
		return "", fmt.Errorf("shipping nothing is still shipping, technically")
	}
	return fmt.Sprintf("%s (%d) → %s", e.Name, e.Age, idea), nil
}

func main() {
	me := Engineer{
		Name:     "Eugenio Guevara",
		Age:      25,
		Location: "Monterrey, México 🇲🇽",
		Role:     "CTO & Co-founder @ YEYAR",
		Stack:    []string{"Go", "TypeScript", "Next.js", "Postgres", "AWS"},
	}

	out, err := me.Ship("real estate presales, in production")
	if err != nil {
		panic(err)
	}
	fmt.Println(out) // Eugenio Guevara (25) → real estate presales, in production
}
```

---

### `~/now.ts`

```ts
type Now = {
  building: string[];
  learning: string[];
  reading: `${string} algorithms`;
  openTo: "interesting problems" | "coffee" | "both";
};

export const now: Now = {
  building: ["YEYAR — real estate presale platform", "side projects that escape localhost"],
  learning: ["distributed systems", "Go internals", "everything AWS keeps renaming"],
  reading: "graph algorithms",
  openTo: "both",
} as const;
```

---

### `stack`

<p align="left">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
</p>
<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

---

### `stats`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR-USERNAME&show_icons=true&count_private=true&hide_border=true&theme=tokyonight&icon_color=00ADD8" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-USERNAME&layout=compact&langs_count=8&hide_border=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=YOUR-USERNAME&hide_border=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=YOUR-USERNAME&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" />
</p>

---

### `fun fact`

```bash
$ cat /dev/eugenio/fun_fact.txt
> When the compiler wins, I go climb something.
> Currently working toward certifying as a summit guide
> for "La M" at Chipinque — the only trail I can't refactor.
```

<p align="center"><i>defer close(readme)</i></p>
