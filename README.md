# git-bars

> [!NOTE]
> Disclaimer 📢
>
> This is a fork of the original git-bars, if you are looking for the original version, check the link below


[official repository](https://github.com/knadh/git-bars)

`git-bars` is a utility that uses `git log` to render a simple git commit activity bars on the terminal. Commit activity can be grouped by day, month, year, between two dates, and can be filtered by author.

```shell
$> cd /path/to/a/git/repo
$> git-bars -p day

78 commits
2018-11-27 4    ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-11-26 9    ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-11-06 10   ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-11-05 11   ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-11-03 2    ▀▀▀▀▀▀▀▀
2018-11-02 12   ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-11-01 5    ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-10-31 8    ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-10-30 4    ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-10-29 4    ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-10-26 7    ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
2018-10-25 2    ▀▀▀▀▀▀▀▀
```

## Install with pipx
```bash
pipx install git+https://github.com/Gpocas/git-bars.git
```

See `git-bars --help` for options.

## Native Install with briefcase
```bash
poetry run briefcase build
poetry run briefcase package
```

install native package (Ubuntu)

```bash
sudo apt install package.deb
```
