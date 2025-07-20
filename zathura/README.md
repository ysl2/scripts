# zathura

## Mac installation

> Ref: <https://github.com/homebrew-zathura/homebrew-zathura>

```bash
brew tap homebrew-zathura/zathura
brew install zathura --with-synctex
brew install zathura-pdf-mupdf zathura-pdf-poppler
d=$(brew --prefix zathura)/lib/zathura ; mkdir -p $d ; for n in cb djvu pdf-mupdf pdf-poppler ps ; do p=$(brew --prefix zathura-$n)/lib$n.dylib ; [[ -f $p ]] && ln -s $p $d ; done
```
