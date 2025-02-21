This is a install guide for d77void (a simple respin of Void GNU/Linux with a Window Manager)

This guide was made using mdBook.
To see the book in your browser, it is required mdBook, mdbook-toc and mdbook-admonish.

You can install them like this on Void or any derivative.

```
sudo xbps-install mdBook mdbook-toc
```

Note that mdbook-admonish isn't currently packaged on Void Linux. You can download its executable ![here](https://github.com/tommilligan/mdbook-admonish/releases/latest).

You'll have to extract the appropriate archive and put the executable into a directory in $PATH.

Then, after cloning this repo.

```
mdbook serve
```

Open your browser at http://localhost:3000/
