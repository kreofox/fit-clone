# git-clone
### More precisely, we’ll implement: 

    add (wyag source) git man page
    cat-file (wyag source) git man page
    check-ignore (wyag source) git man page
    checkout (wyag source) git man page
    commit (wyag source) git man page
    hash-object (wyag source) git man page
    init (wyag source) git man page
    log (wyag source) git man page
    ls-files (wyag source) git man page
    ls-tree (wyag source) git man page
    rev-parse (wyag source) git man page
    rm (wyag source) git man page
    show-ref (wyag source) git man page
    status (wyag source) git man page
    tag (wyag source) git man page
> [!WARNING]
> Note for Windows users
> wyag should run on any Unix-like system with a Python interpreter, but I have absolutely no idea how it will behave on Windows. The test suite absolutely requires a bash-compatible shell, which I assume the WSL can provide. Also, if you are using WSL, make sure your wyag file uses Unix-style line endings (See this StackOverflow solution if you use VS Code). Feedback from Windows users would be appreciated!

```
import libwyag
libwyag.main()
```
```
$ chmod +x wyag
```