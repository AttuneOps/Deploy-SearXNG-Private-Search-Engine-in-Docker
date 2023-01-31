# SearXNG Search Engine




## Project Blueprints


### Deploy and Setup SearXNG Docker

```markdown
You can clone this Attune Project into your own instance of Attune. If you'd
like to build this Attune Blueprint yourself please follow these steps.

This workflow will take you through Designing your processes, planning your
deployment, and running your deployment.

Let's get started!

Before we can create our Blueprint and a steps to perform our procedure we 
need to create the parameters we'll be using.

Create Parameters
===

To deploy the SearXNG Private Search Engine we'll need three Parameters:

* Linux Node - `SearXNG Search Engine Node`
* Linux Credentials - `SearXNG Search Engine root User`
* Text - `SearXNG Search Engine Base Directory`

These are the placeholders for the values you'll substitute into the Plan
later in the workflow.

The Node Parameter is for the address of the node you are conneting to.
The root User is for the root user credential to connect to the node. The Base
Directory is for the directory to deploy your files.

Now you're ready to create your Blueprint.

Create the Blueprint
===

Create your Blueprint and Name it: `Deploy and Setup SearXNG Docker`

In this Blueprint we want to create four Execute Linux Script Steps:
```




## Project Parameters


| Name | Type | Script Reference |
| ---- | ---- | ---------------- |
| SearXNG Search Engine Node | Linux/Unix Node | `searxngsearchenginenode` |
| SearXNG Search Engine Node root User | Linux/Unix Credential | `searxngsearchenginenoderootuser` |
| SearXNG Search Engine Node User | Linux/Unix Credential | `searxngsearchenginenodeuser` |
| SearXNG Search Engine Base Directory | Text | `searxngsearchenginebasedirectory` |
| SearXNG Search Engine Lets Encrypt Set Email | Text | `searxngsearchengineletsencryptsetemail` |
| SearXNG Search Engine Lets Encrypt Email | Text | `searxngsearchengineletsencryptemail` |




## Project Files


| Name | Type |
| ---- | ---- |




# ServerTribe

*ServerTribe’s mission* is to provide the community access to intuitive and
flexible open-source IT automated and orchestrated SysOps processes.

This is an *Attune Project* that contains IT automated and orchestrated
processes.

Attune is your flexible IT Automation & Orchestration solution, a
self-documenting central source of reusable proven processes, files and
backups to build and maintain your IT/OT infrastructure. Attune can be
configured to perform any process or task that a System Administrator or
Database Administrator would perform through a terminal.

The *Attune Community Edition* can be
[downloaded for free](https://www.servertribe.com/comunity-edition/)
from our [ServerTribe website](https://www.servertribe.com/). You can learn
more about Attune through [ServerTribe's YouTube Channel](https://www.youtube
.com/channel/UCLRvZajNQXfQPJnYFdeXZ3w).


Thank you.
