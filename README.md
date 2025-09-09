## Project Requirements

- VS Code
- Git
- Python 

## Commands to Manage Virtual Environment

For Windows PowerShell (change if using Mac/Linux).
Verify that all required packages are included in requirements.txt (and have NOT been commented out).

```powershell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install --upgrade -r requirements.txt
```

## Commands to Run Python Scripts

Remember to activate your .venv (and install packages if they haven't been installed yet) before running files.

```shell
py demo-script.py
```

## Commands to Git add-commit-push

```shell
git add .
git commit -m "custom message"
git push -u origin main
```

## Troubleshooting and Tips
- See [TROUBLESHOOTING.md](docs/TROUBLESHOOTING.md)

## Additional Resources 
- See [RESOURCES.md](docs/RESOURCES.md)

## Reference Projects

Custom implementation of the example project at 
[datafun-04-notebooks](https://github.com/denisecase/datafun-04-notebooks/)

- [datafun-03-analytics](https://github.com/denisecase/datafun-03-analytics/)
- [datafun-02-project-setup](https://github.com/denisecase/datafun-02-project-setup/)
- [datafun-01-utils](https://github.com/denisecase/datafun-01-utils/)