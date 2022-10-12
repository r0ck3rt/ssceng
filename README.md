<p align="center">
    <img width="200" src="https://kyoto.codes/images/logo.svg" />
</p>

<h1 align="center">Kyoto Framework</h1>

<p align="center">
    Set of libraries and tools to create asynchronous frontends with Go
</p>

<p align="center">
    <img src="https://img.shields.io/github/license/kyoto-framework/kyoto">
    <a href="https://opencollective.com/kyoto-framework">
        <img src="https://img.shields.io/opencollective/all/kyoto-framework?label=backers%20%26%20sponsors">
    </a>
    <img src="https://visitor-badge.glitch.me/badge?page_id=kyoto-framework&left_color=grey&right_color=green">
</p>

<p align="center">
    <a href="https://pkg.go.dev/git.sr.ht/~kyoto-framework/kyoto">Website</a>&nbsp;&bull; <a href="#team">Get Started</a>&nbsp;&bull; <a href="#who-uses">Repository</a>&nbsp;&bull; <a href="#support-us">Support us</a>
</p>

## Motivation

Creating asynchronous and dynamic layout parts is a complex problem for larger projects using `html/template`.
Library tries to simplify this process.

## What kyoto proposes?

- Organize code into configurable, standalone components structure
- SSR-first, zero JavaScript payload (without actions client)
- Organize code into configurable and standalone components structure
- Simple asynchronous lifecycle
- Built-in dynamics like Hotwire or Laravel Livewire (requires thin JS client)
- Using a familiar built-in `html/template`
- No external dependencies

## Reasons to opt out

- API may change drastically between major versions
- You want to develop SPA/PWA
- You're just feeling OK with JS frameworks
- Not suitable for a frontend with a lot of client-side logic

## Team

- Yurii Zinets: [email](mailto:yurii.zinets@icloud.com), [telegram](https://t.me/yuriizinets)
- Viktor Korniichuk: [email](mailto:rowdyhcs@gmail.com), [telegram](https://t.me/dinoarmless)

## Who uses?

### Broker One

**Website**: [https://mybrokerone.com](https://mybrokerone.com)

The first version of the site was developed with Vue and suffered from large payload and low performance.
After discussion, it was decided to migrate to Go with a built-in `html/template` due to existing libraries infrastructure inside the project.  
Despite the good performance result, the code was badly structured, and it was very uncomfortable to work in the existing paradigm.  
On the basis of these problems, kyoto was born. Now, this library lies in the core of the platform.

### Using the library in your project?

Please tell us about your story! We would love to talk about your usage experience.

## Why using sr.ht instead of GitHub?

Please, check this article: [Project is moving from GitHub to sr.ht](https://kyoto.codes/blog/migration-srht)  

Anyway, I'm keeping this repository to not break communication with people using GitHub. Think of it as an embassy of the project on GitHub. Feel free to open discussions or issues right here.

## Contributing

Sourcehut differs from GitHub/GitLab/etc in terms of collaborating. It doesn't have Pull Requests and utilizes patchsets and mailing lists as the main form of contribution.

You don't have to create an account on Sourcehut, fork project, etc (but doing so simplifies patchset creation and sending with UI). It's enough to clone repository, create a new branch with your changes, generate a patchset and send it to the specific email (even my personal one).

```bash
# A usual read-only git clone
$ git clone https://git.sr.ht/~kyoto-framework/kyoto
# Going to the project directory
$ cd kyoto
# Creating a new branch that will hold our changes
$ git checkout patchset-branch
# Make any changes you want here
# ...
# Adding and committing your changes
$ git add .
$ git commit -m "My change"
# Creating patchset
$ git format-patch master --stdout > mypatch.patch
# Then, just send this patch to this email: ~kyoto-framework/patches@lists.sr.ht
# It will be displayed here: https://lists.sr.ht/~kyoto-framework/patches
```

## Support us

Any project support is appreciated! Providing feedback, patches, new ideas, whatever. Also, donations and sponsoring will help us to keep high updates frequency. Just send us a quick email or a message on contacts provided above.

If you have an option to donate to us with a crypto, we are glad to provide these addresses:

Bitcoin: `bc1qgxe4u799f8pdyzk65sqpq28xj0yc6g05ckhvkk`  
Ethereum: `0xEB2f24e830223bE081264e0c81fb5FD4DDD2B7B0`

Also, we have a page on open collective for backers support.

Open Collective: [https://opencollective.com/kyoto-framework](https://opencollective.com/kyoto-framework)
