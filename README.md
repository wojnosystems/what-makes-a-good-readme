# Overview

Promote the use of effective README's to help developers find and use the right tools in the right way.

# How to install it

You're installing it into your brain as we speak.

# Sections

I always have at least 3 sections:

* Overview: What is this thing's purpose? What problem(s) is it solving?
* How to install it
* How to use it with code examples

Here's a sample to get you started:

<pre>
# Overview

This library starts a process and waits for all files listed to exist before shutting down the process and returning control to the caller.

# How to install

`go get -u github.com/wojnosystems/go-filewaiter`

# How to use

```golang
package main

import "github.com/wojnosystems/go-thing-doer"

func main() {
    [...fill this out next...]
    thingDoer.CureCancer()
}
```
</pre>

This helps developers new to your library by showing them how to get started quickly. Most new GitHub libraries and frameworks operate this way. It's usually much more helpful than writing copious documentation without examples. So let's get to that example.
