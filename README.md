# bump

bumps up the string in version.NewSemver.

``` go
$ cat main.go
package main

import version "github.com/hashicorp/go-version"

var ver = version.Must(version.NewSemver("0.1.2"))

$ bump patch main.go
package main

import version "github.com/hashicorp/go-version"

var ver = version.Must(version.NewSemver("0.1.3"))
```
