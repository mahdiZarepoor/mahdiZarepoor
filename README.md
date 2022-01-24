**HEY THERE**
> I'm student of software engineering at Iran/Mashhad .

***
![Me](https://pasteboard.co/7NLffVBNQCC9.jpg)

> more about me )

```go 
package main

import "fmt"

func main() {

	myAbilities := make(map[string][]string)
	myAbilities["Languages"] = []string{"Python", "Golang", "a little JS"}
	myAbilities["Databases"] = []string{"Mysql", "Postgresql", "Redis"}
	myAbilities["OS"] = []string{"Linux(mainly)", "windows"}
	myAbilities["Tools and stuff"] = []string{"API", "Git", "docker", "sessions and cookies", "jwt", "golang web frameworks"}

	wannaLearnMore := make(map[string][]string)
	wannaLearnMore["Backend Development"] = []string{"domain driven development", "microservices", "solid implementation",
		"Cloud computing"}
	wannaLearnMore["general stuff"] = []string{"Data structure", "Algorithms", "competitive programming"}

	likes := []string{"The walking dead TV show", "Running", "Nature", "The queen"}

	for key, value := range myAbilities {
		fmt.Println(key, value)
	}

	for key, value := range wannaLearnMore {
		fmt.Println(key, value)
	}
	fmt.Println("\nI like : ", likes)
}

```


