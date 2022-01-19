# Guilded Emoji Replace

Theme for Guilded.gg that replaces the default emoji pack with a custom one

Requires [ReGuilded](https://reguilded.dev/) or a [browser extension](https://github.com/openstyles/stylus/) for css injection

Emoji sheets and individual images are imported from [iamcal/emoji-data](https://github.com/iamcal/emoji-data/)

Emoji packs can be switched out in the `theme.css` file - by default each pack uses 64x64 images for standalone emojis (used in chat, user statuses etc) and 32x32 emojis in the emoji picker (stored in one large "sheet", as a grid of emojis)

# Available emoji packs
- [Apple](#apple)
- [Google](#google)
- [Facebook](#facebook)
## Apple
![guilded-apple-emojis](https://user-images.githubusercontent.com/42148912/149998541-2ab0160b-4cff-4052-a68c-cf4a820a0376.png)\
Emoji support: 3234/3237
### Options
High resolution emoji sheet (64x64) ~ 18 MB:
```css
:root { --sheet_emoji_size: 64 !important; --sheet: var(--sheet_high_resolution) !important; }
```
## Google
![guilded-google-emojis](https://user-images.githubusercontent.com/42148912/149998716-a509cb9d-8502-4fcd-b875-c121c44aa22e.png)\
Emoji support: 3237/3237
### Options
High resolution emoji sheet (64x64) ~ 12.3 MB:
```css
:root { --sheet_emoji_size: 64 !important; --sheet: var(--sheet_high_resolution) !important; }
```
## Facebook
![guilded-facebook-emojis](https://user-images.githubusercontent.com/42148912/149998740-462753bd-a256-4304-aa1d-dba41b840232.png)\
Emoji support: 3144/3237
### Options
High resolution emoji sheet (64x64) ~ 17.7 MB:
```css
:root { --sheet_emoji_size: 64 !important; --sheet: var(--sheet_high_resolution) !important; }
```
---
### More packs will be added in the future
