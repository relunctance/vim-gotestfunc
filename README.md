# vim-gotestfunc
go test function keyboard shortcut: `gt` to exec `go test -run '...'`

This plug depends on  [Vundle](https://github.com/VundleVim/Vundle.vim) and [vim-go](https://github.com/fatih/vim-go)



![useage](https://s17.aconvert.com/convert/p3r68-cdx67/gzs1g-kxfb8.gif)


## INSTALL

Before you install , you should installed [Vundle](https://github.com/VundleVim/Vundle.vim) and [vim-go](https://github.com/fatih/vim-go)



```vim
Plugin 'relunctance/vim-gotestfunc'
```





## Install Step:

Step1 : modify you .vimrc 

```
vim ~/.vimrc
```

Step2: add the plug `vim-gotestfunc` into `.vimrc`

```vim
Plugin 'relunctance/vim-gotestfunc'
```

Step3: quit `~/.vimrc`
```
:wq
```

Step4: Install Bundle Plug

```
vim ~/.vimrc
:BundleInstall
```
    

### Useage Example

`vim demo_test.go`

```go
package demo

import (
	"testing"
)

func TestMax(t *testing.T) {
	v := 1
	if v != 2 {
		t.Fatalf("should be == 2")
	}

}
```
