### Issues

```sh
# github.com/dell/gofsutil
/go/pkg/mod/github.com/dell/gofsutil@v1.19.0/gofsutil.go:89:19: cannot use &FS{…} (value of type *FS) as FSinterface value in variable declaration: *FS does not implement FSinterface (missing method getNVMeController)
                have GetNVMeController(string) (string, error)
                want getNVMeController(string) (string, error)
/go/pkg/mod/github.com/dell/gofsutil@v1.19.0/gofsutil_fs.go:188:18: undefined: unix.Statfs_t
/go/pkg/mod/github.com/dell/gofsutil@v1.19.0/gofsutil_fs.go:189:14: undefined: unix.Statfs
/go/pkg/mod/github.com/dell/gofsutil@v1.19.0/gofsutil_fs.go:244:12: fs.getNVMeController undefined (type *FS has no field or method getNVMeController, but does have method GetNVMeController)
make: *** [Makefile:41: build-win] Error 1
```