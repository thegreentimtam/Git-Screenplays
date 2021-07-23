# Setting Up Git and Visual Studio Code

The best way of working on your screenplay is on a computer. You will need to install [Visual Studio Code](https://code.visualstudio.com/) and [Git](https://git-scm.com/). These software are available for Windows, Mac and Linux (including Chrome OS).

These are both trusted programs. Visual Studio Code is a Microsoft product, and Git is used by virtually every software developer in the world.

If you are unable to get permission to install Git and VS Code on your computer, your best option will be to edit documents directly on Github in a web browser. If you don't always have Internet access, using the Spck app on your phone is another option.

## Initial Set Up

### Setting Up VS Code

The first step is to Clone the repository. To do this, open a new window in Visual Studio Code, and go to the `Source Control` tab in the left sidebar. This will be the third button down, between `Search` and `Run and Debug`.

Click the `Clone Repository` button, paste the URL of your Github repository, and press Enter.

Select a folder to save the repository to. When asked if you'd like to Open the repository, click `Open`.

### Setting Up Git

#### Using the Terminal

In VS Code, go to `Terminal > New Terminal`. Type in the following code:

`git config --global user.name "Your Name"`

Press Enter, then type

`git config --global user.email "example@example.com"`

Press Enter.

#### GUI

When you instaled Git, the Git GUI may also have installed. If you are uncomfortable using the Terminal (don't be - it's actually not that difficult), you may wish to use this instead.

Open Git GUI, and click the `Open a Folder` button. Navigate to your repository.

Go to `Edit > Options`. Type in your name and email in the relevant fields on the right-hand column and click Save.