## Install and Configure git
Firstly, you need to create an account on github. If you dont have one, go to the [github](https://github.com/) page and create a new account. Note your email ID and user name.

### 1. Installation
If you have git installed but not configured git, then skip to the Configuration section.

#### 1. a. *Mac OS*
**Step 1:** Open a terminal and execute the following line of code:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
to install brew.

**Step 2:** Install git: `brew install git`

**Step 3:** Verify installation: `git --version`

#### 1. b. *Windows*

Download the git [installer](https://gitforwindows.org/) from windows and install git keeping all the options to their default settings by clicking **Next** and ultimately **Finish**.

#### 1. c. *Linux Distributions*

**Step 1:** Open a terminal and execute the following lines of code:

```
sudo apt-get update
```
This updates the information about packages on the apt-get repository.
```
sudo apt-get install git
```
This will install git into your linux system.

**Step 2:** Verify the installation by typing: `git --version`

### 2. Configuring the git installation
In the same open terminal, type the 2 commands as shown below, writing your user ID and email that you entered in the github page within the `""`.
```
git config --global user.name "YOUR_GITHUB_USER_NAME"
git config --global user.email "YOUR_USER_EMAIL"
```

### 3. Cloning the repository
In your terminal/command prompt, navigate to the location where you want to save the downloaded repository and execute the following line of commands:
```
git clone "https://github.com/PratyayPande/cisce-java"
```
This will download the files of code and save it in the folder where the above line of code has been executed
