# One-line Firefox

## Screenshots

![Light](images/light.png)

![Dark](images/dark.png)

## Instructions

- Use with compact density, auto-hide downloads button, remove all flexible space and unnecessary items.

![Customize](images/customize.png)

- In Firefox:
  - Open _`about:config`_ and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
  - Open _`about:support`_, click on **Open Folder**.

- Create a sub-folder named `chrome`.

- Put this [`userChrome.css`](https://raw.githubusercontent.com/khuedoan98/one-line-firefox/master/userChrome.css) into that folder (you can download this file by right-click and select _Save link as..._).

- Restart Firefox

- If your bar doesn't show up in fullscreen when moving the cursor to the top edge of the screen, see https://github.com/khuedoan98/one-line-firefox/issues/2

Based on original layout by /u/Herkt and /u/bleeps__:

https://www.reddit.com/r/FirefoxCSS/comments/7eazix/my_attempt_at_a_oneline_interface/

https://www.reddit.com/r/FirefoxCSS/comments/7ignsk/oneline_flat_interface_dark_light/
