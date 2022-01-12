# Install Node Tools

- Now, we'll install Node.js using `nvm`

### Install NVM

Run the following command to install NVM:

```bash
brew install nvm
```

- it will take a while to install NVM so be patient.
- after completion, follow the instructions in the resulting output.
- when your installation is complete, you should restart your terminal.
- make sure you have a hidden folder called `.nvm` in your home directory, run `mkdir ~/.nvm`.

### Install Node

Run the following command to install Node.js:

```bash
nvm install --lts
```

- verify that you have Node.js installed by running the following command:

```bash
nvm ls
```

the output should look similar to this:

```bash
->     v16.13.1
default -> v16.13.1
iojs -> N/A (default)
unstable -> N/A (default)
node -> stable (-> v16.13.1) (default)
stable -> 16.13 (-> v16.13.1) (default)
lts/* -> lts/gallium (-> v16.13.1)
lts/argon -> v4.9.1 (-> N/A)
lts/boron -> v6.17.1 (-> N/A)
lts/carbon -> v8.17.0 (-> N/A)
lts/dubnium -> v10.24.1 (-> N/A)
lts/erbium -> v12.22.8 (-> N/A)
lts/fermium -> v14.18.2 (-> N/A)
lts/gallium -> v16.13.1

```

### [❮ Back](./git-installation.md) | [Next ❯](./vscode-installation.md)
