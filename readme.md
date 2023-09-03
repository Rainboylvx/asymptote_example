
## Prepare

under archlinux os

```
sudo pacman -S asymptote texlive
```

download [hello.asy](./hello.asy),then compile it

```bash
asy hello.asy
```

then get `hello.svg`

![hello.svg](./hello.svg)

change `settings.outformat = "svg";`,get below png file
![hello.png](./hello.png)

