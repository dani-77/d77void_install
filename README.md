This is a install guide for d77void (a simple respin of Void GNU/Linux made with WM)

It was made using mdBook.
This book requires mdBook, mdbook-toc and mdbook-admonish.

You can use

```
sudo xbps-install mdBook mdbook-toc
```
to install the dependencies on Void Linux. 


Note that mdbook-admonish isn't currently packaged on Void Linux. You can download its executable in ![HERE](https://github.com/tommilligan/mdbook-admonish/releases/latest).

You'll have to extract the appropriate archive and put the executable into a directory in $PATH.

Then, after cloning this repo.

```
mdbook serve
```

Open your browser ![on](http://localhost:3000/) 
