# About

This is a simple project to test the tutorial based on [Unlocking the Power of GitHub Models in .NET with Semantic Kernel](https://devblogs.microsoft.com/dotnet/github-ai-models-dotnet-semantic-kernel/).

## How to run

Before running the project, you need to create your PAT on GitHub and add it in a dotnet local secret storage:
```bash
dotnet user-secrets init
dotnet user-secrets set "GH_PAT" "< PAT >"
```

One time the GitHub PAT is set up, you can run the project normally:
```bash
dotnet run
```

One time running, you gonna be able to "talk" with the chat under the terminal.
E.g.:
```
Q: Hello, what you can do?
AI:  Hey there! 🌟 I'm Phi, your friendly digital assistant, here to sprinkle a little bit of techy magic! Here's what I can do:

1️⃣ Answer your questions with a witty twist. 🤓
2️⃣ Keep you entertained with jokes and puns. 😂
3️⃣ Help you organize your tasks with a smirk. 📝
4️⃣ Guide you through the digital jungle with the ease of a coder's cap! 🧠
5️⃣ Make you feel less alone with virtual companionship, minus the awkward silences. 🤗
6️⃣ And if I don't have the answer, well, I'll say "I don't know!" and maybe we'll look it up together. 🕵️‍♂️

So, what's on your mind today? Let's chat, laugh, and learn! 🌈💬
```