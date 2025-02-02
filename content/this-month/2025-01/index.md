+++
title = "This Month in Rust OSDev: January 2025"
date = 2025-02-05

[extra]
month = "January 2025"
editors = ["mvolfik"]
+++

Welcome to a new issue of _"This Month in Rust OSDev"_. In these posts, we give a regular overview of notable changes in the Rust operating system development ecosystem.

<!-- more -->

This series is openly developed [on GitHub](https://github.com/rust-osdev/homepage/). Feel free to open pull requests there with content you would like to see in the next issue. If you find some issues on this page, please report them by [creating an issue](https://github.com/rust-osdev/homepage/issues/new) or using our <a href="#comment-form">_comment form_</a> at the bottom of this page.

<!--
    This is a draft for the upcoming "This Month in Rust OSDev (December 2024)" post.
    Feel free to create pull requests against the `next` branch to add your
    content here.
    Please take a look at the past posts on https://rust-osdev.com/ to see the
    general structure of these posts.
-->

## Announcements, News, and Blog Posts

Here we collect news, blog posts, etc. related to OS development in Rust.

<!--
Please follow this template:

- [Title](https://example.com)
  - (optional) Some additional context
-->

## Infrastructure and Tooling

In this section, we collect recent updates to `rustc`, `cargo`, and other tooling that are relevant to Rust OS development.

<!--
    Please use the following template:

- [Title](https://example.com)
  - (optional) Some additional context
-->

- [Improve default target options for `x86_64-unknown-linux-none`](https://github.com/rust-lang/rust/pull/134765)
- [De-duplicate and improve definition of core::ffi::c_char](https://github.com/rust-lang/rust/pull/132975)



## Other Projects

In this section, we describe updates to Rust OS projects that are not directly related to the `rust-osdev` organization. Feel free to [create a pull request](https://github.com/rust-osdev/homepage/pulls) with the updates of your OS project for the next post.

<!--
    Please use the following template:

    ### [`owner_name/repo_name`](https://github.com/rust-osdev/owner_name/repo_name)
    <span class="maintainers">(Section written by [@your_github_name](https://github.com/your_github_name))</span>

    ...<<your project updates>>...
-->

### [`roeeshoshani/genesis`](https://github.com/roeeshoshani/genesis)
<span class="maintainers">(Section written by [@roeeshoshani](https://github.com/roeeshoshani))</span>

`genesis` is a bare metal firmware implementation for mips. it implements everything from the bottom up, from
initializing the cpu caches, to configuring pci devices and the interrupt controller.

i noticed that every kernel implementation is always for x86, so i decided to implement it for something a
little more esoteric - mips.

the project is currently in very early stages but the basics are there.

it is my hobby project for me to learn about embedded programming.

feel free to follow along the development of it :).

## Join Us?

Are you interested in Rust-based operating system development? Our `rust-osdev` organization is always open to new members and new projects. Just let us know if you want to join! A good way for getting in touch is our [Zulip chat](https://rust-osdev.zulipchat.com).
