## PaperEvent

`PaperEvent` is a [Hugo](https://gohugo.io/) theme based on theme [hugo-PaperMod](https://github.com/adityatelange/hugo-PaperMod).

---
### Custom changes with PaperEvent 🚀

> [TODO]

---

### Getting Started 🚀

1. Follow **[Hugo Docs's - Quick Start](https://gohugo.io/getting-started/quick-start/)** guide to install Hugo.
   <br>(Make sure you install **Hugo >= v0.147.2**)

2. Create a new Hugo site
   ```sh
   hugo new site MyNewEventSite --format yaml
   # replace MyNewEventSite with name of your website
   ```
   Note:
   - Older versions of Hugo may not support `--format yaml`
   - Read more here about [Hugo Docs's - hugo new site command](https://gohugo.io/commands/hugo_new_site/#synopsis)

After you have created a new site, follow the below steps to add **PaperEvent**

#### Installing/Updating PaperEvent

- Themes reside in `MyNewEventSite/themes` directory.
- PaperEvent will be installed in `MyNewEventSite/themes/PaperEvent`

> <details>
> <summary><b>Expand Method 1 - Git Clone</b></summary>
>
> **INSTALL** : Inside the folder of your Hugo site `MyNewEventSite`, run:
>
> ```bash
> git clone https://github.com/yogeshjain96/hugo-paper-event themes/PaperEvent --depth=1
> ```
>
> **UPDATE**: Inside the folder of your Hugo site `MyNewEventSite`, run:
>
> ```bash
> cd themes/PaperEvent
> git pull
> ```
>
> </details>

<br>

> <details>
> <summary><b>Expand Method 2 - Git Submodule (recomended)</b></summary>
>
> **INSTALL** : Inside the folder of your Hugo site `MyNewSite`, run:
>
> ```bash
> git submodule add --depth=1 https://github.com/yogeshjain96/hugo-paper-event.git themes/PaperEvent
> git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
> ```
>
> You may use ` --branch v7.0` to end of above command if you want to stick to specific release.
> Read more about git submodules [here](https://www.atlassian.com/git/tutorials/git-submodule).
>
> **UPDATE**: Inside the folder of your Hugo site `MyNewSite`, run:
>
> ```bash
> git submodule update --remote --merge
> ```
>
> </details>

<br>


```yaml
theme: ["PaperEvent"]
```

#### Next - Customizing PaperEvent to suit your preferences

As `PaperEvent` is a custom version of PaperMod theme, existing doc version is still valid.
Documentation of PaperMod theme can be found here: [**📚 Wiki**](https://github.com/adityatelange/hugo-PaperMod/wiki)

Aditionally, following configs are also supported:
> TODO

---

### Support 🫶

- Star 🌟 this repository.
- Help spread the word about PaperEvent by sharing it on social media and recommending it to your friends.

---
