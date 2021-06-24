# One-line Firefox

## Screenshots

![Light](https://user-images.githubusercontent.com/27996771/123281450-e5c6ee00-d533-11eb-85ad-fbabc0220948.png)

![Dark](https://user-images.githubusercontent.com/27996771/123281332-cdef6a00-d533-11eb-889b-8324a9163198.png)

## Get Started

### In Firefox

- Open _`about:config`_ and set:
  - `toolkit.legacyUserProfileCustomizations.stylesheets`: `true`
  - `browser.compactmode.show`: `true`
  - `extensions.pocket.enabled`: `false`
- Go to Menu > More Tools > Customize Toolbar...: use compact density, auto-hide downloads button, remove all flexible space and unnecessary items.
- Open _`about:support`_, copy Profile Folder

### In terminal

```sh
cd $PROFILE_FOLDER # copied from the previous step
git clone https://github.com/khuedoan/one-line-firefox chrome
```

Then restart Firefox.

If your bar doesn't show up in fullscreen when moving the cursor to the top edge of the screen, see [#2](https://github.com/khuedoan98/one-line-firefox/issues/2)

## Acknowledgements

- https://www.reddit.com/r/FirefoxCSS/comments/7eazix/my_attempt_at_a_oneline_interface/
- https://www.reddit.com/r/FirefoxCSS/comments/7ignsk/oneline_flat_interface_dark_light/
- https://github.com/andreasgrafen/ag.proton
