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