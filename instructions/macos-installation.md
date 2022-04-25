# Installation for MacOS

For MacOS, please follow the instructions below.

# Step 1
Open `Terminal` app.

# Step 2

On the `Terminal` app, paste the following command:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

then hit enter on your keyboard.

If you are prompted to install `xcode`, follow the instruction and install it.

This step installs `Homebrew` . It is a package manager that you will rely on throughout the course.

Once the installation is completed, on the `Terminal` app, type `brew` and hit enter . you should see something like the following:

```bash
Example usage:
    brew search TEXT|/REGEX/
    brew info [FORMULA|CASK...]
    brew install FORMULA|CASK...
    brew update
    brew upgrade [FORMULA|CASK...]
    brew uninstall FORMULA|CASK...
    brew list [FORMULA|CASK...]

Troubleshooting:
    brew config
    brew doctor
    brew install --verbose --debug FORMULA|CASK

Contributing:
    brew create URL [--no-fetch]
    brew edit [FORMULA|CASK...]

Further help:
    brew commands
    brew help [COMMAND]
    man brew
    https://docs.brew.sh
```

# Step 3
On the `Terminal` app, paste the following:
```bash
brew install node
```

This installs `NodeJS` and `npm` . `NodeJS` is a `javascript` runtime environment while `npm` is a package manager for `javascript` .

Once the installation has completed, on the `Terminal` app type, `node -v` and hit enter. You should see something like the following:

```bash
v16.4.2
```

Note that the number does not need to the match the above. The number simply indicates the version number of `NodeJS` on your system.

Next, on the `Terminal` app, type `npm -v` and hit enter. You should see something like the following:

```bash
8.3.2
```

Similarly, the version number does not matter.

# Step 4

On the `Terminal` app, paste the following command:

```bash
brew install python@3.9
```

This installs `python3` which will be covered in unit 4.

Next, on the `Terminal` app, type `python3` and hit enter . You should see something like the following:

```bash
eugeneoei@eugenes-MacBook-Pro ~> python3
Python 3.9.6 (default, Jun 29 2021, 04:45:03)
[Clang 11.0.0 (clang-1100.0.33.17)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Next, type `quit()` and hit enter .

That is all! you are done with the installation!