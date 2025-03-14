# cursor-config

My cursor config

## Usage
```
# Link files
ln -sfnv $(pwd)/settings.json ~/Library/Application\ Support/Cursor/User/
ln -sfnv $(pwd)/keybindings.json ~/Library/Application\ Support/Cursor/User/
ln -sfnv $(pwd)/snippets ~/Library/Application\ Support/Cursor/User/

# Install extensions
cat extensions.txt | xargs -L1 cursor --install-extension
```

## Backup
```
cursor --list-extensions > extensions.txt
```

