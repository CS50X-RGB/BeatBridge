# Contribution Rules📚:

- You are allowed to make more than one pull request. We'll merge surely merge the perfect ones :)
- Do NOT add any build steps e.g npm install (we want to keep this a simple static site)
- Do NOT remove other content.
- Styling/code can be pretty, ugly or stupid, big or small as long as it works 😉
- Make sure your create a separate branch before opening a PR.
- Try to keep pull requests small to minimize merge conflicts


## Getting Started 🤩🤗:

- Fork the repository
- Clone your forked repository: 
```bash
git clone https://github.com/<your-github-username>/BeatBridge.git
```
- Navigate to the project directory: 
```bash
cd BeatBridge
```
- Install dependencies: 
```bash
npm install
```
- Start the development server: 
```bash
npm run dev
```
- Create a new branch for your contribution: 
```bash
git checkout -b your-username
```
- Make your changes in the specific folder in `./src/Components` and commit them: 
```bash 
git commit -m "Added a transition"
```
- Push your changes to your fork: 
```bash
git push origin your-username
```
- Create a Pull Request to the master repository!
- **Get your PR merged 🚀**

<br>

## Avoid Conflicts {Syncing your fork}

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.   

```bash
git remote add upstream https://github.com/pooranjoyb/BeatBridge
```

You can verify that the new remote has been added by typing
```bash
git remote -v
```

To pull any new changes from your parent repository simply run
```bash
git merge upstream/master
```

This will give you any eventual conflicts and allow you to easily solve them in your repo. It's a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.
