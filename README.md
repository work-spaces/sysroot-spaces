# sysroot-spaces

To add the `spaces` binary to your sysroot/bin, use:

```star
checkout.add_repo(
    rule = { "name": "tools/sysroot-spaces" },
    repo = {
        "url": "https://github.com/work-spaces/sysroot-spaces",
        "branch": "v0", 
        "checkout": "Revision" 
    }
)
```
