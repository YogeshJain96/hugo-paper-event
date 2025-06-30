<h1 align=center>Hugo PaperEvent | <a href="https://curiousone.in/hugo-paper-event/" target="_blank" rel="nofollow">Demo</a></h1>

<h4 align=center>Designed for events, conferences & Meetups</h4>
<br>

**`PaperEvent`** is a [Hugo](https://gohugo.io/) theme based on theme [hugo-PaperMod](https://github.com/adityatelange/hugo-PaperMod).

**Demo Example Site** can be found here: [**example-site**](https://github.com/yogeshjain96/hugo-paper-event/tree/example-site). Demo is built up with [example-site](https://github.com/yogeshjain96/hugo-paper-event/tree/example-site) as source.

---

### Custom changes with PaperEvent 🚀

- To add new meetups

    Run: `hugo new --kind meetups meetups/3.md`
    or manually add new files in content/meetups dir

- To add new speakers

    Run: `hugo new --kind speakers speakers/speaker-name.md`
    or manually add new files in content/speakers dir

- To add new Talk or session details
   Run: `hugo new --kind speakers talk/talk-2.md`
    or manually add new files in content/talk dir

- To update the Dates, Meetup titles, countdown, venues, links edit [data/info.yaml](https://github.com/YogeshJain96/hugo-paper-event/blob/example-site/data/info.yaml) file in data dir
- To update the SLIDES images, refer example site [data/slider.yaml](https://github.com/YogeshJain96/hugo-paper-event/blob/example-site/data/slider.yaml) file in data dir
- To update the SCHEDULE, refer example site [data/schedule.yaml](https://github.com/YogeshJain96/hugo-paper-event/blob/example-site/data/schedule.yaml) file in data dir
- To update HOME page content, refer example site [config.yaml](https://github.com/YogeshJain96/hugo-paper-event/blob/example-site/config.yaml) file
- To update ABOUT page, refer example site [about.md](https://github.com/YogeshJain96/hugo-paper-event/blob/example-site/content/about.md) file in content dir
- To update CFP page, refer example site [call-for-papers.md](https://github.com/YogeshJain96/hugo-paper-event/blob/example-site/content/call-for-papers.md) file in content dir
- To update REGISTER page, refer example site [register.md](https://github.com/YogeshJain96/hugo-paper-event/blob/example-site/content/register.md) file in content dir

Refer to https://github.com/YogeshJain96/hugo-paper-event/tree/example-site for more details

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
> **INSTALL** : Inside the folder of your Hugo site `MyNewEventSite`, run:
>
> ```bash
> git submodule add --depth=1 https://github.com/yogeshjain96/hugo-paper-event.git themes/PaperEvent
> git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
> ```
>
> You may use ` --branch v7.0` to end of above command if you want to stick to specific release.
> Read more about git submodules [here](https://www.atlassian.com/git/tutorials/git-submodule).
>
> **UPDATE**: Inside the folder of your Hugo site `MyNewEventSite`, run:
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
