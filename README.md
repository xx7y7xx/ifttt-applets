# ifttt-applets

## Brackets Release Notifier

https://ifttt.com/applets/stZrAUne-brackets-release-notifier

Email Subject

```
[adobe/brackets] {{EntryTitle}} 🎉🎉
```

Email Body

```
<!-- This format is base on the HTML of https://github.com/adobe/brackets/releases -->
<div class="release-header">
  <h1 class="release-title text-normal"><a href="https://github.com{{EntryUrl}}">{{EntryTitle}}</a></h1>
</div>
<div class="markdown-body">
{{EntryContent}}
</div>
```

Applet title

```
Brackets Release Notifier
```

Applet description

```
Send email notification when there is a new release of Brackets 🎉🎉✉️✉️
<br><br>
The release notification is based on the feed update of GitHub repo: https://github.com/adobe/brackets/releases.atom
<br><br>
You may also like these Notifier:
<li><a href="/applets/jEq4LsYF">Atom</a></li>
<li><a href="/applets/fqrhkwWe">VSCode</a></li>
```
