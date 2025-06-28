**Conductor** is a platform for building microservices-based applications with workflow orchestration

Originally [built at Netflix](https://netflixtechblog.com/netflix-conductor-a-microservices-orchestrator-2e8d4771bf40), Conductor is an open source platform for building and scaling workflow based applications. 

Conductor lets you build applications with:
* [SAGA pattern](https://learn.microsoft.com/en-us/azure/architecture/patterns/saga)
* Microservices orchestration
* Agentic workflows by orchestrating language models
* Durable code execution

## Building and scaling applications with Conductor
Maintaining state (e.g. order processing, payment workflow, customer onboarding) in an application requires maintaining state across different services.
This becomes especially challenging when you need to guarantee process completion despite temporary or permanent service failures. 
Conductor solves this by offloading state management, failure handling, and other resiliency concerns to the Conductor server
Conductor lets you write stateless code in any programming language and framework of your choice, and orchestrate them using workflows that are defined in Conductor.

Conductor workflows are simple JSON based code that follows the same structure as a program with sub-routines (sub-workflows), branches, loops and parallel execution.

<img alt="Conductor workflow with a branch" height="300" src="https://raw.githubusercontent.com/conductor-oss/.github/refs/heads/main/workflow_branch.png" width="300"/>

Workflow tasks can either be external microservices (exposed over HTTP or gRPC), or service workers built using lightweight Conductor SDKs in your preferred language.

<img alt="Conductor workflow with a branch" height="300" src="https://github.com/conductor-oss/.github/blob/main/workflow_tasks.png?raw=true" width="300"/>
 
## Conductor Users
Thousands of companies rely on Conductor as a bedrock of their reliable application foundation.
Some notable names include Netflix where a number of teams use Conductor, Tesla, Swiggy, Atlassian, GE Healthcare.
Companies choose Conductor for its open-source nature, ease of use, lightweight SDKs, and a healthy, active community.

## Getting Started with Conductor

1. <img src="https://upload.wikimedia.org/wikipedia/commons/7/79/Spring_Boot.svg" width="15" height="15">&nbsp;[Spring-boot and Conductor](https://github.com/conductor-oss/conductor-example-springboot3)
2. Python + Conductor
3. Building with .NET + Conductor
4. Developing in Clojure with Conductor
5. Distributed Applications in Go
6. Typescript + Conductor

### More
1. Workflows with Human in the loop
2. Agentic workflow : Autonomous Interview Agent


## Featured Use cases
Conductor is widely adopted across multiple industries and used for varied use cases:

1. [Orchestrating Netflix Studio Productions](https://www.youtube.com/watch?v=t2qnvQQrDfw)
2. [ML Infrastructure for Personalization at Netflix](https://www.youtube.com/watch?v=cyKMURxmjHQ&list=PLa2RlPLMYyBVVuT_5Rpmv8JNkemYB-8eH&index=20)
2. [Payment Processing](https://www.youtube.com/watch?v=Q74IMa3OKfA&list=PLa2RlPLMYyBVVuT_5Rpmv8JNkemYB-8eH&index=9)
3. [Conductor @ UK Ministry of Justice](https://www.youtube.com/watch?v=LnkgPoJoNn4)
4. [Powering clinical workflows at GE Healthcare](https://www.youtube.com/watch?v=aaS9IVS3ksk)
5. [Securing Public Cloud Infrastructure with Conductor at Normalyze](https://www.youtube.com/watch?v=erJE3rM0H_w&list=PLa2RlPLMYyBVVuT_5Rpmv8JNkemYB-8eH&index=18)

(*Want to feature your use case? Email us at devrel@orkes.io*)

## Resources
- [Orkes](https://orkes.io/)
- [Conductor OSS](https://conductor-oss.org/)
- [Getting Started with Conductor](https://www.youtube.com/watch?v=4azDdDlx27M) (video)
- [Library of Sample applications](https://github.com/conductor-oss/awesome-conductor-apps)
- [Slack Community](https://join.slack.com/t/orkes-conductor/shared_invite/zt-2vdbx239s-Eacdyqya9giNLHfrCavfaA)
- [Documentation](https://orkes.io/content)

## Community
[![Orkes on YouTube](https://img.shields.io/badge/orkes-FF0000?style=flat&logo=youtube)](https://www.youtube.com/@orkesio)
[![Slack Community](https://img.shields.io/badge/conductoross-blue?logo=slack)](https://join.slack.com/t/orkes-conductor/shared_invite/zt-2vdbx239s-Eacdyqya9giNLHfrCavfaA)
[![@orkesio on X](https://img.shields.io/badge/%40orkes-purple?logo=x)](https://x.com/orkesio)
 
## Conductor SDKs
[![Conductor Java SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=java-sdk&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/conductor-oss/java-sdk#gh-light-mode-only)
[![Conductor java SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=java-sdk&show_icons=true&theme=github_dark#gh-dark-mode-only)](https://github.com/conductor-oss/java-sdk#gh-dark-mode-only)
[![Conductor Go SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=go-sdk&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/conductor-oss/go-sdk#gh-light-mode-only)
[![Conductor Go SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=go-sdk&show_icons=true&theme=github_dark#gh-dark-mode-only)](https://github.com/conductor-oss/go-sdk#gh-dark-mode-only)
[![Conductor Python SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=python-sdk&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/conductor-oss/python-sdk#gh-light-mode-only)
[![Conductor Python SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=python-sdk&show_icons=true&theme=github_dark#gh-dark-mode-only)](https://github.com/conductor-oss/python-sdk#gh-dark-mode-only)
[![Conductor Typescript SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=csharp-sdk&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/conductor-oss/pycsharpthon-sdk#gh-light-mode-only)
[![Conductor Typescript SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=csharp-sdk&show_icons=true&theme=github_dark#gh-dark-mode-only)](https://github.com/conductor-oss/csharp-sdk#gh-dark-mode-only)
[![Conductor .NET/CSharp SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=csharp-sdk&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/conductor-oss/pycsharpthon-sdk#gh-light-mode-only)
[![Conductor .NET/CSharp SDK](https://github-readme-stats.vercel.app/api/pin/?username=conductor-oss&repo=csharp-sdk&show_icons=true&theme=github_dark#gh-dark-mode-only)](https://github.com/conductor-oss/csharp-sdk#gh-dark-mode-only)










