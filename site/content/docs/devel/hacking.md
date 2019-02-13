# Coding
## Update
`/hack/update-all.sh` run all update scripts.
The exisitng scripts are `/hack/update-deps.sh`, /hack/update-generated.sh`,
and`/hack/update-gofmt.sh`.

`/hack/update-deps.sh` run [dep][dep] to get all the project into a likely
compilable state by managing all the specified dependencies.
This script is design in a self-contained manner, meaning that you can specify
the path to the dep executable by setting the variable `DEP`.
Else, `hack/update-deps.sh` will installed a vendored version of dep in
``~/go/src/sigs.k8s.io/kind/_output/bin``.

* Verify


# Usage
* Build
* CI
* Release

[dep]: https://github.com/golang/dep
