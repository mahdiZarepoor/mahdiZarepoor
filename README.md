**HEY THERE**
> a student of software engineering from Iran/Mashhad .

***
**Find me On Linkedin**
[![Linkedin: thaianebraga](https://img.shields.io/badge/-Mahdi-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/mahdi-zarepoor-4a48b3211/)](https://www.linkedin.com/in/mahdi-zarepoor-4a48b3211/)
***
**<img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50">more about me**

run this playground here : https://go.dev/play/p/5lVmxemSUVW
```go 
package main

import "fmt"

func main() {

	myAbilities := make(map[string][]string)
	myAbilities["Languages"] = []string{"Python", "Golang", "C"}
	myAbilities["Databases"] = []string{"Mysql", "Postgresql", "Redis"}
	myAbilities["OS"] = []string{"Linux(mainly)", "windows"}
	myAbilities["Tools and stuff"] = []string{"Git", "docker", "jwt", "golang web frameworks"}

	wannaLearnMore := make(map[string][]string)
	wannaLearnMore["Backend Development"] = []string{"domain driven development", "microservices", "solid implementation",
		"Cloud computing"}
	wannaLearnMore["general stuff"] = []string{"Data structure", "Algorithms"}

	likes := []string{"The walking dead TV show", "Running", "Leaning human/computer languages", "MetalHead"}

	fmt.Println("Abilities : ")
	for key, value := range myAbilities {
		fmt.Println(key, value)
	}

	fmt.Println("\nwanna learn more :")
	for key, value := range wannaLearnMore {
		fmt.Println(key, value)
	}

	fmt.Println("\nI also like : ")
	for _, like := range likes {
		fmt.Println(like)
	}
}

```


