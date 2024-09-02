## ✈️ A (travel-themed) journey of Semantic Kernel for .NET Developers
Created By: Peter De Tender - petender@microsoft.com

Sample Notebook, which demonstrates different Semantic Kernel scenarios:

- Prompts
- Plugins
- Functions
- Personas

The choice for using a Jupiter Notebook for my Semantic Kernel demos, is thanks to the [Polyglot Notebooks](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode?) for VS Code integration, allowing to run .NET code straight from within the Notebook, instead of running the actual code in the Terminal. This gives a smoother demo experience. (Based on the same approach used by John Maeda in the [Introducing Semantic Kernel Course](https://www.linkedin.com/learning/introducing-semantic-kernel-building-ai-based-apps/introducing-semantic-kernel?u=3322) on LinkedInLearning)

In order to use this Polyglot Notebook, clone or fork the repo to your local machine, and open the semantickerneldemos.ipynb file in VS Code (or similar Dev IDE)


## Prerequisites
This Polyglot notebook needs to be run from VS Code with the following pre-requisites:

Software to be installed on your computer:

✔️ Visual Studio Code
✔️ The latest .Net 8.0 SDK
✔️ Polyglot Notebooks for VS Code extension

Next, you need to have Azure OpenAI Service and a set of models deployed in your Azure subscription:

✔️ Azure OpenAI Service
✔️ Azure OpenAI Models

>Note: 5k TPM (tokens per minute) would be enough for most of the demos. No need to max out the tokens quota in your Azure subscription.

(I personally like to use the model name as the deployment name, for ease of consistency in namings, as well as to avoid confusion in model name and deployment name. These are sometimes mixed up in sample code and documentation.)

* ✔️  `gpt-4-default`- GPT-4o
* ✔️ `dall-e-3` - DALL-E-3
* ✔️ `text-embedding-ada-002` - text-embedding-ada-002
* ✔️ `text-davinci-002` - text-davinci-002
* ✔️ `gpt-35-turbo-16k` - gpt-35-turbo-16k

>Note: while we won't use all of these in our demos, those are typically the different models I deploy for my AI-inspired/influenced applications. Once you start using GenAI in your app, it's tempting to start using all its capabilities!

🔑 You will use the keys and endpoint parameters during the initialization of this Notebook. You will get prompted for the different parameters. The necessary settings will be stored in a new file settings.json. Make sure you reset or delete this file (see below in step 2 how to do this), before you check in this code in Source Control.
