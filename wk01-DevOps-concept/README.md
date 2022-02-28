### What is DevOps?

DevOps is a set of practices that combines software development `Dev` and IT operations `Ops`. It aims to shorten the systems development life cycle and provide continuous delivery with high software quality. DevOps is complementary with Agile software development; several DevOps aspects came from the Agile methodology.

DevOps toolchain

As ``DevOps`` is intended to be a cross-functional mode of working, those who practice the methodology use different sets of tools—referred to as "toolchains"—rather than a single one. These toolchains are expected to fit into one or more of the following categories, reflective of key aspects of the development and delivery process.

| Tools | Description |
|-----  | -------     |
| Coding | code development and review, source code management tools, code merging. |
| Building | continuous integration tools, build status. |
| Testing | continuous testing tools that provide quick and timely feedback on business risks. |
| Packaging | artifact repository, application pre-deployment staging. |
| Releasing | change management, release approvals, release automation. |
| Configuring | infrastructure configuration and management, infrastructure as code tools. |
| Monitoring | applications performance monitoring, end-user experience. |

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

List of tools:
- Git
- Nexus
