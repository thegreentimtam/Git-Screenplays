# Branches and Pull Requests

[Click here](https://youtu.be/FPJt9AjW7rg) for a video version.

[Click here](https://youtu.be/7Hf07n06pF8) for adding notes within VS Code as you read.

Once you've finished your first draft, you should do any other changes in Branches. Branches are a way of grouping commits together in a separate version of your script, that you can then Merge with your version of the script. This is ideal for trying out ideas, and also getting notes in Pull Requests. 

You might want to create one branch called `Second Draft`, or maybe many branches targetting different notes and different ideas. It's up to you.

Branching is especially useful if you don't neccessarily agree with some notes. When I've been writing scripts, I've certainly had times when my teachers, collaborators or producers had notes that I disagreed with. But it's very difficult to explain to them why their ideas don't work unless you try it out. By creating a branch, you can make those changes completely independently of your main script. Often you'll find, while those ideas don't neccessarily work for your vision, you can see the problems in your script they are trying to address more clearly, and come up with your own way of dealing with them.

Other members of the class, with your permission, can also make suggested changes in their own branch.

## Creating and Changing Branches

In Visual Studio Code, in the `Source Control` tab, click `More > Checkout To...`. You'll get a list of branches, as well as the option to create one.

Now you can just commit, push and pull as you would normally.

>If you want to create multiple branches, go back to the `main` branch before creating a new one.

## Creating Pull Requests

Pull Requests are the place we discuss changes made in Branches. Go to the `Pull Requests` tab in Github, and click `New Pull Request`. Set `main` as the base branch, and the branch you want to discuss as the `compare`.

You can now discuss the pull request just like an Issue. Click the `Files Changes` tab in the pull request to see all the changes made and make comments on individual lines.

## Giving Notes

If you want to give notes on a script, install the `Github Pull Requests and Issues` extension for VS Code. Clone the repository you want to give notes on and go to the Github tab. Right click the Pull Request and click `Checkout to Pull Request`. You will now automatically switch to that branch, and be able to add comments in the Github tab, or directly in the script by clicking the white line at the left of the editor.

## Merging

Once they're ready, you can click the `Merge` button to combine these changes with your main repository.