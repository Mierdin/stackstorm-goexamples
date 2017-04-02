# Go Examples

This is an experimental StackStorm pack for working with the even more experimental, unstable, and potentially flammable Go runner. Thou hast been warned.

# Update Deps

Quick cheat sheet for updating deps in this pack

```
  cd stackstorm-goexamples/
  GOPATH=$GOPATH:$(pwd)/actions
  cd actions/src/vendor_example
  godep save ./...
```
