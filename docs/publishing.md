# Publishing checklist

## 1. Repository

- **Name:** `vanta`
- **Description:** Fabric utility client for Minecraft 1.21 - 120+ modules, ClickGUI, per-server configs.
- **Topics:** `minecraft fabric minecraft-client minecraft-mod fabric-mod utility-client clickgui`
- **Visibility:** public

## 2. First push

```bash
git init
git add .
git commit -m "Vanta 2.1.0 - initial release"
git branch -M main
git remote add origin https://github.com/<you>/vanta.git
git push -u origin main
```

## 3. Release

1. Draft a release tagged `v2.1.0`.
2. Title: `Vanta 2.1.0`.
3. Body: copy the top entry from `CHANGELOG.md`.
4. Attach the build archive.
5. Publish.

## 4. Settings

| Setting | Value |
| --- | --- |
| Website | the download folder |
| Discussions | enabled |
| Issues | enabled |
| Social preview | export `assets/hero.svg` at 1280x640 |

## 5. First week

- [ ] Release + pin
- [ ] Push a small follow-up commit
- [ ] Reply to every issue within 24 h
- [ ] Publish one screenshot or clip
- [ ] Ship 2.1.0 patch with a visible fix

Keep a 2-3 day commit cadence. Consistency beats volume.