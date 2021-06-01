# issues
Various `/etc/issue` files I've used

I've used tux JPG images and then with something like
```
jp2a --size=65x45 tux.jpg > tux_letters.txt
```
I created the `tux_*.txt` files.

I might've also `sed`-ed some characters to make it cleaner.

Finally, I joined them with
```
paste tux_letters.txt arch > issue.arch
```

to create a Tux + Distro logo issue.
