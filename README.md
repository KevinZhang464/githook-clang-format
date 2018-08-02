githook-clang-format
====================

For Objective-C

When committing code, added files will been formatted

auto format code via git-hook(pre-commit)

Install
-------

Install dependence

```bash
brew install clang-format
```

Init pre-commit(git-hook) file

```bash
cd $PROJECT
cd .git/hooks
wget https://raw.githubusercontent.com/motherapp/githook-clang-format/master/clang-format.hook -O pre-commit
sudo chmod +x pre-commit
```

Custom Code Style
-------

[Clang Format](https://clang.llvm.org/docs/ClangFormat.html)

[Clang Format Style Options](https://clang.llvm.org/docs/ClangFormatStyleOptions.html)

```bash
vim .git/hooks/pre-commit
```
