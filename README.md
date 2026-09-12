<h1 align="center">
  Hi! I'm Guilherme Vozniak
  <img src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/Hi.gif" width="30px">
</h1>

<p align="center">
  <img src="assets/terminal-profile.svg" width="1000" alt="Terminal profile of Guilherme Vozniak with an ASCII avatar. Full-Stack Software Engineer in Italy working with Go, TypeScript, AWS and GCP. Speaks Portuguese, English and Italian. Contact: guilherme.voziak.a@gmail.com." />
</p>

<p align="center">
  <a href="https://br.linkedin.com/in/guilherme-vozniak-229428122" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:guilherme.voziak.a@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://instagram.com/gui.vozniak" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
</p>

<p align="center">
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=GuilhermeVozniak&label=Profile%20views&color=0e75b6&style=for-the-badge" />
  <a href="https://github.com/GuilhermeVozniak?tab=followers">
    <img alt="GitHub followers" src="https://img.shields.io/github/followers/GuilhermeVozniak?label=Followers&style=for-the-badge&color=blueviolet" />
  </a>
  <a href="https://github.com/GuilhermeVozniak?tab=repositories">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/GuilhermeVozniak?label=Stars&style=for-the-badge&color=ffca28" />
  </a>
</p>

---

### 🛠️ Tech stack as a Go struct

```go
package developer

// TechStack is the toolkit I use to build and ship software.
type TechStack struct {
	Backend   []string
	Frontend  []string
	APIs      []string
	Events    []string
	Databases []string
	Cloud     []string
	DevOps    []string
}

// NewTechStack returns my go-to technologies.
func NewTechStack() *TechStack {
	return &TechStack{
		Backend:   []string{"Go", "Node.js", "Bun", "NestJS", "Express", "Gin", "Gorilla"},
		Frontend:  []string{"TypeScript", "JavaScript", "Next.js", "React", "Angular", "Vue", "Electron"},
		APIs:      []string{"REST", "GraphQL", "gRPC", "SOAP"},
		Events:    []string{"Kafka", "RabbitMQ", "Redis", "SQS", "SNS"},
		Databases: []string{"PostgreSQL", "MySQL", "MongoDB", "Elasticsearch", "OpenSearch", "Pinecone"},
		Cloud:     []string{"AWS", "GCP"},
		DevOps:    []string{"Docker", "Kubernetes", "Serverless", "Jenkins", "Git", "Linux"},
	}
}
```
