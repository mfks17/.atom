# .atom
:octocat: My ATOM setting

## Usage

- clone .atom

```
$ git clone git@github.com:mfks17/.atom.git ~/
```

- Install atom packages with package list.

```
$ apm list --installed --bare > packages.txt
```

- If you wanna manage atom packages with stars.

```
$ apm star --installed

Welcome to Atom!

Before you can publish packages, you'll need an API token.

Visit your account page on Atom.io https://atom.io/account,
copy the token and paste it below when prompted.

Press [Enter] to open your account page on Atom.io.
Token>
```

- Copy API token from [atom.io](https://atom.io/) page and paste API Token after ```Token>``` .

- When you wanna install atom packages with star.

```
$ apm stars --install
```
