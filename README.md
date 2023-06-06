# udemy-building-modern-web-applications-with-go

## Section 1: Introduction

### What we will do?

- Learn the fundamentals of Go programming language
- Learn how to build a web application with Go
- Learn how to deploy a web application to a live server

### Why go?

- compiled language, single binary file (fast)
- no runtime to worry about
- statically typed, so no surprises at runtime
- object-oriented (sort of), but not class based
- concurrency built in
- garbage collected
- cross-platform
- excellent package management and testing built in

now, let look at examples:

- the left terminal is running a Go program, and the right terminal is running a PHP program. then we run command `top`
  and `uptime` to see load of each server:

![load](./img/section-01-001.png)

- as we can see that the server that running Go program has a lower load than the server that running PHP program. this
  is because Go is a compiled language, so it's faster than PHP, which is an interpreted language.
