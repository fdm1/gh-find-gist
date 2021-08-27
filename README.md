# gh-find-gist

A super-quick hacked together extension to make the `gh gist` usage a bit friendler (acting on filenames instead of gist ids)

## Usage
### Create a gist

```
gh find-gist your-gist-filename.md create
```

So long as the gist does not exist, it will create a new one with that filename with "hello world", and open it in an editor.


### Find gist

```
gh find-gist string-in-filename
```

If one gist found, it will list that gist info.

If multiple found, it will list those filenames.


### Do something with a gist

```
gh find-gist string-in-filename [edit|view|delete|clone]
```

If one gist found, it will do the command passed for that gist.

If multiple found, it will list those filenames.
