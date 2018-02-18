# development_workflow
A collection of various scripts, tools, documentation, etc. for improving
workflow.

## Git Ignore

You really should have these in your Git repos to avoid accidentally committing
things you shouldn't.

- [gitignore.io](https://www.gitignore.io/)

## Markdown

This is a pretty lightweight ASCII-text based method of authoring documentation
that renders well on various platforms (e.g. GitHub, BitBucket, etc.)

- [cheat-sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [GitHub-flavored](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)


## Git Flow

I highly recommend the Git Flow branch management technique.

- [The Model](http://nvie.com/posts/a-successful-git-branching-model/)
- [The Source](https://github.com/nvie/gitflow)
- [cheat-sheet](https://danielkummer.github.io/git-flow-cheatsheet/)

```bash
apt-get install git-flow
yum install git-flow
```

## pymgit

This is a little Python command-line utility I wrote to checkout a bunch of
git repos in one shot.  The pymgit folder contains various requirements files
(the files I use to document which repos to clone)

`pymgit` is on [PyPi](https://pypi.python.org/pypi/pymgit)

```bash
pip install pymgit
```

## git-run

I highly recommend the NodeJS program `git-run` to manage the fetching, pushing,
pulling, etc. https://www.npmjs.com/package/git-run

`git-run` is on the [npmjs registry](https://www.npmjs.com/package/git-run)

```bash
yum install nodejs
npm install git-run -g
```

## IDEs

Always a highly opinionated subject.

I've used [Eclipse](https://www.eclipse.org/) as a general purpose IDE for years.
**Slightly** bloated at times, many versions, but works.

Lately, I've been favoring [IntelliJ IDEA](https://www.jetbrains.com/idea/)

- [sharing settings](https://www.jetbrains.com/help/idea/sharing-your-ide-settings.html)
- [export/import settings](https://www.jetbrains.com/help/idea/exporting-and-importing-settings.html)
- [my settings](https://github.com/watsonb/intellij_settings)

## License

MIT

## Authors

| Author | E-mail | Note |
|---|---|---|
|Ben Watson|bwatson1979@gmail.com|Primary author|