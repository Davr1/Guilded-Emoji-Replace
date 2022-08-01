# Guilded Emoji Replace

Theme for Guilded.gg that replaces the default emoji pack with a custom one

Requires [ReGuilded](https://reguilded.dev/) or a [browser extension](https://github.com/openstyles/stylus/) for css injection

Emoji packs can be switched out in the `theme.css` file - by default each pack uses ~64x64 images or svgs for standalone emojis (used in chat, user statuses etc) and ~32x32 emojis in the emoji picker (if available, stored in one large "sheet" as a grid of emojis)

If you want to add your own emoji pack, you can check out the [wiki](https://github.com/Davr1/Guilded-Emoji-Replace/wiki/Example-emoji-pack)

# Available emoji packs
- [Apple](#apple)
- [Google](#google)
- [Microsoft_Fluent](#microsoft_fluent)
- [Facebook](#facebook)
- [Mutant_Remix](#mutant_remix)
## [Apple](https://raw.githubusercontent.com/Davr1/Guilded-Emoji-Replace/main/emojis/Apple.css)
![guilded-apple-emojis](https://user-images.githubusercontent.com/42148912/149998541-2ab0160b-4cff-4052-a68c-cf4a820a0376.png)\
Emoji support: 3326/3329
### Options
High resolution emoji sheet (64x64) ~ 18 MB:
```css
:root { --sheet_emoji_size: 64 !important; --sheet: var(--sheet_high_resolution) !important; }
```
## [Google](https://raw.githubusercontent.com/Davr1/Guilded-Emoji-Replace/main/emojis/Google.css)
[https://github.com/googlefonts/noto-emoji/](https://github.com/googlefonts/noto-emoji/) (Apache License 2.0)\
![guilded-google-emojis](https://user-images.githubusercontent.com/42148912/149998716-a509cb9d-8502-4fcd-b875-c121c44aa22e.png)\
Emoji support: 3329/3329
### Options
High resolution emoji sheet (64x64) ~ 12.3 MB:
```css
:root { --sheet_emoji_size: 64 !important; --sheet_emoji_padding: 5 !important; --sheet: var(--sheet_high_resolution) !important; }
```
## [Microsoft_Fluent](https://raw.githubusercontent.com/Davr1/Guilded-Emoji-Replace/main/emojis/Microsoft_Fluent.css)
Emoji support: 2922/3329
### Otions
High resolution sheet (each emoji is an individual image):
```css
.ReactionIcon-image { --sheet: var(--img) !important; }
```
## [Facebook](https://raw.githubusercontent.com/Davr1/Guilded-Emoji-Replace/main/emojis/Facebook.css)
![guilded-facebook-emojis](https://user-images.githubusercontent.com/42148912/149998740-462753bd-a256-4304-aa1d-dba41b840232.png)\
Emoji support: 3149/3329
### Options
High resolution emoji sheet (64x64) ~ 17.7 MB:
```css
:root { --sheet_emoji_size: 64 !important; --sheet: var(--sheet_high_resolution) !important; }
```
## [Mutant_Remix](https://raw.githubusercontent.com/Davr1/Guilded-Emoji-Replace/main/emojis/Mutant_Remix.css)
[https://mutant.revolt.chat/](https://mutant.revolt.chat/) (CC BY-NC-SA 4.0)\
![guilded-mutant_remix-emojis](https://user-images.githubusercontent.com/42148912/152642026-1ff4b337-ad49-4883-8239-000f2bc13ead.png)\
Emoji support: 1019/3329

---
### More packs will be added in the future
