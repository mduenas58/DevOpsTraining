<p>What is DevOps?</p>
<p>AWS Definition:</p> 
https://aws.amazon.com/devops/what-is-devops/


```mermaid
classDiagram
    DevOps <|-- Linux
    DevOps <|-- Bash Scripting
    DevOps <|-- Git
    DevOps : Linux Fundamentals
    DevOps : Github
    DevOps: AWS
    DevOps: Linode
    class Linux{
      System admin
      local
      remote
    }
    class Git{
      Repository
      Github
    }
    class AWS{
      EC2
      create Instance
    }
