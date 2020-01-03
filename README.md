# python-package

offline
```cmd
pip download [package-name]

pip install --no-index --find-links=/local/wheels -r requirements.txt
pip install --no-index --find-links [file-path] [package-name]
```

pyinstaller offline fail for error: Could not find a version that satisfies the requirement setuptools>=40.8.0 (from versions:none)
https://github.com/pyinstaller/pyinstaller/issues/4557
```cmd
pip install --no-index --find-links [file-path] [altgraph, future, pefile, pywin32_ctypes]

cd [PyInstaller-3.5.tar.gz existed path]
pip install --no-index --no-build-isolation PyInstaller-3.5.tar.gz
```
