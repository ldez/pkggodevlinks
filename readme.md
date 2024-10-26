# Adding Links to pkg.go.dev Module Page

Read the article: [How I published links inside the Go documentation of my module](https://ldez.github.io//blog/2024/10/26/links-godoc-module/)

## Examples

```markdown
## Links

- [Title from readme 1](https://example.com)
- [Title from readme 2](https://example.org)
```

```go
// Package foo
//
// Links
//
// - Title from godoc 1, https://example.com
// - Title from godoc 2, https://example.org
package foo
```

## Positions

- `readme.md`
- `<package>/readme.md`
- `godoc`
- `<package> godoc`

## References

- https://pkg.go.dev/about#adding-links
- https://github.com/golang/go/issues/42968
- https://go-review.googlesource.com/c/pkgsite/+/274958
- https://go-review.googlesource.com/c/pkgsite/+/274957
- https://go-review.googlesource.com/c/pkgsite/+/275276

Note: the repository must have a license that follow the [license policy](https://pkg.go.dev/license-policy).

## Links

- [🚴‍♀️ Title from readme 1](https://example.com)
- [🚴 Title from readme 2](https://example.org)
