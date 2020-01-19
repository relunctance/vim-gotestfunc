# vim-gotestfunc
go test function keyboard shortcut: `gt` to exec `go test -run '...'`

the plug be dependent on [vim-go](https://github.com/fatih/vim-go)

## INSTALL

Before you install , you should installed [Vundle](https://github.com/VundleVim/Vundle.vim)


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
    if Max(1, 2) != 1 { 
        t.Fatalf("should be == 2")
    } 

}

func Max(a, b int) int { 
    if a > b { 
        return a 
    } 
    return b 
}
```
