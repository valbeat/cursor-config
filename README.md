# cursor-settings

My cursor-settings

## Usage
```
# Link files
ln -sfnv $(pwd)/settings.json ~/Library/Application\ Support/Cursor/User/
ln -sfnv $(pwd)/keybindings.json ~/Library/Application\ Support/Cursor/User/
ln -sfnv $(pwd)/snippets ~/Library/Application\ Support/Cursor/User/

# Install extensions
cat extensions.txt | xargs -L1 code --install-extension
```

## Backup
```
code --list-extensions > extensions.txt
```

