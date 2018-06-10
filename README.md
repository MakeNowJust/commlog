<img src="./assets/img/logo.png" align="center">

[![Build Status][travis-badge]](https://travis-ci.org/MakeNowJust/commlog)

[travis-badge]: https://img.shields.io/travis/MakeNowJust/commlog/master.svg?style=for-the-badge&logo=travis

## Development

Clone repository and change directory:

```console
$ git clone https://github.com/MakeNowJust/commlog
Cloning into 'commlog'...
$ cd commlog
```

Checkout `master` branch:

```console
$ echo '*' > .gitignore
$ git worktree add dev master
Preparing dev (identifier dev)
$ cd dev
```

Install dependencies:

```console
$ yarn
yarn install v1.6.0
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...
✨  Done in 25.89s.
```

Start development server:

```console
$ yarn dev
yarn run v1.6.0

 INFO  Building project

✔ success Builder initialized
✔ success Nuxt files generated

 READY  Listening on http://localhost:3000
```

Then, open <http://localhost:3000/commlog/>.

## License

MIT - TSUYUSATO "[MakeNowJust]" Kitsune

[makenowjust]: https://github.com/MakeNowJust
