# Tree-sitter

**Tree-sitter** is a parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited. Tree-sitter aims to be:

- **General** enough to parse any programming language.
- **Fast** enough to parse on every keystroke in a text editor.
- **Robust** enough to provide useful results even in the presence of syntax errors.
- **Dependency-free** so that the runtime library (which is written in pure C) can be embedded in any application.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/tree-sitter
$ dnf install -y tree-sitter
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y tree-sitter
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/tree-sitter).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/tree-sitter) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
