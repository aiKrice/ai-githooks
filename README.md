<div id="header" align="center">
  <img src="https://github.com/aiKrice/ai-githooks/assets/3344647/e35db5d3-7f32-4ad9-9076-761990922de4" width="300"/>
</div>
<p align="center">
    Android-iOS Githooks
</p>

# Intro
📣 This repo is not a library but a set of tools. I will work to make it a universal tools for any iOS and Android Repo. If you have any idea, please open an issue 🙏. I would like to keep a single repo for iOS and Android to mutualize effort

# Usage
## Step 1
Clone the project and copy paste or merge `configure`, `Brewfile`, `gitooks` folder in your project

## Step 2
Edit `configure` file to your platform project (iOS or Android)
```bash
git config --local core.hooksPath githooks/ios/ #change last folder to android
```

## Step 2
Execute `configure`
```bash
./configure
```

And you are all set 🎉

