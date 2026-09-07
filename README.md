### Joaquin Girardi
**Senior Full Stack Software Engineer**

> Engineering fault-tolerant event-driven pipelines, AI document extraction workflows, and enterprise Web3/SaaS architectures.

```go
package main

import "fmt"

type Stack struct {
    Languages []string
    Backend   []string
    AIData    []string
    CloudWeb3 []string
}

func main() {
    me := Stack{
        Languages: []string{"Go", "TypeScript", "Python", "SQL", "Bash"},
        Backend:   []string{"NATS", "NestJS", "Node.js", "GraphQL", "REST"},
        AIData:    []string{"RAG", "Vector DBs (Pinecone/Milvus)", "ClickHouse", "PostgreSQL", "Redis"},
        CloudWeb3: []string{"AWS", "GCP", "Kubernetes", "Docker", "Terraform", "CI/CD", "Web3 Security"},
    }
    
    fmt.Printf("Core Expertise: %+v\n", me)
}
