
# competitive

ganyariya's competitive repository with VSCode devContainer

### Languages

- c++
- c#
- go
- python
- lua

# Setup

```bash
gh repo clone ganyariya/competitive
# or 
git clone https://github.com/ganyariya/competitive.git
```

- Install & Setup `Docker Desktop`
- Open `ganyariya/competitive` directory with VSCode
- Open VSCode CommandPalette and select `Dev containers: Reopen in Container`
  - Automatically create & launch a devcontainer

# How to use

## oj & acc commands
- Log in
```bash
acc login
oj login https://atcoder.jp
acc check-oj
```

- Add new contest
```bash
acc new abc001 # abc001 dir will be created
cd abc001/a
```

- Run tests
```bash
oj t -c "go run ./main.go" -d tests/
```

## Run

You can write any code in `cpp`, `go`, and `python` directory.   
After writing, you can run codes automatically with `Ctrl + Option + N` with Code Runner Extension.

![](https://i.gyazo.com/630d0c2e5a7c764b737774fafcd2be94.gif)

## Debug

Open your code (ex: `main.go`) and Open `Debug` vscode sidebar.   
Then, launch debug task (ex: `Go Debug`).

![](https://i.gyazo.com/855254e07ad1a7608618bdf6fb1f626d.gif)

# Links

- Devcontainers
  - https://code.visualstudio.com/docs/devcontainers/containers
  - https://zenn.dev/bells17/articles/remote-ssh-devcontainer
- cpp
  - https://code.visualstudio.com/docs/languages/cpp
  - https://code.visualstudio.com/docs/cpp/launch-json-reference
