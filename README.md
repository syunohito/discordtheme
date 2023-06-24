:root {
  --fluent-version: "1.1.0";
  --transition: cubic-bezier(0, 0, 0, 1);
  --accent-text: #000;
  --accent-solid: rgb(var(--accent));
  --pill-width: 4px;
  --pill-height: 16px;
  --pill-transition: opacity 0.15s var(--transition), height 0.15s var(--transition);
  --btn-radius: 6px;
  --rounded-high: 8px;
  --rounded: 4px;
  --toolbar-height: 64px;
  --bottombar-height: 64px;
  --font-weight-light: 300;
  --font-weight-semilight: 350;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-size-xs: 12px;
  --font-size-sm: 14px;
  --font-size: 16px;
  --font-size-md: 18px;
  --font-size-lg: 20px;
  --font-size-xl: 28px;
  --font-size-2xl: 40px;
  --line-height: 16px;
  --line-height-md: 20px;
  --line-height-lg: 24px;
  --line-height-xl: 28px;
  --line-height-2xl: 36px;
  --line-height-3xl: 52px;
  --font-display: "Segoe UI", sans-serif;
  --font-primary: "Segoe UI", sans-serif;
  --shadow-flyout: 0px 8px 16px hsla(0 0% 0% / 0.14);
  --shadow-dialog: 0px 32px 64px hsla(0 0% 0% / 0.188) 0px 2px 21px hsla(0 0% 0% / 0.147);
  --cursor: default;
  --chat-mention-colour: var(--accent);
  --chat-padding-y: 12px;
  --chat-padding-x: 16px;
  --chat-spacing-y: 32px;
  --chat-spacing-x: 24px;
  --server-icon-size: 28px;
  --server-container: calc(var(--server-size) + 16px);
  --server-hover-selected: inset 0 0 0 100vmax var(--server-bg), inset 1px 0 0 var(--btn-border-x), inset 0 1px 0 var(--btn-border-t),
  	inset -1px 0 var(--btn-border-x), inset 0 -1px 0 var(--btn-border-b);
  --server-icon-shape: 50%;
  --server-folder-icon-shape: 2px;
  --channel-padding: 8px;
  --banner-height: 155px;
  --win-btn-height: 32px;
  --win-btn-width: 52px;
  --profile-premium-text-shadow: 0 2px 5px hsl(0 0% 0% / 0.75);
  --discord-pink: 302 calc(var(--saturation-factor, 1) * 100%) 72.5%;
  --discord-red: 359 calc(var(--saturation-factor, 1) * 82.6%) 59.4%;
  --discord-grey: 217 8% 34%;
  --text-normal: var(--text-primary);
  --text-muted: var(--text-tertiary);
  --interactive-muted: var(--text-quaternary);
  --text-link: rgb(var(--accent));
}

.theme-dark,
html.theme-dark #app-mount .theme-light .root-g14mjS {
  --dark-bg-h: var(--dark-background-hue, 0);
  --dark-bg-s: var(--dark-background-saturation, 0%);
  --bg-main: hsl(var(--dark-bg-h) var(--dark-bg-s) 13%);
  --bg-alt: hsl(var(--dark-bg-h) var(--dark-bg-s) 15%);
  --bg-content: hsl(var(--dark-bg-h) var(--dark-bg-s) 17%);
  --bg-content-alt: hsl(var(--dark-bg-h) var(--dark-bg-s) 18%);
  --bg-transparent: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.25);
  --bg-transparent-hover: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.35);
  --bg-transparent-active: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.4);
  --bg-interactive: hsl(var(--dark-bg-h) var(--dark-bg-s) 18%);
  --bg-interactive-high: hsl(var(--dark-bg-h) var(--dark-bg-s) 20%);
  --bg-interactive-hover: hsl(var(--dark-bg-h) var(--dark-bg-s) 16%);
  --bg-interactive-high-hover: hsl(var(--dark-bg-h) var(--dark-bg-s) 18%);
  --bg-high: hsl(var(--dark-bg-h) var(--dark-bg-s) 20%);
  --bg-higher: hsl(var(--dark-bg-h) var(--dark-bg-s) 23%);
  --bg-highest: hsl(var(--dark-bg-h) var(--dark-bg-s) 28%);
  --bg-menu: hsl(var(--dark-bg-h) var(--dark-bg-s) 17%);
  --bg-menu-item: hsl(var(--dark-bg-h) var(--dark-bg-s) 22%);
  --bg-menu-item-hover: hsl(var(--dark-bg-h) var(--dark-bg-s) 20%);
  --chat-bubble-bg: hsl(var(--dark-bg-h) var(--dark-bg-s) 18%);
  --chat-mention-bubble: hsl(var(--dark-bg-h) var(--dark-bg-s) 100% / 0.05);
  --border: hsl(var(--dark-bg-h) var(--dark-bg-s) 11%);
  --border-mid: hsl(var(--dark-bg-h) var(--dark-bg-s) 20%);
  --border-high: hsl(var(--dark-bg-h) var(--dark-bg-s) 23%);
  --pill-unread: hsl(var(--dark-bg-h) var(--dark-bg-s) 60%);
  --pill-hovered: #fff;
  --btn-bg: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.2);
  --btn-bg-hover: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.25);
  --btn-bg-active: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.1);
  --btn-border-t: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.3);
  --btn-border-x: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.1);
  --btn-border-b: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.1);
  --btn-border-active: hsl(var(--dark-bg-h) var(--dark-bg-s) 40% / 0.2);
  --scrollbar-background: hsl(var(--dark-bg-h) var(--dark-bg-s) 50%);
  --server-bg: hsl(var(--dark-bg-h) var(--dark-bg-s) 50% / 0.2);
  --folder-bg: var(--server-bg);
  --textbox-bg: hsl(var(--dark-bg-h) var(--dark-bg-s) 18%);
  --textbox-bg-high: hsl(var(--dark-bg-h) var(--dark-bg-s) 20%);
  --textbox-bg-hover: hsl(var(--dark-bg-h) var(--dark-bg-s) 20%);
  --textbox-bg-high-hover: hsl(var(--dark-bg-h) var(--dark-bg-s) 22%);
  --textbox-bg-active: hsl(var(--dark-bg-h) var(--dark-bg-s) 13%);
  --textbox-bg-high-active: hsl(var(--dark-bg-h) var(--dark-bg-s) 16%);
  --textbox-border: hsl(var(--dark-bg-h) var(--dark-bg-s) 19%);
  --textbox-underline: hsl(var(--dark-bg-h) var(--dark-bg-s) 60%);
  --switch-border: hsl(var(--dark-bg-h) var(--dark-bg-s) 94% / 54.42%);
  --text-primary: hsl(var(--dark-bg-h) var(--dark-bg-s) 90%);
  --text-secondary: hsl(var(--dark-bg-h) var(--dark-bg-s) 85% / 75%);
  --text-tertiary: hsl(var(--dark-bg-h) var(--dark-bg-s) 80% / 55%);
  --text-quaternary: hsl(var(--dark-bg-h) var(--dark-bg-s) 75% / 35%);
}

.theme-light,
html.theme-light #app-mount .theme-light .root-g14mjS {
  --bg-main: #f3f3f3;
  --bg-alt: #fafafa;
  --bg-content: #fbfbfb;
  --bg-content-alt: #f6f6f6;
  --bg-transparent: hsl(0 0% 40% / 0.25);
  --bg-transparent-hover: hsl(0 0% 40% / 0.35);
  --bg-transparent-active: hsl(0 0% 40% / 0.4);
  --bg-interactive: #eaeaea;
  --bg-interactive-hover: #ededed;
  --bg-interactive-high: #eeeeee;
  --bg-interactive-high-hover: #f1f1f1;
  --bg-high: #fff;
  --bg-higher: #fff;
  --bg-highest: #fff;
  --bg-menu: #f9f9f9;
  --bg-menu-item: #f0f0f0;
  --bg-menu-item-hover: #f3f3f3;
  --chat-bubble-bg: var(--bg-main);
  --chat-mention-bubble: hsl(0 0% 0% / 0.05);
  --border: #e5e5e5;
  --border-mid: #e8e8e8;
  --border-high: #ececec;
  --pill-unread: #9a9a9a;
  --pill-hovered: #fff;
  --btn-bg: hsl(0 0% 100%);
  --btn-bg-hover: hsl(0 0% 0% / 0.005);
  --btn-bg-active: hsl(0 0% 100% / 0.005);
  --btn-border-t: hsl(0 0% 0% / 0.06);
  --btn-border-x: hsl(0 0% 0% / 0.06);
  --btn-border-b: hsl(0 0% 0% / 0.15);
  --btn-border-active: hsl(0 0% 0% / 0.15);
  --scrollbar-background: hsl(0 0% 50%);
  --server-bg: hsl(0 0% 0% / 0.08);
  --folder-bg: var(--server-bg);
  --textbox-bg: #fbfbfb;
  --textbox-bg-hover: #f6f6f6;
  --textbox-bg-active: #f6f6f6;
  --textbox-border: #e5e5e5;
  --textbox-underline: #868686;
  --switch-border: hsl(0 0% 0% / 54.42%);
  --text-primary: hsl(0 0% 0% / 100%);
  --text-secondary: hsl(0 0% 0% / 75%);
  --text-tertiary: hsl(0 0% 0% / 55%);
}

@font-face {
  font-family: "Segoe UI";
  src: local("Segoe UI Light"), url("https://discordstyles.github.io/Fluent/fonts/light.woff2") format("woff2");
  font-weight: 100;
}
@font-face {
  font-family: "Segoe UI";
  src: local("Segoe UI Semilight"), url("https://discordstyles.github.io/Fluent/fonts/semilight.woff2") format("woff2");
  font-weight: 200;
}
@font-face {
  font-family: "Segoe UI";
  src: local("Segoe UI"), url("https://discordstyles.github.io/Fluent/fonts/normal.woff2") format("woff2");
  font-weight: 400;
}
@font-face {
  font-family: "Segoe UI";
  src: local("Segoe UI Semibold"), url("https://discordstyles.github.io/Fluent/fonts/semibold.woff2") format("woff2");
  font-weight: 600;
}
@font-face {
  font-family: "Segoe UI";
  src: local("Segoe UI Bold"), url("https://discordstyles.github.io/Fluent/fonts/bold.woff2") format("woff2");
  font-weight: 700;
}
html,
span:not([class*=spinner-], [class*=spinnerItem]) {
  backface-visibility: hidden;
}

body,
#app-mount,
.app-2CXKsg {
  background: var(--bg-main);
}

.bg-1QIAus {
  background: transparent;
}

[class*=clickable-],
[class*=cursorPointer-],
[class*=selectable-] {
  cursor: var(--cursor) !important;
}

.base-2jDfDU {
  background: var(--bg-alt);
  border-top: 1px solid var(--border-high);
  border-left: 1px solid var(--border-high);
  border-top-left-radius: var(--rounded);
  overflow: visible;
}

.content-1SgpWY {
  width: calc(100vw - var(--server-container));
}

.layer-86YKbF:not(.baseLayer-W6S8cY) .info-3pQQBb > .line-18uChy:first-child::before {
  display: block;
  content: "Fluent v" var(--fluent-version);
  text-transform: none;
}

.layer-86YKbF {
  transform: scale(1) !important;
  z-index: 1;
}
.layer-86YKbF.baseLayer-W6S8cY {
  transform: none !important;
  opacity: 1 !important;
  padding-top: 0 !important;
  transition: none !important;
}

#app-mount .tooltip-14MtrL {
  box-shadow: var(--shadow-flyout);
  font-size: 14px;
  border-radius: var(--rounded);
}
#app-mount .tooltipContent-38tm3I {
  padding: 6px 8px;
}
#app-mount .tooltipPointer-sMBQqe {
  border-top-color: var(--border-high);
}
#app-mount .tooltipPrimary-2466a2 {
  border: 1px solid var(--bg-highest);
  background: var(--bg-high);
}
#app-mount .guildNameText-jBFbNC,
#app-mount .tooltipContent-38tm3I {
  font-weight: 500;
}

::-webkit-scrollbar-track {
  background: transparent !important;
  border-color: transparent !important;
}

::-webkit-scrollbar-thumb {
  background-color: var(--scrollbar-background) !important;
}

.chatContent-3KubbW .scroller-kQBbkU::-webkit-scrollbar,
.peopleList-2VBrVI::-webkit-scrollbar,
.scroller-2qwVWY::-webkit-scrollbar {
  width: 10px;
  height: 10px;
}
.chatContent-3KubbW .scroller-kQBbkU::-webkit-scrollbar-track,
.peopleList-2VBrVI::-webkit-scrollbar-track,
.scroller-2qwVWY::-webkit-scrollbar-track {
  background: transparent !important;
  border-color: transparent !important;
}
.chatContent-3KubbW .scroller-kQBbkU::-webkit-scrollbar-thumb,
.peopleList-2VBrVI::-webkit-scrollbar-thumb,
.scroller-2qwVWY::-webkit-scrollbar-thumb {
  background-color: var(--scrollbar-background);
}

.members-3WRCEx::-webkit-scrollbar,
.container-1NXEtd .scroller-1ox3I2::-webkit-scrollbar,
.sidebarRegionScroller-FXiQOh::-webkit-scrollbar,
.scroller-WSmht3::-webkit-scrollbar {
  width: 6px;
  height: 6px;
}

#app-mount .container-ZMc96U {
  background: var(--bg-alt);
  border-bottom: 1px solid var(--border-mid);
  height: var(--toolbar-height);
  padding: 0 16px;
}
#app-mount .container-ZMc96U::before {
  content: none;
}
#app-mount .children-3xh0VB {
  margin-right: 16px;
}
#app-mount .children-3xh0VB > .iconWrapper-2awDjA {
  margin: 0 16px 0 0;
}
#app-mount .children-3xh0VB .divider-q3P9HC {
  display: none;
}
#app-mount .children-3xh0VB::after {
  content: none;
}
#app-mount .toolbar-3_r2xA {
  gap: 16px;
}
#app-mount .toolbar-3_r2xA .iconWrapper-2awDjA {
  margin: 0;
}
#app-mount .toolbar-3_r2xA a[href="https://support.discord.com"] {
  display: none;
}
#app-mount .search-39IXmY {
  border-radius: var(--rounded);
  overflow: hidden;
  margin: 0 0 0 8px;
  order: 1;
}
#app-mount .searchBar-jGtisZ {
  background: var(--textbox-bg);
  border: 1px solid var(--textbox-border);
  height: 30px;
  padding: 0;
  width: calc(var(--members-width) - 32px);
}
#app-mount .searchBar-jGtisZ .DraftEditor-root {
  padding-top: 4px;
}
#app-mount .searchBar-jGtisZ .public-DraftEditor-content,
#app-mount .searchBar-jGtisZ .public-DraftEditorPlaceholder-root {
  padding-left: 8px;
  padding-right: 8px;
}
#app-mount .searchBar-jGtisZ .icon-tZMHgY {
  height: 28px;
}
#app-mount .searchBar-jGtisZ::before {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 1px;
  background: var(--textbox-underline);
}
#app-mount .searchBar-jGtisZ:hover {
  background: var(--textbox-bg-hover);
}
#app-mount .searchBar-jGtisZ:focus-within {
  background: var(--bg-alt);
}
#app-mount .searchBar-jGtisZ:focus-within::before {
  height: 2px;
  background: rgb(var(--accent));
}

#app-mount svg:not([name=GamepadDisabled]) path[d="M14.99 11C14.99 12.66 13.66 14 12 14C10.34 14 9 12.66 9 11V5C9 3.34 10.34 2 12 2C13.66 2 15 3.34 15 5L14.99 11ZM12 16.1C14.76 16.1 17.3 14 17.3 11H19C19 14.42 16.28 17.24 13 17.72V21H11V17.72C7.72 17.23 5 14.41 5 11H6.7C6.7 14 9.24 16.1 12 16.1ZM12 4C11.2 4 11 4.66667 11 5V11C11 11.3333 11.2 12 12 12C12.8 12 13 11.3333 13 11V5C13 4.66667 12.8 4 12 4Z"] {
  display: none;
}
#app-mount svg:not([name=GamepadDisabled]) path[d="M14.99 11C14.99 12.66 13.66 14 12 14C10.34 14 9 12.66 9 11V5C9 3.34 10.34 2 12 2C13.66 2 15 3.34 15 5L14.99 11ZM12 16.1C14.76 16.1 17.3 14 17.3 11H19C19 14.42 16.28 17.24 13 17.72V22H11V17.72C7.72 17.23 5 14.41 5 11H6.7C6.7 14 9.24 16.1 12 16.1Z"] {
  d: path("M18.25 11a.75.75 0 0 1 .743.648l.007.102v.5a6.75 6.75 0 0 1-6.249 6.732l-.001 2.268a.75.75 0 0 1-1.493.102l-.007-.102v-2.268a6.75 6.75 0 0 1-6.246-6.496L5 12.25v-.5a.75.75 0 0 1 1.493-.102l.007.102v.5a5.25 5.25 0 0 0 5.034 5.246l.216.004h.5a5.25 5.25 0 0 0 5.246-5.034l.004-.216v-.5a.75.75 0 0 1 .75-.75ZM12 2a4 4 0 0 1 4 4v6a4 4 0 0 1-8 0V6a4 4 0 0 1 4-4Zm0 1.5A2.5 2.5 0 0 0 9.5 6v6a2.5 2.5 0 0 0 5 0V6A2.5 2.5 0 0 0 12 3.5Z");
}
#app-mount svg:not([name=GamepadDisabled]) path[d="M6.7 11H5C5 12.19 5.34 13.3 5.9 14.28L7.13 13.05C6.86 12.43 6.7 11.74 6.7 11Z"], #app-mount svg:not([name=GamepadDisabled]) path[d="M9.01 11.085C9.015 11.1125 9.02 11.14 9.02 11.17L15 5.18V5C15 3.34 13.66 2 12 2C10.34 2 9 3.34 9 5V11C9 11.03 9.005 11.0575 9.01 11.085Z"], #app-mount svg:not([name=GamepadDisabled]) path[d="M11.7237 16.0927L10.9632 16.8531L10.2533 17.5688C10.4978 17.633 10.747 17.6839 11 17.72V22H13V17.72C16.28 17.23 19 14.41 19 11H17.3C17.3 14 14.76 16.1 12 16.1C11.9076 16.1 11.8155 16.0975 11.7237 16.0927Z"] {
  display: none;
}
#app-mount svg:not([name=GamepadDisabled]) path[d="M21 4.27L19.73 3L3 19.73L4.27 21L8.46 16.82L9.69 15.58L11.35 13.92L14.99 10.28L21 4.27Z"] {
  d: path("M3.28 2.22a.75.75 0 1 0-1.06 1.06L8 9.06V12a4 4 0 0 0 6.248 3.309l1.146 1.146A5.227 5.227 0 0 1 12.25 17.5h-.5l-.216-.004A5.25 5.25 0 0 1 6.5 12.25v-.5l-.007-.102A.75.75 0 0 0 5 11.75v.5l.004.236a6.75 6.75 0 0 0 6.246 6.496v2.268l.007.102a.75.75 0 0 0 1.493-.102l.001-2.268a6.718 6.718 0 0 0 3.712-1.458l4.256 4.256a.75.75 0 0 0 1.061-1.06L3.28 2.22Zm9.876 11.997A2.5 2.5 0 0 1 9.5 12v-1.44l3.656 3.657ZM14.5 6v5.318l1.43 1.43c.046-.242.07-.492.07-.748V6a4 4 0 0 0-7.862-1.044L9.5 6.318V6a2.5 2.5 0 0 1 5 0ZM17.196 14.014l1.146 1.146A6.725 6.725 0 0 0 19 12.25v-.5l-.007-.102a.75.75 0 0 0-1.493.102v.5l-.004.216a5.233 5.233 0 0 1-.3 1.548Z");
}
#app-mount path[d="M12 2.00305C6.486 2.00305 2 6.48805 2 12.0031V20.0031C2 21.1071 2.895 22.0031 4 22.0031H6C7.104 22.0031 8 21.1071 8 20.0031V17.0031C8 15.8991 7.104 15.0031 6 15.0031H4V12.0031C4 7.59105 7.589 4.00305 12 4.00305C16.411 4.00305 20 7.59105 20 12.0031V15.0031H18C16.896 15.0031 16 15.8991 16 17.0031V20.0031C16 21.1071 16.896 22.0031 18 22.0031H20C21.104 22.0031 22 21.1071 22 20.0031V12.0031C22 6.48805 17.514 2.00305 12 2.00305Z"] {
  d: path("M15 4.25c0-1.079-1.274-1.65-2.08-.934L8.427 7.309a.75.75 0 0 1-.498.19H4.25A2.25 2.25 0 0 0 2 9.749v4.497a2.25 2.25 0 0 0 2.25 2.25h3.68a.75.75 0 0 1 .498.19l4.491 3.994c.806.716 2.081.144 2.081-.934V4.25ZM9.425 8.43 13.5 4.807v14.382l-4.075-3.624a2.25 2.25 0 0 0-1.495-.569H4.25a.75.75 0 0 1-.75-.75V9.75a.75.75 0 0 1 .75-.75h3.68a2.25 2.25 0 0 0 1.495-.569ZM18.992 5.897a.75.75 0 0 1 1.049.157A9.959 9.959 0 0 1 22 12a9.96 9.96 0 0 1-1.96 5.946.75.75 0 0 1-1.205-.892A8.459 8.459 0 0 0 20.5 12a8.459 8.459 0 0 0-1.665-5.054.75.75 0 0 1 .157-1.049Z");
}
#app-mount path[d="M6.16204 15.0065C6.10859 15.0022 6.05455 15 6 15H4V12C4 7.588 7.589 4 12 4C13.4809 4 14.8691 4.40439 16.0599 5.10859L17.5102 3.65835C15.9292 2.61064 14.0346 2 12 2C6.486 2 2 6.485 2 12V19.1685L6.16204 15.0065Z"], #app-mount path[d="M19.725 9.91686C19.9043 10.5813 20 11.2796 20 12V15H18C16.896 15 16 15.896 16 17V20C16 21.104 16.896 22 18 22H20C21.105 22 22 21.104 22 20V12C22 10.7075 21.7536 9.47149 21.3053 8.33658L19.725 9.91686Z"] {
  display: none;
}
#app-mount path[d="M3.20101 23.6243L1.7868 22.2101L21.5858 2.41113L23 3.82535L3.20101 23.6243Z"] {
  d: path("M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z");
}
#app-mount path[d="M19.738 10H22V14H19.739C19.498 14.931 19.1 15.798 18.565 16.564L20 18L18 20L16.565 18.564C15.797 19.099 14.932 19.498 14 19.738V22H10V19.738C9.069 19.498 8.203 19.099 7.436 18.564L6 20L4 18L5.436 16.564C4.901 15.799 4.502 14.932 4.262 14H2V10H4.262C4.502 9.068 4.9 8.202 5.436 7.436L4 6L6 4L7.436 5.436C8.202 4.9 9.068 4.502 10 4.262V2H14V4.261C14.932 4.502 15.797 4.9 16.565 5.435L18 3.999L20 5.999L18.564 7.436C19.099 8.202 19.498 9.069 19.738 10ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z"] {
  d: path("M12.012 2.25c.734.008 1.465.093 2.182.253a.75.75 0 0 1 .582.649l.17 1.527a1.384 1.384 0 0 0 1.927 1.116l1.401-.615a.75.75 0 0 1 .85.174 9.792 9.792 0 0 1 2.204 3.792.75.75 0 0 1-.271.825l-1.242.916a1.381 1.381 0 0 0 0 2.226l1.243.915a.75.75 0 0 1 .272.826 9.797 9.797 0 0 1-2.204 3.792.75.75 0 0 1-.848.175l-1.407-.617a1.38 1.38 0 0 0-1.926 1.114l-.169 1.526a.75.75 0 0 1-.572.647 9.518 9.518 0 0 1-4.406 0 .75.75 0 0 1-.572-.647l-.168-1.524a1.382 1.382 0 0 0-1.926-1.11l-1.406.616a.75.75 0 0 1-.849-.175 9.798 9.798 0 0 1-2.204-3.796.75.75 0 0 1 .272-.826l1.243-.916a1.38 1.38 0 0 0 0-2.226l-1.243-.914a.75.75 0 0 1-.271-.826 9.793 9.793 0 0 1 2.204-3.792.75.75 0 0 1 .85-.174l1.4.615a1.387 1.387 0 0 0 1.93-1.118l.17-1.526a.75.75 0 0 1 .583-.65c.717-.159 1.45-.243 2.201-.252Zm0 1.5a9.135 9.135 0 0 0-1.354.117l-.109.977A2.886 2.886 0 0 1 6.525 7.17l-.898-.394a8.293 8.293 0 0 0-1.348 2.317l.798.587a2.881 2.881 0 0 1 0 4.643l-.799.588c.32.842.776 1.626 1.348 2.322l.905-.397a2.882 2.882 0 0 1 4.017 2.318l.11.984c.889.15 1.798.15 2.687 0l.11-.984a2.881 2.881 0 0 1 4.018-2.322l.905.396a8.296 8.296 0 0 0 1.347-2.318l-.798-.588a2.881 2.881 0 0 1 0-4.643l.796-.587a8.293 8.293 0 0 0-1.348-2.317l-.896.393a2.884 2.884 0 0 1-4.023-2.324l-.11-.976a8.988 8.988 0 0 0-1.333-.117ZM12 8.25a3.75 3.75 0 1 1 0 7.5 3.75 3.75 0 0 1 0-7.5Zm0 1.5a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z");
}
#app-mount path[d="M21.1169 1.11603L22.8839 2.88403L19.7679 6.00003L22.8839 9.11603L21.1169 10.884L17.9999 7.76803L14.8839 10.884L13.1169 9.11603L16.2329 6.00003L13.1169 2.88403L14.8839 1.11603L17.9999 4.23203L21.1169 1.11603ZM18 22H13C6.925 22 2 17.075 2 11V6C2 5.447 2.448 5 3 5H7C7.553 5 8 5.447 8 6V10C8 10.553 7.553 11 7 11H6C6.063 14.938 9 18 13 18V17C13 16.447 13.447 16 14 16H18C18.553 16 19 16.447 19 17V21C19 21.553 18.553 22 18 22Z"] {
  d: path("m9.525 3.572.902 2.005a2.75 2.75 0 0 1-.633 3.14L8.3 10.11a.25.25 0 0 0-.078.155c-.044.397.225 1.17.845 2.244.451.782.86 1.33 1.207 1.638.242.214.375.26.432.244l2.01-.615a2.75 2.75 0 0 1 3.035 1.021l1.28 1.775a2.75 2.75 0 0 1-.339 3.606l-.886.84a3.75 3.75 0 0 1-3.587.889c-2.754-.77-5.223-3.093-7.435-6.924-2.215-3.837-2.992-7.141-2.276-9.913A3.75 3.75 0 0 1 4.85 2.487l.206-.07 1.167-.35a2.75 2.75 0 0 1 3.302 1.505Zm-2.869-.07-1.167.352-.158.054a2.25 2.25 0 0 0-1.37 1.537c-.603 2.332.086 5.26 2.122 8.788 2.033 3.522 4.222 5.582 6.54 6.229a2.25 2.25 0 0 0 2.151-.534l.887-.84a1.25 1.25 0 0 0 .154-1.638l-1.28-1.775a1.25 1.25 0 0 0-1.38-.464l-2.015.616c-1.17.349-2.232-.593-3.372-2.568C7 11.93 6.642 10.9 6.731 10.1c.047-.416.24-.801.546-1.086l1.494-1.394a1.25 1.25 0 0 0 .288-1.427l-.902-2.005a1.25 1.25 0 0 0-1.5-.685ZM21.78 2.22a.75.75 0 0 1 0 1.06L18.56 6.5l3.22 3.22a.75.75 0 1 1-1.06 1.06L17.5 7.56l-3.22 3.22a.75.75 0 1 1-1.06-1.06l3.22-3.22-3.22-3.22a.75.75 0 0 1 1.06-1.06l3.22 3.22 3.22-3.22a.75.75 0 0 1 1.06 0Z");
}
#app-mount path[d="M14 8.00598C14 10.211 12.206 12.006 10 12.006C7.795 12.006 6 10.211 6 8.00598C6 5.80098 7.794 4.00598 10 4.00598C12.206 4.00598 14 5.80098 14 8.00598ZM2 19.006C2 15.473 5.29 13.006 10 13.006C14.711 13.006 18 15.473 18 19.006V20.006H2V19.006Z"] {
  d: path("M4 13.999 13 14a2 2 0 0 1 1.995 1.85L15 16v1.5C14.999 21 11.284 22 8.5 22c-2.722 0-6.335-.956-6.495-4.27L2 17.5v-1.501c0-1.054.816-1.918 1.85-1.995L4 14ZM15.22 14H20c1.054 0 1.918.816 1.994 1.85L22 16v1c-.001 3.062-2.858 4-5 4a7.16 7.16 0 0 1-2.14-.322c.336-.386.607-.827.802-1.327A6.19 6.19 0 0 0 17 19.5l.267-.006c.985-.043 3.086-.363 3.226-2.289L20.5 17v-1a.501.501 0 0 0-.41-.492L20 15.5h-4.051a2.957 2.957 0 0 0-.595-1.34L15.22 14H20h-4.78ZM4 15.499l-.1.01a.51.51 0 0 0-.254.136.506.506 0 0 0-.136.253l-.01.101V17.5c0 1.009.45 1.722 1.417 2.242.826.445 2.003.714 3.266.753l.317.005.317-.005c1.263-.039 2.439-.308 3.266-.753.906-.488 1.359-1.145 1.412-2.057l.005-.186V16a.501.501 0 0 0-.41-.492L13 15.5l-9-.001ZM8.5 3a4.5 4.5 0 1 1 0 9 4.5 4.5 0 0 1 0-9Zm9 2a3.5 3.5 0 1 1 0 7 3.5 3.5 0 0 1 0-7Zm-9-.5c-1.654 0-3 1.346-3 3s1.346 3 3 3 3-1.346 3-3-1.346-3-3-3Zm9 2c-1.103 0-2 .897-2 2s.897 2 2 2 2-.897 2-2-.897-2-2-2Z");
}
#app-mount path[d="M14 8.00598C14 10.211 12.206 12.006 10 12.006C7.795 12.006 6 10.211 6 8.00598C6 5.80098 7.794 4.00598 10 4.00598C12.206 4.00598 14 5.80098 14 8.00598ZM2 19.006C2 15.473 5.29 13.006 10 13.006C14.711 13.006 18 15.473 18 19.006V20.006H2V19.006Z"] ~ path {
  display: none;
}
#app-mount path[d="M21 3H24V5H21V8H19V5H16V3H19V0H21V3ZM10 12C12.205 12 14 10.205 14 8C14 5.795 12.205 4 10 4C7.795 4 6 5.795 6 8C6 10.205 7.795 12 10 12ZM10 13C5.289 13 2 15.467 2 19V20H18V19C18 15.467 14.711 13 10 13Z"] {
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z");
}
#app-mount path[d="M22 12L12.101 2.10101L10.686 3.51401L12.101 4.92901L7.15096 9.87801V9.88001L5.73596 8.46501L4.32196 9.88001L8.56496 14.122L2.90796 19.778L4.32196 21.192L9.97896 15.536L14.222 19.778L15.636 18.364L14.222 16.95L19.171 12H19.172L20.586 13.414L22 12Z"] {
  d: path("m16.242 2.932 4.826 4.826a2.75 2.75 0 0 1-.715 4.404l-4.87 2.435a.75.75 0 0 0-.374.426l-1.44 4.166a1.25 1.25 0 0 1-2.065.476L8.5 16.561 4.06 21H3v-1.06l4.44-4.44-3.105-3.104a1.25 1.25 0 0 1 .476-2.066l4.166-1.44a.75.75 0 0 0 .426-.373l2.435-4.87a2.75 2.75 0 0 1 4.405-.715Zm3.766 5.886-4.826-4.826a1.25 1.25 0 0 0-2.002.325l-2.435 4.871a2.25 2.25 0 0 1-1.278 1.12l-3.789 1.31 6.705 6.704 1.308-3.789a2.25 2.25 0 0 1 1.12-1.277l4.872-2.436a1.25 1.25 0 0 0 .325-2.002Z");
}
#app-mount path[d="M18 9V14C18 15.657 19.344 17 21 17V18H3V17C4.656 17 6 15.657 6 14V9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9ZM11.9999 21C10.5239 21 9.24793 20.19 8.55493 19H15.4449C14.7519 20.19 13.4759 21 11.9999 21Z"] {
  d: path("M12 1.996a7.49 7.49 0 0 1 7.496 7.25l.004.25v4.097l1.38 3.156a1.25 1.25 0 0 1-1.145 1.75L15 18.502a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-4.155 3.352-7.5 7.5-7.5ZM13.5 18.5l-3 .002a1.5 1.5 0 0 0 2.993.145l.006-.147ZM12 3.496c-3.32 0-6 2.674-6 6v4.41L4.656 17h14.697L18 13.907V9.509l-.004-.225A5.988 5.988 0 0 0 12 3.496Z");
}
#app-mount path[d="M21.178 1.70703L22.592 3.12103L4.12103 21.593L2.70703 20.178L21.178 1.70703Z"] {
  d: path("m5.22 6.28-3-3a.75.75 0 0 1 1.06-1.06l18.5 18.5a.75.75 0 1 1-1.06 1.06l-3.28-3.28-2.44.001a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-1.152.258-2.242.72-3.216ZM15.94 17 6.364 7.425A6.019 6.019 0 0 0 6 9.496v4.41L4.656 17H15.94Zm-2.44 1.5-3 .001a1.5 1.5 0 0 0 2.993.145l.007-.147ZM18 13.907l.708 1.62 2.188 2.187a1.247 1.247 0 0 0-.016-.965l-1.38-3.156V9.496l-.004-.25A7.49 7.49 0 0 0 12 1.995a7.476 7.476 0 0 0-4.957 1.865l1.064 1.064A5.981 5.981 0 0 1 12 3.496a5.988 5.988 0 0 1 5.997 5.788l.003.225v4.398Z");
}
#app-mount path[d="M21.178 1.70703L22.592 3.12103L4.12103 21.593L2.70703 20.178L21.178 1.70703Z"] ~ path {
  display: none;
}
#app-mount path[d="M5.43309 21C5.35842 21 5.30189 20.9325 5.31494 20.859L5.99991 17H2.14274C2.06819 17 2.01168 16.9327 2.02453 16.8593L2.33253 15.0993C2.34258 15.0419 2.39244 15 2.45074 15H6.34991L7.40991 9H3.55274C3.47819 9 3.42168 8.93274 3.43453 8.85931L3.74253 7.09931C3.75258 7.04189 3.80244 7 3.86074 7H7.75991L8.45234 3.09903C8.46251 3.04174 8.51231 3 8.57049 3H10.3267C10.4014 3 10.4579 3.06746 10.4449 3.14097L9.75991 7H15.7599L16.4523 3.09903C16.4625 3.04174 16.5123 3 16.5705 3H18.3267C18.4014 3 18.4579 3.06746 18.4449 3.14097L17.7599 7H21.6171C21.6916 7 21.7481 7.06725 21.7353 7.14069L21.4273 8.90069C21.4172 8.95811 21.3674 9 21.3091 9H17.4099L17.0495 11.04H15.05L15.4104 9H9.41035L8.35035 15H10.5599V17H7.99991L7.30749 20.901C7.29732 20.9583 7.24752 21 7.18934 21H5.43309Z"] {
  d: path("M5.25 18A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3h13.5A3.25 3.25 0 0 1 22 6.25v8.5A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75Zm7.264-1.5h6.236a1.75 1.75 0 0 0 1.75-1.75v-8.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75Z");
}
#app-mount path[d="M5.43309 21C5.35842 21 5.30189 20.9325 5.31494 20.859L5.99991 17H2.14274C2.06819 17 2.01168 16.9327 2.02453 16.8593L2.33253 15.0993C2.34258 15.0419 2.39244 15 2.45074 15H6.34991L7.40991 9H3.55274C3.47819 9 3.42168 8.93274 3.43453 8.85931L3.74253 7.09931C3.75258 7.04189 3.80244 7 3.86074 7H7.75991L8.45234 3.09903C8.46251 3.04174 8.51231 3 8.57049 3H10.3267C10.4014 3 10.4579 3.06746 10.4449 3.14097L9.75991 7H15.7599L16.4523 3.09903C16.4625 3.04174 16.5123 3 16.5705 3H18.3267C18.4014 3 18.4579 3.06746 18.4449 3.14097L17.7599 7H21.6171C21.6916 7 21.7481 7.06725 21.7353 7.14069L21.4273 8.90069C21.4172 8.95811 21.3674 9 21.3091 9H17.4099L17.0495 11.04H15.05L15.4104 9H9.41035L8.35035 15H10.5599V17H7.99991L7.30749 20.901C7.29732 20.9583 7.24752 21 7.18934 21H5.43309Z"] + path {
  display: none;
}
#app-mount path[d="M19 3H4.99C3.88 3 3.01 3.89 3.01 5L3 19C3 20.1 3.88 21 4.99 21H19C20.1 21 21 20.1 21 19V5C21 3.89 20.1 3 19 3ZM19 15H15C15 16.66 13.65 18 12 18C10.35 18 9 16.66 9 15H4.99V5H19V15Z"] {
  d: path("M6.25 3h11.5a3.25 3.25 0 0 1 3.245 3.066L21 6.25v11.5a3.25 3.25 0 0 1-3.066 3.245L17.75 21H6.25a3.25 3.25 0 0 1-3.245-3.066L3 17.75V6.25a3.25 3.25 0 0 1 3.066-3.245L6.25 3h11.5-11.5ZM4.5 14.5v3.25a1.75 1.75 0 0 0 1.606 1.744l.144.006h11.5a1.75 1.75 0 0 0 1.744-1.607l.006-.143V14.5h-3.825a3.752 3.752 0 0 1-3.475 2.995l-.2.005a3.752 3.752 0 0 1-3.632-2.812l-.043-.188H4.5v3.25-3.25Zm13.25-10H6.25a1.75 1.75 0 0 0-1.744 1.606L4.5 6.25V13H9a.75.75 0 0 1 .743.648l.007.102a2.25 2.25 0 0 0 4.495.154l.005-.154a.75.75 0 0 1 .648-.743L15 13h4.5V6.25a1.75 1.75 0 0 0-1.607-1.744L17.75 4.5Z");
}
#app-mount path[d="M12 2C6.486 2 2 6.487 2 12C2 17.515 6.486 22 12 22C17.514 22 22 17.515 22 12C22 6.487 17.514 2 12 2ZM12 18.25C11.31 18.25 10.75 17.691 10.75 17C10.75 16.31 11.31 15.75 12 15.75C12.69 15.75 13.25 16.31 13.25 17C13.25 17.691 12.69 18.25 12 18.25ZM13 13.875V15H11V12H12C13.104 12 14 11.103 14 10C14 8.896 13.104 8 12 8C10.896 8 10 8.896 10 10H8C8 7.795 9.795 6 12 6C14.205 6 16 7.795 16 10C16 11.861 14.723 13.429 13 13.875Z"] {
  d: path("M12 2c5.523 0 10 4.478 10 10s-4.477 10-10 10S2 17.522 2 12 6.477 2 12 2Zm0 1.667c-4.595 0-8.333 3.738-8.333 8.333 0 4.595 3.738 8.333 8.333 8.333 4.595 0 8.333-3.738 8.333-8.333 0-4.595-3.738-8.333-8.333-8.333ZM12 15.5a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm0-8.75a2.75 2.75 0 0 1 2.75 2.75c0 1.01-.297 1.574-1.051 2.359l-.169.171c-.622.622-.78.886-.78 1.47a.75.75 0 0 1-1.5 0c0-1.01.297-1.574 1.051-2.359l.169-.171c.622-.622.78-.886.78-1.47a1.25 1.25 0 0 0-2.493-.128l-.007.128a.75.75 0 0 1-1.5 0A2.75 2.75 0 0 1 12 6.75Z");
}
#app-mount path[d="M21.526 8.149C21.231 7.966 20.862 7.951 20.553 8.105L18 9.382V7C18 5.897 17.103 5 16 5H4C2.897 5 2 5.897 2 7V17C2 18.104 2.897 19 4 19H16C17.103 19 18 18.104 18 17V14.618L20.553 15.894C20.694 15.965 20.847 16 21 16C21.183 16 21.365 15.949 21.526 15.851C21.82 15.668 22 15.347 22 15V9C22 8.653 21.82 8.332 21.526 8.149Z"] {
  d: path("M13.75 4.5A3.25 3.25 0 0 1 17 7.75v.173l3.864-2.318A.75.75 0 0 1 22 6.248V17.75a.75.75 0 0 1-1.136.643L17 16.075v.175a3.25 3.25 0 0 1-3.25 3.25h-8.5A3.25 3.25 0 0 1 2 16.25v-8.5A3.25 3.25 0 0 1 5.25 4.5h8.5Zm0 1.5h-8.5A1.75 1.75 0 0 0 3.5 7.75v8.5c0 .966.784 1.75 1.75 1.75h8.5a1.75 1.75 0 0 0 1.75-1.75v-8.5A1.75 1.75 0 0 0 13.75 6Zm6.75 1.573L17 9.674v4.651l3.5 2.1V7.573Z");
}
#app-mount path[d="M11 5V3C16.515 3 21 7.486 21 13H19C19 8.589 15.411 5 11 5ZM17 13H15C15 10.795 13.206 9 11 9V7C14.309 7 17 9.691 17 13ZM11 11V13H13C13 11.896 12.105 11 11 11ZM14 16H18C18.553 16 19 16.447 19 17V21C19 21.553 18.553 22 18 22H13C6.925 22 2 17.075 2 11V6C2 5.447 2.448 5 3 5H7C7.553 5 8 5.447 8 6V10C8 10.553 7.553 11 7 11H6C6.063 14.938 9 18 13 18V17C13 16.447 13.447 16 14 16Z"] {
  d: path("m7.056 2.418 1.167-.351a2.75 2.75 0 0 1 3.302 1.505l.902 2.006a2.75 2.75 0 0 1-.633 3.139L10.3 10.11a.25.25 0 0 0-.078.155c-.044.397.225 1.17.845 2.245.451.781.86 1.33 1.207 1.637.242.215.375.261.432.245l2.01-.615a2.75 2.75 0 0 1 3.034 1.02l1.281 1.776a2.75 2.75 0 0 1-.339 3.605l-.886.84a3.75 3.75 0 0 1-3.587.889c-2.754-.769-5.223-3.093-7.435-6.924-2.215-3.836-2.992-7.14-2.276-9.913a3.75 3.75 0 0 1 2.548-2.652Zm.433 1.437a2.25 2.25 0 0 0-1.529 1.59c-.602 2.332.087 5.261 2.123 8.788 2.033 3.522 4.222 5.582 6.54 6.23a2.25 2.25 0 0 0 2.151-.534l.887-.84a1.25 1.25 0 0 0 .154-1.639l-1.28-1.775a1.25 1.25 0 0 0-1.38-.464l-2.015.617c-1.17.348-2.232-.593-3.372-2.568C9 11.93 8.642 10.9 8.731 10.099c.047-.416.24-.8.546-1.086l1.494-1.393a1.25 1.25 0 0 0 .288-1.427l-.902-2.006a1.25 1.25 0 0 0-1.5-.684l-1.168.352Z");
}

#app-mount [class*=tabBar-] {
  display: flex;
  height: auto;
  gap: 0;
}
#app-mount [class*=tabBar-] [class*=item-],
#app-mount [class*=tabBar-] [class*=tabBarItem-] {
  margin: 0;
  border: none;
  padding: 10px 12px;
  height: auto;
  border-radius: var(--btn-radius);
  cursor: var(--cursor);
  background: transparent !important;
  color: var(--text-secondary) !important;
  text-transform: none;
  font-weight: var(--font-weight-normal);
}
#app-mount [class*=tabBar-] [class*=item-]::before,
#app-mount [class*=tabBar-] [class*=tabBarItem-]::before {
  content: "";
  height: 2px;
  width: 0%;
  display: block;
  opacity: 0;
  border-radius: 30px;
  background: rgb(var(--accent));
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  transition: opacity 0.15s var(--transition), width 0.15s var(--transition);
}
#app-mount [class*=tabBar-] [class*=item-]:hover,
#app-mount [class*=tabBar-] [class*=tabBarItem-]:hover {
  color: var(--text-primary) !important;
}
#app-mount [class*=tabBar-] [class*=item-][aria-selected=true],
#app-mount [class*=tabBar-] [class*=tabBarItem-][aria-selected=true] {
  color: var(--text-primary) !important;
}
#app-mount [class*=tabBar-] [class*=item-][aria-selected=true]::before,
#app-mount [class*=tabBar-] [class*=tabBarItem-][aria-selected=true]::before {
  width: 40%;
  opacity: 1;
}

#app-mount .guilds-2JjMmN {
  width: var(--server-container);
  background: transparent;
}
#app-mount .guilds-2JjMmN.hidden-10MsGQ {
  display: none;
}
#app-mount .guilds-2JjMmN.hidden-10MsGQ + .base-2jDfDU {
  border: none;
}
#app-mount .guilds-2JjMmN > ul[role=tree] {
  margin-bottom: var(--server-container);
}
#app-mount .scroller-3X7KbA {
  background: var(--bg-main);
  padding-top: 0;
}
#app-mount .scroller-3X7KbA .tutorialContainer-1pL9QS + div:not([class]) {
  height: var(--server-size) !important;
  margin-bottom: 4px;
}

#app-mount .guilds-2JjMmN [class*=pill] {
  width: 4px;
  margin-left: 0;
  left: calc(var(--server-container) / 2 - var(--server-size) / 2);
  z-index: 1;
  height: var(--server-size);
}
#app-mount .guilds-2JjMmN [class*=pill] span {
  height: var(--pill-height) !important;
  width: 100% !important;
  transform: scale(0, 1) !important;
  transition: 0.15s var(--transition) !important;
  margin-left: 0;
  border-radius: var(--rounded-high);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 0"] {
  transform: scale(1, 0.5) !important;
  background: var(--pill-unread);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 1"] {
  transform: scale(1, 0.5) !important;
  background: var(--pill-unread);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 2"] {
  transform: scale(1, 0.5) !important;
  background: var(--pill-unread);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 3"] {
  transform: scale(1, 0.5) !important;
  background: var(--pill-unread);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 4"] {
  transform: scale(1, 0.5) !important;
  background: var(--pill-unread);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 5"] {
  transform: scale(1, 0.5) !important;
  background: var(--pill-unread);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 6"] {
  transform: scale(1, 0.5) !important;
  background: var(--pill-unread);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 7"] {
  transform: scale(1, 0.5) !important;
  background: var(--pill-unread);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 8"] {
  transform: scale(1, 0.5) !important;
  background: var(--pill-unread);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 9"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 10"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 11"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 12"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 13"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 14"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 15"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 16"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 17"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 18"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 19"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 20"] {
  transform: scale(1, 0.7) !important;
  background: var(--pill-hovered);
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 21"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 22"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 23"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 24"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 25"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 26"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 27"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 28"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 29"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 30"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 31"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 32"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 33"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 34"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 35"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 36"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 37"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 38"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 39"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .guilds-2JjMmN [class*=pill] span[style*="height: 40"] {
  transform: scale(1, 1) !important;
  background: rgb(var(--accent));
}
#app-mount .listItem-3SmSlK {
  margin: 0 0 4px;
  width: var(--server-container);
  position: relative;
}
#app-mount .listItem-3SmSlK foreignObject {
  -webkit-mask: none;
          mask: none;
  border-radius: var(--rounded);
  box-sizing: border-box;
}
#app-mount .wrapper-28eC3z {
  border-radius: var(--rounded);
  cursor: var(--cursor);
  width: var(--server-size);
  height: var(--server-size);
}
#app-mount .wrapper-2PSQCG {
  cursor: var(--cursor);
}
#app-mount .wrapper-3kah-n {
  position: relative;
  transition: box-shadow 0.15s var(--transition);
}
#app-mount .wrapper-3kah-n:hover, #app-mount .wrapper-3kah-n.selected-1Drb7Z {
  box-shadow: var(--server-hover-selected);
}
#app-mount .svg-2zuE5p {
  border-radius: 50%;
  box-sizing: border-box;
  width: var(--server-size);
  height: var(--server-size);
}
#app-mount .svg-2zuE5p foreignObject {
  width: 100%;
  height: 100%;
}
#app-mount .icon-3AqZ2e,
#app-mount .childWrapper-1j_1ub {
  width: var(--server-icon-size);
  height: var(--server-icon-size);
  border-radius: var(--server-icon-shape);
  position: relative;
  z-index: 2;
}
#app-mount .homeIcon-r0w4ny {
  width: 75%;
  height: 75%;
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M10.55 2.533a2.25 2.25 0 0 1 2.9 0l6.75 5.695c.508.427.8 1.056.8 1.72v9.802a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75v-5a.75.75 0 0 0-.75-.75h-3.5a.75.75 0 0 0-.75.75v5a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 3 19.75V9.947c0-.663.292-1.292.8-1.72l6.75-5.694Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M10.55 2.533a2.25 2.25 0 0 1 2.9 0l6.75 5.695c.508.427.8 1.056.8 1.72v9.802a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75v-5a.75.75 0 0 0-.75-.75h-3.5a.75.75 0 0 0-.75.75v5a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 3 19.75V9.947c0-.663.292-1.292.8-1.72l6.75-5.694Z" /></svg>') center/cover;
  background: var(--interactive-normal);
}
#app-mount .homeIcon-r0w4ny path {
  display: none;
}
#app-mount .childWrapper-1j_1ub {
  background: transparent;
  font-weight: var(--font-weight-semibold);
}
#app-mount .wrapper-3kah-n.selected-1Drb7Z .childWrapper-1j_1ub {
  background: transparent;
  color: var(--text-primary);
}
#app-mount .circleIconButton-1VxDrg {
  background: transparent;
}
#app-mount .circleIconButton-1VxDrg.selected-2r1Hvo {
  background: transparent;
}
#app-mount .blobContainer-ikKyFs:active {
  transform: none;
}

#app-mount .wrapper-38slSD {
  width: 100%;
}
#app-mount .closedFolderIconWrapper-3tRb2d {
  padding: 6px;
  position: relative;
  z-index: 1;
}
#app-mount .folderIconWrapper-1oRIZr {
  border-radius: var(--rounded);
  transition: box-shadow 0.15s var(--transition);
}
#app-mount .folderIconWrapper-1oRIZr[style^=background-color] {
  background: var(--folder-bg) !important;
}
#app-mount .folderIconWrapper-1oRIZr[style^=background-color]:hover {
  box-shadow: var(--server-hover-selected);
}
#app-mount .expandedFolderBackground-1kSAf6 {
  border-radius: var(--rounded);
  height: 100%;
  width: var(--server-size);
  left: 50%;
  transform: translateX(-50%);
}
#app-mount .expandedFolderBackground-1kSAf6:not(.collapsed-uGXEbi) {
  background: var(--server-bg);
}
#app-mount .folder-241Joy {
  background: transparent;
  cursor: var(--cursor);
}
#app-mount .guildIcon-2I5sfu {
  border-radius: var(--server-folder-icon-shape);
  width: calc(var(--server-icon-size) / 1.8);
  height: calc(var(--server-icon-size) / 1.8);
}
#app-mount [id^=folder-items][role=group] {
  height: auto !important;
}

#app-mount .sidebar-1tnWFu {
  width: var(--channels-width);
  background: var(--bg-alt);
  border-right: 1px solid var(--border-mid);
  box-sizing: border-box;
  border-radius: var(--rounded) 0 0 0;
  overflow: visible;
}
#app-mount .sidebar-1tnWFu .scroller-1ox3I2 {
  padding: 8px !important;
}
#app-mount .sidebar-1tnWFu .scroller-1ox3I2::-webkit-scrollbar {
  display: none;
}
#app-mount .sidebar-1tnWFu .scroller-1ox3I2 > ul > li:first-of-type {
  padding-top: 0;
}
#app-mount .sidebar-1tnWFu.hidden-38rxp9 {
  display: none;
}
#app-mount .content-yjf30S > li:last-child {
  padding-bottom: calc(var(--bottombar-height) + 32px);
}
#app-mount .container-1NXEtd {
  background: var(--bg-alt);
}

#app-mount .wrapper-NhbLHG {
  padding: 2px 0;
}
#app-mount .wrapper-NhbLHG:hover .content-1gYQeQ {
  background: var(--bg-interactive-high);
}
#app-mount .wrapper-NhbLHG:hover .content-1gYQeQ .icon-2W8DHg {
  color: var(--interactive-normal);
}
#app-mount .wrapper-NhbLHG.modeUnread-3Cxepe::before {
  height: 10px;
  background: var(--pill-unread);
  opacity: 1;
}
#app-mount .wrapper-NhbLHG.modeSelected-3DmyhH::before {
  height: var(--pill-height);
  background: rgb(var(--accent));
  opacity: 1;
}
#app-mount .wrapper-NhbLHG.modeSelected-3DmyhH .content-1gYQeQ {
  background: var(--bg-interactive-high);
}
#app-mount .wrapper-NhbLHG.modeSelected-3DmyhH .content-1gYQeQ .icon-2W8DHg {
  color: var(--interactive-active);
}
#app-mount .wrapper-NhbLHG.modeSelected-3DmyhH:hover .content-1gYQeQ {
  background: var(--bg-interactive-high-hover);
}
#app-mount .wrapper-NhbLHG::before {
  content: "";
  position: absolute;
  top: 50%;
  left: 0;
  border-radius: 50px;
  height: 0;
  opacity: 1;
  width: var(--pill-width);
  transform: translateY(-50%);
  transition: var(--pill-transition);
  z-index: 1;
}
#app-mount .content-1gYQeQ {
  border-radius: var(--rounded);
  margin-left: 0;
  margin-right: 0;
  padding: 0 8px 0 16px;
}
#app-mount .content-1gYQeQ .iconItem-1EjiK0:not(.cursorPointer-B3uwDA) svg {
  background: var(--interactive-normal);
}
#app-mount .content-1gYQeQ .iconItem-1EjiK0:not(.cursorPointer-B3uwDA):first-child svg {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>') center/cover;
}
#app-mount .content-1gYQeQ .iconItem-1EjiK0:not(.cursorPointer-B3uwDA) + .iconItem-1EjiK0 svg {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.012 2.25c.734.008 1.465.093 2.182.253a.75.75 0 0 1 .582.649l.17 1.527a1.384 1.384 0 0 0 1.927 1.116l1.401-.615a.75.75 0 0 1 .85.174 9.792 9.792 0 0 1 2.204 3.792.75.75 0 0 1-.271.825l-1.242.916a1.381 1.381 0 0 0 0 2.226l1.243.915a.75.75 0 0 1 .272.826 9.797 9.797 0 0 1-2.204 3.792.75.75 0 0 1-.848.175l-1.407-.617a1.38 1.38 0 0 0-1.926 1.114l-.169 1.526a.75.75 0 0 1-.572.647 9.518 9.518 0 0 1-4.406 0 .75.75 0 0 1-.572-.647l-.168-1.524a1.382 1.382 0 0 0-1.926-1.11l-1.406.616a.75.75 0 0 1-.849-.175 9.798 9.798 0 0 1-2.204-3.796.75.75 0 0 1 .272-.826l1.243-.916a1.38 1.38 0 0 0 0-2.226l-1.243-.914a.75.75 0 0 1-.271-.826 9.793 9.793 0 0 1 2.204-3.792.75.75 0 0 1 .85-.174l1.4.615a1.387 1.387 0 0 0 1.93-1.118l.17-1.526a.75.75 0 0 1 .583-.65c.717-.159 1.45-.243 2.201-.252Zm0 1.5a9.135 9.135 0 0 0-1.354.117l-.109.977A2.886 2.886 0 0 1 6.525 7.17l-.898-.394a8.293 8.293 0 0 0-1.348 2.317l.798.587a2.881 2.881 0 0 1 0 4.643l-.799.588c.32.842.776 1.626 1.348 2.322l.905-.397a2.882 2.882 0 0 1 4.017 2.318l.11.984c.889.15 1.798.15 2.687 0l.11-.984a2.881 2.881 0 0 1 4.018-2.322l.905.396a8.296 8.296 0 0 0 1.347-2.318l-.798-.588a2.881 2.881 0 0 1 0-4.643l.796-.587a8.293 8.293 0 0 0-1.348-2.317l-.896.393a2.884 2.884 0 0 1-4.023-2.324l-.11-.976a8.988 8.988 0 0 0-1.333-.117ZM12 8.25a3.75 3.75 0 1 1 0 7.5 3.75 3.75 0 0 1 0-7.5Zm0 1.5a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.012 2.25c.734.008 1.465.093 2.182.253a.75.75 0 0 1 .582.649l.17 1.527a1.384 1.384 0 0 0 1.927 1.116l1.401-.615a.75.75 0 0 1 .85.174 9.792 9.792 0 0 1 2.204 3.792.75.75 0 0 1-.271.825l-1.242.916a1.381 1.381 0 0 0 0 2.226l1.243.915a.75.75 0 0 1 .272.826 9.797 9.797 0 0 1-2.204 3.792.75.75 0 0 1-.848.175l-1.407-.617a1.38 1.38 0 0 0-1.926 1.114l-.169 1.526a.75.75 0 0 1-.572.647 9.518 9.518 0 0 1-4.406 0 .75.75 0 0 1-.572-.647l-.168-1.524a1.382 1.382 0 0 0-1.926-1.11l-1.406.616a.75.75 0 0 1-.849-.175 9.798 9.798 0 0 1-2.204-3.796.75.75 0 0 1 .272-.826l1.243-.916a1.38 1.38 0 0 0 0-2.226l-1.243-.914a.75.75 0 0 1-.271-.826 9.793 9.793 0 0 1 2.204-3.792.75.75 0 0 1 .85-.174l1.4.615a1.387 1.387 0 0 0 1.93-1.118l.17-1.526a.75.75 0 0 1 .583-.65c.717-.159 1.45-.243 2.201-.252Zm0 1.5a9.135 9.135 0 0 0-1.354.117l-.109.977A2.886 2.886 0 0 1 6.525 7.17l-.898-.394a8.293 8.293 0 0 0-1.348 2.317l.798.587a2.881 2.881 0 0 1 0 4.643l-.799.588c.32.842.776 1.626 1.348 2.322l.905-.397a2.882 2.882 0 0 1 4.017 2.318l.11.984c.889.15 1.798.15 2.687 0l.11-.984a2.881 2.881 0 0 1 4.018-2.322l.905.396a8.296 8.296 0 0 0 1.347-2.318l-.798-.588a2.881 2.881 0 0 1 0-4.643l.796-.587a8.293 8.293 0 0 0-1.348-2.317l-.896.393a2.884 2.884 0 0 1-4.023-2.324l-.11-.976a8.988 8.988 0 0 0-1.333-.117ZM12 8.25a3.75 3.75 0 1 1 0 7.5 3.75 3.75 0 0 1 0-7.5Zm0 1.5a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z" /></svg>') center/cover;
}
#app-mount .content-1gYQeQ .iconItem-1EjiK0:not(.cursorPointer-B3uwDA).openChatIconItem-2kj5qO svg {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.068-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2Zm0 1.5A8.5 8.5 0 0 0 3.5 12c0 1.47.373 2.883 1.073 4.137l.15.27-1.112 3.984 3.987-1.112.27.15A8.5 8.5 0 1 0 12 3.5ZM8.75 13h4.498a.75.75 0 0 1 .102 1.493l-.102.007H8.75a.75.75 0 0 1-.102-1.493L8.75 13h4.498H8.75Zm0-3.5h6.505a.75.75 0 0 1 .101 1.493l-.101.007H8.75a.75.75 0 0 1-.102-1.493L8.75 9.5h6.505H8.75Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.068-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2Zm0 1.5A8.5 8.5 0 0 0 3.5 12c0 1.47.373 2.883 1.073 4.137l.15.27-1.112 3.984 3.987-1.112.27.15A8.5 8.5 0 1 0 12 3.5ZM8.75 13h4.498a.75.75 0 0 1 .102 1.493l-.102.007H8.75a.75.75 0 0 1-.102-1.493L8.75 13h4.498H8.75Zm0-3.5h6.505a.75.75 0 0 1 .101 1.493l-.101.007H8.75a.75.75 0 0 1-.102-1.493L8.75 9.5h6.505H8.75Z" /></svg>') center/cover;
}
#app-mount .content-1gYQeQ .iconItem-1EjiK0:not(.cursorPointer-B3uwDA).openChatIconItem-2kj5qO + .iconItem-1EjiK0 svg {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>') center/cover;
}
#app-mount .name-28HaxV {
  font-weight: var(--font-weight-normal);
}
#app-mount .mainContent-20q_Hp {
  padding: var(--channel-padding) 0;
  cursor: var(--cursor);
}
#app-mount .unread-36eUEm {
  display: none;
  border-radius: 50px;
  left: 0;
  width: 4px;
  height: 10px;
  margin-top: 0;
  transform: translateY(-50%);
  background: var(--pill-unread);
  z-index: 1;
}
#app-mount .wrapper-NhbLHG.modeConnected-NrO4cP .icon-2W8DHg {
  color: var(--text-primary) !important;
}
#app-mount .container-1Bj0eq {
  margin-left: 28px;
}
#app-mount .spine-29OFwR, #app-mount .spineBorder-1-F4s1 {
  display: none;
}
#app-mount path[d="M11.383 3.07904C11.009 2.92504 10.579 3.01004 10.293 3.29604L6 8.00204H3C2.45 8.00204 2 8.45304 2 9.00204V15.002C2 15.552 2.45 16.002 3 16.002H6L10.293 20.71C10.579 20.996 11.009 21.082 11.383 20.927C11.757 20.772 12 20.407 12 20.002V4.00204C12 3.59904 11.757 3.23204 11.383 3.07904ZM14 5.00195V7.00195C16.757 7.00195 19 9.24595 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 8.14295 17.86 5.00195 14 5.00195ZM14 9.00195C15.654 9.00195 17 10.349 17 12.002C17 13.657 15.654 15.002 14 15.002V13.002C14.551 13.002 15 12.553 15 12.002C15 11.451 14.551 11.002 14 11.002V9.00195Z"] {
  d: path("M15 4.25c0-1.079-1.274-1.65-2.08-.934L8.427 7.309a.75.75 0 0 1-.498.19H4.25A2.25 2.25 0 0 0 2 9.749v4.497a2.25 2.25 0 0 0 2.25 2.25h3.68a.75.75 0 0 1 .498.19l4.491 3.994c.806.716 2.081.144 2.081-.934V4.25ZM9.425 8.43 13.5 4.807v14.382l-4.075-3.624a2.25 2.25 0 0 0-1.495-.569H4.25a.75.75 0 0 1-.75-.75V9.75a.75.75 0 0 1 .75-.75h3.68a2.25 2.25 0 0 0 1.495-.569ZM18.992 5.897a.75.75 0 0 1 1.049.157A9.959 9.959 0 0 1 22 12a9.96 9.96 0 0 1-1.96 5.946.75.75 0 0 1-1.205-.892A8.459 8.459 0 0 0 20.5 12a8.459 8.459 0 0 0-1.665-5.054.75.75 0 0 1 .157-1.049Z");
}
#app-mount path[d="M15 12C15 12.0007 15 12.0013 15 12.002C15 12.553 14.551 13.002 14 13.002V15.002C15.654 15.002 17 13.657 17 12.002C17 12.0013 17 12.0007 17 12H15ZM19 12C19 12.0007 19 12.0013 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 12.0013 21 12.0007 21 12H19ZM10.293 3.29604C10.579 3.01004 11.009 2.92504 11.383 3.07904C11.757 3.23204 12 3.59904 12 4.00204V20.002C12 20.407 11.757 20.772 11.383 20.927C11.009 21.082 10.579 20.996 10.293 20.71L6 16.002H3C2.45 16.002 2 15.552 2 15.002V9.00204C2 8.45304 2.45 8.00204 3 8.00204H6L10.293 3.29604Z"] {
  d: path("M15 4.25c0-1.079-1.274-1.65-2.08-.934L8.427 7.309a.75.75 0 0 1-.498.19H4.25A2.25 2.25 0 0 0 2 9.749v4.497a2.25 2.25 0 0 0 2.25 2.25h3.68a.75.75 0 0 1 .498.19l4.491 3.994c.806.716 2.081.144 2.081-.934V4.25ZM9.425 8.43 13.5 4.807v14.382l-4.075-3.624a2.25 2.25 0 0 0-1.495-.569H4.25a.75.75 0 0 1-.75-.75V9.75a.75.75 0 0 1 .75-.75h3.68a2.25 2.25 0 0 0 1.495-.569ZM18.992 5.897a.75.75 0 0 1 1.049.157A9.959 9.959 0 0 1 22 12a9.96 9.96 0 0 1-1.96 5.946.75.75 0 0 1-1.205-.892A8.459 8.459 0 0 0 20.5 12a8.459 8.459 0 0 0-1.665-5.054.75.75 0 0 1 .157-1.049Z");
}
#app-mount path[d="M5.88657 21C5.57547 21 5.3399 20.7189 5.39427 20.4126L6.00001 17H2.59511C2.28449 17 2.04905 16.7198 2.10259 16.4138L2.27759 15.4138C2.31946 15.1746 2.52722 15 2.77011 15H6.35001L7.41001 9H4.00511C3.69449 9 3.45905 8.71977 3.51259 8.41381L3.68759 7.41381C3.72946 7.17456 3.93722 7 4.18011 7H7.76001L8.39677 3.41262C8.43914 3.17391 8.64664 3 8.88907 3H9.87344C10.1845 3 10.4201 3.28107 10.3657 3.58738L9.76001 7H15.76L16.3968 3.41262C16.4391 3.17391 16.6466 3 16.8891 3H17.8734C18.1845 3 18.4201 3.28107 18.3657 3.58738L17.76 7H21.1649C21.4755 7 21.711 7.28023 21.6574 7.58619L21.4824 8.58619C21.4406 8.82544 21.2328 9 20.9899 9H17.41L16.35 15H19.7549C20.0655 15 20.301 15.2802 20.2474 15.5862L20.0724 16.5862C20.0306 16.8254 19.8228 17 19.5799 17H16L15.3632 20.5874C15.3209 20.8261 15.1134 21 14.8709 21H13.8866C13.5755 21 13.3399 20.7189 13.3943 20.4126L14 17H8.00001L7.36325 20.5874C7.32088 20.8261 7.11337 21 6.87094 21H5.88657ZM9.41045 9L8.35045 15H14.3504L15.4104 9H9.41045Z"] {
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.068-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2Zm0 1.5A8.5 8.5 0 0 0 3.5 12c0 1.47.373 2.883 1.073 4.137l.15.27-1.112 3.984 3.987-1.112.27.15A8.5 8.5 0 1 0 12 3.5ZM8.75 13h4.498a.75.75 0 0 1 .102 1.493l-.102.007H8.75a.75.75 0 0 1-.102-1.493L8.75 13h4.498H8.75Zm0-3.5h6.505a.75.75 0 0 1 .101 1.493l-.101.007H8.75a.75.75 0 0 1-.102-1.493L8.75 9.5h6.505H8.75Z");
}
#app-mount path[d="M14 8C14 7.44772 13.5523 7 13 7H9.76001L10.3657 3.58738C10.4201 3.28107 10.1845 3 9.87344 3H8.88907C8.64664 3 8.43914 3.17391 8.39677 3.41262L7.76001 7H4.18011C3.93722 7 3.72946 7.17456 3.68759 7.41381L3.51259 8.41381C3.45905 8.71977 3.69449 9 4.00511 9H7.41001L6.35001 15H2.77011C2.52722 15 2.31946 15.1746 2.27759 15.4138L2.10259 16.4138C2.04905 16.7198 2.28449 17 2.59511 17H6.00001L5.39427 20.4126C5.3399 20.7189 5.57547 21 5.88657 21H6.87094C7.11337 21 7.32088 20.8261 7.36325 20.5874L8.00001 17H14L13.3943 20.4126C13.3399 20.7189 13.5755 21 13.8866 21H14.8709C15.1134 21 15.3209 20.8261 15.3632 20.5874L16 17H19.5799C19.8228 17 20.0306 16.8254 20.0724 16.5862L20.2474 15.5862C20.301 15.2802 20.0655 15 19.7549 15H16.35L16.6758 13.1558C16.7823 12.5529 16.3186 12 15.7063 12C15.2286 12 14.8199 12.3429 14.7368 12.8133L14.3504 15H8.35045L9.41045 9H13C13.5523 9 14 8.55228 14 8Z"] {
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.068-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2Zm0 1.5A8.5 8.5 0 0 0 3.5 12c0 1.47.373 2.883 1.073 4.137l.15.27-1.112 3.984 3.987-1.112.27.15A8.5 8.5 0 1 0 12 3.5ZM8.75 13h4.498a.75.75 0 0 1 .102 1.493l-.102.007H8.75a.75.75 0 0 1-.102-1.493L8.75 13h4.498H8.75Zm0-3.5h6.505a.75.75 0 0 1 .101 1.493l-.101.007H8.75a.75.75 0 0 1-.102-1.493L8.75 9.5h6.505H8.75Z");
}
#app-mount path[d="M14 8C14 7.44772 13.5523 7 13 7H9.76001L10.3657 3.58738C10.4201 3.28107 10.1845 3 9.87344 3H8.88907C8.64664 3 8.43914 3.17391 8.39677 3.41262L7.76001 7H4.18011C3.93722 7 3.72946 7.17456 3.68759 7.41381L3.51259 8.41381C3.45905 8.71977 3.69449 9 4.00511 9H7.41001L6.35001 15H2.77011C2.52722 15 2.31946 15.1746 2.27759 15.4138L2.10259 16.4138C2.04905 16.7198 2.28449 17 2.59511 17H6.00001L5.39427 20.4126C5.3399 20.7189 5.57547 21 5.88657 21H6.87094C7.11337 21 7.32088 20.8261 7.36325 20.5874L8.00001 17H14L13.3943 20.4126C13.3399 20.7189 13.5755 21 13.8866 21H14.8709C15.1134 21 15.3209 20.8261 15.3632 20.5874L16 17H19.5799C19.8228 17 20.0306 16.8254 20.0724 16.5862L20.2474 15.5862C20.301 15.2802 20.0655 15 19.7549 15H16.35L16.6758 13.1558C16.7823 12.5529 16.3186 12 15.7063 12C15.2286 12 14.8199 12.3429 14.7368 12.8133L14.3504 15H8.35045L9.41045 9H13C13.5523 9 14 8.55228 14 8Z"] + path {
  transform: translate(2px, -2px);
}
#app-mount path[d="M3.9 8.26H2V15.2941H3.9V8.26Z"] {
  display: none;
}
#app-mount path[d="M19.1 4V5.12659L4.85 8.26447V18.1176C4.85 18.5496 5.1464 18.9252 5.5701 19.0315L9.3701 19.9727C9.4461 19.9906 9.524 20 9.6 20C9.89545 20 10.1776 19.8635 10.36 19.6235L12.7065 16.5242L19.1 17.9304V19.0588H21V4H19.1ZM9.2181 17.9944L6.75 17.3826V15.2113L10.6706 16.0753L9.2181 17.9944Z"] {
  d: path("M21.907 5.622c.062.208.093.424.093.641V17.74a2.25 2.25 0 0 1-2.891 2.156l-5.514-1.64a4.002 4.002 0 0 1-7.59-1.556L6 16.5l-.001-.5-2.39-.711A2.25 2.25 0 0 1 2 13.131V10.87a2.25 2.25 0 0 1 1.61-2.156l15.5-4.606a2.25 2.25 0 0 1 2.797 1.515ZM7.499 16.445l.001.054a2.5 2.5 0 0 0 4.624 1.321l-4.625-1.375Zm12.037-10.9-15.5 4.605a.75.75 0 0 0-.536.72v2.261a.75.75 0 0 0 .536.72l15.5 4.607a.75.75 0 0 0 .964-.72V6.264a.75.75 0 0 0-.964-.719Z");
}
#app-mount path[d="M33 34.5833V7.49998H35V36.6666H9C6.791 36.6666 5 34.801 5 32.5V7.49998C5 5.19894 6.791 3.33331 9 3.33331H31V30.4166H9C7.8955 30.4166 7 31.3485 7 32.5C7 33.6515 7.8955 34.5833 9 34.5833H33ZM23.9718 9.99998L15.8889 17.9915L12.7086 14.8441L10 17.5058L15.8885 23.3333L26.6667 12.6669L23.9718 9.99998Z"] {
  d: path("M12 2.002a3.875 3.875 0 0 0-3.875 3.875c0 2.92 1.207 6.552 1.813 8.199a2.187 2.187 0 0 0 2.064 1.423c.904 0 1.739-.542 2.063-1.418.606-1.64 1.81-5.254 1.81-8.204A3.875 3.875 0 0 0 12 2.002ZM9.625 5.877a2.375 2.375 0 0 1 4.75 0c0 2.655-1.111 6.043-1.717 7.684a.686.686 0 0 1-.655.438.687.687 0 0 1-.657-.44c-.607-1.652-1.721-5.058-1.721-7.682ZM12.001 17.001a2.501 2.501 0 1 0 0 5.002 2.501 2.501 0 0 0 0-5.002ZM11 19.502a1.001 1.001 0 1 1 2.002 0 1.001 1.001 0 0 1-2.002 0Z");
  transform: scale(1.667);
}
#app-mount path[d="M15.44 6.99992C15.5725 6.99992 15.68 7.10737 15.68 7.23992V8.75992C15.68 8.89247 15.5725 8.99992 15.44 8.99992H9.41045L8.35045 14.9999H10.56V16.9999H8.00001L7.36325 20.5873C7.32088 20.826 7.11337 20.9999 6.87094 20.9999H5.88657C5.57547 20.9999 5.3399 20.7189 5.39427 20.4125L6.00001 16.9999H2.59511C2.28449 16.9999 2.04905 16.7197 2.10259 16.4137L2.27759 15.4137C2.31946 15.1745 2.52722 14.9999 2.77011 14.9999H6.35001L7.41001 8.99992H4.00511C3.69449 8.99992 3.45905 8.71969 3.51259 8.41373L3.68759 7.41373C3.72946 7.17448 3.93722 6.99992 4.18011 6.99992H7.76001L8.39677 3.41254C8.43914 3.17384 8.64664 2.99992 8.88907 2.99992H9.87344C10.1845 2.99992 10.4201 3.28099 10.3657 3.58731L9.76001 6.99992H15.44Z"] {
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.068-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2Zm0 1.5A8.5 8.5 0 0 0 3.5 12c0 1.47.373 2.883 1.073 4.137l.15.27-1.112 3.984 3.987-1.112.27.15A8.5 8.5 0 1 0 12 3.5ZM8.75 13h4.498a.75.75 0 0 1 .102 1.493l-.102.007H8.75a.75.75 0 0 1-.102-1.493L8.75 13h4.498H8.75Zm0-3.5h6.505a.75.75 0 0 1 .101 1.493l-.101.007H8.75a.75.75 0 0 1-.102-1.493L8.75 9.5h6.505H8.75Z");
}
#app-mount path[d="M13.44 12.9599C12.9098 12.9599 12.48 13.3897 12.48 13.9199V20.2212C12.48 20.7514 12.9098 21.1812 13.44 21.1812H14.4C14.5326 21.1812 14.64 21.2886 14.64 21.4212V23.4597C14.64 23.6677 14.8866 23.7772 15.0409 23.6377L17.4859 21.4289C17.6623 21.2694 17.8917 21.1812 18.1294 21.1812H22.56C23.0902 21.1812 23.52 20.7514 23.52 20.2212V13.9199C23.52 13.3897 23.0902 12.9599 22.56 12.9599H13.44Z"] {
  stroke: var(--bg-alt);
}

#app-mount .containerDefault-3TQ5YN .wrapper-1S43wv {
  padding-right: 0;
}
#app-mount .containerDefault-3TQ5YN .button-ejjZWC {
  padding: 0;
}

#app-mount .sidebar-1tnWFu .content-yjf30S > div[style="height: 84px;"],
#app-mount .sidebar-1tnWFu .content-yjf30S > div[style="height: 16px;"] {
  display: none;
}
#app-mount .container-1-ERn5 {
  display: flex;
  flex-direction: column-reverse;
}
#app-mount .header-3OsQeK {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  margin: 8px;
  filter: none;
  height: 42px;
  transition: none;
}
#app-mount .header-3OsQeK:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .header-3OsQeK:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .header-3OsQeK .headerContent-2SNbie {
  flex: 1;
}
#app-mount .header-3OsQeK .headerChildren-2qV9P8 {
  display: flex;
}
#app-mount .header-3OsQeK .guildIconContainer-3QvE6w {
  display: none;
}
#app-mount .header-3OsQeK .name-3Uvkvr {
  font-weight: var(--font-weight-normal);
  max-width: calc(var(--channels-width) - 64px);
}
#app-mount .header-3OsQeK:hover {
  background: var(--btn-bg-hover);
}
#app-mount .animatedContainer-2laTjx {
  background: transparent;
  height: var(--banner-height);
  box-shadow: none;
  width: var(--channels-width);
  position: relative;
  transform: none !important;
  opacity: 1 !important;
  border-bottom: 1px solid var(--border-mid);
}
#app-mount .bannerImage-ubW8K- {
  overflow: hidden;
  width: 100%;
  transform: none !important;
  height: var(--banner-height);
}
#app-mount .bannerImage-ubW8K- img {
  width: 100%;
  height: 100%;
}
#app-mount .bannerImage-ubW8K-::before {
  content: none;
}
#app-mount .communityInfoContainer-1dMVpU {
  margin-top: 75px;
  left: 0;
}
#app-mount .communityInfoPill-2Mll66 {
  border-radius: var(--rounded);
  background: var(--bg-main);
}

#app-mount .panels-3wFtMD {
  background: transparent;
  border: none;
}
#app-mount .panels-3wFtMD > .container-YkUktl {
  position: absolute;
  box-sizing: border-box;
  bottom: 11px;
  left: 12px;
  background: var(--bg-main);
  padding: 8px 14px;
  width: calc(var(--channels-width) - 12px);
  border-radius: var(--rounded) 0 0 var(--rounded);
  border: 1px solid var(--border-high);
  border-right: none;
  height: var(--bottombar-height);
  z-index: 1;
}
#app-mount .panels-3wFtMD > .container-YkUktl::before {
  content: "";
  position: absolute;
  right: 0;
  height: calc(var(--bottombar-height) / 2);
  width: 1px;
  background: var(--border-mid);
}
#app-mount .panels-3wFtMD > .container-YkUktl > .flex-2S1XBF {
  gap: 8px;
  height: 75%;
  width: 100%;
}
#app-mount .panels-3wFtMD > .container-YkUktl button {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  flex: 1;
}
#app-mount .panels-3wFtMD > .container-YkUktl button:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .panels-3wFtMD > .container-YkUktl button:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .panels-3wFtMD > .container-YkUktl button svg {
  width: 18px;
  height: 18px;
}
#app-mount .panels-3wFtMD > .container-YkUktl .avatarWrapper-1B9FTW {
  padding: 6px;
  min-width: unset;
  margin: 0 8px 0 0;
}
#app-mount .panels-3wFtMD > .container-YkUktl .avatarWrapper-1B9FTW:hover {
  background: transparent;
  box-shadow: var(--server-hover-selected);
}
#app-mount .panels-3wFtMD > .container-YkUktl .nameTag-sc-gpq {
  display: none;
}
#app-mount .panels-3wFtMD:hover .container-1zzFcN {
  translate: 0 0;
  opacity: 1;
  visibility: visible;
}
#app-mount .panels-3wFtMD:has(.wrapper-3Hk9OB) {
  background-color: red;
}
#app-mount .container-1zzFcN {
  background: transparent;
  padding-bottom: 0;
  position: absolute;
  bottom: calc(var(--bottombar-height) + 9px);
  left: 12px;
  right: 12px;
  border-radius: var(--rounded) var(--rounded) 0 0;
  background: var(--bg-main);
  padding: 8px 8px 11px 8px;
  border: 1px solid var(--border-high);
  border-bottom: none;
  flex-direction: column-reverse;
  display: flex;
  gap: 8px;
}
#app-mount .container-1zzFcN > .flex-2S1XBF {
  padding-bottom: 0;
  position: relative;
  z-index: 1;
}
#app-mount .container-1zzFcN > .flex-2S1XBF::before {
  content: "";
  position: absolute;
  inset: -8px;
  border-radius: var(--rounded) var(--rounded) 0 0;
  background-color: var(--bg-main);
}
#app-mount .container-1zzFcN > .flex-2S1XBF > .flex-2S1XBF {
  gap: 4px;
}
#app-mount .container-1zzFcN > .flex-2S1XBF > .flex-2S1XBF button {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .container-1zzFcN > .flex-2S1XBF > .flex-2S1XBF button:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .container-1zzFcN > .flex-2S1XBF > .flex-2S1XBF button:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .container-1zzFcN > .flex-2S1XBF:hover + .actionButtons-2vEOUh {
  bottom: calc(100% - 2px);
  opacity: 1;
  visibility: visible;
  transition-delay: 0.45s;
}
#app-mount .container-1zzFcN a[href^="/channel"] {
  display: none;
}
#app-mount .inner-llGtyq {
  position: relative;
}
#app-mount .rtcConnectionStatus-c5A6Av {
  display: flex;
  align-items: center;
}
#app-mount .rtcConnectionStatus-c5A6Av .button-ejjZWC {
  padding: 0;
  margin-left: 4px;
}
#app-mount .ping-2IpLcU {
  width: 24px;
  height: 24px;
}
#app-mount .actionButtons-2vEOUh {
  position: absolute;
  bottom: calc(0% - 2px);
  width: calc(100% - 16px);
  background: var(--bg-main);
  border-radius: var(--rounded) var(--rounded) 0 0;
  border: 1px solid var(--border-high);
  border-bottom: none;
  padding: 8px;
  left: -1px;
  visibility: hidden;
  transition: 0.15s var(--transition) 0s;
  z-index: 0;
}
#app-mount .actionButtons-2vEOUh .button-1EGGcP.buttonColor-3bP3fX.colorBrand-I6CyqQ {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .actionButtons-2vEOUh .button-1EGGcP.buttonColor-3bP3fX.colorBrand-I6CyqQ:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .actionButtons-2vEOUh .button-1EGGcP.buttonColor-3bP3fX.colorBrand-I6CyqQ:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .actionButtons-2vEOUh:hover {
  visibility: visible;
  opacity: 1;
  bottom: calc(100% - 2px);
}

#app-mount .privateChannels-oVe7HL {
  background: transparent;
}
#app-mount .scroller-WSmht3 {
  background: transparent;
  padding: 8px 2px 8px 8px !important;
}
#app-mount .scroller-WSmht3 div[style="height: 8px;"] {
  display: none;
}
#app-mount .searchBar-3TnChZ {
  height: var(--toolbar-height);
  box-shadow: none;
  border-bottom: 1px solid var(--border-mid);
  box-sizing: border-box;
  padding: 0 8px;
}
#app-mount .searchBar-3TnChZ button {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .searchBar-3TnChZ button:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .searchBar-3TnChZ button:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .channel-1Shao0 {
  max-width: unset;
  margin: 0 0 4px 0;
  padding: 0;
}
#app-mount .channel-1Shao0 .layout-1LjVue {
  height: 48px;
  padding: 0 18px;
  cursor: var(--cursor);
}
#app-mount .channel-1Shao0 .interactive-26HRN_ {
  cursor: var(--cursor);
  background: transparent;
}
#app-mount .channel-1Shao0 .interactive-26HRN_::before {
  content: "";
  border-radius: 50px;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: var(--pill-width);
  height: 0;
  left: 0;
  opacity: 0;
  background: rgb(var(--accent));
  transition: var(--pill-transition);
}
#app-mount .channel-1Shao0 .content-66wMin {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
#app-mount .channel-1Shao0:hover .interactive-26HRN_ {
  background: var(--bg-interactive-high);
}
#app-mount .channel-1Shao0 .selected-26oxtA {
  background: var(--bg-interactive-high);
}
#app-mount .channel-1Shao0 .selected-26oxtA::before {
  height: var(--pill-height);
  opacity: 1;
}
#app-mount .channel-1Shao0 .selected-26oxtA:hover {
  background: var(--bg-interactive-high-hover);
}
#app-mount .link-39sEB3 {
  cursor: var(--cursor);
}
#app-mount .link-39sEB3[href="/channels/@me"] .linkButtonIcon-7rsZcu {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M4 13.999 13 14a2 2 0 0 1 1.995 1.85L15 16v1.5C14.999 21 11.284 22 8.5 22c-2.722 0-6.335-.956-6.495-4.27L2 17.5v-1.501c0-1.054.816-1.918 1.85-1.995L4 14ZM15.22 14H20c1.054 0 1.918.816 1.994 1.85L22 16v1c-.001 3.062-2.858 4-5 4a7.16 7.16 0 0 1-2.14-.322c.336-.386.607-.827.802-1.327A6.19 6.19 0 0 0 17 19.5l.267-.006c.985-.043 3.086-.363 3.226-2.289L20.5 17v-1a.501.501 0 0 0-.41-.492L20 15.5h-4.051a2.957 2.957 0 0 0-.595-1.34L15.22 14H20h-4.78ZM4 15.499l-.1.01a.51.51 0 0 0-.254.136.506.506 0 0 0-.136.253l-.01.101V17.5c0 1.009.45 1.722 1.417 2.242.826.445 2.003.714 3.266.753l.317.005.317-.005c1.263-.039 2.439-.308 3.266-.753.906-.488 1.359-1.145 1.412-2.057l.005-.186V16a.501.501 0 0 0-.41-.492L13 15.5l-9-.001ZM8.5 3a4.5 4.5 0 1 1 0 9 4.5 4.5 0 0 1 0-9Zm9 2a3.5 3.5 0 1 1 0 7 3.5 3.5 0 0 1 0-7Zm-9-.5c-1.654 0-3 1.346-3 3s1.346 3 3 3 3-1.346 3-3-1.346-3-3-3Zm9 2c-1.103 0-2 .897-2 2s.897 2 2 2 2-.897 2-2-.897-2-2-2Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M4 13.999 13 14a2 2 0 0 1 1.995 1.85L15 16v1.5C14.999 21 11.284 22 8.5 22c-2.722 0-6.335-.956-6.495-4.27L2 17.5v-1.501c0-1.054.816-1.918 1.85-1.995L4 14ZM15.22 14H20c1.054 0 1.918.816 1.994 1.85L22 16v1c-.001 3.062-2.858 4-5 4a7.16 7.16 0 0 1-2.14-.322c.336-.386.607-.827.802-1.327A6.19 6.19 0 0 0 17 19.5l.267-.006c.985-.043 3.086-.363 3.226-2.289L20.5 17v-1a.501.501 0 0 0-.41-.492L20 15.5h-4.051a2.957 2.957 0 0 0-.595-1.34L15.22 14H20h-4.78ZM4 15.499l-.1.01a.51.51 0 0 0-.254.136.506.506 0 0 0-.136.253l-.01.101V17.5c0 1.009.45 1.722 1.417 2.242.826.445 2.003.714 3.266.753l.317.005.317-.005c1.263-.039 2.439-.308 3.266-.753.906-.488 1.359-1.145 1.412-2.057l.005-.186V16a.501.501 0 0 0-.41-.492L13 15.5l-9-.001ZM8.5 3a4.5 4.5 0 1 1 0 9 4.5 4.5 0 0 1 0-9Zm9 2a3.5 3.5 0 1 1 0 7 3.5 3.5 0 0 1 0-7Zm-9-.5c-1.654 0-3 1.346-3 3s1.346 3 3 3 3-1.346 3-3-1.346-3-3-3Zm9 2c-1.103 0-2 .897-2 2s.897 2 2 2 2-.897 2-2-.897-2-2-2Z" /></svg>') center/cover;
  background: var(--interactive-normal);
}
#app-mount .link-39sEB3[href="/channels/@me"] .linkButtonIcon-7rsZcu g {
  display: none;
}

#app-mount .list-2x9Cl9 {
  padding: 4px 0 0 0;
}
#app-mount .list-2x9Cl9 .draggable-S2aEx4 {
  height: auto;
}
#app-mount .list-2x9Cl9 .draggable-S2aEx4:not(:last-child) {
  margin-bottom: 4px;
}
#app-mount .voiceUser-3nRK-K {
  height: auto;
}
#app-mount .voiceUser-3nRK-K::before {
  content: "";
  display: block;
  height: 0;
  width: var(--pill-width);
  background: rgb(var(--accent));
  border-radius: 50px;
  transition: var(--pill-transition);
  opacity: 0;
  position: absolute;
  left: 0;
  top: 50%;
  transform: translateY(-50%);
  z-index: 1;
}
#app-mount .voiceUser-3nRK-K:hover .content-1Tgc42 {
  background: var(--bg-interactive-high);
}
#app-mount .voiceUser-3nRK-K.selected-1oxcpH::before {
  height: var(--pill-height);
  opacity: 1;
}
#app-mount .voiceUser-3nRK-K.selected-1oxcpH .content-1Tgc42 {
  background: var(--bg-interactive-high);
}
#app-mount .voiceUser-3nRK-K.selected-1oxcpH:hover .content-1Tgc42 {
  background: var(--bg-interactive-high-hover);
}
#app-mount .avatarSpeaking-2pCGrZ {
  box-shadow: inset 0 0 0 2px rgb(var(--accent)), inset 0 0 0 4px var(--bg-alt);
}
#app-mount .content-1Tgc42 {
  margin: 0;
  padding: 2px 8px 2px 32px;
}

#app-mount .container-2giAcK {
  margin: -8px 0 0 0;
}
#app-mount .progressBar-2yl2pi {
  background: linear-gradient(90deg, rgb(var(--accent), 0.5), rgb(var(--accent)));
}

#app-mount .chat-2ZfjoI {
  background: transparent;
}
#app-mount .content-1jQy2l::before {
  content: none;
}
#app-mount .chatContent-3KubbW {
  background: var(--bg-alt);
}
#app-mount .chatContent-3KubbW:only-child {
  margin-right: 0;
  border-top-right-radius: 0;
}
#app-mount .scrollerSpacer-3AqkT9 {
  height: 24px;
}
#app-mount .iconWrapper-3plkqh {
  background: var(--bg-content);
  border: 1px solid var(--border-mid);
}
#app-mount .messagesWrapper-RpOMA3::before {
  content: "";
  position: absolute;
  bottom: 0;
  width: calc(100% - 8px);
  height: 24px;
  background: linear-gradient(transparent, var(--bg-alt));
  z-index: 2;
  pointer-events: none;
}

#app-mount .message-2CShn3.selected-2LX7Jy.cozyMessage-1DWF9U .contents-2MsGLg {
  display: block;
  width: 100%;
  background: var(--bg-content);
}
#app-mount .message-2CShn3.selected-2LX7Jy.cozyMessage-1DWF9U .contents-2MsGLg .textArea-2CLwUE {
  height: auto;
  min-height: auto;
}
#app-mount .message-2CShn3.selected-2LX7Jy.cozyMessage-1DWF9U .contents-2MsGLg .channelTextArea-220_Gz {
  margin-top: 0;
}
#app-mount .message-2CShn3.selected-2LX7Jy.cozyMessage-1DWF9U .contents-2MsGLg .slateTextArea-27tjG0 {
  padding-top: 0;
  padding-bottom: 0;
}
#app-mount .message-2CShn3.selected-2LX7Jy.cozyMessage-1DWF9U .contents-2MsGLg .inner-NQg18Y::before {
  content: none;
}
#app-mount .operations-3q3u6E {
  padding: 12px;
}
#app-mount .mentioned-Tre-dv {
  background: rgb(var(--chat-mention-colour), 0.05);
}
#app-mount .mentioned-Tre-dv::before {
  background: rgb(var(--chat-mention-colour));
}
#app-mount .mentioned-Tre-dv.groupStart-3Mlgv1 .contents-2MsGLg {
  background: var(--chat-mention-bubble) !important;
}
#app-mount .mentioned-Tre-dv.groupStart-3Mlgv1 .contents-2MsGLg .messageContent-2t3eCI:not(:empty) {
  background: transparent !important;
}
#app-mount .mentioned-Tre-dv:not(.groupStart-3Mlgv1) .messageContent-2t3eCI:not(:empty) {
  background: var(--chat-mention-bubble) !important;
}
#app-mount .cozy-VmLDNB .avatar-2e8lTP {
  left: var(--chat-spacing-x);
  margin-top: 0;
}
#app-mount .cozy-VmLDNB .contents-2MsGLg > .messageContent-2t3eCI:not(:empty) {
  margin-left: 0;
  padding: var(--chat-padding-y) var(--chat-padding-x);
  background: var(--chat-bubble-bg);
  border-radius: var(--rounded);
  display: inline-block;
  max-width: calc(100% - var(--chat-spacing-x));
}
#app-mount .cozy-VmLDNB .container-x059i8 {
  padding: 0;
}
#app-mount .cozy-VmLDNB.groupStart-3Mlgv1 .contents-2MsGLg {
  background: var(--chat-bubble-bg);
  display: inline-block;
  border-radius: var(--rounded) var(--rounded);
  max-width: 100%;
}
#app-mount .cozy-VmLDNB.groupStart-3Mlgv1 .contents-2MsGLg .header-2jRmjb {
  padding-top: var(--chat-padding-y);
  padding-right: var(--chat-padding-x);
  padding-bottom: 2px;
  padding-left: var(--chat-padding-x);
  margin-left: 0;
}
#app-mount .cozy-VmLDNB.groupStart-3Mlgv1 .contents-2MsGLg .messageContent-2t3eCI:empty {
  margin-top: 8px;
  display: block;
}
#app-mount .cozy-VmLDNB.groupStart-3Mlgv1 .contents-2MsGLg .messageContent-2t3eCI:not(:empty) {
  padding-top: 0;
}
#app-mount .cozy-VmLDNB.isSystemMessage-QNv9ZH .messageContent-2t3eCI {
  padding: 16px !important;
}
#app-mount .cozy-VmLDNB.wrapper-30-Nkg {
  padding-left: calc(var(--chat-spacing-x) + 56px);
  padding-right: calc(var(--chat-spacing-x) - 11px) !important;
}
#app-mount .embedFull-1HGV2S {
  background: var(--chat-bubble-bg);
}
#app-mount .markup-eYLPri pre {
  margin: 0;
  max-width: 100%;
}
#app-mount .wrapper-2vIMkT {
  background: var(--bg-content);
  border-radius: var(--btn-radius);
  box-shadow: var(--shadow-flyout);
  height: auto;
}
#app-mount .wrapper-2vIMkT .button-3bklZh {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  width: auto;
  height: auto;
  min-width: auto;
  border-radius: 0;
}
#app-mount .wrapper-2vIMkT .button-3bklZh:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .wrapper-2vIMkT .button-3bklZh:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .wrapper-2vIMkT .button-3bklZh.dangerous-Y36ifs {
  color: hsl(var(--discord-red));
}
#app-mount .wrapper-1ZcZW- {
  background: rgb(var(--accent), 0.1);
  color: rgb(var(--accent));
  font-weight: var(--font-weight-semibold);
  cursor: default;
}
#app-mount .wrapper-1ZcZW-:hover {
  box-shadow: inset 0 0 0 100vmax var(--btn-bg-hover);
}
#app-mount .reaction-102jx9 {
  background: transparent;
  border-color: var(--border-high);
  border-radius: 50px;
  cursor: default;
  transition: none;
}
#app-mount .reaction-102jx9:hover {
  background: var(--bg-interactive-high);
}
#app-mount .reaction-102jx9.reactionMe-2zhiyZ {
  border-color: rgb(var(--accent));
}
#app-mount .reaction-102jx9.reactionMe-2zhiyZ .reactionCount-SWXh9W {
  color: rgb(var(--accent));
}
#app-mount .markup-eYLPri code {
  background: var(--bg-alt);
  border-color: var(--border-mid);
}
#app-mount .textContainer-36wgKK {
  background: var(--bg-content);
  border-radius: var(--rounded);
  border: 1px solid var(--border-mid);
}
#app-mount .footer-GXWBBp {
  background: transparent;
  border: none;
  margin-top: 4px;
  padding: 0;
  height: auto;
}
#app-mount .toggleExpandSection-1710zV,
#app-mount .anchor-1MIwyf.downloadSection-20OayS,
#app-mount .codeIcon-Ni8XUA {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  margin-right: 4px;
  min-height: 34px;
  min-width: 38px;
}
#app-mount .toggleExpandSection-1710zV:hover,
#app-mount .anchor-1MIwyf.downloadSection-20OayS:hover,
#app-mount .codeIcon-Ni8XUA:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .toggleExpandSection-1710zV:active,
#app-mount .anchor-1MIwyf.downloadSection-20OayS:active,
#app-mount .codeIcon-Ni8XUA:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .openFullPreviewSection-31zc2v {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  min-height: 34px;
}
#app-mount .openFullPreviewSection-31zc2v:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .openFullPreviewSection-31zc2v:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .downloadButton-2PkwZg {
  padding: 0;
  width: 16px;
  height: 16px;
}
#app-mount .anchor-1MIwyf.downloadSection-20OayS {
  margin-left: 8px;
}

.theme-light #app-mount .mentioned-Tre-dv {
  background: rgb(var(--accent), 0.15);
}

#app-mount .form-3gdLxP {
  margin: 0 12px 12px 0;
  padding: 8px 8px 8px 14px;
  background: var(--bg-main);
  min-height: var(--bottombar-height);
  align-items: center;
  display: flex;
  border: 1px solid var(--border-high);
  border-left: none;
  border-radius: 0 var(--rounded) var(--rounded) 0;
  box-sizing: border-box;
}
#app-mount .form-3gdLxP::before {
  content: none;
}
#app-mount .channelTextArea-1FufC0 {
  margin: 0;
  background: var(--bg-alt);
  position: relative;
  border-radius: var(--rounded);
}
#app-mount .channelTextArea-1FufC0:focus-within {
  background: var(--bg-content-alt);
}
#app-mount .channelTextArea-1FufC0:focus-within .inner-NQg18Y::before {
  height: 2px;
  background: rgb(var(--accent));
}
#app-mount .inner-NQg18Y::before {
  content: "";
  width: 100vw;
  height: 1px;
  background: var(--textbox-underline);
  bottom: 0;
  position: absolute;
  display: block;
}
#app-mount .sansAttachButton-1ERHue:has(.attachWrapper-3slhXI) {
  padding-left: 0;
}
#app-mount .attachButton-_ACFSu {
  height: 44px !important;
  width: 46px !important;
}
#app-mount .attachButton-_ACFSu svg {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12 6.477 2 12 2Zm0 1.5a8.5 8.5 0 1 0 0 17 8.5 8.5 0 0 0 0-17ZM12 7a.75.75 0 0 1 .75.75v3.5h3.5a.75.75 0 0 1 0 1.5h-3.5v3.5a.75.75 0 0 1-1.5 0v-3.5h-3.5a.75.75 0 0 1 0-1.5h3.5v-3.5A.75.75 0 0 1 12 7Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12 6.477 2 12 2Zm0 1.5a8.5 8.5 0 1 0 0 17 8.5 8.5 0 0 0 0-17ZM12 7a.75.75 0 0 1 .75.75v3.5h3.5a.75.75 0 0 1 0 1.5h-3.5v3.5a.75.75 0 0 1-1.5 0v-3.5h-3.5a.75.75 0 0 1 0-1.5h3.5v-3.5A.75.75 0 0 1 12 7Z" /></svg>') center/cover;
  background: var(--interactive-normal);
  width: 24px;
  height: 24px;
}
#app-mount .attachButton-_ACFSu path {
  display: none;
}
#app-mount .attachButton-_ACFSu:hover svg {
  background: var(--interactive-active);
}
#app-mount .scrollableContainer-15eg7h {
  background: transparent;
  padding-right: 8px;
  border-radius: var(--rounded);
}
#app-mount .scrollableContainer-15eg7h::-webkit-scrollbar {
  display: none;
}
#app-mount .scrollableContainer-15eg7h .button-ejjZWC {
  padding: 0 10px;
  margin: 0;
  height: 100%;
}
#app-mount .scrollableContainer-15eg7h .button-ejjZWC svg {
  background: var(--interactive-normal);
}
#app-mount .scrollableContainer-15eg7h .button-ejjZWC path {
  display: none;
}
#app-mount .scrollableContainer-15eg7h .button-ejjZWC:hover svg {
  background: var(--interactive-active);
}
#app-mount .scrollableContainer-15eg7h .contents-3NembX {
  margin: 0;
  padding: 0;
  height: 100%;
}
#app-mount .scrollableContainer-15eg7h .buttonWrapper-3YFQGJ {
  cursor: var(--cursor);
}
#app-mount .typingDots-1Y8dki {
  filter: drop-shadow(0 3px 5px hsla(0, 0%, 0%, 0.5));
}
#app-mount svg:has(path[d^="M16.886 7.999H20C21.104"]) {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2a3.25 3.25 0 0 1 2.739 5h2.511c.69 0 1.25.56 1.25 1.25v3.5a1.25 1.25 0 0 1-1 1.225v5.775a3.25 3.25 0 0 1-3.066 3.245L16.75 22h-9.5a3.25 3.25 0 0 1-3.245-3.066L4 18.75v-5.775c-.57-.116-1-.62-1-1.225v-3.5C3 7.56 3.56 7 4.25 7h2.511a3.25 3.25 0 0 1 5.24-3.827A3.24 3.24 0 0 1 14.5 2Zm-3.25 10.999H5.5v5.751a1.75 1.75 0 0 0 1.606 1.744l.144.006h4v-7.501Zm7.25 0h-5.75V20.5h4a1.75 1.75 0 0 0 1.744-1.607l.006-.143v-5.751ZM11.25 8.5H4.5v3l6.75-.001V8.5Zm8.25 3v-3h-6.75v2.999l6.75.001Zm-5-8a1.75 1.75 0 0 0-1.75 1.75v1.749h1.774l.12-.005A1.75 1.75 0 0 0 14.5 3.5Zm-5 0a1.75 1.75 0 0 0-.144 3.494l.12.005h1.774V5.25l-.006-.144A1.75 1.75 0 0 0 9.5 3.5Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2a3.25 3.25 0 0 1 2.739 5h2.511c.69 0 1.25.56 1.25 1.25v3.5a1.25 1.25 0 0 1-1 1.225v5.775a3.25 3.25 0 0 1-3.066 3.245L16.75 22h-9.5a3.25 3.25 0 0 1-3.245-3.066L4 18.75v-5.775c-.57-.116-1-.62-1-1.225v-3.5C3 7.56 3.56 7 4.25 7h2.511a3.25 3.25 0 0 1 5.24-3.827A3.24 3.24 0 0 1 14.5 2Zm-3.25 10.999H5.5v5.751a1.75 1.75 0 0 0 1.606 1.744l.144.006h4v-7.501Zm7.25 0h-5.75V20.5h4a1.75 1.75 0 0 0 1.744-1.607l.006-.143v-5.751ZM11.25 8.5H4.5v3l6.75-.001V8.5Zm8.25 3v-3h-6.75v2.999l6.75.001Zm-5-8a1.75 1.75 0 0 0-1.75 1.75v1.749h1.774l.12-.005A1.75 1.75 0 0 0 14.5 3.5Zm-5 0a1.75 1.75 0 0 0-.144 3.494l.12.005h1.774V5.25l-.006-.144A1.75 1.75 0 0 0 9.5 3.5Z" /></svg>') center/cover;
}
#app-mount svg:has(path[d^="m2 2c-1.1046"]) {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M18.75 3.501A3.25 3.25 0 0 1 22 6.751v10.503a3.25 3.25 0 0 1-3.25 3.25H5.25A3.25 3.25 0 0 1 2 17.254V6.75a3.25 3.25 0 0 1 3.25-3.25h13.5Zm0 1.5H5.25a1.75 1.75 0 0 0-1.75 1.75v10.503c0 .966.784 1.75 1.75 1.75h13.5a1.75 1.75 0 0 0 1.75-1.75V6.75a1.75 1.75 0 0 0-1.75-1.75ZM8.015 8.872c.596 0 1.019.082 1.502.314a.625.625 0 0 1-.541 1.127c-.3-.144-.54-.19-.961-.19-.867 0-1.504.796-1.504 1.872 0 1.077.638 1.876 1.504 1.876.428 0 .791-.18.98-.501L9 13.355v-.734h-.376a.625.625 0 0 1-.618-.532L8 11.997c0-.314.231-.574.533-.619l.092-.006h1.002c.314 0 .573.23.618.532l.007.093-.002 1.547-.006.056-.021.09-.02.055c-.377.89-1.241 1.376-2.188 1.376-1.626 0-2.754-1.413-2.754-3.126 0-1.713 1.127-3.123 2.754-3.123Zm4.614.122c.314 0 .574.232.618.533l.007.092v4.763a.625.625 0 0 1-1.243.092l-.007-.092V9.619c0-.345.28-.625.625-.625Zm2.996 0 1.997.007a.625.625 0 0 1 .088 1.244l-.092.006-1.371-.005V12h1.123c.314 0 .574.232.618.534l.007.092a.625.625 0 0 1-.533.618l-.092.007-1.123-.001v1.115a.625.625 0 0 1-.532.619l-.092.006a.625.625 0 0 1-.619-.532l-.006-.093V9.617a.625.625 0 0 1 .534-.616l.093-.007Z" /></svg>') center/28px;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M18.75 3.501A3.25 3.25 0 0 1 22 6.751v10.503a3.25 3.25 0 0 1-3.25 3.25H5.25A3.25 3.25 0 0 1 2 17.254V6.75a3.25 3.25 0 0 1 3.25-3.25h13.5Zm0 1.5H5.25a1.75 1.75 0 0 0-1.75 1.75v10.503c0 .966.784 1.75 1.75 1.75h13.5a1.75 1.75 0 0 0 1.75-1.75V6.75a1.75 1.75 0 0 0-1.75-1.75ZM8.015 8.872c.596 0 1.019.082 1.502.314a.625.625 0 0 1-.541 1.127c-.3-.144-.54-.19-.961-.19-.867 0-1.504.796-1.504 1.872 0 1.077.638 1.876 1.504 1.876.428 0 .791-.18.98-.501L9 13.355v-.734h-.376a.625.625 0 0 1-.618-.532L8 11.997c0-.314.231-.574.533-.619l.092-.006h1.002c.314 0 .573.23.618.532l.007.093-.002 1.547-.006.056-.021.09-.02.055c-.377.89-1.241 1.376-2.188 1.376-1.626 0-2.754-1.413-2.754-3.126 0-1.713 1.127-3.123 2.754-3.123Zm4.614.122c.314 0 .574.232.618.533l.007.092v4.763a.625.625 0 0 1-1.243.092l-.007-.092V9.619c0-.345.28-.625.625-.625Zm2.996 0 1.997.007a.625.625 0 0 1 .088 1.244l-.092.006-1.371-.005V12h1.123c.314 0 .574.232.618.534l.007.092a.625.625 0 0 1-.533.618l-.092.007-1.123-.001v1.115a.625.625 0 0 1-.532.619l-.092.006a.625.625 0 0 1-.619-.532l-.006-.093V9.617a.625.625 0 0 1 .534-.616l.093-.007Z" /></svg>') center/28px;
}
#app-mount svg:has(path[d^="M12.0002 0.662583V5.40204C12.0002"]) {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v6.879a2.25 2.25 0 0 1-.659 1.59l-5.621 5.622a2.25 2.25 0 0 1-1.591.659H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm0 1.5H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75H13v-3.064a6.657 6.657 0 0 1-.673.066L12 16.51a6.334 6.334 0 0 1-3.678-1.14.75.75 0 1 1 .854-1.234c.845.584 1.78.874 2.824.874.462 0 .903-.057 1.324-.171a3.247 3.247 0 0 1 2.713-1.832l.213-.007H19.5V6.25a1.75 1.75 0 0 0-1.75-1.75Zm.689 10h-2.188c-.918 0-1.671.707-1.744 1.607l-.006.143-.001 2.189 3.939-3.939ZM9 7.751a1.25 1.25 0 1 1 0 2.499A1.25 1.25 0 0 1 9 7.75Zm6 0a1.25 1.25 0 1 1 0 2.499 1.25 1.25 0 0 1 0-2.499Z" /></svg>') center/28px;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v6.879a2.25 2.25 0 0 1-.659 1.59l-5.621 5.622a2.25 2.25 0 0 1-1.591.659H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm0 1.5H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75H13v-3.064a6.657 6.657 0 0 1-.673.066L12 16.51a6.334 6.334 0 0 1-3.678-1.14.75.75 0 1 1 .854-1.234c.845.584 1.78.874 2.824.874.462 0 .903-.057 1.324-.171a3.247 3.247 0 0 1 2.713-1.832l.213-.007H19.5V6.25a1.75 1.75 0 0 0-1.75-1.75Zm.689 10h-2.188c-.918 0-1.671.707-1.744 1.607l-.006.143-.001 2.189 3.939-3.939ZM9 7.751a1.25 1.25 0 1 1 0 2.499A1.25 1.25 0 0 1 9 7.75Zm6 0a1.25 1.25 0 1 1 0 2.499 1.25 1.25 0 0 1 0-2.499Z" /></svg>') center/28px;
}
#app-mount .sprite-2lxwfc {
  width: 26px;
  height: 26px;
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.999c5.524 0 10.002 4.478 10.002 10.002 0 5.523-4.478 10.001-10.002 10.001-5.524 0-10.002-4.478-10.002-10.001C1.998 6.477 6.476 1.999 12 1.999Zm0 1.5a8.502 8.502 0 1 0 0 17.003A8.502 8.502 0 0 0 12 3.5ZM8.462 14.784A4.491 4.491 0 0 0 12 16.502a4.492 4.492 0 0 0 3.535-1.714.75.75 0 1 1 1.177.93A5.991 5.991 0 0 1 12 18.002a5.991 5.991 0 0 1-4.716-2.29.75.75 0 0 1 1.178-.928ZM9 8.75a1.25 1.25 0 1 1 0 2.499A1.25 1.25 0 0 1 9 8.75Zm6 0a1.25 1.25 0 1 1 0 2.499 1.25 1.25 0 0 1 0-2.499Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.999c5.524 0 10.002 4.478 10.002 10.002 0 5.523-4.478 10.001-10.002 10.001-5.524 0-10.002-4.478-10.002-10.001C1.998 6.477 6.476 1.999 12 1.999Zm0 1.5a8.502 8.502 0 1 0 0 17.003A8.502 8.502 0 0 0 12 3.5ZM8.462 14.784A4.491 4.491 0 0 0 12 16.502a4.492 4.492 0 0 0 3.535-1.714.75.75 0 1 1 1.177.93A5.991 5.991 0 0 1 12 18.002a5.991 5.991 0 0 1-4.716-2.29.75.75 0 0 1 1.178-.928ZM9 8.75a1.25 1.25 0 1 1 0 2.499A1.25 1.25 0 0 1 9 8.75Zm6 0a1.25 1.25 0 1 1 0 2.499 1.25 1.25 0 0 1 0-2.499Z" /></svg>') center/cover;
  background: var(--interactive-normal);
  filter: none !important;
  transform: none !important;
  transition: none !important;
}
#app-mount .sprite-2lxwfc:hover {
  background: var(--interactive-active);
}

#app-mount .typing-2J1mQU {
  bottom: 100%;
  left: 0;
  padding: 0 10px;
  right: -1px;
  pointer-events: none;
}
#app-mount .newMessagesBar-1hF-9G,
#app-mount .jumpToPresentBar-1cEnH0 {
  border-radius: var(--btn-radius);
  opacity: 1;
  left: unset;
  opacity: 1;
  background: var(--bg-alt);
  box-shadow: none;
}
#app-mount .newMessagesBar-1hF-9G button,
#app-mount .jumpToPresentBar-1cEnH0 button {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  cursor: var(--cursor);
  height: auto;
}
#app-mount .newMessagesBar-1hF-9G button:hover,
#app-mount .jumpToPresentBar-1cEnH0 button:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .newMessagesBar-1hF-9G button:active,
#app-mount .jumpToPresentBar-1cEnH0 button:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .newMessagesBar-1hF-9G button:first-child,
#app-mount .jumpToPresentBar-1cEnH0 button:first-child {
  border-radius: var(--btn-radius) 0 0 var(--btn-radius);
  margin-right: -1px;
}
#app-mount .newMessagesBar-1hF-9G button:last-child,
#app-mount .jumpToPresentBar-1cEnH0 button:last-child {
  border-radius: 0 var(--btn-radius) var(--btn-radius) 0;
}
#app-mount .newMessagesBar-1hF-9G:active,
#app-mount .jumpToPresentBar-1cEnH0:active {
  padding-top: 0;
}
#app-mount .newMessagesBar-1hF-9G {
  top: 16px;
}
#app-mount .newMessagesBar-1hF-9G .barButtonIcon-bMvzp2 {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.023 2.999a6.47 6.47 0 0 0-.71 1.5L5.25 4.5A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75h6.236a1.75 1.75 0 0 0 1.75-1.75l.001-2.483a6.517 6.517 0 0 0 1.5-1.077L22 14.75A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3l6.773-.001ZM17.5 1a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm2.646 3.146L16.055 8.24 14.9 6.7a.5.5 0 0 0-.8.6l1.5 2a.5.5 0 0 0 .754.054l4.5-4.5a.5.5 0 0 0-.707-.708Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.023 2.999a6.47 6.47 0 0 0-.71 1.5L5.25 4.5A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75h6.236a1.75 1.75 0 0 0 1.75-1.75l.001-2.483a6.517 6.517 0 0 0 1.5-1.077L22 14.75A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3l6.773-.001ZM17.5 1a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm2.646 3.146L16.055 8.24 14.9 6.7a.5.5 0 0 0-.8.6l1.5 2a.5.5 0 0 0 .754.054l4.5-4.5a.5.5 0 0 0-.707-.708Z" /></svg>') center/cover;
  background: currentColor;
}
#app-mount .newMessagesBar-1hF-9G .barButtonIcon-bMvzp2 path {
  display: none;
}
#app-mount .attachedBars-2BCP3l {
  background: transparent;
}
#app-mount .replyBar-1oi75v {
  background: var(--bg-alt);
}
#app-mount .jumpToPresentBar-1cEnH0 {
  bottom: 0;
  padding-bottom: 0;
}
#app-mount .jumpToPresentBar-1cEnH0 > span {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  border-radius: 0 var(--btn-radius) var(--btn-radius) 0;
  height: 30px;
  box-sizing: border-box;
}
#app-mount .jumpToPresentBar-1cEnH0 > span:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .jumpToPresentBar-1cEnH0 > span:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}

#app-mount .divider-IqmEqJ {
  margin: var(--chat-spacing-y) calc(var(--chat-spacing-x) - 11px) var(--chat-spacing-y) var(--chat-spacing-x);
  border-color: var(--border-mid);
  top: 0;
}
#app-mount .divider-IqmEqJ.isUnread-3Lojb- {
  border-color: hsl(359, calc(var(--saturation-factor, 1) * 82.6%), 59.4%);
}
#app-mount .content-3spvdd {
  border: none;
  background: var(--bg-alt);
  padding: 2px 32px;
}

#app-mount .searchResultsWrap-5RVOkx {
  border-left: 1px solid var(--border-mid);
  background: var(--bg-alt);
}
#app-mount .searchHeader-1r_ZSh {
  background: var(--bg-main);
  border-bottom: 1px solid var(--border-mid);
  padding: 8px 8px 8px 16px;
}
#app-mount .searchHeader-1r_ZSh .size16-rrJ6ag {
  color: var(--text-secondary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height-lg);
}
#app-mount .searchHeader-1r_ZSh .item-3XjbnG {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  margin: 0;
  height: auto;
}
#app-mount .searchHeader-1r_ZSh .item-3XjbnG:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .searchHeader-1r_ZSh .item-3XjbnG:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .searchHeader-1r_ZSh .item-3XjbnG.selected-g-kMVV {
  background: rgb(var(--accent));
  color: var(--accent-text);
  transition: box-shadow 0.15s var(--transition);
  font-weight: var(--font-weight-semibold);
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
}
#app-mount .searchHeader-1r_ZSh .item-3XjbnG.selected-g-kMVV:hover {
  background: rgb(var(--accent));
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.1) !important;
  border-color: hsla(0, 0%, 0%, 0.1);
}
#app-mount .searchHeader-1r_ZSh .item-3XjbnG.selected-g-kMVV:active {
  background: rgb(var(--accent));
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.2) !important;
  border-color: hsla(0, 0%, 0%, 0.2);
}
#app-mount .channelName-3w2Y3c {
  background: transparent;
}
#app-mount .container-rZM65Y .button-cfOvv- {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  height: auto;
}
#app-mount .container-rZM65Y .button-cfOvv-:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .container-rZM65Y .button-cfOvv-:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .searchResult-O9NDji {
  background: transparent;
  border-radius: 0;
  margin-bottom: 0;
  cursor: var(--cursor);
}
#app-mount .searchResult-O9NDji .cozy-VmLDNB {
  padding-left: calc(var(--chat-spacing-x) + 20px);
}
#app-mount .searchResult-O9NDji .avatar-2e8lTP {
  left: calc(var(--chat-spacing-x) / 2 - 16px);
}
#app-mount .message-24k8JL {
  padding-bottom: 0;
}
#app-mount .pageControl-1XvHg0 {
  padding-bottom: 16px;
}
#app-mount .pageControl-1XvHg0 > .pageButton-1GMGeJ,
#app-mount .pageControl-1XvHg0 div[role=button] {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  min-height: 32px;
  max-height: 32px;
  margin: 0;
  border-radius: 0 !important;
}
#app-mount .pageControl-1XvHg0 > .pageButton-1GMGeJ:hover,
#app-mount .pageControl-1XvHg0 div[role=button]:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .pageControl-1XvHg0 > .pageButton-1GMGeJ:active,
#app-mount .pageControl-1XvHg0 div[role=button]:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .pageControl-1XvHg0 > .pageButton-1GMGeJ.activeButton-LRWFC_ {
  background: rgb(var(--accent));
  color: var(--accent-text);
  transition: box-shadow 0.15s var(--transition);
  font-weight: var(--font-weight-semibold);
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
}
#app-mount .pageControl-1XvHg0 > .pageButton-1GMGeJ.activeButton-LRWFC_:hover {
  background: rgb(var(--accent));
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.1) !important;
  border-color: hsla(0, 0%, 0%, 0.1);
}
#app-mount .pageControl-1XvHg0 > .pageButton-1GMGeJ.activeButton-LRWFC_:active {
  background: rgb(var(--accent));
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.2) !important;
  border-color: hsla(0, 0%, 0%, 0.2);
}
#app-mount .pageControl-1XvHg0 > button:first-child {
  border-radius: var(--rounded) 0 0 var(--rounded) !important;
}
#app-mount .pageControl-1XvHg0 > button:last-child {
  border-radius: 0 var(--rounded) var(--rounded) 0 !important;
}
#app-mount .pageControl-1XvHg0 .gap-35QmZH {
  margin: 0;
  width: auto;
  height: auto;
  min-width: unset;
  padding: 0;
}

#app-mount .wrapper-1gVUIN {
  background: var(--bg-main);
  border-bottom: 1px solid var(--border-mid);
}
#app-mount .wrapper-1gVUIN.minimum-fXpVNc {
  height: 300px;
}
#app-mount .voiceCallWrapper-3UtDiC {
  padding-bottom: 0;
  gap: 12px;
}
#app-mount .participant-1l6khj {
  margin: 0;
}
#app-mount .wrapper-3t3Yqv {
  gap: 8px;
}
#app-mount .wrapper-3t3Yqv .button-f2h6uQ {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  height: 32px;
  width: 44px;
}
#app-mount .wrapper-3t3Yqv .button-f2h6uQ:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .wrapper-3t3Yqv .button-f2h6uQ:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .wrapper-3t3Yqv .button-f2h6uQ svg {
  width: 18px;
  height: 18px;
}
#app-mount .wrapper-3t3Yqv button.red-3T8maV {
  background: hsl(var(--discord-red));
  color: #fff;
}
#app-mount .wrapper-3t3Yqv button.red-3T8maV:hover {
  background: hsl(var(--discord-red));
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.1) !important;
  border-color: hsla(0, 0%, 0%, 0.1);
}
#app-mount .wrapper-3t3Yqv button.red-3T8maV:active {
  background: hsl(var(--discord-red));
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.2) !important;
  border-color: hsla(0, 0%, 0%, 0.2);
}
#app-mount div.controlButton-2PMNom {
  margin: 0;
}
#app-mount button.controlButton-2PMNom {
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount button.controlButton-2PMNom:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount button.controlButton-2PMNom:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .contextMenuContainer-1RO4DQ {
  display: flex;
  height: 32px;
  width: 70px;
  overflow: hidden;
}
#app-mount .contextMenuContainer-1RO4DQ > svg {
  transform: translateX(6px) scale(1.2726);
}
#app-mount .contextMenuContainer-1RO4DQ foreignObject {
  -webkit-mask: none;
          mask: none;
}
#app-mount .contextMenuContainer-1RO4DQ button {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  border-radius: var(--btn-radius) 0 0 var(--btn-radius) !important;
  height: 32px;
  width: 44px;
}
#app-mount .contextMenuContainer-1RO4DQ button:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .contextMenuContainer-1RO4DQ button:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .contextMenuNub-NuTZ_U {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  height: 32px;
  padding: 4px;
  width: auto;
  position: static;
  border-radius: 0 var(--btn-radius) var(--btn-radius) 0 !important;
}
#app-mount .contextMenuNub-NuTZ_U:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .contextMenuNub-NuTZ_U:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .contextMenuNub-NuTZ_U svg {
  cursor: var(--cursor);
}
#app-mount .video-3n15R6 .transparent-1lUmft {
  background: transparent;
  border-bottom: none;
}

#app-mount .channelAttachmentArea-HwpkuQ {
  margin: 0;
  padding: 16px;
}
#app-mount .upload-vLbqu- {
  background: var(--bg-alt);
  border: 1px solid var(--border-high);
}

#app-mount .container-3XgAHv {
  border-left: 1px solid var(--border-mid);
  border-radius: 0;
  background: transparent;
}
#app-mount .chat-25x62K::before {
  content: none;
}
#app-mount .container-3YcgdM {
  background: var(--bg-alt);
  box-shadow: none;
  border-top: 1px solid var(--border-mid);
  border-bottom: 1px solid var(--border-mid);
}
#app-mount .container-3YcgdM .button-DAkLIy {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .container-3YcgdM .button-DAkLIy:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .container-3YcgdM .button-DAkLIy:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .container-3YcgdM .button-DAkLIy > div {
  background: transparent;
  border-radius: 0;
  border: none;
}
#app-mount .divider-AZrXIA {
  height: 0;
  background: var(--border-mid);
}

#app-mount .container-3wLKDe {
  background: transparent;
}
#app-mount .header-1Uy0p6 {
  background: transparent;
  box-shadow: none;
  border: none;
}
#app-mount .titleContainer-2YK93J {
  align-items: center;
  gap: 16px;
  cursor: default;
}
#app-mount .container-JhuCwn {
  padding: 0;
}
#app-mount .container-JhuCwn .input-2g-os5 {
  margin-top: 0;
}
#app-mount .container-2qVG6q {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0;
  position: relative;
  cursor: default;
  transition: none;
}
#app-mount .container-2qVG6q:hover {
  box-shadow: none;
  transform: none;
  background: var(--bg-content-alt);
}
#app-mount .pill-3pRQlO {
  border: 1px solid var(--border-high);
  background: transparent;
  height: 28px;
}
#app-mount .pill-3pRQlO .emoji-Z6vF9e {
  margin-right: 8px;
  width: 14px;
  height: 14px;
}
#app-mount .pill-3pRQlO .text-sm-semibold-3TWn25 {
  font-size: var(--font-size-xs);
}
#app-mount .pill-3pRQlO:hover {
  background: var(--bg-interactive-high);
}
#app-mount .pill-3pRQlO.selected-24z1Ou {
  border-color: rgb(var(--accent));
}
#app-mount .sidebarCard-1Gn1ch,
#app-mount .container-2IhveL {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 0 18px;
  position: relative;
}

#app-mount .container-2o3qEW,
#app-mount .members-3WRCEx,
#app-mount .members-3WRCEx > div {
  background: var(--bg-alt);
}
#app-mount .membersWrap-3NUR2t {
  border-left: 1px solid var(--border-mid);
  min-width: var(--members-width);
  width: var(--members-width);
  height: 100%;
}
#app-mount .members-3WRCEx {
  width: 100%;
  padding: 8px 2px 8px 8px !important;
  box-sizing: border-box;
}

#app-mount .member-2gU6Ar {
  max-width: none;
  margin: 0;
  padding: 2px 0;
  background: transparent;
}
#app-mount .member-2gU6Ar .layout-1qmrhw {
  height: 48px;
  padding: 0 16px;
  cursor: var(--cursor);
}
#app-mount .member-2gU6Ar .layout-1qmrhw::before {
  content: "";
  border-radius: 50px;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: var(--pill-width);
  height: 0;
  left: 0;
  opacity: 0;
  background: rgb(var(--accent));
  transition: var(--pill-transition);
}
#app-mount .member-2gU6Ar .name-3Vmqxm {
  color: var(--text-secondary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height-lg);
}
#app-mount .member-2gU6Ar:hover .layout-1qmrhw {
  background: var(--bg-interactive-high);
}
#app-mount .member-2gU6Ar.selected-1-Z6gm .layout-1qmrhw {
  background: var(--bg-interactive-high);
}
#app-mount .member-2gU6Ar.selected-1-Z6gm .layout-1qmrhw::before {
  height: var(--pill-height);
  opacity: 1;
}
#app-mount .member-2gU6Ar.selected-1-Z6gm .layout-1qmrhw:hover {
  background: var(--bg-interactive-high-hover);
}

#app-mount .membersGroup-2eiWxl {
  padding: 16px 16px 8px;
  height: auto;
}

#app-mount [role=dialog] .header-3_zmOb,
#app-mount [role=dialog] .header-1w9Q93 {
  border-bottom: 1px solid var(--border-high);
  background: var(--bg-alt);
  box-shadow: none;
  padding: 0 12px;
  display: flex;
  align-items: center;
  height: 48px;
  min-height: 48px;
}
#app-mount [role=dialog] .header-3_zmOb .size16-rrJ6ag,
#app-mount [role=dialog] .header-1w9Q93 .size16-rrJ6ag {
  color: var(--text-primary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height-lg);
}
#app-mount [role=dialog] [class^=jumpButton-] {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  height: auto;
  margin: 0;
  top: 0;
  right: 12px;
}
#app-mount [role=dialog] [class^=jumpButton-]:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount [role=dialog] [class^=jumpButton-]:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}

#app-mount .menu-2TXYjN {
  min-width: 280px;
  background: var(--bg-menu);
  border: 1px solid var(--border-high);
  border-radius: var(--rounded-high);
  box-shadow: none;
}
#app-mount .menu-2TXYjN .scroller-nxCRu_ {
  padding: 0 !important;
}
#app-mount .menu-2TXYjN .scroller-nxCRu_::-webkit-scrollbar {
  display: none;
}
#app-mount .menu-2TXYjN .scroller-nxCRu_ > .item-5ApiZt, #app-mount .menu-2TXYjN .scroller-nxCRu_ > div:not([class], [role=group]) {
  margin: 6px;
}
#app-mount .menu-2TXYjN .wrapper--nA0oy {
  padding: 6px 6px 0 !important;
}
#app-mount .menu-2TXYjN .wrapper--nA0oy::after {
  content: "";
  display: block;
  height: 1px;
  width: 100%;
  grid-column: 1/-1;
  background: var(--border-high);
  margin-top: 6px;
}
#app-mount .menu-2TXYjN .customItem-1KYL7t {
  width: 100%;
}
#app-mount .menu-2TXYjN .button-1zW0-r {
  width: 100%;
  border-radius: var(--rounded);
  background: transparent;
  cursor: var(--cursor);
  padding: 4px 0;
}
#app-mount .menu-2TXYjN .button-1zW0-r:hover {
  background: var(--bg-higher);
}
#app-mount .menu-2TXYjN [role=group]:not(.wrapper--nA0oy, .container-1gYwHN) {
  padding: 6px;
  display: flex;
  flex-direction: column;
  gap: 4px;
}
#app-mount .menu-2TXYjN [role=group]:not(.wrapper--nA0oy, .container-1gYwHN) > .item-5ApiZt:last-child {
  margin-bottom: 0;
}
#app-mount .menu-2TXYjN [role=group]:not(.wrapper--nA0oy, .container-1gYwHN) > .hideInteraction-1vQrZJ {
  padding: 0;
}
#app-mount .menu-2TXYjN [role=separator] {
  margin: 2px 6px;
  border-color: var(--border-high);
}
#app-mount .menu-2TXYjN [role=slider] .grabber-2GQyvM {
  width: 14px;
  height: 14px;
  transform: translateY(0);
}
#app-mount .menu-2TXYjN .groupLabel-16o1xl {
  padding-top: 0;
  padding-bottom: 6px;
  min-height: auto;
}
#app-mount .menu-2TXYjN .item-5ApiZt {
  margin: 0;
  border-radius: var(--rounded);
  padding: 8px 12px;
  cursor: var(--cursor);
  flex-direction: row-reverse;
  gap: 8px;
}
#app-mount .menu-2TXYjN .item-5ApiZt .label-3CEiKJ:only-child {
  order: -1;
}
#app-mount .menu-2TXYjN .item-5ApiZt .iconContainer-Ksy8Oj {
  margin: 0;
  display: flex;
}
#app-mount .menu-2TXYjN .item-5ApiZt .iconContainer-Ksy8Oj svg {
  margin: auto;
}
#app-mount .menu-2TXYjN .item-5ApiZt .icon-3XHs8t {
  color: currentColor;
}
#app-mount .menu-2TXYjN .item-5ApiZt .newBadge-1bHewI {
  font-size: 10px;
  border-radius: var(--rounded);
  margin-top: -4px;
  font-weight: 500;
  padding: 0 4px;
}
#app-mount .menu-2TXYjN .item-5ApiZt.hideInteraction-2jPGL_ {
  padding: 0;
}
#app-mount .menu-2TXYjN .item-5ApiZt.focused-3LIdPu, #app-mount .menu-2TXYjN .item-5ApiZt:active:not(.hideInteraction-2jPGL_) {
  background: var(--bg-menu-item);
  color: var(--text-primary) !important;
}
#app-mount .menu-2TXYjN .item-5ApiZt.colorPremium-vwmYZQ {
  color: hsl(var(--discord-pink));
}
#app-mount .menu-2TXYjN .item-5ApiZt.colorBrand-3cPPsm {
  color: rgb(var(--accent));
}
#app-mount .menu-2TXYjN [role=menuitemcheckbox],
#app-mount .menu-2TXYjN [role=menuitemradio], #app-mount .menu-2TXYjN > div > div:not([class]) + div:not([class]) .item-5ApiZt {
  flex-direction: row;
}
#app-mount .menu-2TXYjN .submenuContainer-3EVTeH .item-5ApiZt {
  flex-direction: row;
}
#app-mount .menu-2TXYjN .submenuContainer-3EVTeH .layer-2aCOJ3 {
  margin-top: -6px;
}

#app-mount .accountProfilePopoutWrapper-3GskID {
  left: 0;
}
#app-mount .accountProfilePopoutWrapper-3GskID .overlayBackground-2aa7wt > .menu-2TXYjN {
  background: transparent;
  padding: 0;
  border: none;
}
#app-mount .scroller-nxCRu_ > [role=group] {
  padding: 0;
}
#app-mount .statusItem-2a1giL {
  padding: 0;
}
#app-mount .description-22_U3B {
  display: none;
}

.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio]) .icon-3XHs8t,
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio]) .iconContainer-Ksy8Oj:has(.icon-3XHs8t):not(:has(path[d*="M18.625"])) {
  display: none !important;
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[aria-haspopup=true] {
  flex-direction: row;
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[role=menuitem]:not([id^=message-add-reaction-])::before, .item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[role=menuitemcheckbox]::before {
  width: 18px;
  height: 18px;
  -webkit-mask-size: cover;
          mask-size: cover;
  -webkit-mask-position: center;
          mask-position: center;
  background: currentColor;
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[role=menuitem]:not([id^=message-add-reaction-]).focused-3qFvc8::before, .item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[role=menuitemcheckbox].focused-3qFvc8::before {
  background: var(--text-primary);
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-edit]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-edit]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-pin]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m16.242 2.932 4.826 4.826a2.75 2.75 0 0 1-.715 4.404l-4.87 2.435a.75.75 0 0 0-.374.426l-1.44 4.166a1.25 1.25 0 0 1-2.065.476L8.5 16.561 4.06 21H3v-1.06l4.44-4.44-3.105-3.104a1.25 1.25 0 0 1 .476-2.066l4.166-1.44a.75.75 0 0 0 .426-.373l2.435-4.87a2.75 2.75 0 0 1 4.405-.715Zm3.766 5.886-4.826-4.826a1.25 1.25 0 0 0-2.002.325l-2.435 4.871a2.25 2.25 0 0 1-1.278 1.12l-3.789 1.31 6.705 6.704 1.308-3.789a2.25 2.25 0 0 1 1.12-1.277l4.872-2.436a1.25 1.25 0 0 0 .325-2.002Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m16.242 2.932 4.826 4.826a2.75 2.75 0 0 1-.715 4.404l-4.87 2.435a.75.75 0 0 0-.374.426l-1.44 4.166a1.25 1.25 0 0 1-2.065.476L8.5 16.561 4.06 21H3v-1.06l4.44-4.44-3.105-3.104a1.25 1.25 0 0 1 .476-2.066l4.166-1.44a.75.75 0 0 0 .426-.373l2.435-4.87a2.75 2.75 0 0 1 4.405-.715Zm3.766 5.886-4.826-4.826a1.25 1.25 0 0 0-2.002.325l-2.435 4.871a2.25 2.25 0 0 1-1.278 1.12l-3.789 1.31 6.705 6.704 1.308-3.789a2.25 2.25 0 0 1 1.12-1.277l4.872-2.436a1.25 1.25 0 0 0 .325-2.002Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-pin]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m16.242 2.932 4.826 4.826a2.75 2.75 0 0 1-.715 4.404l-4.87 2.435a.75.75 0 0 0-.374.426l-1.44 4.166a1.25 1.25 0 0 1-2.065.476L8.5 16.561 4.06 21H3v-1.06l4.44-4.44-3.105-3.104a1.25 1.25 0 0 1 .476-2.066l4.166-1.44a.75.75 0 0 0 .426-.373l2.435-4.87a2.75 2.75 0 0 1 4.405-.715Zm3.766 5.886-4.826-4.826a1.25 1.25 0 0 0-2.002.325l-2.435 4.871a2.25 2.25 0 0 1-1.278 1.12l-3.789 1.31 6.705 6.704 1.308-3.789a2.25 2.25 0 0 1 1.12-1.277l4.872-2.436a1.25 1.25 0 0 0 .325-2.002Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m16.242 2.932 4.826 4.826a2.75 2.75 0 0 1-.715 4.404l-4.87 2.435a.75.75 0 0 0-.374.426l-1.44 4.166a1.25 1.25 0 0 1-2.065.476L8.5 16.561 4.06 21H3v-1.06l4.44-4.44-3.105-3.104a1.25 1.25 0 0 1 .476-2.066l4.166-1.44a.75.75 0 0 0 .426-.373l2.435-4.87a2.75 2.75 0 0 1 4.405-.715Zm3.766 5.886-4.826-4.826a1.25 1.25 0 0 0-2.002.325l-2.435 4.871a2.25 2.25 0 0 1-1.278 1.12l-3.789 1.31 6.705 6.704 1.308-3.789a2.25 2.25 0 0 1 1.12-1.277l4.872-2.436a1.25 1.25 0 0 0 .325-2.002Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-reply]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.277 16.221a.75.75 0 0 1-1.061 1.06l-4.997-5.003a.75.75 0 0 1 0-1.06L8.217 6.22a.75.75 0 0 1 1.061 1.06L5.557 11h7.842c1.595 0 2.81.242 3.889.764l.246.126a6.203 6.203 0 0 1 2.576 2.576c.61 1.14.89 2.418.89 4.135a.75.75 0 0 1-1.5 0c0-1.484-.228-2.52-.713-3.428a4.702 4.702 0 0 0-1.96-1.96c-.838-.448-1.786-.676-3.094-.709L13.4 12.5H5.562l3.715 3.721Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.277 16.221a.75.75 0 0 1-1.061 1.06l-4.997-5.003a.75.75 0 0 1 0-1.06L8.217 6.22a.75.75 0 0 1 1.061 1.06L5.557 11h7.842c1.595 0 2.81.242 3.889.764l.246.126a6.203 6.203 0 0 1 2.576 2.576c.61 1.14.89 2.418.89 4.135a.75.75 0 0 1-1.5 0c0-1.484-.228-2.52-.713-3.428a4.702 4.702 0 0 0-1.96-1.96c-.838-.448-1.786-.676-3.094-.709L13.4 12.5H5.562l3.715 3.721Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-thread]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.009 5.009A3.25 3.25 0 0 1 8.25 2h9A4.75 4.75 0 0 1 22 6.75v6a3.25 3.25 0 0 1-3.009 3.241A3.25 3.25 0 0 1 15.75 19h-5.083L7 21.75c-.824.618-2 .03-2-1v-1.76a3.25 3.25 0 0 1-3-3.24v-7.5a3.25 3.25 0 0 1 3.009-3.241ZM6.518 5h9.232A3.25 3.25 0 0 1 19 8.25v6.232a1.75 1.75 0 0 0 1.5-1.732v-6a3.25 3.25 0 0 0-3.25-3.25h-9A1.75 1.75 0 0 0 6.518 5ZM5.25 17.5H6.5v2.75l3.667-2.75h5.583a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 8.25v7.5c0 .966.784 1.75 1.75 1.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.009 5.009A3.25 3.25 0 0 1 8.25 2h9A4.75 4.75 0 0 1 22 6.75v6a3.25 3.25 0 0 1-3.009 3.241A3.25 3.25 0 0 1 15.75 19h-5.083L7 21.75c-.824.618-2 .03-2-1v-1.76a3.25 3.25 0 0 1-3-3.24v-7.5a3.25 3.25 0 0 1 3.009-3.241ZM6.518 5h9.232A3.25 3.25 0 0 1 19 8.25v6.232a1.75 1.75 0 0 0 1.5-1.732v-6a3.25 3.25 0 0 0-3.25-3.25h-9A1.75 1.75 0 0 0 6.518 5ZM5.25 17.5H6.5v2.75l3.667-2.75h5.583a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 8.25v7.5c0 .966.784 1.75 1.75 1.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-thread]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.009 5.009A3.25 3.25 0 0 1 8.25 2h9A4.75 4.75 0 0 1 22 6.75v6a3.25 3.25 0 0 1-3.009 3.241A3.25 3.25 0 0 1 15.75 19h-5.083L7 21.75c-.824.618-2 .03-2-1v-1.76a3.25 3.25 0 0 1-3-3.24v-7.5a3.25 3.25 0 0 1 3.009-3.241ZM6.518 5h9.232A3.25 3.25 0 0 1 19 8.25v6.232a1.75 1.75 0 0 0 1.5-1.732v-6a3.25 3.25 0 0 0-3.25-3.25h-9A1.75 1.75 0 0 0 6.518 5ZM5.25 17.5H6.5v2.75l3.667-2.75h5.583a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 8.25v7.5c0 .966.784 1.75 1.75 1.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.009 5.009A3.25 3.25 0 0 1 8.25 2h9A4.75 4.75 0 0 1 22 6.75v6a3.25 3.25 0 0 1-3.009 3.241A3.25 3.25 0 0 1 15.75 19h-5.083L7 21.75c-.824.618-2 .03-2-1v-1.76a3.25 3.25 0 0 1-3-3.24v-7.5a3.25 3.25 0 0 1 3.009-3.241ZM6.518 5h9.232A3.25 3.25 0 0 1 19 8.25v6.232a1.75 1.75 0 0 0 1.5-1.732v-6a3.25 3.25 0 0 0-3.25-3.25h-9A1.75 1.75 0 0 0 6.518 5ZM5.25 17.5H6.5v2.75l3.667-2.75h5.583a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 8.25v7.5c0 .966.784 1.75 1.75 1.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-mark-unread]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.022 3a6.473 6.473 0 0 0-.709 1.5H5.25A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75h6.236a1.75 1.75 0 0 0 1.75-1.75l.001-2.483a6.517 6.517 0 0 0 1.5-1.077L22 14.75A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3h6.772ZM17.5 1a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-2.784 2.589-.07.057-.057.07a.5.5 0 0 0 0 .568l.057.07L16.793 6.5l-2.147 2.146-.057.07a.5.5 0 0 0 0 .568l.057.07.07.057a.5.5 0 0 0 .568 0l.07-.057L17.5 7.207l2.146 2.147.07.057a.5.5 0 0 0 .568 0l.07-.057.057-.07a.5.5 0 0 0 0-.568l-.057-.07L18.207 6.5l2.147-2.146.057-.07a.5.5 0 0 0 0-.568l-.057-.07-.07-.057a.5.5 0 0 0-.568 0l-.07.057L17.5 5.793l-2.146-2.147-.07-.057a.5.5 0 0 0-.492-.044l-.076.044Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.022 3a6.473 6.473 0 0 0-.709 1.5H5.25A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75h6.236a1.75 1.75 0 0 0 1.75-1.75l.001-2.483a6.517 6.517 0 0 0 1.5-1.077L22 14.75A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3h6.772ZM17.5 1a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-2.784 2.589-.07.057-.057.07a.5.5 0 0 0 0 .568l.057.07L16.793 6.5l-2.147 2.146-.057.07a.5.5 0 0 0 0 .568l.057.07.07.057a.5.5 0 0 0 .568 0l.07-.057L17.5 7.207l2.146 2.147.07.057a.5.5 0 0 0 .568 0l.07-.057.057-.07a.5.5 0 0 0 0-.568l-.057-.07L18.207 6.5l2.147-2.146.057-.07a.5.5 0 0 0 0-.568l-.057-.07-.07-.057a.5.5 0 0 0-.568 0l-.07.057L17.5 5.793l-2.146-2.147-.07-.057a.5.5 0 0 0-.492-.044l-.076.044Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-copy-link]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.25 7a.75.75 0 0 1 .11 1.492l-.11.008H7a3.5 3.5 0 0 0-.206 6.994L7 15.5h2.25a.75.75 0 0 1 .11 1.492L9.25 17H7a5 5 0 0 1-.25-9.994L7 7h2.25ZM17 7a5 5 0 0 1 .25 9.994L17 17h-2.25a.75.75 0 0 1-.11-1.492l.11-.008H17a3.5 3.5 0 0 0 .206-6.994L17 8.5h-2.25a.75.75 0 0 1-.11-1.492L14.75 7H17ZM7 11.25h10a.75.75 0 0 1 .102 1.493L17 12.75H7a.75.75 0 0 1-.102-1.493L7 11.25h10H7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.25 7a.75.75 0 0 1 .11 1.492l-.11.008H7a3.5 3.5 0 0 0-.206 6.994L7 15.5h2.25a.75.75 0 0 1 .11 1.492L9.25 17H7a5 5 0 0 1-.25-9.994L7 7h2.25ZM17 7a5 5 0 0 1 .25 9.994L17 17h-2.25a.75.75 0 0 1-.11-1.492l.11-.008H17a3.5 3.5 0 0 0 .206-6.994L17 8.5h-2.25a.75.75 0 0 1-.11-1.492L14.75 7H17ZM7 11.25h10a.75.75 0 0 1 .102 1.493L17 12.75H7a.75.75 0 0 1-.102-1.493L7 11.25h10H7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-copy-text]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5 4.75A.75.75 0 0 1 5.75 4h12.5a.75.75 0 0 1 .75.75v2a.75.75 0 0 1-1.5 0V5.5h-4.75v13h1.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5h1.5v-13H6.5v1.25a.75.75 0 0 1-1.5 0v-2Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5 4.75A.75.75 0 0 1 5.75 4h12.5a.75.75 0 0 1 .75.75v2a.75.75 0 0 1-1.5 0V5.5h-4.75v13h1.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5h1.5v-13H6.5v1.25a.75.75 0 0 1-1.5 0v-2Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-tts]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15 4.25c0-1.079-1.274-1.65-2.08-.934L8.427 7.309a.75.75 0 0 1-.498.19H4.25A2.25 2.25 0 0 0 2 9.749v4.497a2.25 2.25 0 0 0 2.25 2.25h3.68a.75.75 0 0 1 .498.19l4.491 3.994c.806.716 2.081.144 2.081-.934V4.25ZM9.425 8.43 13.5 4.807v14.382l-4.075-3.624a2.25 2.25 0 0 0-1.495-.569H4.25a.75.75 0 0 1-.75-.75V9.75a.75.75 0 0 1 .75-.75h3.68a2.25 2.25 0 0 0 1.495-.569ZM18.992 5.897a.75.75 0 0 1 1.049.157A9.959 9.959 0 0 1 22 12a9.96 9.96 0 0 1-1.96 5.946.75.75 0 0 1-1.205-.892A8.459 8.459 0 0 0 20.5 12a8.459 8.459 0 0 0-1.665-5.054.75.75 0 0 1 .157-1.049Z" /><path d="M17.143 8.37a.75.75 0 0 1 1.017.302c.536.99.84 2.125.84 3.328a6.973 6.973 0 0 1-.84 3.328.75.75 0 0 1-1.32-.714c.42-.777.66-1.666.66-2.614s-.24-1.837-.66-2.614a.75.75 0 0 1 .303-1.017Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15 4.25c0-1.079-1.274-1.65-2.08-.934L8.427 7.309a.75.75 0 0 1-.498.19H4.25A2.25 2.25 0 0 0 2 9.749v4.497a2.25 2.25 0 0 0 2.25 2.25h3.68a.75.75 0 0 1 .498.19l4.491 3.994c.806.716 2.081.144 2.081-.934V4.25ZM9.425 8.43 13.5 4.807v14.382l-4.075-3.624a2.25 2.25 0 0 0-1.495-.569H4.25a.75.75 0 0 1-.75-.75V9.75a.75.75 0 0 1 .75-.75h3.68a2.25 2.25 0 0 0 1.495-.569ZM18.992 5.897a.75.75 0 0 1 1.049.157A9.959 9.959 0 0 1 22 12a9.96 9.96 0 0 1-1.96 5.946.75.75 0 0 1-1.205-.892A8.459 8.459 0 0 0 20.5 12a8.459 8.459 0 0 0-1.665-5.054.75.75 0 0 1 .157-1.049Z" /><path d="M17.143 8.37a.75.75 0 0 1 1.017.302c.536.99.84 2.125.84 3.328a6.973 6.973 0 0 1-.84 3.328.75.75 0 0 1-1.32-.714c.42-.777.66-1.666.66-2.614s-.24-1.837-.66-2.614a.75.75 0 0 1 .303-1.017Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-delete]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.75a3.25 3.25 0 0 1 3.245 3.066L15.25 5h5.25a.75.75 0 0 1 .102 1.493L20.5 6.5h-.796l-1.28 13.02a2.75 2.75 0 0 1-2.561 2.474l-.176.006H8.313a2.75 2.75 0 0 1-2.714-2.307l-.023-.174L4.295 6.5H3.5a.75.75 0 0 1-.743-.648L2.75 5.75a.75.75 0 0 1 .648-.743L3.5 5h5.25A3.25 3.25 0 0 1 12 1.75Zm6.197 4.75H5.802l1.267 12.872a1.25 1.25 0 0 0 1.117 1.122l.127.006h7.374c.6 0 1.109-.425 1.225-1.002l.02-.126L18.196 6.5ZM13.75 9.25a.75.75 0 0 1 .743.648L14.5 10v7a.75.75 0 0 1-1.493.102L13 17v-7a.75.75 0 0 1 .75-.75Zm-3.5 0a.75.75 0 0 1 .743.648L11 10v7a.75.75 0 0 1-1.493.102L9.5 17v-7a.75.75 0 0 1 .75-.75Zm1.75-6a1.75 1.75 0 0 0-1.744 1.606L10.25 5h3.5A1.75 1.75 0 0 0 12 3.25Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.75a3.25 3.25 0 0 1 3.245 3.066L15.25 5h5.25a.75.75 0 0 1 .102 1.493L20.5 6.5h-.796l-1.28 13.02a2.75 2.75 0 0 1-2.561 2.474l-.176.006H8.313a2.75 2.75 0 0 1-2.714-2.307l-.023-.174L4.295 6.5H3.5a.75.75 0 0 1-.743-.648L2.75 5.75a.75.75 0 0 1 .648-.743L3.5 5h5.25A3.25 3.25 0 0 1 12 1.75Zm6.197 4.75H5.802l1.267 12.872a1.25 1.25 0 0 0 1.117 1.122l.127.006h7.374c.6 0 1.109-.425 1.225-1.002l.02-.126L18.196 6.5ZM13.75 9.25a.75.75 0 0 1 .743.648L14.5 10v7a.75.75 0 0 1-1.493.102L13 17v-7a.75.75 0 0 1 .75-.75Zm-3.5 0a.75.75 0 0 1 .743.648L11 10v7a.75.75 0 0 1-1.493.102L9.5 17v-7a.75.75 0 0 1 .75-.75Zm1.75-6a1.75 1.75 0 0 0-1.744 1.606L10.25 5h3.5A1.75 1.75 0 0 0 12 3.25Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-delete]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.75a3.25 3.25 0 0 1 3.245 3.066L15.25 5h5.25a.75.75 0 0 1 .102 1.493L20.5 6.5h-.796l-1.28 13.02a2.75 2.75 0 0 1-2.561 2.474l-.176.006H8.313a2.75 2.75 0 0 1-2.714-2.307l-.023-.174L4.295 6.5H3.5a.75.75 0 0 1-.743-.648L2.75 5.75a.75.75 0 0 1 .648-.743L3.5 5h5.25A3.25 3.25 0 0 1 12 1.75Zm6.197 4.75H5.802l1.267 12.872a1.25 1.25 0 0 0 1.117 1.122l.127.006h7.374c.6 0 1.109-.425 1.225-1.002l.02-.126L18.196 6.5ZM13.75 9.25a.75.75 0 0 1 .743.648L14.5 10v7a.75.75 0 0 1-1.493.102L13 17v-7a.75.75 0 0 1 .75-.75Zm-3.5 0a.75.75 0 0 1 .743.648L11 10v7a.75.75 0 0 1-1.493.102L9.5 17v-7a.75.75 0 0 1 .75-.75Zm1.75-6a1.75 1.75 0 0 0-1.744 1.606L10.25 5h3.5A1.75 1.75 0 0 0 12 3.25Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.75a3.25 3.25 0 0 1 3.245 3.066L15.25 5h5.25a.75.75 0 0 1 .102 1.493L20.5 6.5h-.796l-1.28 13.02a2.75 2.75 0 0 1-2.561 2.474l-.176.006H8.313a2.75 2.75 0 0 1-2.714-2.307l-.023-.174L4.295 6.5H3.5a.75.75 0 0 1-.743-.648L2.75 5.75a.75.75 0 0 1 .648-.743L3.5 5h5.25A3.25 3.25 0 0 1 12 1.75Zm6.197 4.75H5.802l1.267 12.872a1.25 1.25 0 0 0 1.117 1.122l.127.006h7.374c.6 0 1.109-.425 1.225-1.002l.02-.126L18.196 6.5ZM13.75 9.25a.75.75 0 0 1 .743.648L14.5 10v7a.75.75 0 0 1-1.493.102L13 17v-7a.75.75 0 0 1 .75-.75Zm-3.5 0a.75.75 0 0 1 .743.648L11 10v7a.75.75 0 0 1-1.493.102L9.5 17v-7a.75.75 0 0 1 .75-.75Zm1.75-6a1.75 1.75 0 0 0-1.744 1.606L10.25 5h3.5A1.75 1.75 0 0 0 12 3.25Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-devmode-copy-id]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-report]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.907 5.622c.062.208.093.424.093.641V17.74a2.25 2.25 0 0 1-2.891 2.156l-5.514-1.64a4.002 4.002 0 0 1-7.59-1.556L6 16.5l-.001-.5-2.39-.711A2.25 2.25 0 0 1 2 13.131V10.87a2.25 2.25 0 0 1 1.61-2.156l15.5-4.606a2.25 2.25 0 0 1 2.797 1.515ZM7.499 16.445l.001.054a2.5 2.5 0 0 0 4.624 1.321l-4.625-1.375Zm12.037-10.9-15.5 4.605a.75.75 0 0 0-.536.72v2.261a.75.75 0 0 0 .536.72l15.5 4.607a.75.75 0 0 0 .964-.72V6.264a.75.75 0 0 0-.964-.719Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.907 5.622c.062.208.093.424.093.641V17.74a2.25 2.25 0 0 1-2.891 2.156l-5.514-1.64a4.002 4.002 0 0 1-7.59-1.556L6 16.5l-.001-.5-2.39-.711A2.25 2.25 0 0 1 2 13.131V10.87a2.25 2.25 0 0 1 1.61-2.156l15.5-4.606a2.25 2.25 0 0 1 2.797 1.515ZM7.499 16.445l.001.054a2.5 2.5 0 0 0 4.624 1.321l-4.625-1.375Zm12.037-10.9-15.5 4.605a.75.75 0 0 0-.536.72v2.261a.75.75 0 0 0 .536.72l15.5 4.607a.75.75 0 0 0 .964-.72V6.264a.75.75 0 0 0-.964-.719Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-mark-channel-read]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-user-profile]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.754 14a2.249 2.249 0 0 1 2.25 2.249v.575c0 .894-.32 1.76-.902 2.438-1.57 1.834-3.957 2.739-7.102 2.739-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h11.501Zm0 1.5H6.253a.749.749 0 0 0-.75.749v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214s4.706-.746 5.962-2.214a2.25 2.25 0 0 0 .541-1.463v-.575a.749.749 0 0 0-.749-.75ZM12 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.754 14a2.249 2.249 0 0 1 2.25 2.249v.575c0 .894-.32 1.76-.902 2.438-1.57 1.834-3.957 2.739-7.102 2.739-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h11.501Zm0 1.5H6.253a.749.749 0 0 0-.75.749v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214s4.706-.746 5.962-2.214a2.25 2.25 0 0 0 .541-1.463v-.575a.749.749 0 0 0-.749-.75ZM12 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-mention]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.068-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2Zm0 1.5A8.5 8.5 0 0 0 3.5 12c0 1.47.373 2.883 1.073 4.137l.15.27-1.112 3.984 3.987-1.112.27.15A8.5 8.5 0 1 0 12 3.5ZM8.75 13h4.498a.75.75 0 0 1 .102 1.493l-.102.007H8.75a.75.75 0 0 1-.102-1.493L8.75 13h4.498H8.75Zm0-3.5h6.505a.75.75 0 0 1 .101 1.493l-.101.007H8.75a.75.75 0 0 1-.102-1.493L8.75 9.5h6.505H8.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.068-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2Zm0 1.5A8.5 8.5 0 0 0 3.5 12c0 1.47.373 2.883 1.073 4.137l.15.27-1.112 3.984 3.987-1.112.27.15A8.5 8.5 0 1 0 12 3.5ZM8.75 13h4.498a.75.75 0 0 1 .102 1.493l-.102.007H8.75a.75.75 0 0 1-.102-1.493L8.75 13h4.498H8.75Zm0-3.5h6.505a.75.75 0 0 1 .101 1.493l-.101.007H8.75a.75.75 0 0 1-.102-1.493L8.75 9.5h6.505H8.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-message-user]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.25 18A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3h13.5A3.25 3.25 0 0 1 22 6.25v8.5A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75Zm7.264-1.5h6.236a1.75 1.75 0 0 0 1.75-1.75v-8.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.25 18A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3h13.5A3.25 3.25 0 0 1 22 6.25v8.5A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75Zm7.264-1.5h6.236a1.75 1.75 0 0 0 1.75-1.75v-8.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-call]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m7.056 2.418 1.167-.351a2.75 2.75 0 0 1 3.302 1.505l.902 2.006a2.75 2.75 0 0 1-.633 3.139L10.3 10.11a.25.25 0 0 0-.078.155c-.044.397.225 1.17.845 2.245.451.781.86 1.33 1.207 1.637.242.215.375.261.432.245l2.01-.615a2.75 2.75 0 0 1 3.034 1.02l1.281 1.776a2.75 2.75 0 0 1-.339 3.605l-.886.84a3.75 3.75 0 0 1-3.587.889c-2.754-.769-5.223-3.093-7.435-6.924-2.215-3.836-2.992-7.14-2.276-9.913a3.75 3.75 0 0 1 2.548-2.652Zm.433 1.437a2.25 2.25 0 0 0-1.529 1.59c-.602 2.332.087 5.261 2.123 8.788 2.033 3.522 4.222 5.582 6.54 6.23a2.25 2.25 0 0 0 2.151-.534l.887-.84a1.25 1.25 0 0 0 .154-1.639l-1.28-1.775a1.25 1.25 0 0 0-1.38-.464l-2.015.617c-1.17.348-2.232-.593-3.372-2.568C9 11.93 8.642 10.9 8.731 10.099c.047-.416.24-.8.546-1.086l1.494-1.393a1.25 1.25 0 0 0 .288-1.427l-.902-2.006a1.25 1.25 0 0 0-1.5-.684l-1.168.352Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m7.056 2.418 1.167-.351a2.75 2.75 0 0 1 3.302 1.505l.902 2.006a2.75 2.75 0 0 1-.633 3.139L10.3 10.11a.25.25 0 0 0-.078.155c-.044.397.225 1.17.845 2.245.451.781.86 1.33 1.207 1.637.242.215.375.261.432.245l2.01-.615a2.75 2.75 0 0 1 3.034 1.02l1.281 1.776a2.75 2.75 0 0 1-.339 3.605l-.886.84a3.75 3.75 0 0 1-3.587.889c-2.754-.769-5.223-3.093-7.435-6.924-2.215-3.836-2.992-7.14-2.276-9.913a3.75 3.75 0 0 1 2.548-2.652Zm.433 1.437a2.25 2.25 0 0 0-1.529 1.59c-.602 2.332.087 5.261 2.123 8.788 2.033 3.522 4.222 5.582 6.54 6.23a2.25 2.25 0 0 0 2.151-.534l.887-.84a1.25 1.25 0 0 0 .154-1.639l-1.28-1.775a1.25 1.25 0 0 0-1.38-.464l-2.015.617c-1.17.348-2.232-.593-3.372-2.568C9 11.93 8.642 10.9 8.731 10.099c.047-.416.24-.8.546-1.086l1.494-1.393a1.25 1.25 0 0 0 .288-1.427l-.902-2.006a1.25 1.25 0 0 0-1.5-.684l-1.168.352Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-note]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v6.879a2.25 2.25 0 0 1-.659 1.59l-5.621 5.622a2.25 2.25 0 0 1-1.591.659H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm0 1.5H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75H13v-3.25a3.25 3.25 0 0 1 3.066-3.245L16.25 13h3.25V6.25a1.75 1.75 0 0 0-1.75-1.75Zm.689 10H16.25a1.75 1.75 0 0 0-1.744 1.607l-.006.143v2.189l3.939-3.939Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v6.879a2.25 2.25 0 0 1-.659 1.59l-5.621 5.622a2.25 2.25 0 0 1-1.591.659H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm0 1.5H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75H13v-3.25a3.25 3.25 0 0 1 3.066-3.245L16.25 13h3.25V6.25a1.75 1.75 0 0 0-1.75-1.75Zm.689 10H16.25a1.75 1.75 0 0 0-1.744 1.607l-.006.143v2.189l3.939-3.939Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-close-dm]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.022 3a6.473 6.473 0 0 0-.709 1.5H5.25A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75h6.236a1.75 1.75 0 0 0 1.75-1.75l.001-2.483a6.517 6.517 0 0 0 1.5-1.077L22 14.75A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3h6.772ZM17.5 1a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-2.784 2.589-.07.057-.057.07a.5.5 0 0 0 0 .568l.057.07L16.793 6.5l-2.147 2.146-.057.07a.5.5 0 0 0 0 .568l.057.07.07.057a.5.5 0 0 0 .568 0l.07-.057L17.5 7.207l2.146 2.147.07.057a.5.5 0 0 0 .568 0l.07-.057.057-.07a.5.5 0 0 0 0-.568l-.057-.07L18.207 6.5l2.147-2.146.057-.07a.5.5 0 0 0 0-.568l-.057-.07-.07-.057a.5.5 0 0 0-.568 0l-.07.057L17.5 5.793l-2.146-2.147-.07-.057a.5.5 0 0 0-.492-.044l-.076.044Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.022 3a6.473 6.473 0 0 0-.709 1.5H5.25A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75h6.236a1.75 1.75 0 0 0 1.75-1.75l.001-2.483a6.517 6.517 0 0 0 1.5-1.077L22 14.75A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3h6.772ZM17.5 1a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-2.784 2.589-.07.057-.057.07a.5.5 0 0 0 0 .568l.057.07L16.793 6.5l-2.147 2.146-.057.07a.5.5 0 0 0 0 .568l.057.07.07.057a.5.5 0 0 0 .568 0l.07-.057L17.5 7.207l2.146 2.147.07.057a.5.5 0 0 0 .568 0l.07-.057.057-.07a.5.5 0 0 0 0-.568l-.057-.07L18.207 6.5l2.147-2.146.057-.07a.5.5 0 0 0 0-.568l-.057-.07-.07-.057a.5.5 0 0 0-.568 0l-.07.057L17.5 5.793l-2.146-2.147-.07-.057a.5.5 0 0 0-.492-.044l-.076.044Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-change-nickname]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.75 2h3.998a.75.75 0 0 1 .102 1.493l-.102.007H12.5v17h1.245a.75.75 0 0 1 .743.648l.007.102a.75.75 0 0 1-.648.743l-.102.007H9.75a.75.75 0 0 1-.102-1.493l.102-.007H11v-17H9.75a.75.75 0 0 1-.743-.648L9 2.75a.75.75 0 0 1 .648-.743L9.75 2h3.998H9.75Zm8.496 2.997a3.253 3.253 0 0 1 3.25 3.25l.004 7.504a3.249 3.249 0 0 1-3.064 3.246l-.186.005h-4.745v-1.5h4.803A1.749 1.749 0 0 0 20 15.751l-.003-7.505a1.753 1.753 0 0 0-1.752-1.75h-4.74v-1.5h4.74Zm-8.246 0v1.5H5.25a1.75 1.75 0 0 0-1.75 1.75v7.504c0 .967.784 1.75 1.75 1.75h4.745v1.5H5.25A3.25 3.25 0 0 1 2 15.751V8.247a3.25 3.25 0 0 1 3.25-3.25H10Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.75 2h3.998a.75.75 0 0 1 .102 1.493l-.102.007H12.5v17h1.245a.75.75 0 0 1 .743.648l.007.102a.75.75 0 0 1-.648.743l-.102.007H9.75a.75.75 0 0 1-.102-1.493l.102-.007H11v-17H9.75a.75.75 0 0 1-.743-.648L9 2.75a.75.75 0 0 1 .648-.743L9.75 2h3.998H9.75Zm8.496 2.997a3.253 3.253 0 0 1 3.25 3.25l.004 7.504a3.249 3.249 0 0 1-3.064 3.246l-.186.005h-4.745v-1.5h4.803A1.749 1.749 0 0 0 20 15.751l-.003-7.505a1.753 1.753 0 0 0-1.752-1.75h-4.74v-1.5h4.74Zm-8.246 0v1.5H5.25a1.75 1.75 0 0 0-1.75 1.75v7.504c0 .967.784 1.75 1.75 1.75h4.745v1.5H5.25A3.25 3.25 0 0 1 2 15.751V8.247a3.25 3.25 0 0 1 3.25-3.25H10Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-invite-to-server]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M11.75 3a.75.75 0 0 1 .743.648l.007.102.001 7.25h7.253a.75.75 0 0 1 .102 1.493l-.102.007h-7.253l.002 7.25a.75.75 0 0 1-1.493.101l-.007-.102-.002-7.249H3.752a.75.75 0 0 1-.102-1.493L3.752 11h7.25L11 3.75a.75.75 0 0 1 .75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M11.75 3a.75.75 0 0 1 .743.648l.007.102.001 7.25h7.253a.75.75 0 0 1 .102 1.493l-.102.007h-7.253l.002 7.25a.75.75 0 0 1-1.493.101l-.007-.102-.002-7.249H3.752a.75.75 0 0 1-.102-1.493L3.752 11h7.25L11 3.75a.75.75 0 0 1 .75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-add-friend]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-remove-friend]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm3.071.966-.07.058-.057.07a.5.5 0 0 0 0 .568l.058.069 1.77 1.77-1.768 1.766-.057.07a.5.5 0 0 0 0 .568l.058.07.069.057a.5.5 0 0 0 .568 0l.07-.058 1.766-1.767 1.77 1.77.069.058a.5.5 0 0 0 .568 0l.07-.058.058-.07a.5.5 0 0 0 0-.568l-.058-.07-1.77-1.768 1.772-1.77.058-.07a.5.5 0 0 0 0-.568l-.058-.069-.069-.058a.5.5 0 0 0-.569 0l-.069.058-1.771 1.77-1.77-1.77-.07-.058a.5.5 0 0 0-.492-.043l-.076.043ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm3.071.966-.07.058-.057.07a.5.5 0 0 0 0 .568l.058.069 1.77 1.77-1.768 1.766-.057.07a.5.5 0 0 0 0 .568l.058.07.069.057a.5.5 0 0 0 .568 0l.07-.058 1.766-1.767 1.77 1.77.069.058a.5.5 0 0 0 .568 0l.07-.058.058-.07a.5.5 0 0 0 0-.568l-.058-.07-1.77-1.768 1.772-1.77.058-.07a.5.5 0 0 0 0-.568l-.058-.069-.069-.058a.5.5 0 0 0-.569 0l-.069.058-1.771 1.77-1.77-1.77-.07-.058a.5.5 0 0 0-.492-.043l-.076.043ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-block]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm8.787 1.252-5.557 5.557a4 4 0 0 0 5.557-5.557ZM17.5 13.5a4 4 0 0 0-3.31 6.247l5.558-5.556A3.982 3.982 0 0 0 17.5 13.5ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm8.787 1.252-5.557 5.557a4 4 0 0 0 5.557-5.557ZM17.5 13.5a4 4 0 0 0-3.31 6.247l5.558-5.556A3.982 3.982 0 0 0 17.5 13.5ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-mute]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-disable-video]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3.28 2.22a.75.75 0 1 0-1.06 1.06l1.567 1.567A3.25 3.25 0 0 0 2 7.75v8.5a3.25 3.25 0 0 0 3.25 3.25h8.5a3.25 3.25 0 0 0 2.903-1.786l4.066 4.067a.75.75 0 0 0 1.061-1.061L3.28 2.22Zm12.196 14.317A1.75 1.75 0 0 1 13.75 18h-8.5a1.75 1.75 0 0 1-1.75-1.75v-8.5c0-.869.633-1.59 1.463-1.727l10.514 10.514ZM15.5 12.318V7.75A1.75 1.75 0 0 0 13.75 6H9.182l-1.5-1.5h6.068A3.25 3.25 0 0 1 17 7.75v.173l3.864-2.318A.75.75 0 0 1 22 6.248V17.75c0 .301-.17.543-.403.665L20.5 17.318V7.573L17 9.674v4.144l-1.5-1.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3.28 2.22a.75.75 0 1 0-1.06 1.06l1.567 1.567A3.25 3.25 0 0 0 2 7.75v8.5a3.25 3.25 0 0 0 3.25 3.25h8.5a3.25 3.25 0 0 0 2.903-1.786l4.066 4.067a.75.75 0 0 0 1.061-1.061L3.28 2.22Zm12.196 14.317A1.75 1.75 0 0 1 13.75 18h-8.5a1.75 1.75 0 0 1-1.75-1.75v-8.5c0-.869.633-1.59 1.463-1.727l10.514 10.514ZM15.5 12.318V7.75A1.75 1.75 0 0 0 13.75 6H9.182l-1.5-1.5h6.068A3.25 3.25 0 0 1 17 7.75v.173l3.864-2.318A.75.75 0 0 1 22 6.248V17.75c0 .301-.17.543-.403.665L20.5 17.318V7.573L17 9.674v4.144l-1.5-1.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-voice-mute]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3.28 2.22a.75.75 0 1 0-1.06 1.06L8 9.06V12a4 4 0 0 0 6.248 3.309l1.146 1.146A5.227 5.227 0 0 1 12.25 17.5h-.5l-.216-.004A5.25 5.25 0 0 1 6.5 12.25v-.5l-.007-.102A.75.75 0 0 0 5 11.75v.5l.004.236a6.75 6.75 0 0 0 6.246 6.496v2.268l.007.102a.75.75 0 0 0 1.493-.102l.001-2.268a6.718 6.718 0 0 0 3.712-1.458l4.256 4.256a.75.75 0 0 0 1.061-1.06L3.28 2.22Zm9.876 11.997A2.5 2.5 0 0 1 9.5 12v-1.44l3.656 3.657ZM14.5 6v5.318l1.43 1.43c.046-.242.07-.492.07-.748V6a4 4 0 0 0-7.862-1.044L9.5 6.318V6a2.5 2.5 0 0 1 5 0ZM17.196 14.014l1.146 1.146A6.725 6.725 0 0 0 19 12.25v-.5l-.007-.102a.75.75 0 0 0-1.493.102v.5l-.004.216a5.233 5.233 0 0 1-.3 1.548Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3.28 2.22a.75.75 0 1 0-1.06 1.06L8 9.06V12a4 4 0 0 0 6.248 3.309l1.146 1.146A5.227 5.227 0 0 1 12.25 17.5h-.5l-.216-.004A5.25 5.25 0 0 1 6.5 12.25v-.5l-.007-.102A.75.75 0 0 0 5 11.75v.5l.004.236a6.75 6.75 0 0 0 6.246 6.496v2.268l.007.102a.75.75 0 0 0 1.493-.102l.001-2.268a6.718 6.718 0 0 0 3.712-1.458l4.256 4.256a.75.75 0 0 0 1.061-1.06L3.28 2.22Zm9.876 11.997A2.5 2.5 0 0 1 9.5 12v-1.44l3.656 3.657ZM14.5 6v5.318l1.43 1.43c.046-.242.07-.492.07-.748V6a4 4 0 0 0-7.862-1.044L9.5 6.318V6a2.5 2.5 0 0 1 5 0ZM17.196 14.014l1.146 1.146A6.725 6.725 0 0 0 19 12.25v-.5l-.007-.102a.75.75 0 0 0-1.493.102v.5l-.004.216a5.233 5.233 0 0 1-.3 1.548Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-voice-deafen]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-timeout]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3.28 2.22a.75.75 0 1 0-1.06 1.06l3.993 3.994a8.5 8.5 0 1 0 12.013 12.013l2.493 2.494a.75.75 0 0 0 1.061-1.061L3.28 2.22Zm13.884 16.005a7 7 0 1 1-9.89-9.89l3.976 3.976v.939l.007.102a.75.75 0 0 0 1.36.325l4.547 4.548ZM11.437 8.255l1.313 1.313V8.75l-.007-.102a.75.75 0 0 0-1.306-.393Z" /><path d="M19 13.5a7 7 0 0 1-.296 2.022l1.174 1.175A8.5 8.5 0 0 0 8.803 5.622l1.175 1.174A7 7 0 0 1 19 13.5Z" /><path d="m19.147 5.114.083.06 1.158.964a.75.75 0 0 1-.877 1.212l-.082-.06-1.159-.964a.75.75 0 0 1 .877-1.212ZM14.25 2.5a.75.75 0 0 1 .102 1.493L14.25 4h-4.5a.75.75 0 0 1-.102-1.493L9.75 2.5h4.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3.28 2.22a.75.75 0 1 0-1.06 1.06l3.993 3.994a8.5 8.5 0 1 0 12.013 12.013l2.493 2.494a.75.75 0 0 0 1.061-1.061L3.28 2.22Zm13.884 16.005a7 7 0 1 1-9.89-9.89l3.976 3.976v.939l.007.102a.75.75 0 0 0 1.36.325l4.547 4.548ZM11.437 8.255l1.313 1.313V8.75l-.007-.102a.75.75 0 0 0-1.306-.393Z" /><path d="M19 13.5a7 7 0 0 1-.296 2.022l1.174 1.175A8.5 8.5 0 0 0 8.803 5.622l1.175 1.174A7 7 0 0 1 19 13.5Z" /><path d="m19.147 5.114.083.06 1.158.964a.75.75 0 0 1-.877 1.212l-.082-.06-1.159-.964a.75.75 0 0 1 .877-1.212ZM14.25 2.5a.75.75 0 0 1 .102 1.493L14.25 4h-4.5a.75.75 0 0 1-.102-1.493L9.75 2.5h4.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-voice-disconnect]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.78 3.28a.75.75 0 0 0-1.06-1.06l-2.012 2.012a4.251 4.251 0 0 0-5.463.462l-1.068 1.069a1.75 1.75 0 0 0 0 2.474l3.585 3.586a1.75 1.75 0 0 0 2.475 0l1.068-1.068a4.251 4.251 0 0 0 .463-5.463L21.78 3.28Zm-3.585 2.475.022.023.003.002.002.003.023.022a2.75 2.75 0 0 1 0 3.89l-1.068 1.067a.25.25 0 0 1-.354 0l-3.586-3.585a.25.25 0 0 1 0-.354l1.068-1.068a2.75 2.75 0 0 1 3.89 0ZM10.78 11.28a.75.75 0 1 0-1.06-1.06L8 11.94l-.47-.47a.75.75 0 0 0-1.06 0l-1.775 1.775a4.251 4.251 0 0 0-.463 5.463L2.22 20.72a.75.75 0 1 0 1.06 1.06l2.012-2.012a4.251 4.251 0 0 0 5.463-.463l1.775-1.775a.75.75 0 0 0 0-1.06l-.47-.47 1.72-1.72a.75.75 0 1 0-1.06-1.06L11 14.94 9.06 13l1.72-1.72Zm-3.314 2.247.004.003.003.004 2.993 2.993.004.003.003.004.466.466-1.244 1.245a2.75 2.75 0 0 1-3.89 0l-.05-.05a2.75 2.75 0 0 1 0-3.89L7 13.062l.466.466Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.78 3.28a.75.75 0 0 0-1.06-1.06l-2.012 2.012a4.251 4.251 0 0 0-5.463.462l-1.068 1.069a1.75 1.75 0 0 0 0 2.474l3.585 3.586a1.75 1.75 0 0 0 2.475 0l1.068-1.068a4.251 4.251 0 0 0 .463-5.463L21.78 3.28Zm-3.585 2.475.022.023.003.002.002.003.023.022a2.75 2.75 0 0 1 0 3.89l-1.068 1.067a.25.25 0 0 1-.354 0l-3.586-3.585a.25.25 0 0 1 0-.354l1.068-1.068a2.75 2.75 0 0 1 3.89 0ZM10.78 11.28a.75.75 0 1 0-1.06-1.06L8 11.94l-.47-.47a.75.75 0 0 0-1.06 0l-1.775 1.775a4.251 4.251 0 0 0-.463 5.463L2.22 20.72a.75.75 0 1 0 1.06 1.06l2.012-2.012a4.251 4.251 0 0 0 5.463-.463l1.775-1.775a.75.75 0 0 0 0-1.06l-.47-.47 1.72-1.72a.75.75 0 1 0-1.06-1.06L11 14.94 9.06 13l1.72-1.72Zm-3.314 2.247.004.003.003.004 2.993 2.993.004.003.003.004.466.466-1.244 1.245a2.75 2.75 0 0 1-3.89 0l-.05-.05a2.75 2.75 0 0 1 0-3.89L7 13.062l.466.466Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-kick]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm3.071.966-.07.058-.057.07a.5.5 0 0 0 0 .568l.058.069 1.77 1.77-1.768 1.766-.057.07a.5.5 0 0 0 0 .568l.058.07.069.057a.5.5 0 0 0 .568 0l.07-.058 1.766-1.767 1.77 1.77.069.058a.5.5 0 0 0 .568 0l.07-.058.058-.07a.5.5 0 0 0 0-.568l-.058-.07-1.77-1.768 1.772-1.77.058-.07a.5.5 0 0 0 0-.568l-.058-.069-.069-.058a.5.5 0 0 0-.569 0l-.069.058-1.771 1.77-1.77-1.77-.07-.058a.5.5 0 0 0-.492-.043l-.076.043ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm3.071.966-.07.058-.057.07a.5.5 0 0 0 0 .568l.058.069 1.77 1.77-1.768 1.766-.057.07a.5.5 0 0 0 0 .568l.058.07.069.057a.5.5 0 0 0 .568 0l.07-.058 1.766-1.767 1.77 1.77.069.058a.5.5 0 0 0 .568 0l.07-.058.058-.07a.5.5 0 0 0 0-.568l-.058-.07-1.77-1.768 1.772-1.77.058-.07a.5.5 0 0 0 0-.568l-.058-.069-.069-.058a.5.5 0 0 0-.569 0l-.069.058-1.771 1.77-1.77-1.77-.07-.058a.5.5 0 0 0-.492-.043l-.076.043ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-ban]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm8.787 1.252-5.557 5.557a4 4 0 0 0 5.557-5.557ZM17.5 13.5a4 4 0 0 0-3.31 6.247l5.558-5.556A3.982 3.982 0 0 0 17.5 13.5ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm8.787 1.252-5.557 5.557a4 4 0 0 0 5.557-5.557ZM17.5 13.5a4 4 0 0 0-3.31 6.247l5.558-5.556A3.982 3.982 0 0 0 17.5 13.5ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-roles]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M19.75 2A2.25 2.25 0 0 1 22 4.25v5.462a3.25 3.25 0 0 1-.952 2.298l-8.5 8.503a3.255 3.255 0 0 1-4.597.001L3.489 16.06a3.25 3.25 0 0 1-.003-4.596l8.5-8.51A3.25 3.25 0 0 1 14.284 2h5.465Zm0 1.5h-5.465c-.465 0-.91.185-1.239.513l-8.512 8.523a1.75 1.75 0 0 0 .015 2.462l4.461 4.454a1.755 1.755 0 0 0 2.477 0l8.5-8.503a1.75 1.75 0 0 0 .513-1.237V4.25a.75.75 0 0 0-.75-.75ZM17 5.502a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M19.75 2A2.25 2.25 0 0 1 22 4.25v5.462a3.25 3.25 0 0 1-.952 2.298l-8.5 8.503a3.255 3.255 0 0 1-4.597.001L3.489 16.06a3.25 3.25 0 0 1-.003-4.596l8.5-8.51A3.25 3.25 0 0 1 14.284 2h5.465Zm0 1.5h-5.465c-.465 0-.91.185-1.239.513l-8.512 8.523a1.75 1.75 0 0 0 .015 2.462l4.461 4.454a1.755 1.755 0 0 0 2.477 0l8.5-8.503a1.75 1.75 0 0 0 .513-1.237V4.25a.75.75 0 0 0-.75-.75ZM17 5.502a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-mute-channel]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-voice-move]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15.28 6.03a.75.75 0 0 1-1.06 0l-1.47-1.47v3.69a.75.75 0 0 1-1.5 0V4.56L9.78 6.03a.75.75 0 0 1-1.06-1.06l2.75-2.75a.75.75 0 0 1 1.06 0l2.75 2.75a.75.75 0 0 1 0 1.06ZM6.03 14.22a.75.75 0 1 1-1.06 1.06l-2.75-2.75a.75.75 0 0 1 0-1.06l2.75-2.75a.75.75 0 0 1 1.06 1.06l-1.47 1.47h3.69a.75.75 0 0 1 0 1.5H4.56l1.47 1.47ZM17.97 15.28a.75.75 0 0 1 0-1.06l1.47-1.47h-3.69a.75.75 0 0 1 0-1.5h3.69l-1.47-1.47a.75.75 0 0 1 1.06-1.06l2.75 2.75a.75.75 0 0 1 0 1.06l-2.75 2.75a.75.75 0 0 1-1.06 0ZM15.28 17.97a.75.75 0 0 0-1.06 0l-1.47 1.47v-3.69a.75.75 0 0 0-1.5 0v3.69l-1.47-1.47a.75.75 0 0 0-1.06 1.06l2.75 2.75a.75.75 0 0 0 1.06 0l2.75-2.75a.75.75 0 0 0 0-1.06Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15.28 6.03a.75.75 0 0 1-1.06 0l-1.47-1.47v3.69a.75.75 0 0 1-1.5 0V4.56L9.78 6.03a.75.75 0 0 1-1.06-1.06l2.75-2.75a.75.75 0 0 1 1.06 0l2.75 2.75a.75.75 0 0 1 0 1.06ZM6.03 14.22a.75.75 0 1 1-1.06 1.06l-2.75-2.75a.75.75 0 0 1 0-1.06l2.75-2.75a.75.75 0 0 1 1.06 1.06l-1.47 1.47h3.69a.75.75 0 0 1 0 1.5H4.56l1.47 1.47ZM17.97 15.28a.75.75 0 0 1 0-1.06l1.47-1.47h-3.69a.75.75 0 0 1 0-1.5h3.69l-1.47-1.47a.75.75 0 0 1 1.06-1.06l2.75 2.75a.75.75 0 0 1 0 1.06l-2.75 2.75a.75.75 0 0 1-1.06 0ZM15.28 17.97a.75.75 0 0 0-1.06 0l-1.47 1.47v-3.69a.75.75 0 0 0-1.5 0v3.69l-1.47-1.47a.75.75 0 0 0-1.06 1.06l2.75 2.75a.75.75 0 0 0 1.06 0l2.75-2.75a.75.75 0 0 0 0-1.06Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-devmode-copy-id]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-add-friend-nickname]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.75 2h3.998a.75.75 0 0 1 .102 1.493l-.102.007H12.5v17h1.245a.75.75 0 0 1 .743.648l.007.102a.75.75 0 0 1-.648.743l-.102.007H9.75a.75.75 0 0 1-.102-1.493l.102-.007H11v-17H9.75a.75.75 0 0 1-.743-.648L9 2.75a.75.75 0 0 1 .648-.743L9.75 2h3.998H9.75Zm8.496 2.997a3.253 3.253 0 0 1 3.25 3.25l.004 7.504a3.249 3.249 0 0 1-3.064 3.246l-.186.005h-4.745v-1.5h4.803A1.749 1.749 0 0 0 20 15.751l-.003-7.505a1.753 1.753 0 0 0-1.752-1.75h-4.74v-1.5h4.74Zm-8.246 0v1.5H5.25a1.75 1.75 0 0 0-1.75 1.75v7.504c0 .967.784 1.75 1.75 1.75h4.745v1.5H5.25A3.25 3.25 0 0 1 2 15.751V8.247a3.25 3.25 0 0 1 3.25-3.25H10Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.75 2h3.998a.75.75 0 0 1 .102 1.493l-.102.007H12.5v17h1.245a.75.75 0 0 1 .743.648l.007.102a.75.75 0 0 1-.648.743l-.102.007H9.75a.75.75 0 0 1-.102-1.493l.102-.007H11v-17H9.75a.75.75 0 0 1-.743-.648L9 2.75a.75.75 0 0 1 .648-.743L9.75 2h3.998H9.75Zm8.496 2.997a3.253 3.253 0 0 1 3.25 3.25l.004 7.504a3.249 3.249 0 0 1-3.064 3.246l-.186.005h-4.745v-1.5h4.803A1.749 1.749 0 0 0 20 15.751l-.003-7.505a1.753 1.753 0 0 0-1.752-1.75h-4.74v-1.5h4.74Zm-8.246 0v1.5H5.25a1.75 1.75 0 0 0-1.75 1.75v7.504c0 .967.784 1.75 1.75 1.75h4.745v1.5H5.25A3.25 3.25 0 0 1 2 15.751V8.247a3.25 3.25 0 0 1 3.25-3.25H10Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-context-soundboard-sound-mute]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-My_Account]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.754 14a2.249 2.249 0 0 1 2.25 2.249v.575c0 .894-.32 1.76-.902 2.438-1.57 1.834-3.957 2.739-7.102 2.739-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h11.501Zm0 1.5H6.253a.749.749 0 0 0-.75.749v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214s4.706-.746 5.962-2.214a2.25 2.25 0 0 0 .541-1.463v-.575a.749.749 0 0 0-.749-.75ZM12 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.754 14a2.249 2.249 0 0 1 2.25 2.249v.575c0 .894-.32 1.76-.902 2.438-1.57 1.834-3.957 2.739-7.102 2.739-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h11.501Zm0 1.5H6.253a.749.749 0 0 0-.75.749v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214s4.706-.746 5.962-2.214a2.25 2.25 0 0 0 .541-1.463v-.575a.749.749 0 0 0-.749-.75ZM12 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Profile_Customization]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm0 7.75a.625.625 0 1 0 0 1.25.625.625 0 0 0 0-1.25Zm0-5.876c-1.048 0-1.864.817-1.853 1.954a.5.5 0 1 0 1-.01c-.006-.579.36-.944.853-.944.473 0 .854.392.854.95 0 .192-.056.342-.224.56l-.094.117-.1.113-.265.29-.136.157c-.384.457-.535.793-.535 1.31a.5.5 0 1 0 1 0c0-.203.059-.359.239-.59l.085-.104.1-.116.267-.29.134-.155c.378-.45.529-.783.529-1.293 0-1.103-.823-1.95-1.854-1.95Zm-5.478.125a6.474 6.474 0 0 0-.708 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214.597 0 1.156-.036 1.68-.106.245.495.553.953.912 1.366-.796.16-1.66.24-2.592.24-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h7.77ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm0 7.75a.625.625 0 1 0 0 1.25.625.625 0 0 0 0-1.25Zm0-5.876c-1.048 0-1.864.817-1.853 1.954a.5.5 0 1 0 1-.01c-.006-.579.36-.944.853-.944.473 0 .854.392.854.95 0 .192-.056.342-.224.56l-.094.117-.1.113-.265.29-.136.157c-.384.457-.535.793-.535 1.31a.5.5 0 1 0 1 0c0-.203.059-.359.239-.59l.085-.104.1-.116.267-.29.134-.155c.378-.45.529-.783.529-1.293 0-1.103-.823-1.95-1.854-1.95Zm-5.478.125a6.474 6.474 0 0 0-.708 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214.597 0 1.156-.036 1.68-.106.245.495.553.953.912 1.366-.796.16-1.66.24-2.592.24-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h7.77ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Privacy___Safety]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M10 2a4 4 0 0 1 4 4v2h1.75A2.25 2.25 0 0 1 18 10.25V11c-.319 0-.637.11-.896.329l-.107.1c-.164.17-.33.323-.496.457L16.5 10.25a.75.75 0 0 0-.75-.75H4.25a.75.75 0 0 0-.75.75v9.5c0 .414.336.75.75.75h9.888a6.024 6.024 0 0 0 1.54 1.5H4.25A2.25 2.25 0 0 1 2 19.75v-9.5A2.25 2.25 0 0 1 4.25 8H6V6a4 4 0 0 1 4-4Zm8.284 10.122c.992 1.036 2.091 1.545 3.316 1.545.193 0 .355.143.392.332l.008.084v2.501c0 2.682-1.313 4.506-3.873 5.395a.385.385 0 0 1-.253 0c-2.476-.86-3.785-2.592-3.87-5.13L14 16.585v-2.5c0-.23.18-.417.4-.417 1.223 0 2.323-.51 3.318-1.545a.389.389 0 0 1 .566 0ZM10 13.5a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Zm0-10A2.5 2.5 0 0 0 7.5 6v2h5V6A2.5 2.5 0 0 0 10 3.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M10 2a4 4 0 0 1 4 4v2h1.75A2.25 2.25 0 0 1 18 10.25V11c-.319 0-.637.11-.896.329l-.107.1c-.164.17-.33.323-.496.457L16.5 10.25a.75.75 0 0 0-.75-.75H4.25a.75.75 0 0 0-.75.75v9.5c0 .414.336.75.75.75h9.888a6.024 6.024 0 0 0 1.54 1.5H4.25A2.25 2.25 0 0 1 2 19.75v-9.5A2.25 2.25 0 0 1 4.25 8H6V6a4 4 0 0 1 4-4Zm8.284 10.122c.992 1.036 2.091 1.545 3.316 1.545.193 0 .355.143.392.332l.008.084v2.501c0 2.682-1.313 4.506-3.873 5.395a.385.385 0 0 1-.253 0c-2.476-.86-3.785-2.592-3.87-5.13L14 16.585v-2.5c0-.23.18-.417.4-.417 1.223 0 2.323-.51 3.318-1.545a.389.389 0 0 1 .566 0ZM10 13.5a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Zm0-10A2.5 2.5 0 0 0 7.5 6v2h5V6A2.5 2.5 0 0 0 10 3.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Authorized_Apps]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m18.492 2.33 3.179 3.179a2.25 2.25 0 0 1 0 3.182l-2.584 2.584A2.25 2.25 0 0 1 21 13.5v5.25A2.25 2.25 0 0 1 18.75 21H5.25A2.25 2.25 0 0 1 3 18.75V5.25A2.25 2.25 0 0 1 5.25 3h5.25a2.25 2.25 0 0 1 2.225 1.915L15.31 2.33a2.25 2.25 0 0 1 3.182 0ZM4.5 18.75c0 .414.336.75.75.75l5.999-.001.001-6.75H4.5v6Zm8.249.749h6.001a.75.75 0 0 0 .75-.75V13.5a.75.75 0 0 0-.75-.75h-6.001v6.75Zm-2.249-15H5.25a.75.75 0 0 0-.75.75v6h6.75v-6a.75.75 0 0 0-.75-.75Zm2.25 4.81v1.94h1.94l-1.94-1.94Zm3.62-5.918-3.178 3.178a.75.75 0 0 0 0 1.061l3.179 3.179a.75.75 0 0 0 1.06 0l3.18-3.179a.75.75 0 0 0 0-1.06l-3.18-3.18a.75.75 0 0 0-1.06 0Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m18.492 2.33 3.179 3.179a2.25 2.25 0 0 1 0 3.182l-2.584 2.584A2.25 2.25 0 0 1 21 13.5v5.25A2.25 2.25 0 0 1 18.75 21H5.25A2.25 2.25 0 0 1 3 18.75V5.25A2.25 2.25 0 0 1 5.25 3h5.25a2.25 2.25 0 0 1 2.225 1.915L15.31 2.33a2.25 2.25 0 0 1 3.182 0ZM4.5 18.75c0 .414.336.75.75.75l5.999-.001.001-6.75H4.5v6Zm8.249.749h6.001a.75.75 0 0 0 .75-.75V13.5a.75.75 0 0 0-.75-.75h-6.001v6.75Zm-2.249-15H5.25a.75.75 0 0 0-.75.75v6h6.75v-6a.75.75 0 0 0-.75-.75Zm2.25 4.81v1.94h1.94l-1.94-1.94Zm3.62-5.918-3.178 3.178a.75.75 0 0 0 0 1.061l3.179 3.179a.75.75 0 0 0 1.06 0l3.18-3.179a.75.75 0 0 0 0-1.06l-3.18-3.18a.75.75 0 0 0-1.06 0Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Connections]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.25 7a.75.75 0 0 1 .11 1.492l-.11.008H7a3.5 3.5 0 0 0-.206 6.994L7 15.5h2.25a.75.75 0 0 1 .11 1.492L9.25 17H7a5 5 0 0 1-.25-9.994L7 7h2.25ZM17 7a5 5 0 0 1 .25 9.994L17 17h-2.25a.75.75 0 0 1-.11-1.492l.11-.008H17a3.5 3.5 0 0 0 .206-6.994L17 8.5h-2.25a.75.75 0 0 1-.11-1.492L14.75 7H17ZM7 11.25h10a.75.75 0 0 1 .102 1.493L17 12.75H7a.75.75 0 0 1-.102-1.493L7 11.25h10H7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.25 7a.75.75 0 0 1 .11 1.492l-.11.008H7a3.5 3.5 0 0 0-.206 6.994L7 15.5h2.25a.75.75 0 0 1 .11 1.492L9.25 17H7a5 5 0 0 1-.25-9.994L7 7h2.25ZM17 7a5 5 0 0 1 .25 9.994L17 17h-2.25a.75.75 0 0 1-.11-1.492l.11-.008H17a3.5 3.5 0 0 0 .206-6.994L17 8.5h-2.25a.75.75 0 0 1-.11-1.492L14.75 7H17ZM7 11.25h10a.75.75 0 0 1 .102 1.493L17 12.75H7a.75.75 0 0 1-.102-1.493L7 11.25h10H7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Discord_Nitro]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path clip-rule="evenodd" d="M15 5.5C11.4101 5.5 8.5 8.41015 8.5 12C8.5 15.5899 11.4101 18.5 15 18.5C18.5899 18.5 21.5 15.5899 21.5 12C21.5 8.41015 18.5899 5.5 15 5.5ZM7.5 12C7.5 7.85786 10.8579 4.5 15 4.5C19.1421 4.5 22.5 7.85786 22.5 12C22.5 16.1421 19.1421 19.5 15 19.5C10.8579 19.5 7.5 16.1421 7.5 12Z" /><path clip-rule="evenodd" d="M6 4.5H15V5.5H6V4.5Z" /><path clip-rule="evenodd" d="M5.5 8H8.5V9H5.5V8Z" /><path clip-rule="evenodd" d="M2 8H3.5V9H2V8Z" /><path clip-rule="evenodd" d="M4 12H8V13H4V12Z" /><path clip-rule="evenodd" d="M12.584 8.72265C12.6767 8.58355 12.8328 8.5 13 8.5H17C17.1672 8.5 17.3233 8.58355 17.416 8.72265L19.416 11.7226C19.528 11.8906 19.528 12.1094 19.416 12.2774L17.416 15.2773C17.3233 15.4164 17.1672 15.5 17 15.5H13C12.8328 15.5 12.6767 15.4164 12.584 15.2773L10.584 12.2774C10.472 12.1094 10.472 11.8906 10.584 11.7226L12.584 8.72265ZM13.2676 9.5L11.6009 12L13.2676 14.5H16.7324L18.3991 12L16.7324 9.5H13.2676Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path clip-rule="evenodd" d="M15 5.5C11.4101 5.5 8.5 8.41015 8.5 12C8.5 15.5899 11.4101 18.5 15 18.5C18.5899 18.5 21.5 15.5899 21.5 12C21.5 8.41015 18.5899 5.5 15 5.5ZM7.5 12C7.5 7.85786 10.8579 4.5 15 4.5C19.1421 4.5 22.5 7.85786 22.5 12C22.5 16.1421 19.1421 19.5 15 19.5C10.8579 19.5 7.5 16.1421 7.5 12Z" /><path clip-rule="evenodd" d="M6 4.5H15V5.5H6V4.5Z" /><path clip-rule="evenodd" d="M5.5 8H8.5V9H5.5V8Z" /><path clip-rule="evenodd" d="M2 8H3.5V9H2V8Z" /><path clip-rule="evenodd" d="M4 12H8V13H4V12Z" /><path clip-rule="evenodd" d="M12.584 8.72265C12.6767 8.58355 12.8328 8.5 13 8.5H17C17.1672 8.5 17.3233 8.58355 17.416 8.72265L19.416 11.7226C19.528 11.8906 19.528 12.1094 19.416 12.2774L17.416 15.2773C17.3233 15.4164 17.1672 15.5 17 15.5H13C12.8328 15.5 12.6767 15.4164 12.584 15.2773L10.584 12.2774C10.472 12.1094 10.472 11.8906 10.584 11.7226L12.584 8.72265ZM13.2676 9.5L11.6009 12L13.2676 14.5H16.7324L18.3991 12L16.7324 9.5H13.2676Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Nitro_Server_Boost]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M13.057 7.431a2.5 2.5 0 1 1 3.536 3.536 2.5 2.5 0 0 1-3.536-3.536Zm2.475 1.06a1 1 0 1 0-1.414 1.415 1 1 0 0 0 1.414-1.414Z" /><path d="M21.509 4.323a2.75 2.75 0 0 0-1.811-1.81l-.663-.206a6.75 6.75 0 0 0-6.773 1.674l-.996.995a3.498 3.498 0 0 0-4.57.327L5.455 6.546a.75.75 0 0 0 0 1.06l1.591 1.591-.18.18a1.75 1.75 0 0 0 0 2.475l.496.495-1.396.796a.75.75 0 0 0-.158 1.182l3.889 3.89a.75.75 0 0 0 1.181-.159l.798-1.395.497.497a1.75 1.75 0 0 0 2.475 0l.177-.176 1.59 1.59a.75.75 0 0 0 1.06 0l1.242-1.243a3.497 3.497 0 0 0 .328-4.568l.998-.998a6.75 6.75 0 0 0 1.673-6.776l-.206-.664Zm-2.256-.378c.393.122.701.43.823.823l.207.664a5.25 5.25 0 0 1-1.302 5.27l-5.395 5.396a.25.25 0 0 1-.353 0L7.926 10.79a.25.25 0 0 1 0-.353l5.396-5.397a5.25 5.25 0 0 1 5.269-1.301l.662.205Zm-1.289 9.896c.453.766.35 1.769-.308 2.427l-.712.712-1.06-1.059 2.08-2.08ZM7.758 6.364a1.998 1.998 0 0 1 2.428-.308l-2.08 2.08-1.06-1.06.712-.712Zm2.818 9.198-.514.897-2.5-2.5.898-.512 2.116 2.115ZM6.69 18.395a.75.75 0 0 0-1.06-1.061l-2.476 2.475a.75.75 0 0 0 1.061 1.06l2.475-2.474ZM4.745 15.39a.75.75 0 0 1 0 1.06l-1.06 1.06a.75.75 0 1 1-1.061-1.06l1.06-1.06a.75.75 0 0 1 1.061 0ZM8.632 20.341a.75.75 0 1 0-1.06-1.06l-1.059 1.058a.75.75 0 0 0 1.06 1.06l1.06-1.058Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M13.057 7.431a2.5 2.5 0 1 1 3.536 3.536 2.5 2.5 0 0 1-3.536-3.536Zm2.475 1.06a1 1 0 1 0-1.414 1.415 1 1 0 0 0 1.414-1.414Z" /><path d="M21.509 4.323a2.75 2.75 0 0 0-1.811-1.81l-.663-.206a6.75 6.75 0 0 0-6.773 1.674l-.996.995a3.498 3.498 0 0 0-4.57.327L5.455 6.546a.75.75 0 0 0 0 1.06l1.591 1.591-.18.18a1.75 1.75 0 0 0 0 2.475l.496.495-1.396.796a.75.75 0 0 0-.158 1.182l3.889 3.89a.75.75 0 0 0 1.181-.159l.798-1.395.497.497a1.75 1.75 0 0 0 2.475 0l.177-.176 1.59 1.59a.75.75 0 0 0 1.06 0l1.242-1.243a3.497 3.497 0 0 0 .328-4.568l.998-.998a6.75 6.75 0 0 0 1.673-6.776l-.206-.664Zm-2.256-.378c.393.122.701.43.823.823l.207.664a5.25 5.25 0 0 1-1.302 5.27l-5.395 5.396a.25.25 0 0 1-.353 0L7.926 10.79a.25.25 0 0 1 0-.353l5.396-5.397a5.25 5.25 0 0 1 5.269-1.301l.662.205Zm-1.289 9.896c.453.766.35 1.769-.308 2.427l-.712.712-1.06-1.059 2.08-2.08ZM7.758 6.364a1.998 1.998 0 0 1 2.428-.308l-2.08 2.08-1.06-1.06.712-.712Zm2.818 9.198-.514.897-2.5-2.5.898-.512 2.116 2.115ZM6.69 18.395a.75.75 0 0 0-1.06-1.061l-2.476 2.475a.75.75 0 0 0 1.061 1.06l2.475-2.474ZM4.745 15.39a.75.75 0 0 1 0 1.06l-1.06 1.06a.75.75 0 1 1-1.061-1.06l1.06-1.06a.75.75 0 0 1 1.061 0ZM8.632 20.341a.75.75 0 1 0-1.06-1.06l-1.059 1.058a.75.75 0 0 0 1.06 1.06l1.06-1.058Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Subscriptions]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M2 7.25A3.25 3.25 0 0 1 5.25 4h13.5A3.25 3.25 0 0 1 22 7.25V10h-.258A3.74 3.74 0 0 0 20.5 7.455V7.25a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 7.25v.25h11.95c-.44.409-.782.922-.987 1.5H3.5v5.75c0 .966.784 1.75 1.75 1.75h6.78c.06.522.217 1.028.458 1.5H5.25A3.25 3.25 0 0 1 2 14.75v-7.5Zm21 8.25a1.5 1.5 0 0 0-1.5-1.5h-7a1.5 1.5 0 0 0-1.5 1.5v.5c0 1.971 1.86 4 5 4 3.14 0 5-2.029 5-4v-.5Zm-2.25-5.25a2.75 2.75 0 1 0-5.5 0 2.75 2.75 0 0 0 5.5 0Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M2 7.25A3.25 3.25 0 0 1 5.25 4h13.5A3.25 3.25 0 0 1 22 7.25V10h-.258A3.74 3.74 0 0 0 20.5 7.455V7.25a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 7.25v.25h11.95c-.44.409-.782.922-.987 1.5H3.5v5.75c0 .966.784 1.75 1.75 1.75h6.78c.06.522.217 1.028.458 1.5H5.25A3.25 3.25 0 0 1 2 14.75v-7.5Zm21 8.25a1.5 1.5 0 0 0-1.5-1.5h-7a1.5 1.5 0 0 0-1.5 1.5v.5c0 1.971 1.86 4 5 4 3.14 0 5-2.029 5-4v-.5Zm-2.25-5.25a2.75 2.75 0 1 0-5.5 0 2.75 2.75 0 0 0 5.5 0Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Library_Inventory]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2a3.25 3.25 0 0 1 2.739 5h2.511c.69 0 1.25.56 1.25 1.25v3.5a1.25 1.25 0 0 1-1 1.225v5.775a3.25 3.25 0 0 1-3.066 3.245L16.75 22h-9.5a3.25 3.25 0 0 1-3.245-3.066L4 18.75v-5.775c-.57-.116-1-.62-1-1.225v-3.5C3 7.56 3.56 7 4.25 7h2.511a3.25 3.25 0 0 1 5.24-3.827A3.24 3.24 0 0 1 14.5 2Zm-3.25 10.999H5.5v5.751a1.75 1.75 0 0 0 1.606 1.744l.144.006h4v-7.501Zm7.25 0h-5.75V20.5h4a1.75 1.75 0 0 0 1.744-1.607l.006-.143v-5.751ZM11.25 8.5H4.5v3l6.75-.001V8.5Zm8.25 3v-3h-6.75v2.999l6.75.001Zm-5-8a1.75 1.75 0 0 0-1.75 1.75v1.749h1.774l.12-.005A1.75 1.75 0 0 0 14.5 3.5Zm-5 0a1.75 1.75 0 0 0-.144 3.494l.12.005h1.774V5.25l-.006-.144A1.75 1.75 0 0 0 9.5 3.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2a3.25 3.25 0 0 1 2.739 5h2.511c.69 0 1.25.56 1.25 1.25v3.5a1.25 1.25 0 0 1-1 1.225v5.775a3.25 3.25 0 0 1-3.066 3.245L16.75 22h-9.5a3.25 3.25 0 0 1-3.245-3.066L4 18.75v-5.775c-.57-.116-1-.62-1-1.225v-3.5C3 7.56 3.56 7 4.25 7h2.511a3.25 3.25 0 0 1 5.24-3.827A3.24 3.24 0 0 1 14.5 2Zm-3.25 10.999H5.5v5.751a1.75 1.75 0 0 0 1.606 1.744l.144.006h4v-7.501Zm7.25 0h-5.75V20.5h4a1.75 1.75 0 0 0 1.744-1.607l.006-.143v-5.751ZM11.25 8.5H4.5v3l6.75-.001V8.5Zm8.25 3v-3h-6.75v2.999l6.75.001Zm-5-8a1.75 1.75 0 0 0-1.75 1.75v1.749h1.774l.12-.005A1.75 1.75 0 0 0 14.5 3.5Zm-5 0a1.75 1.75 0 0 0-.144 3.494l.12.005h1.774V5.25l-.006-.144A1.75 1.75 0 0 0 9.5 3.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Billing]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5 6.25A2.25 2.25 0 0 1 7.25 4h8.5A2.25 2.25 0 0 1 18 6.25V14h3.5v3.25a3.25 3.25 0 0 1-3.25 3.25H13V19h3.5V6.25a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0-.75.75V14H5V6.25ZM18 19h.25A1.75 1.75 0 0 0 20 17.25V15.5h-2V19Zm-3.75-2.5H13a2.49 2.49 0 0 0-.5-1.5h1.75a.75.75 0 0 1 0 1.5ZM8 8.75A.75.75 0 0 1 8.75 8h5.5a.75.75 0 0 1 0 1.5h-5.5A.75.75 0 0 1 8 8.75Zm0 3.5a.75.75 0 0 1 .75-.75h5.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1-.75-.75ZM1 16.5A1.5 1.5 0 0 1 2.5 15h8a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 1 20.5v-4Zm10 .5a1 1 0 0 1-1-1H9a2 2 0 0 0 2 2v-1Zm0 2a2 2 0 0 0-2 2h1a1 1 0 0 1 1-1v-1Zm-8-3a1 1 0 0 1-1 1v1a2 2 0 0 0 2-2H3Zm1 5a2 2 0 0 0-2-2v1a1 1 0 0 1 1 1h1Zm4.25-2.5a1.75 1.75 0 1 0-3.5 0 1.75 1.75 0 0 0 3.5 0Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5 6.25A2.25 2.25 0 0 1 7.25 4h8.5A2.25 2.25 0 0 1 18 6.25V14h3.5v3.25a3.25 3.25 0 0 1-3.25 3.25H13V19h3.5V6.25a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0-.75.75V14H5V6.25ZM18 19h.25A1.75 1.75 0 0 0 20 17.25V15.5h-2V19Zm-3.75-2.5H13a2.49 2.49 0 0 0-.5-1.5h1.75a.75.75 0 0 1 0 1.5ZM8 8.75A.75.75 0 0 1 8.75 8h5.5a.75.75 0 0 1 0 1.5h-5.5A.75.75 0 0 1 8 8.75Zm0 3.5a.75.75 0 0 1 .75-.75h5.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1-.75-.75ZM1 16.5A1.5 1.5 0 0 1 2.5 15h8a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 1 20.5v-4Zm10 .5a1 1 0 0 1-1-1H9a2 2 0 0 0 2 2v-1Zm0 2a2 2 0 0 0-2 2h1a1 1 0 0 1 1-1v-1Zm-8-3a1 1 0 0 1-1 1v1a2 2 0 0 0 2-2H3Zm1 5a2 2 0 0 0-2-2v1a1 1 0 0 1 1 1h1Zm4.25-2.5a1.75 1.75 0 1 0-3.5 0 1.75 1.75 0 0 0 3.5 0Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Appearance]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Accessibility]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.04 5.493a3 3 0 1 1 5.919.002l2.432-.908a2.359 2.359 0 0 1 1.766 4.372L16 10.335v3.11l1.883 5.467a2.316 2.316 0 0 1-4.365 1.549l-1.515-4.148-1.512 4.15a2.32 2.32 0 0 1-4.373-1.55L8 13.457v-3.12L4.694 8.884A2.35 2.35 0 0 1 6.46 4.53l2.58.962Zm1.46-.495a1.5 1.5 0 0 0 .896 1.373 1.75 1.75 0 0 0 1.187.01A1.5 1.5 0 1 0 10.5 4.997Zm.33 2.763L5.937 5.936a.85.85 0 0 0-.64 1.574l3.755 1.653a.75.75 0 0 1 .448.686v3.735a.75.75 0 0 1-.04.245L7.535 19.4a.82.82 0 0 0 1.545.549l1.65-4.527c.433-1.186 2.11-1.187 2.544 0l1.652 4.523a.816.816 0 0 0 1.538-.546l-1.924-5.584a.752.752 0 0 1-.04-.245V9.843a.75.75 0 0 1 .45-.688l3.607-1.57a.859.859 0 0 0-.643-1.592l-4.78 1.783c-.35.143-.733.222-1.135.222a2.99 2.99 0 0 1-1.17-.237Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.04 5.493a3 3 0 1 1 5.919.002l2.432-.908a2.359 2.359 0 0 1 1.766 4.372L16 10.335v3.11l1.883 5.467a2.316 2.316 0 0 1-4.365 1.549l-1.515-4.148-1.512 4.15a2.32 2.32 0 0 1-4.373-1.55L8 13.457v-3.12L4.694 8.884A2.35 2.35 0 0 1 6.46 4.53l2.58.962Zm1.46-.495a1.5 1.5 0 0 0 .896 1.373 1.75 1.75 0 0 0 1.187.01A1.5 1.5 0 1 0 10.5 4.997Zm.33 2.763L5.937 5.936a.85.85 0 0 0-.64 1.574l3.755 1.653a.75.75 0 0 1 .448.686v3.735a.75.75 0 0 1-.04.245L7.535 19.4a.82.82 0 0 0 1.545.549l1.65-4.527c.433-1.186 2.11-1.187 2.544 0l1.652 4.523a.816.816 0 0 0 1.538-.546l-1.924-5.584a.752.752 0 0 1-.04-.245V9.843a.75.75 0 0 1 .45-.688l3.607-1.57a.859.859 0 0 0-.643-1.592l-4.78 1.783c-.35.143-.733.222-1.135.222a2.99 2.99 0 0 1-1.17-.237Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Voice___Video]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M18.25 11a.75.75 0 0 1 .743.648l.007.102v.5a6.75 6.75 0 0 1-6.249 6.732l-.001 2.268a.75.75 0 0 1-1.493.102l-.007-.102v-2.268a6.75 6.75 0 0 1-6.246-6.496L5 12.25v-.5a.75.75 0 0 1 1.493-.102l.007.102v.5a5.25 5.25 0 0 0 5.034 5.246l.216.004h.5a5.25 5.25 0 0 0 5.246-5.034l.004-.216v-.5a.75.75 0 0 1 .75-.75ZM12 2a4 4 0 0 1 4 4v6a4 4 0 0 1-8 0V6a4 4 0 0 1 4-4Zm0 1.5A2.5 2.5 0 0 0 9.5 6v6a2.5 2.5 0 0 0 5 0V6A2.5 2.5 0 0 0 12 3.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M18.25 11a.75.75 0 0 1 .743.648l.007.102v.5a6.75 6.75 0 0 1-6.249 6.732l-.001 2.268a.75.75 0 0 1-1.493.102l-.007-.102v-2.268a6.75 6.75 0 0 1-6.246-6.496L5 12.25v-.5a.75.75 0 0 1 1.493-.102l.007.102v.5a5.25 5.25 0 0 0 5.034 5.246l.216.004h.5a5.25 5.25 0 0 0 5.246-5.034l.004-.216v-.5a.75.75 0 0 1 .75-.75ZM12 2a4 4 0 0 1 4 4v6a4 4 0 0 1-8 0V6a4 4 0 0 1 4-4Zm0 1.5A2.5 2.5 0 0 0 9.5 6v6a2.5 2.5 0 0 0 5 0V6A2.5 2.5 0 0 0 12 3.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Text___Images]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.068-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2Zm0 1.5A8.5 8.5 0 0 0 3.5 12c0 1.47.373 2.883 1.073 4.137l.15.27-1.112 3.984 3.987-1.112.27.15A8.5 8.5 0 1 0 12 3.5ZM8.75 13h4.498a.75.75 0 0 1 .102 1.493l-.102.007H8.75a.75.75 0 0 1-.102-1.493L8.75 13h4.498H8.75Zm0-3.5h6.505a.75.75 0 0 1 .101 1.493l-.101.007H8.75a.75.75 0 0 1-.102-1.493L8.75 9.5h6.505H8.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.068-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2Zm0 1.5A8.5 8.5 0 0 0 3.5 12c0 1.47.373 2.883 1.073 4.137l.15.27-1.112 3.984 3.987-1.112.27.15A8.5 8.5 0 1 0 12 3.5ZM8.75 13h4.498a.75.75 0 0 1 .102 1.493l-.102.007H8.75a.75.75 0 0 1-.102-1.493L8.75 13h4.498H8.75Zm0-3.5h6.505a.75.75 0 0 1 .101 1.493l-.101.007H8.75a.75.75 0 0 1-.102-1.493L8.75 9.5h6.505H8.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Notifications]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.996a7.49 7.49 0 0 1 7.496 7.25l.004.25v4.097l1.38 3.156a1.25 1.25 0 0 1-1.145 1.75L15 18.502a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-4.155 3.352-7.5 7.5-7.5ZM13.5 18.5l-3 .002a1.5 1.5 0 0 0 2.993.145l.006-.147ZM12 3.496c-3.32 0-6 2.674-6 6v4.41L4.656 17h14.697L18 13.907V9.509l-.004-.225A5.988 5.988 0 0 0 12 3.496Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.996a7.49 7.49 0 0 1 7.496 7.25l.004.25v4.097l1.38 3.156a1.25 1.25 0 0 1-1.145 1.75L15 18.502a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-4.155 3.352-7.5 7.5-7.5ZM13.5 18.5l-3 .002a1.5 1.5 0 0 0 2.993.145l.006-.147ZM12 3.496c-3.32 0-6 2.674-6 6v4.41L4.656 17h14.697L18 13.907V9.509l-.004-.225A5.988 5.988 0 0 0 12 3.496Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Keybinds]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M19.745 5a2.25 2.25 0 0 1 2.25 2.25v9.505a2.25 2.25 0 0 1-2.25 2.25H4.25A2.25 2.25 0 0 1 2 16.755V7.25A2.25 2.25 0 0 1 4.25 5h15.495Zm0 1.5H4.25a.75.75 0 0 0-.75.75v9.505c0 .414.336.75.75.75h15.495a.75.75 0 0 0 .75-.75V7.25a.75.75 0 0 0-.75-.75Zm-12.995 8h10.5a.75.75 0 0 1 .102 1.493L17.25 16H6.75a.75.75 0 0 1-.102-1.493l.102-.007h10.5-10.5ZM16.5 11a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm-5.995 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm-3 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm6 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2ZM6 8a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm2.995 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm3 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm3 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm3 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M19.745 5a2.25 2.25 0 0 1 2.25 2.25v9.505a2.25 2.25 0 0 1-2.25 2.25H4.25A2.25 2.25 0 0 1 2 16.755V7.25A2.25 2.25 0 0 1 4.25 5h15.495Zm0 1.5H4.25a.75.75 0 0 0-.75.75v9.505c0 .414.336.75.75.75h15.495a.75.75 0 0 0 .75-.75V7.25a.75.75 0 0 0-.75-.75Zm-12.995 8h10.5a.75.75 0 0 1 .102 1.493L17.25 16H6.75a.75.75 0 0 1-.102-1.493l.102-.007h10.5-10.5ZM16.5 11a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm-5.995 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm-3 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm6 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2ZM6 8a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm2.995 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm3 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm3 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Zm3 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Language]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m9.34 6.372.05.105 5.56 14.5a.755.755 0 0 1-.418.971.73.73 0 0 1-.91-.333l-.043-.092-1.433-3.737H5.06l-.094-.006-1.546 3.76a.73.73 0 0 1-.963.401.754.754 0 0 1-.427-.885l.033-.096 5.964-14.5a.73.73 0 0 1 1.314-.088Zm9.406-4.37a.75.75 0 0 1 .743.65l.007.1V7.5h1.75a.75.75 0 0 1 .743.649l.007.102a.75.75 0 0 1-.648.743L21.245 9l-1.75-.001v7.25a.75.75 0 0 1-.648.744l-.102.007a.75.75 0 0 1-.743-.648l-.007-.102V2.753a.75.75 0 0 1 .75-.75ZM8.81 8.748 5.65 16.286h6.11L8.81 8.747Zm1.937-6.744h5.498a.75.75 0 0 1 .743.648l.006.102v3.004c0 2.344-1.9 4.245-4.245 4.245a.75.75 0 0 1 0-1.5c1.46 0 2.654-1.14 2.74-2.578l.005-.167V3.503h-4.747a.75.75 0 0 1-.102-1.493l.102-.007h5.498-5.498Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m9.34 6.372.05.105 5.56 14.5a.755.755 0 0 1-.418.971.73.73 0 0 1-.91-.333l-.043-.092-1.433-3.737H5.06l-.094-.006-1.546 3.76a.73.73 0 0 1-.963.401.754.754 0 0 1-.427-.885l.033-.096 5.964-14.5a.73.73 0 0 1 1.314-.088Zm9.406-4.37a.75.75 0 0 1 .743.65l.007.1V7.5h1.75a.75.75 0 0 1 .743.649l.007.102a.75.75 0 0 1-.648.743L21.245 9l-1.75-.001v7.25a.75.75 0 0 1-.648.744l-.102.007a.75.75 0 0 1-.743-.648l-.007-.102V2.753a.75.75 0 0 1 .75-.75ZM8.81 8.748 5.65 16.286h6.11L8.81 8.747Zm1.937-6.744h5.498a.75.75 0 0 1 .743.648l.006.102v3.004c0 2.344-1.9 4.245-4.245 4.245a.75.75 0 0 1 0-1.5c1.46 0 2.654-1.14 2.74-2.578l.005-.167V3.503h-4.747a.75.75 0 0 1-.102-1.493l.102-.007h5.498-5.498Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Windows]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 480 480" xmlns="http://www.w3.org/2000/svg" ><g><g><path d="M0.2,224L0,68l192-26.1V224H0.2z M224,37.2L479.9,0v224H224V37.2z M480,256l-0.1,224L224,444V256H480z M192,439.9 L0.2,413.6l0-157.6H192V439.9z"/></g></g></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 480 480" xmlns="http://www.w3.org/2000/svg" ><g><g><path d="M0.2,224L0,68l192-26.1V224H0.2z M224,37.2L479.9,0v224H224V37.2z M480,256l-0.1,224L224,444V256H480z M192,439.9 L0.2,413.6l0-157.6H192V439.9z"/></g></g></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Streamer_Mode]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.99 4.929a.75.75 0 0 1 0 1.06 8.5 8.5 0 0 0 0 12.021.75.75 0 0 1-1.061 1.06c-3.905-3.905-3.905-10.236 0-14.141a.75.75 0 0 1 1.06 0Zm13.081 0c3.905 3.905 3.905 10.236 0 14.142a.75.75 0 0 1-1.06-1.06 8.5 8.5 0 0 0 0-12.022.75.75 0 1 1 1.06-1.06ZM8.818 7.757a.75.75 0 0 1 0 1.06 4.5 4.5 0 0 0 0 6.365.75.75 0 0 1-1.06 1.06 6 6 0 0 1 0-8.485.75.75 0 0 1 1.06 0Zm7.425 0a6 6 0 0 1 0 8.485.75.75 0 1 1-1.061-1.06 4.5 4.5 0 0 0 0-6.364.75.75 0 0 1 1.06-1.06ZM12 10.5a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.99 4.929a.75.75 0 0 1 0 1.06 8.5 8.5 0 0 0 0 12.021.75.75 0 0 1-1.061 1.06c-3.905-3.905-3.905-10.236 0-14.141a.75.75 0 0 1 1.06 0Zm13.081 0c3.905 3.905 3.905 10.236 0 14.142a.75.75 0 0 1-1.06-1.06 8.5 8.5 0 0 0 0-12.022.75.75 0 1 1 1.06-1.06ZM8.818 7.757a.75.75 0 0 1 0 1.06 4.5 4.5 0 0 0 0 6.365.75.75 0 0 1-1.06 1.06 6 6 0 0 1 0-8.485.75.75 0 0 1 1.06 0Zm7.425 0a6 6 0 0 1 0 8.485.75.75 0 1 1-1.061-1.06 4.5 4.5 0 0 0 0-6.364.75.75 0 0 1 1.06-1.06ZM12 10.5a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Advanced]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.012 2.25c.734.008 1.465.093 2.182.253a.75.75 0 0 1 .582.649l.17 1.527a1.384 1.384 0 0 0 1.927 1.116l1.401-.615a.75.75 0 0 1 .85.174 9.792 9.792 0 0 1 2.204 3.792.75.75 0 0 1-.271.825l-1.242.916a1.381 1.381 0 0 0 0 2.226l1.243.915a.75.75 0 0 1 .272.826 9.797 9.797 0 0 1-2.204 3.792.75.75 0 0 1-.848.175l-1.407-.617a1.38 1.38 0 0 0-1.926 1.114l-.169 1.526a.75.75 0 0 1-.572.647 9.518 9.518 0 0 1-4.406 0 .75.75 0 0 1-.572-.647l-.168-1.524a1.382 1.382 0 0 0-1.926-1.11l-1.406.616a.75.75 0 0 1-.849-.175 9.798 9.798 0 0 1-2.204-3.796.75.75 0 0 1 .272-.826l1.243-.916a1.38 1.38 0 0 0 0-2.226l-1.243-.914a.75.75 0 0 1-.271-.826 9.793 9.793 0 0 1 2.204-3.792.75.75 0 0 1 .85-.174l1.4.615a1.387 1.387 0 0 0 1.93-1.118l.17-1.526a.75.75 0 0 1 .583-.65c.717-.159 1.45-.243 2.201-.252Zm0 1.5a9.135 9.135 0 0 0-1.354.117l-.109.977A2.886 2.886 0 0 1 6.525 7.17l-.898-.394a8.293 8.293 0 0 0-1.348 2.317l.798.587a2.881 2.881 0 0 1 0 4.643l-.799.588c.32.842.776 1.626 1.348 2.322l.905-.397a2.882 2.882 0 0 1 4.017 2.318l.11.984c.889.15 1.798.15 2.687 0l.11-.984a2.881 2.881 0 0 1 4.018-2.322l.905.396a8.296 8.296 0 0 0 1.347-2.318l-.798-.588a2.881 2.881 0 0 1 0-4.643l.796-.587a8.293 8.293 0 0 0-1.348-2.317l-.896.393a2.884 2.884 0 0 1-4.023-2.324l-.11-.976a8.988 8.988 0 0 0-1.333-.117ZM12 8.25a3.75 3.75 0 1 1 0 7.5 3.75 3.75 0 0 1 0-7.5Zm0 1.5a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.012 2.25c.734.008 1.465.093 2.182.253a.75.75 0 0 1 .582.649l.17 1.527a1.384 1.384 0 0 0 1.927 1.116l1.401-.615a.75.75 0 0 1 .85.174 9.792 9.792 0 0 1 2.204 3.792.75.75 0 0 1-.271.825l-1.242.916a1.381 1.381 0 0 0 0 2.226l1.243.915a.75.75 0 0 1 .272.826 9.797 9.797 0 0 1-2.204 3.792.75.75 0 0 1-.848.175l-1.407-.617a1.38 1.38 0 0 0-1.926 1.114l-.169 1.526a.75.75 0 0 1-.572.647 9.518 9.518 0 0 1-4.406 0 .75.75 0 0 1-.572-.647l-.168-1.524a1.382 1.382 0 0 0-1.926-1.11l-1.406.616a.75.75 0 0 1-.849-.175 9.798 9.798 0 0 1-2.204-3.796.75.75 0 0 1 .272-.826l1.243-.916a1.38 1.38 0 0 0 0-2.226l-1.243-.914a.75.75 0 0 1-.271-.826 9.793 9.793 0 0 1 2.204-3.792.75.75 0 0 1 .85-.174l1.4.615a1.387 1.387 0 0 0 1.93-1.118l.17-1.526a.75.75 0 0 1 .583-.65c.717-.159 1.45-.243 2.201-.252Zm0 1.5a9.135 9.135 0 0 0-1.354.117l-.109.977A2.886 2.886 0 0 1 6.525 7.17l-.898-.394a8.293 8.293 0 0 0-1.348 2.317l.798.587a2.881 2.881 0 0 1 0 4.643l-.799.588c.32.842.776 1.626 1.348 2.322l.905-.397a2.882 2.882 0 0 1 4.017 2.318l.11.984c.889.15 1.798.15 2.687 0l.11-.984a2.881 2.881 0 0 1 4.018-2.322l.905.396a8.296 8.296 0 0 0 1.347-2.318l-.798-.588a2.881 2.881 0 0 1 0-4.643l.796-.587a8.293 8.293 0 0 0-1.348-2.317l-.896.393a2.884 2.884 0 0 1-4.023-2.324l-.11-.976a8.988 8.988 0 0 0-1.333-.117ZM12 8.25a3.75 3.75 0 1 1 0 7.5 3.75 3.75 0 0 1 0-7.5Zm0 1.5a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Game_Activity]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M6.75 7.5c-.405 0-.75-.317-.75-.722v-.055c0-.393.305-.721.698-.723h.052C12.963 6 18 11.037 18 17.25v.052a.711.711 0 0 1-.723.698h-.055c-.405 0-.722-.345-.722-.75 0-5.385-4.365-9.75-9.75-9.75ZM13.294 18c.38 0 .701-.287.705-.666L14 17.25A7.25 7.25 0 0 0 6.666 10c-.379.005-.666.327-.666.706v.09c0 .399.351.704.75.704a5.75 5.75 0 0 1 5.75 5.75c0 .399.305.75.704.75h.09ZM9 16.5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0ZM6.25 3A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75V6.25A3.25 3.25 0 0 0 17.75 3H6.25ZM4.5 6.25c0-.966.784-1.75 1.75-1.75h11.5c.966 0 1.75.784 1.75 1.75v11.5a1.75 1.75 0 0 1-1.75 1.75H6.25a1.75 1.75 0 0 1-1.75-1.75V6.25Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M6.75 7.5c-.405 0-.75-.317-.75-.722v-.055c0-.393.305-.721.698-.723h.052C12.963 6 18 11.037 18 17.25v.052a.711.711 0 0 1-.723.698h-.055c-.405 0-.722-.345-.722-.75 0-5.385-4.365-9.75-9.75-9.75ZM13.294 18c.38 0 .701-.287.705-.666L14 17.25A7.25 7.25 0 0 0 6.666 10c-.379.005-.666.327-.666.706v.09c0 .399.351.704.75.704a5.75 5.75 0 0 1 5.75 5.75c0 .399.305.75.704.75h.09ZM9 16.5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0ZM6.25 3A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75V6.25A3.25 3.25 0 0 0 17.75 3H6.25ZM4.5 6.25c0-.966.784-1.75 1.75-1.75h11.5c.966 0 1.75.784 1.75 1.75v11.5a1.75 1.75 0 0 1-1.75 1.75H6.25a1.75 1.75 0 0 1-1.75-1.75V6.25Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Overlay]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M2 7.25A3.25 3.25 0 0 1 5.25 4h13.5A3.25 3.25 0 0 1 22 7.25V13h-.258a3.74 3.74 0 0 0-1.242-2.545V7.25a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 7.25v9.5c0 .966.784 1.75 1.75 1.75H12v.5c0 .34.04.674.118 1H5.25A3.25 3.25 0 0 1 2 16.75v-9.5Zm3 1C5 7.56 5.56 7 6.25 7h4.5c.69 0 1.25.56 1.25 1.25v3.5c0 .69-.56 1.25-1.25 1.25h-4.5C5.56 13 5 12.44 5 11.75v-3.5ZM21.5 17a1.5 1.5 0 0 1 1.5 1.5v.5c0 1.971-1.86 4-5 4-3.14 0-5-2.029-5-4v-.5a1.5 1.5 0 0 1 1.5-1.5h7ZM18 10.5a2.75 2.75 0 1 1 0 5.5 2.75 2.75 0 0 1 0-5.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M2 7.25A3.25 3.25 0 0 1 5.25 4h13.5A3.25 3.25 0 0 1 22 7.25V13h-.258a3.74 3.74 0 0 0-1.242-2.545V7.25a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 7.25v9.5c0 .966.784 1.75 1.75 1.75H12v.5c0 .34.04.674.118 1H5.25A3.25 3.25 0 0 1 2 16.75v-9.5Zm3 1C5 7.56 5.56 7 6.25 7h4.5c.69 0 1.25.56 1.25 1.25v3.5c0 .69-.56 1.25-1.25 1.25h-4.5C5.56 13 5 12.44 5 11.75v-3.5ZM21.5 17a1.5 1.5 0 0 1 1.5 1.5v.5c0 1.971-1.86 4-5 4-3.14 0-5-2.029-5-4v-.5a1.5 1.5 0 0 1 1.5-1.5h7ZM18 10.5a2.75 2.75 0 1 1 0 5.5 2.75 2.75 0 0 1 0-5.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-changelog]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m19.414 8.414-5.829-5.828a.493.493 0 0 0-.049-.04.626.626 0 0 1-.036-.03 2.072 2.072 0 0 0-.219-.18.652.652 0 0 0-.08-.044l-.048-.024-.05-.029c-.054-.031-.109-.063-.166-.087a1.977 1.977 0 0 0-.624-.138c-.02-.001-.04-.004-.059-.007A.605.605 0 0 0 12.172 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h6.81a6.518 6.518 0 0 1-1.078-1.5H6a.5.5 0 0 1-.5-.5V4a.5.5 0 0 1 .5-.5h6V8a2 2 0 0 0 2 2h4.5v1.076c.523.081 1.026.224 1.5.422v-1.67a2 2 0 0 0-.586-1.414ZM13.5 4.621 17.378 8.5H14a.5.5 0 0 1-.5-.5V4.621ZM10.75 17.5H11c0 .516.06 1.018.174 1.5h-.424a.75.75 0 0 1 0-1.5Zm.424-1.5c.125-.528.314-1.03.558-1.5h-.982a.75.75 0 0 0 0 1.5h.424Zm1.636-3a6.511 6.511 0 0 1 2.186-1.5H10.75a.75.75 0 0 0 0 1.5h2.06Zm-5.06-1.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5ZM7 15.25a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0Zm0 3a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0Zm16-.75a5.5 5.5 0 1 0-11 0 5.5 5.5 0 0 0 11 0Zm-5.78.418a.5.5 0 0 1-.219-.489L17 13.5a.5.5 0 1 1 1 0L18.001 17h2.496a.5.5 0 0 1 0 1H17.56a.507.507 0 0 1-.34-.082Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m19.414 8.414-5.829-5.828a.493.493 0 0 0-.049-.04.626.626 0 0 1-.036-.03 2.072 2.072 0 0 0-.219-.18.652.652 0 0 0-.08-.044l-.048-.024-.05-.029c-.054-.031-.109-.063-.166-.087a1.977 1.977 0 0 0-.624-.138c-.02-.001-.04-.004-.059-.007A.605.605 0 0 0 12.172 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h6.81a6.518 6.518 0 0 1-1.078-1.5H6a.5.5 0 0 1-.5-.5V4a.5.5 0 0 1 .5-.5h6V8a2 2 0 0 0 2 2h4.5v1.076c.523.081 1.026.224 1.5.422v-1.67a2 2 0 0 0-.586-1.414ZM13.5 4.621 17.378 8.5H14a.5.5 0 0 1-.5-.5V4.621ZM10.75 17.5H11c0 .516.06 1.018.174 1.5h-.424a.75.75 0 0 1 0-1.5Zm.424-1.5c.125-.528.314-1.03.558-1.5h-.982a.75.75 0 0 0 0 1.5h.424Zm1.636-3a6.511 6.511 0 0 1 2.186-1.5H10.75a.75.75 0 0 0 0 1.5h2.06Zm-5.06-1.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5ZM7 15.25a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0Zm0 3a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0Zm16-.75a5.5 5.5 0 1 0-11 0 5.5 5.5 0 0 0 11 0Zm-5.78.418a.5.5 0 0 1-.219-.489L17 13.5a.5.5 0 1 1 1 0L18.001 17h2.496a.5.5 0 0 1 0 1H17.56a.507.507 0 0 1-.34-.082Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Hypesquad_Online]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M10.788 3.103c.495-1.004 1.926-1.004 2.421 0l2.358 4.777 5.273.766c1.107.161 1.549 1.522.748 2.303l-3.816 3.72.901 5.25c.19 1.103-.968 1.944-1.959 1.424l-4.716-2.48-4.715 2.48c-.99.52-2.148-.32-1.96-1.424l.901-5.25-3.815-3.72c-.801-.78-.359-2.142.748-2.303L8.43 7.88l2.358-4.777Zm1.21.936L9.74 8.615a1.35 1.35 0 0 1-1.016.738l-5.05.734 3.654 3.562c.318.31.463.757.388 1.195l-.862 5.03 4.516-2.375a1.35 1.35 0 0 1 1.257 0l4.516 2.374-.862-5.029a1.35 1.35 0 0 1 .388-1.195l3.654-3.562-5.05-.734a1.35 1.35 0 0 1-1.016-.738l-2.259-4.576Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M10.788 3.103c.495-1.004 1.926-1.004 2.421 0l2.358 4.777 5.273.766c1.107.161 1.549 1.522.748 2.303l-3.816 3.72.901 5.25c.19 1.103-.968 1.944-1.959 1.424l-4.716-2.48-4.715 2.48c-.99.52-2.148-.32-1.96-1.424l.901-5.25-3.815-3.72c-.801-.78-.359-2.142.748-2.303L8.43 7.88l2.358-4.777Zm1.21.936L9.74 8.615a1.35 1.35 0 0 1-1.016.738l-5.05.734 3.654 3.562c.318.31.463.757.388 1.195l-.862 5.03 4.516-2.375a1.35 1.35 0 0 1 1.257 0l4.516 2.374-.862-5.029a1.35 1.35 0 0 1 .388-1.195l3.654-3.562-5.05-.734a1.35 1.35 0 0 1-1.016-.738l-2.259-4.576Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Sessions]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M8.254 8.003c.967 0 1.75.784 1.75 1.75v9.5a1.75 1.75 0 0 1-1.75 1.75H3.75A1.75 1.75 0 0 1 2 19.253v-9.5c0-.966.784-1.75 1.75-1.75h4.504Zm0 1.5H3.75a.25.25 0 0 0-.25.25v9.5c0 .138.112.25.25.25h4.504a.25.25 0 0 0 .25-.25v-9.5a.25.25 0 0 0-.25-.25ZM6.252 17a.75.75 0 0 1 .102 1.493l-.102.007h-.5a.75.75 0 0 1-.102-1.493L5.752 17h.5Zm14.997-.5a.75.75 0 0 1 .102 1.493L21.25 18H11v-1.5h10.25ZM18.25 5c.966 0 1.75.784 1.75 1.75v7.5A1.75 1.75 0 0 1 18.25 16H11v-1.5h7.25a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25L5.499 7H4v-.25C4 5.784 4.784 5 5.75 5h12.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M8.254 8.003c.967 0 1.75.784 1.75 1.75v9.5a1.75 1.75 0 0 1-1.75 1.75H3.75A1.75 1.75 0 0 1 2 19.253v-9.5c0-.966.784-1.75 1.75-1.75h4.504Zm0 1.5H3.75a.25.25 0 0 0-.25.25v9.5c0 .138.112.25.25.25h4.504a.25.25 0 0 0 .25-.25v-9.5a.25.25 0 0 0-.25-.25ZM6.252 17a.75.75 0 0 1 .102 1.493l-.102.007h-.5a.75.75 0 0 1-.102-1.493L5.752 17h.5Zm14.997-.5a.75.75 0 0 1 .102 1.493L21.25 18H11v-1.5h10.25ZM18.25 5c.966 0 1.75.784 1.75 1.75v7.5A1.75 1.75 0 0 1 18.25 16H11v-1.5h7.25a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25L5.499 7H4v-.25C4 5.784 4.784 5 5.75 5h12.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Friend_Requests]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-2.646 5.146a.5.5 0 0 0-.707.707l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 0 0-.707-.707L16.5 18.793l-1.646-1.647ZM12.022 14a6.474 6.474 0 0 0-.708 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214.597 0 1.156-.036 1.68-.106.245.495.553.953.912 1.366-.796.16-1.66.24-2.592.24-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h7.77ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-2.646 5.146a.5.5 0 0 0-.707.707l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 0 0-.707-.707L16.5 18.793l-1.646-1.647ZM12.022 14a6.474 6.474 0 0 0-.708 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214.597 0 1.156-.036 1.68-.106.245.495.553.953.912 1.366-.796.16-1.66.24-2.592.24-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h7.77ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=user-settings-cog-Activity_Privacy]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3 5.75A.75.75 0 0 1 3.75 5c2.663 0 5.258-.943 7.8-2.85a.75.75 0 0 1 .9 0C14.992 4.057 17.587 5 20.25 5a.75.75 0 0 1 .75.75V11c0 .338-.014.67-.04.996a6.467 6.467 0 0 0-1.465-.684c.003-.103.005-.207.005-.312V6.478c-2.577-.152-5.08-1.09-7.5-2.8-2.42 1.71-4.923 2.648-7.5 2.8V11c0 4.149 2.332 7.221 7.125 9.285a6.506 6.506 0 0 0 1.005 1.52l-.355.143a.75.75 0 0 1-.55 0C5.958 19.676 3 16 3 11V5.75ZM23 17.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0Zm-2.146-2.354a.5.5 0 0 0-.708 0L16.5 18.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.708Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3 5.75A.75.75 0 0 1 3.75 5c2.663 0 5.258-.943 7.8-2.85a.75.75 0 0 1 .9 0C14.992 4.057 17.587 5 20.25 5a.75.75 0 0 1 .75.75V11c0 .338-.014.67-.04.996a6.467 6.467 0 0 0-1.465-.684c.003-.103.005-.207.005-.312V6.478c-2.577-.152-5.08-1.09-7.5-2.8-2.42 1.71-4.923 2.648-7.5 2.8V11c0 4.149 2.332 7.221 7.125 9.285a6.506 6.506 0 0 0 1.005 1.52l-.355.143a.75.75 0 0 1-.55 0C5.958 19.676 3 16 3 11V5.75ZM23 17.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0Zm-2.146-2.354a.5.5 0 0 0-.708 0L16.5 18.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.708Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-mute-channel]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-copy-channel-topic]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-edit-channel]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-invite-people]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-clone-channel]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M20.496 5.627A2.25 2.25 0 0 1 22 7.75v10A4.25 4.25 0 0 1 17.75 22h-10a2.25 2.25 0 0 1-2.123-1.504l2.097.004H17.75a2.75 2.75 0 0 0 2.75-2.75v-10l-.004-.051V5.627ZM17.246 2a2.25 2.25 0 0 1 2.25 2.25v12.997a2.25 2.25 0 0 1-2.25 2.25H4.25A2.25 2.25 0 0 1 2 17.247V4.25A2.25 2.25 0 0 1 4.25 2h12.997Zm0 1.5H4.25a.75.75 0 0 0-.75.75v12.997c0 .414.336.75.75.75h12.997a.75.75 0 0 0 .75-.75V4.25a.75.75 0 0 0-.75-.75ZM10.75 6.75a.75.75 0 0 1 .75.75V10H14a.75.75 0 0 1 0 1.5h-2.5V14a.75.75 0 0 1-1.5 0v-2.5H7.5a.75.75 0 0 1 0-1.5H10V7.5a.75.75 0 0 1 .75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M20.496 5.627A2.25 2.25 0 0 1 22 7.75v10A4.25 4.25 0 0 1 17.75 22h-10a2.25 2.25 0 0 1-2.123-1.504l2.097.004H17.75a2.75 2.75 0 0 0 2.75-2.75v-10l-.004-.051V5.627ZM17.246 2a2.25 2.25 0 0 1 2.25 2.25v12.997a2.25 2.25 0 0 1-2.25 2.25H4.25A2.25 2.25 0 0 1 2 17.247V4.25A2.25 2.25 0 0 1 4.25 2h12.997Zm0 1.5H4.25a.75.75 0 0 0-.75.75v12.997c0 .414.336.75.75.75h12.997a.75.75 0 0 0 .75-.75V4.25a.75.75 0 0 0-.75-.75ZM10.75 6.75a.75.75 0 0 1 .75.75V10H14a.75.75 0 0 1 0 1.5h-2.5V14a.75.75 0 0 1-1.5 0v-2.5H7.5a.75.75 0 0 1 0-1.5H10V7.5a.75.75 0 0 1 .75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-create-text-channel]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5 4.75A.75.75 0 0 1 5.75 4h12.5a.75.75 0 0 1 .75.75v2a.75.75 0 0 1-1.5 0V5.5h-4.75v13h1.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5h1.5v-13H6.5v1.25a.75.75 0 0 1-1.5 0v-2Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5 4.75A.75.75 0 0 1 5.75 4h12.5a.75.75 0 0 1 .75.75v2a.75.75 0 0 1-1.5 0V5.5h-4.75v13h1.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5h1.5v-13H6.5v1.25a.75.75 0 0 1-1.5 0v-2Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-create-voice-channel]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M18.25 11a.75.75 0 0 1 .743.648l.007.102v.5a6.75 6.75 0 0 1-6.249 6.732l-.001 2.268a.75.75 0 0 1-1.493.102l-.007-.102v-2.268a6.75 6.75 0 0 1-6.246-6.496L5 12.25v-.5a.75.75 0 0 1 1.493-.102l.007.102v.5a5.25 5.25 0 0 0 5.034 5.246l.216.004h.5a5.25 5.25 0 0 0 5.246-5.034l.004-.216v-.5a.75.75 0 0 1 .75-.75ZM12 2a4 4 0 0 1 4 4v6a4 4 0 0 1-8 0V6a4 4 0 0 1 4-4Zm0 1.5A2.5 2.5 0 0 0 9.5 6v6a2.5 2.5 0 0 0 5 0V6A2.5 2.5 0 0 0 12 3.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M18.25 11a.75.75 0 0 1 .743.648l.007.102v.5a6.75 6.75 0 0 1-6.249 6.732l-.001 2.268a.75.75 0 0 1-1.493.102l-.007-.102v-2.268a6.75 6.75 0 0 1-6.246-6.496L5 12.25v-.5a.75.75 0 0 1 1.493-.102l.007.102v.5a5.25 5.25 0 0 0 5.034 5.246l.216.004h.5a5.25 5.25 0 0 0 5.246-5.034l.004-.216v-.5a.75.75 0 0 1 .75-.75ZM12 2a4 4 0 0 1 4 4v6a4 4 0 0 1-8 0V6a4 4 0 0 1 4-4Zm0 1.5A2.5 2.5 0 0 0 9.5 6v6a2.5 2.5 0 0 0 5 0V6A2.5 2.5 0 0 0 12 3.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-delete-channel]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.75a3.25 3.25 0 0 1 3.245 3.066L15.25 5h5.25a.75.75 0 0 1 .102 1.493L20.5 6.5h-.796l-1.28 13.02a2.75 2.75 0 0 1-2.561 2.474l-.176.006H8.313a2.75 2.75 0 0 1-2.714-2.307l-.023-.174L4.295 6.5H3.5a.75.75 0 0 1-.743-.648L2.75 5.75a.75.75 0 0 1 .648-.743L3.5 5h5.25A3.25 3.25 0 0 1 12 1.75Zm6.197 4.75H5.802l1.267 12.872a1.25 1.25 0 0 0 1.117 1.122l.127.006h7.374c.6 0 1.109-.425 1.225-1.002l.02-.126L18.196 6.5ZM13.75 9.25a.75.75 0 0 1 .743.648L14.5 10v7a.75.75 0 0 1-1.493.102L13 17v-7a.75.75 0 0 1 .75-.75Zm-3.5 0a.75.75 0 0 1 .743.648L11 10v7a.75.75 0 0 1-1.493.102L9.5 17v-7a.75.75 0 0 1 .75-.75Zm1.75-6a1.75 1.75 0 0 0-1.744 1.606L10.25 5h3.5A1.75 1.75 0 0 0 12 3.25Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.75a3.25 3.25 0 0 1 3.245 3.066L15.25 5h5.25a.75.75 0 0 1 .102 1.493L20.5 6.5h-.796l-1.28 13.02a2.75 2.75 0 0 1-2.561 2.474l-.176.006H8.313a2.75 2.75 0 0 1-2.714-2.307l-.023-.174L4.295 6.5H3.5a.75.75 0 0 1-.743-.648L2.75 5.75a.75.75 0 0 1 .648-.743L3.5 5h5.25A3.25 3.25 0 0 1 12 1.75Zm6.197 4.75H5.802l1.267 12.872a1.25 1.25 0 0 0 1.117 1.122l.127.006h7.374c.6 0 1.109-.425 1.225-1.002l.02-.126L18.196 6.5ZM13.75 9.25a.75.75 0 0 1 .743.648L14.5 10v7a.75.75 0 0 1-1.493.102L13 17v-7a.75.75 0 0 1 .75-.75Zm-3.5 0a.75.75 0 0 1 .743.648L11 10v7a.75.75 0 0 1-1.493.102L9.5 17v-7a.75.75 0 0 1 .75-.75Zm1.75-6a1.75 1.75 0 0 0-1.744 1.606L10.25 5h3.5A1.75 1.75 0 0 0 12 3.25Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-channel-notifications]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.996a7.49 7.49 0 0 1 7.496 7.25l.004.25v4.097l1.38 3.156a1.25 1.25 0 0 1-1.145 1.75L15 18.502a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-4.155 3.352-7.5 7.5-7.5ZM13.5 18.5l-3 .002a1.5 1.5 0 0 0 2.993.145l.006-.147ZM12 3.496c-3.32 0-6 2.674-6 6v4.41L4.656 17h14.697L18 13.907V9.509l-.004-.225A5.988 5.988 0 0 0 12 3.496Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.996a7.49 7.49 0 0 1 7.496 7.25l.004.25v4.097l1.38 3.156a1.25 1.25 0 0 1-1.145 1.75L15 18.502a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-4.155 3.352-7.5 7.5-7.5ZM13.5 18.5l-3 .002a1.5 1.5 0 0 0 2.993.145l.006-.147ZM12 3.496c-3.32 0-6 2.674-6 6v4.41L4.656 17h14.697L18 13.907V9.509l-.004-.225A5.988 5.988 0 0 0 12 3.496Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-channel-copy-link]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.25 7a.75.75 0 0 1 .11 1.492l-.11.008H7a3.5 3.5 0 0 0-.206 6.994L7 15.5h2.25a.75.75 0 0 1 .11 1.492L9.25 17H7a5 5 0 0 1-.25-9.994L7 7h2.25ZM17 7a5 5 0 0 1 .25 9.994L17 17h-2.25a.75.75 0 0 1-.11-1.492l.11-.008H17a3.5 3.5 0 0 0 .206-6.994L17 8.5h-2.25a.75.75 0 0 1-.11-1.492L14.75 7H17ZM7 11.25h10a.75.75 0 0 1 .102 1.493L17 12.75H7a.75.75 0 0 1-.102-1.493L7 11.25h10H7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.25 7a.75.75 0 0 1 .11 1.492l-.11.008H7a3.5 3.5 0 0 0-.206 6.994L7 15.5h2.25a.75.75 0 0 1 .11 1.492L9.25 17H7a5 5 0 0 1-.25-9.994L7 7h2.25ZM17 7a5 5 0 0 1 .25 9.994L17 17h-2.25a.75.75 0 0 1-.11-1.492l.11-.008H17a3.5 3.5 0 0 0 .206-6.994L17 8.5h-2.25a.75.75 0 0 1-.11-1.492L14.75 7H17ZM7 11.25h10a.75.75 0 0 1 .102 1.493L17 12.75H7a.75.75 0 0 1-.102-1.493L7 11.25h10H7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=channel-context-devmode-copy-id]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-premium-subscribe]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M13.057 7.431a2.5 2.5 0 1 1 3.536 3.536 2.5 2.5 0 0 1-3.536-3.536Zm2.475 1.06a1 1 0 1 0-1.414 1.415 1 1 0 0 0 1.414-1.414Z" /><path d="M21.509 4.323a2.75 2.75 0 0 0-1.811-1.81l-.663-.206a6.75 6.75 0 0 0-6.773 1.674l-.996.995a3.498 3.498 0 0 0-4.57.327L5.455 6.546a.75.75 0 0 0 0 1.06l1.591 1.591-.18.18a1.75 1.75 0 0 0 0 2.475l.496.495-1.396.796a.75.75 0 0 0-.158 1.182l3.889 3.89a.75.75 0 0 0 1.181-.159l.798-1.395.497.497a1.75 1.75 0 0 0 2.475 0l.177-.176 1.59 1.59a.75.75 0 0 0 1.06 0l1.242-1.243a3.497 3.497 0 0 0 .328-4.568l.998-.998a6.75 6.75 0 0 0 1.673-6.776l-.206-.664Zm-2.256-.378c.393.122.701.43.823.823l.207.664a5.25 5.25 0 0 1-1.302 5.27l-5.395 5.396a.25.25 0 0 1-.353 0L7.926 10.79a.25.25 0 0 1 0-.353l5.396-5.397a5.25 5.25 0 0 1 5.269-1.301l.662.205Zm-1.289 9.896c.453.766.35 1.769-.308 2.427l-.712.712-1.06-1.059 2.08-2.08ZM7.758 6.364a1.998 1.998 0 0 1 2.428-.308l-2.08 2.08-1.06-1.06.712-.712Zm2.818 9.198-.514.897-2.5-2.5.898-.512 2.116 2.115ZM6.69 18.395a.75.75 0 0 0-1.06-1.061l-2.476 2.475a.75.75 0 0 0 1.061 1.06l2.475-2.474ZM4.745 15.39a.75.75 0 0 1 0 1.06l-1.06 1.06a.75.75 0 1 1-1.061-1.06l1.06-1.06a.75.75 0 0 1 1.061 0ZM8.632 20.341a.75.75 0 1 0-1.06-1.06l-1.059 1.058a.75.75 0 0 0 1.06 1.06l1.06-1.058Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M13.057 7.431a2.5 2.5 0 1 1 3.536 3.536 2.5 2.5 0 0 1-3.536-3.536Zm2.475 1.06a1 1 0 1 0-1.414 1.415 1 1 0 0 0 1.414-1.414Z" /><path d="M21.509 4.323a2.75 2.75 0 0 0-1.811-1.81l-.663-.206a6.75 6.75 0 0 0-6.773 1.674l-.996.995a3.498 3.498 0 0 0-4.57.327L5.455 6.546a.75.75 0 0 0 0 1.06l1.591 1.591-.18.18a1.75 1.75 0 0 0 0 2.475l.496.495-1.396.796a.75.75 0 0 0-.158 1.182l3.889 3.89a.75.75 0 0 0 1.181-.159l.798-1.395.497.497a1.75 1.75 0 0 0 2.475 0l.177-.176 1.59 1.59a.75.75 0 0 0 1.06 0l1.242-1.243a3.497 3.497 0 0 0 .328-4.568l.998-.998a6.75 6.75 0 0 0 1.673-6.776l-.206-.664Zm-2.256-.378c.393.122.701.43.823.823l.207.664a5.25 5.25 0 0 1-1.302 5.27l-5.395 5.396a.25.25 0 0 1-.353 0L7.926 10.79a.25.25 0 0 1 0-.353l5.396-5.397a5.25 5.25 0 0 1 5.269-1.301l.662.205Zm-1.289 9.896c.453.766.35 1.769-.308 2.427l-.712.712-1.06-1.059 2.08-2.08ZM7.758 6.364a1.998 1.998 0 0 1 2.428-.308l-2.08 2.08-1.06-1.06.712-.712Zm2.818 9.198-.514.897-2.5-2.5.898-.512 2.116 2.115ZM6.69 18.395a.75.75 0 0 0-1.06-1.061l-2.476 2.475a.75.75 0 0 0 1.061 1.06l2.475-2.474ZM4.745 15.39a.75.75 0 0 1 0 1.06l-1.06 1.06a.75.75 0 1 1-1.061-1.06l1.06-1.06a.75.75 0 0 1 1.061 0ZM8.632 20.341a.75.75 0 1 0-1.06-1.06l-1.059 1.058a.75.75 0 0 0 1.06 1.06l1.06-1.058Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-invite-people]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-settings]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.012 2.25c.734.008 1.465.093 2.182.253a.75.75 0 0 1 .582.649l.17 1.527a1.384 1.384 0 0 0 1.927 1.116l1.401-.615a.75.75 0 0 1 .85.174 9.792 9.792 0 0 1 2.204 3.792.75.75 0 0 1-.271.825l-1.242.916a1.381 1.381 0 0 0 0 2.226l1.243.915a.75.75 0 0 1 .272.826 9.797 9.797 0 0 1-2.204 3.792.75.75 0 0 1-.848.175l-1.407-.617a1.38 1.38 0 0 0-1.926 1.114l-.169 1.526a.75.75 0 0 1-.572.647 9.518 9.518 0 0 1-4.406 0 .75.75 0 0 1-.572-.647l-.168-1.524a1.382 1.382 0 0 0-1.926-1.11l-1.406.616a.75.75 0 0 1-.849-.175 9.798 9.798 0 0 1-2.204-3.796.75.75 0 0 1 .272-.826l1.243-.916a1.38 1.38 0 0 0 0-2.226l-1.243-.914a.75.75 0 0 1-.271-.826 9.793 9.793 0 0 1 2.204-3.792.75.75 0 0 1 .85-.174l1.4.615a1.387 1.387 0 0 0 1.93-1.118l.17-1.526a.75.75 0 0 1 .583-.65c.717-.159 1.45-.243 2.201-.252Zm0 1.5a9.135 9.135 0 0 0-1.354.117l-.109.977A2.886 2.886 0 0 1 6.525 7.17l-.898-.394a8.293 8.293 0 0 0-1.348 2.317l.798.587a2.881 2.881 0 0 1 0 4.643l-.799.588c.32.842.776 1.626 1.348 2.322l.905-.397a2.882 2.882 0 0 1 4.017 2.318l.11.984c.889.15 1.798.15 2.687 0l.11-.984a2.881 2.881 0 0 1 4.018-2.322l.905.396a8.296 8.296 0 0 0 1.347-2.318l-.798-.588a2.881 2.881 0 0 1 0-4.643l.796-.587a8.293 8.293 0 0 0-1.348-2.317l-.896.393a2.884 2.884 0 0 1-4.023-2.324l-.11-.976a8.988 8.988 0 0 0-1.333-.117ZM12 8.25a3.75 3.75 0 1 1 0 7.5 3.75 3.75 0 0 1 0-7.5Zm0 1.5a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.012 2.25c.734.008 1.465.093 2.182.253a.75.75 0 0 1 .582.649l.17 1.527a1.384 1.384 0 0 0 1.927 1.116l1.401-.615a.75.75 0 0 1 .85.174 9.792 9.792 0 0 1 2.204 3.792.75.75 0 0 1-.271.825l-1.242.916a1.381 1.381 0 0 0 0 2.226l1.243.915a.75.75 0 0 1 .272.826 9.797 9.797 0 0 1-2.204 3.792.75.75 0 0 1-.848.175l-1.407-.617a1.38 1.38 0 0 0-1.926 1.114l-.169 1.526a.75.75 0 0 1-.572.647 9.518 9.518 0 0 1-4.406 0 .75.75 0 0 1-.572-.647l-.168-1.524a1.382 1.382 0 0 0-1.926-1.11l-1.406.616a.75.75 0 0 1-.849-.175 9.798 9.798 0 0 1-2.204-3.796.75.75 0 0 1 .272-.826l1.243-.916a1.38 1.38 0 0 0 0-2.226l-1.243-.914a.75.75 0 0 1-.271-.826 9.793 9.793 0 0 1 2.204-3.792.75.75 0 0 1 .85-.174l1.4.615a1.387 1.387 0 0 0 1.93-1.118l.17-1.526a.75.75 0 0 1 .583-.65c.717-.159 1.45-.243 2.201-.252Zm0 1.5a9.135 9.135 0 0 0-1.354.117l-.109.977A2.886 2.886 0 0 1 6.525 7.17l-.898-.394a8.293 8.293 0 0 0-1.348 2.317l.798.587a2.881 2.881 0 0 1 0 4.643l-.799.588c.32.842.776 1.626 1.348 2.322l.905-.397a2.882 2.882 0 0 1 4.017 2.318l.11.984c.889.15 1.798.15 2.687 0l.11-.984a2.881 2.881 0 0 1 4.018-2.322l.905.396a8.296 8.296 0 0 0 1.347-2.318l-.798-.588a2.881 2.881 0 0 1 0-4.643l.796-.587a8.293 8.293 0 0 0-1.348-2.317l-.896.393a2.884 2.884 0 0 1-4.023-2.324l-.11-.976a8.988 8.988 0 0 0-1.333-.117ZM12 8.25a3.75 3.75 0 1 1 0 7.5 3.75 3.75 0 0 1 0-7.5Zm0 1.5a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-create-channel]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m11.066 8.004.184-.005h7.5a3.25 3.25 0 0 1 3.245 3.065l.005.185v7.5a3.25 3.25 0 0 1-3.066 3.245l-.184.005h-7.5a3.25 3.25 0 0 1-3.245-3.066L8 18.75v-7.5a3.25 3.25 0 0 1 3.066-3.245Zm7.684 1.495h-7.5a1.75 1.75 0 0 0-1.744 1.606l-.006.144v7.5a1.75 1.75 0 0 0 1.607 1.744l.143.006h7.5a1.75 1.75 0 0 0 1.744-1.607l.006-.143v-7.5a1.75 1.75 0 0 0-1.75-1.75ZM15 11a.75.75 0 0 1 .75.75v2.498h2.5a.75.75 0 0 1 0 1.5h-2.5v2.502a.75.75 0 0 1-1.5 0v-2.502h-2.5a.75.75 0 1 1 0-1.5h2.5V11.75A.75.75 0 0 1 15 11Zm.582-6.767.052.177.693 2.588h-1.553l-.588-2.2a1.75 1.75 0 0 0-2.144-1.238L4.798 5.502a1.75 1.75 0 0 0-1.27 1.995l.032.148 1.942 7.244A1.75 1.75 0 0 0 7 16.176v1.506a3.252 3.252 0 0 1-2.895-2.228l-.052-.176-1.941-7.245a3.25 3.25 0 0 1 2.12-3.928l.178-.052 7.244-1.941a3.25 3.25 0 0 1 3.928 2.12Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m11.066 8.004.184-.005h7.5a3.25 3.25 0 0 1 3.245 3.065l.005.185v7.5a3.25 3.25 0 0 1-3.066 3.245l-.184.005h-7.5a3.25 3.25 0 0 1-3.245-3.066L8 18.75v-7.5a3.25 3.25 0 0 1 3.066-3.245Zm7.684 1.495h-7.5a1.75 1.75 0 0 0-1.744 1.606l-.006.144v7.5a1.75 1.75 0 0 0 1.607 1.744l.143.006h7.5a1.75 1.75 0 0 0 1.744-1.607l.006-.143v-7.5a1.75 1.75 0 0 0-1.75-1.75ZM15 11a.75.75 0 0 1 .75.75v2.498h2.5a.75.75 0 0 1 0 1.5h-2.5v2.502a.75.75 0 0 1-1.5 0v-2.502h-2.5a.75.75 0 1 1 0-1.5h2.5V11.75A.75.75 0 0 1 15 11Zm.582-6.767.052.177.693 2.588h-1.553l-.588-2.2a1.75 1.75 0 0 0-2.144-1.238L4.798 5.502a1.75 1.75 0 0 0-1.27 1.995l.032.148 1.942 7.244A1.75 1.75 0 0 0 7 16.176v1.506a3.252 3.252 0 0 1-2.895-2.228l-.052-.176-1.941-7.245a3.25 3.25 0 0 1 2.12-3.928l.178-.052 7.244-1.941a3.25 3.25 0 0 1 3.928 2.12Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-create-category]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m11.066 8.004.184-.005h7.5a3.25 3.25 0 0 1 3.245 3.065l.005.185v1.56a6.518 6.518 0 0 0-1.5-1.077v-.483a1.75 1.75 0 0 0-1.75-1.75h-7.5a1.75 1.75 0 0 0-1.744 1.606l-.006.144v7.5a1.75 1.75 0 0 0 1.607 1.744l.143.006h.482c.287.55.65 1.055 1.076 1.5H11.25a3.25 3.25 0 0 1-3.245-3.066L8 18.75v-7.5a3.25 3.25 0 0 1 3.066-3.245Z" /><path d="m15.582 4.233.052.177.693 2.588h-1.553l-.588-2.2a1.75 1.75 0 0 0-2.144-1.238L4.798 5.502a1.75 1.75 0 0 0-1.27 1.995l.032.148 1.942 7.244A1.75 1.75 0 0 0 7 16.176v1.506a3.252 3.252 0 0 1-2.895-2.228l-.052-.176-1.941-7.245a3.25 3.25 0 0 1 2.12-3.928l.178-.052 7.244-1.941a3.25 3.25 0 0 1 3.928 2.12ZM23 17.5a5.5 5.5 0 1 0-11 0 5.5 5.5 0 0 0 11 0Zm-5.59-3.493L17.5 14l.09.008a.5.5 0 0 1 .402.402l.008.09V17l2.505.001.09.008a.5.5 0 0 1 .402.402l.008.09-.008.09a.5.5 0 0 1-.403.402l-.09.008h-2.503v2.503l-.008.09a.5.5 0 0 1-.402.402l-.09.008-.09-.008a.5.5 0 0 1-.402-.402l-.008-.09V18L14.498 18l-.09-.008a.5.5 0 0 1-.402-.402l-.008-.09.008-.09a.5.5 0 0 1 .402-.402l.09-.008H17v-2.5l.008-.09a.5.5 0 0 1 .402-.403Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m11.066 8.004.184-.005h7.5a3.25 3.25 0 0 1 3.245 3.065l.005.185v1.56a6.518 6.518 0 0 0-1.5-1.077v-.483a1.75 1.75 0 0 0-1.75-1.75h-7.5a1.75 1.75 0 0 0-1.744 1.606l-.006.144v7.5a1.75 1.75 0 0 0 1.607 1.744l.143.006h.482c.287.55.65 1.055 1.076 1.5H11.25a3.25 3.25 0 0 1-3.245-3.066L8 18.75v-7.5a3.25 3.25 0 0 1 3.066-3.245Z" /><path d="m15.582 4.233.052.177.693 2.588h-1.553l-.588-2.2a1.75 1.75 0 0 0-2.144-1.238L4.798 5.502a1.75 1.75 0 0 0-1.27 1.995l.032.148 1.942 7.244A1.75 1.75 0 0 0 7 16.176v1.506a3.252 3.252 0 0 1-2.895-2.228l-.052-.176-1.941-7.245a3.25 3.25 0 0 1 2.12-3.928l.178-.052 7.244-1.941a3.25 3.25 0 0 1 3.928 2.12ZM23 17.5a5.5 5.5 0 1 0-11 0 5.5 5.5 0 0 0 11 0Zm-5.59-3.493L17.5 14l.09.008a.5.5 0 0 1 .402.402l.008.09V17l2.505.001.09.008a.5.5 0 0 1 .402.402l.008.09-.008.09a.5.5 0 0 1-.403.402l-.09.008h-2.503v2.503l-.008.09a.5.5 0 0 1-.402.402l-.09.008-.09-.008a.5.5 0 0 1-.402-.402l-.008-.09V18L14.498 18l-.09-.008a.5.5 0 0 1-.402-.402l-.008-.09.008-.09a.5.5 0 0 1 .402-.402l.09-.008H17v-2.5l.008-.09a.5.5 0 0 1 .402-.403Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-create-event]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm1.75 5.5h-15v9.25c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V8.5Zm-11.75 6a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm-4.25-4a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm1.5-6H6.25A1.75 1.75 0 0 0 4.5 6.25V7h15v-.75a1.75 1.75 0 0 0-1.75-1.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm1.75 5.5h-15v9.25c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V8.5Zm-11.75 6a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm-4.25-4a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm1.5-6H6.25A1.75 1.75 0 0 0 4.5 6.25V7h15v-.75a1.75 1.75 0 0 0-1.75-1.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-notifications]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.996a7.49 7.49 0 0 1 7.496 7.25l.004.25v4.097l1.38 3.156a1.25 1.25 0 0 1-1.145 1.75L15 18.502a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-4.155 3.352-7.5 7.5-7.5ZM13.5 18.5l-3 .002a1.5 1.5 0 0 0 2.993.145l.006-.147ZM12 3.496c-3.32 0-6 2.674-6 6v4.41L4.656 17h14.697L18 13.907V9.509l-.004-.225A5.988 5.988 0 0 0 12 3.496Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.996a7.49 7.49 0 0 1 7.496 7.25l.004.25v4.097l1.38 3.156a1.25 1.25 0 0 1-1.145 1.75L15 18.502a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-4.155 3.352-7.5 7.5-7.5ZM13.5 18.5l-3 .002a1.5 1.5 0 0 0 2.993.145l.006-.147ZM12 3.496c-3.32 0-6 2.674-6 6v4.41L4.656 17h14.697L18 13.907V9.509l-.004-.225A5.988 5.988 0 0 0 12 3.496Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-privacy]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3 5.75A.75.75 0 0 1 3.75 5c2.663 0 5.258-.943 7.8-2.85a.75.75 0 0 1 .9 0C14.992 4.057 17.587 5 20.25 5a.75.75 0 0 1 .75.75V11c0 .338-.014.67-.04.996a6.467 6.467 0 0 0-1.465-.684c.003-.103.005-.207.005-.312V6.478c-2.577-.152-5.08-1.09-7.5-2.8-2.42 1.71-4.923 2.648-7.5 2.8V11c0 4.149 2.332 7.221 7.125 9.285a6.506 6.506 0 0 0 1.005 1.52l-.355.143a.75.75 0 0 1-.55 0C5.958 19.676 3 16 3 11V5.75ZM23 17.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0Zm-2.146-2.354a.5.5 0 0 0-.708 0L16.5 18.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.708Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3 5.75A.75.75 0 0 1 3.75 5c2.663 0 5.258-.943 7.8-2.85a.75.75 0 0 1 .9 0C14.992 4.057 17.587 5 20.25 5a.75.75 0 0 1 .75.75V11c0 .338-.014.67-.04.996a6.467 6.467 0 0 0-1.465-.684c.003-.103.005-.207.005-.312V6.478c-2.577-.152-5.08-1.09-7.5-2.8-2.42 1.71-4.923 2.648-7.5 2.8V11c0 4.149 2.332 7.221 7.125 9.285a6.506 6.506 0 0 0 1.005 1.52l-.355.143a.75.75 0 0 1-.55 0C5.958 19.676 3 16 3 11V5.75ZM23 17.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0Zm-2.146-2.354a.5.5 0 0 0-.708 0L16.5 18.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.708Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-change-nickname]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-leave]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M8.502 11.5a1.002 1.002 0 1 1 0 2.004 1.002 1.002 0 0 1 0-2.004Z" /><path d="M12 4.354v6.651l7.442-.001L17.72 9.28a.75.75 0 0 1-.073-.976l.073-.084a.75.75 0 0 1 .976-.073l.084.073 2.997 2.997a.75.75 0 0 1 .073.976l-.073.084-2.996 3.004a.75.75 0 0 1-1.134-.975l.072-.085 1.713-1.717-7.431.001L12 19.25a.75.75 0 0 1-.88.739l-8.5-1.502A.75.75 0 0 1 2 17.75V5.75a.75.75 0 0 1 .628-.74l8.5-1.396a.75.75 0 0 1 .872.74Zm-1.5.883-7 1.15V17.12l7 1.236V5.237Z" /><path d="M13 18.501h.765l.102-.006a.75.75 0 0 0 .648-.745l-.007-4.25H13v5.001ZM13.002 10 13 8.725V5h.745a.75.75 0 0 1 .743.647l.007.102.007 4.251h-1.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M8.502 11.5a1.002 1.002 0 1 1 0 2.004 1.002 1.002 0 0 1 0-2.004Z" /><path d="M12 4.354v6.651l7.442-.001L17.72 9.28a.75.75 0 0 1-.073-.976l.073-.084a.75.75 0 0 1 .976-.073l.084.073 2.997 2.997a.75.75 0 0 1 .073.976l-.073.084-2.996 3.004a.75.75 0 0 1-1.134-.975l.072-.085 1.713-1.717-7.431.001L12 19.25a.75.75 0 0 1-.88.739l-8.5-1.502A.75.75 0 0 1 2 17.75V5.75a.75.75 0 0 1 .628-.74l8.5-1.396a.75.75 0 0 1 .872.74Zm-1.5.883-7 1.15V17.12l7 1.236V5.237Z" /><path d="M13 18.501h.765l.102-.006a.75.75 0 0 0 .648-.745l-.007-4.25H13v5.001ZM13.002 10 13 8.725V5h.745a.75.75 0 0 1 .743.647l.007.102.007 4.251h-1.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-application-directory]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm0 1.5H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V6.25a1.75 1.75 0 0 0-1.75-1.75ZM9.369 15.254l-.51.872a.75.75 0 0 1-1.34-.665l.045-.091.067-.116h1.738Zm3.924-5.23 1.719 2.98h1.74a.75.75 0 0 1 .743.65l.007.1a.75.75 0 0 1-.648.744l-.102.007h-.875l.502.87a.75.75 0 0 1-1.243.834l-.056-.085-2.658-4.608.87-1.492Zm-.03-2.923a.75.75 0 0 1 .315.935l-.046.091-2.85 4.877h1.732l.865 1.5H7.252a.75.75 0 0 1-.102-1.492l.102-.007h1.694l2.18-3.734-.662-1.147a.75.75 0 0 1 .19-.968l.085-.057a.75.75 0 0 1 .968.19l.056.085.233.406.241-.41a.75.75 0 0 1 1.026-.269Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm0 1.5H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V6.25a1.75 1.75 0 0 0-1.75-1.75ZM9.369 15.254l-.51.872a.75.75 0 0 1-1.34-.665l.045-.091.067-.116h1.738Zm3.924-5.23 1.719 2.98h1.74a.75.75 0 0 1 .743.65l.007.1a.75.75 0 0 1-.648.744l-.102.007h-.875l.502.87a.75.75 0 0 1-1.243.834l-.056-.085-2.658-4.608.87-1.492Zm-.03-2.923a.75.75 0 0 1 .315.935l-.046.091-2.85 4.877h1.732l.865 1.5H7.252a.75.75 0 0 1-.102-1.492l.102-.007h1.694l2.18-3.734-.662-1.147a.75.75 0 0 1 .19-.968l.085-.057a.75.75 0 0 1 .968.19l.056.085.233.406.241-.41a.75.75 0 0 1 1.026-.269Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-report-raid]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.907 5.622c.062.208.093.424.093.641V17.74a2.25 2.25 0 0 1-2.891 2.156l-5.514-1.64a4.002 4.002 0 0 1-7.59-1.556L6 16.5l-.001-.5-2.39-.711A2.25 2.25 0 0 1 2 13.131V10.87a2.25 2.25 0 0 1 1.61-2.156l15.5-4.606a2.25 2.25 0 0 1 2.797 1.515ZM7.499 16.445l.001.054a2.5 2.5 0 0 0 4.624 1.321l-4.625-1.375Zm12.037-10.9-15.5 4.605a.75.75 0 0 0-.536.72v2.261a.75.75 0 0 0 .536.72l15.5 4.607a.75.75 0 0 0 .964-.72V6.264a.75.75 0 0 0-.964-.719Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.907 5.622c.062.208.093.424.093.641V17.74a2.25 2.25 0 0 1-2.891 2.156l-5.514-1.64a4.002 4.002 0 0 1-7.59-1.556L6 16.5l-.001-.5-2.39-.711A2.25 2.25 0 0 1 2 13.131V10.87a2.25 2.25 0 0 1 1.61-2.156l15.5-4.606a2.25 2.25 0 0 1 2.797 1.515ZM7.499 16.445l.001.054a2.5 2.5 0 0 0 4.624 1.321l-4.625-1.375Zm12.037-10.9-15.5 4.605a.75.75 0 0 0-.536.72v2.261a.75.75 0 0 0 .536.72l15.5 4.607a.75.75 0 0 0 .964-.72V6.264a.75.75 0 0 0-.964-.719Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-active-threads]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.009 5.009A3.25 3.25 0 0 1 8.25 2h9A4.75 4.75 0 0 1 22 6.75v6a3.25 3.25 0 0 1-3.009 3.241A3.25 3.25 0 0 1 15.75 19h-5.083L7 21.75c-.824.618-2 .03-2-1v-1.76a3.25 3.25 0 0 1-3-3.24v-7.5a3.25 3.25 0 0 1 3.009-3.241ZM6.518 5h9.232A3.25 3.25 0 0 1 19 8.25v6.232a1.75 1.75 0 0 0 1.5-1.732v-6a3.25 3.25 0 0 0-3.25-3.25h-9A1.75 1.75 0 0 0 6.518 5ZM5.25 17.5H6.5v2.75l3.667-2.75h5.583a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 8.25v7.5c0 .966.784 1.75 1.75 1.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.009 5.009A3.25 3.25 0 0 1 8.25 2h9A4.75 4.75 0 0 1 22 6.75v6a3.25 3.25 0 0 1-3.009 3.241A3.25 3.25 0 0 1 15.75 19h-5.083L7 21.75c-.824.618-2 .03-2-1v-1.76a3.25 3.25 0 0 1-3-3.24v-7.5a3.25 3.25 0 0 1 3.009-3.241ZM6.518 5h9.232A3.25 3.25 0 0 1 19 8.25v6.232a1.75 1.75 0 0 0 1.5-1.732v-6a3.25 3.25 0 0 0-3.25-3.25h-9A1.75 1.75 0 0 0 6.518 5ZM5.25 17.5H6.5v2.75l3.667-2.75h5.583a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 8.25v7.5c0 .966.784 1.75 1.75 1.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-header-popout-insights]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-mark-guild-read]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-invite-people]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.477 2a6.47 6.47 0 0 0-.709 1.5H4.253a.749.749 0 0 0-.75.75v.577c0 .535.192 1.053.54 1.46 1.253 1.469 3.22 2.214 5.957 2.214.597 0 1.157-.035 1.68-.106.246.495.553.954.912 1.367-.795.16-1.66.24-2.592.24-3.146 0-5.532-.906-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.578A2.249 2.249 0 0 1 4.253 14h7.77Zm5.477 0-.09.008a.5.5 0 0 0-.402.402L17 14.5V17h-2.496l-.09.008a.5.5 0 0 0-.402.402l-.008.09.008.09a.5.5 0 0 0 .402.402l.09.008H17L17 20.5l.008.09a.5.5 0 0 0 .402.402l.09.008.09-.008a.5.5 0 0 0 .402-.402L18 20.5V18h2.504l.09-.008a.5.5 0 0 0 .402-.402l.008-.09-.008-.09a.5.5 0 0 0-.402-.402l-.09-.008H18L18 14.5l-.008-.09a.5.5 0 0 0-.402-.402L17.5 14ZM10 2.005a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-unmute-guild]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-mute-guild]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.92 3.316c.806-.717 2.08-.145 2.08.934v15.496c0 1.078-1.274 1.65-2.08.934l-4.492-3.994a.75.75 0 0 0-.498-.19H4.25A2.25 2.25 0 0 1 2 14.247V9.75a2.25 2.25 0 0 1 2.25-2.25h3.68a.75.75 0 0 0 .498-.19l4.491-3.993Zm.58 1.49L9.425 8.43A2.25 2.25 0 0 1 7.93 9H4.25a.75.75 0 0 0-.75.75v4.497c0 .415.336.75.75.75h3.68a2.25 2.25 0 0 1 1.495.57l4.075 3.623V4.807ZM16.22 9.22a.75.75 0 0 1 1.06 0L19 10.94l1.72-1.72a.75.75 0 1 1 1.06 1.06L20.06 12l1.72 1.72a.75.75 0 1 1-1.06 1.06L19 13.06l-1.72 1.72a.75.75 0 1 1-1.06-1.06L17.94 12l-1.72-1.72a.75.75 0 0 1 0-1.06Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-guild-notifications]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.996a7.49 7.49 0 0 1 7.496 7.25l.004.25v4.097l1.38 3.156a1.25 1.25 0 0 1-1.145 1.75L15 18.502a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-4.155 3.352-7.5 7.5-7.5ZM13.5 18.5l-3 .002a1.5 1.5 0 0 0 2.993.145l.006-.147ZM12 3.496c-3.32 0-6 2.674-6 6v4.41L4.656 17h14.697L18 13.907V9.509l-.004-.225A5.988 5.988 0 0 0 12 3.496Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 1.996a7.49 7.49 0 0 1 7.496 7.25l.004.25v4.097l1.38 3.156a1.25 1.25 0 0 1-1.145 1.75L15 18.502a3 3 0 0 1-5.995.177L9 18.499H4.275a1.251 1.251 0 0 1-1.147-1.747L4.5 13.594V9.496c0-4.155 3.352-7.5 7.5-7.5ZM13.5 18.5l-3 .002a1.5 1.5 0 0 0 2.993.145l.006-.147ZM12 3.496c-3.32 0-6 2.674-6 6v4.41L4.656 17h14.697L18 13.907V9.509l-.004-.225A5.988 5.988 0 0 0 12 3.496Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-hide-muted-channels]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 9.005a4 4 0 1 1 0 8 4 4 0 0 1 0-8Zm0 1.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5ZM12 5.5c4.613 0 8.596 3.15 9.701 7.564a.75.75 0 1 1-1.455.365 8.503 8.503 0 0 0-16.493.004.75.75 0 0 1-1.455-.363A10.003 10.003 0 0 1 12 5.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-guild-settings]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.012 2.25c.734.008 1.465.093 2.182.253a.75.75 0 0 1 .582.649l.17 1.527a1.384 1.384 0 0 0 1.927 1.116l1.401-.615a.75.75 0 0 1 .85.174 9.792 9.792 0 0 1 2.204 3.792.75.75 0 0 1-.271.825l-1.242.916a1.381 1.381 0 0 0 0 2.226l1.243.915a.75.75 0 0 1 .272.826 9.797 9.797 0 0 1-2.204 3.792.75.75 0 0 1-.848.175l-1.407-.617a1.38 1.38 0 0 0-1.926 1.114l-.169 1.526a.75.75 0 0 1-.572.647 9.518 9.518 0 0 1-4.406 0 .75.75 0 0 1-.572-.647l-.168-1.524a1.382 1.382 0 0 0-1.926-1.11l-1.406.616a.75.75 0 0 1-.849-.175 9.798 9.798 0 0 1-2.204-3.796.75.75 0 0 1 .272-.826l1.243-.916a1.38 1.38 0 0 0 0-2.226l-1.243-.914a.75.75 0 0 1-.271-.826 9.793 9.793 0 0 1 2.204-3.792.75.75 0 0 1 .85-.174l1.4.615a1.387 1.387 0 0 0 1.93-1.118l.17-1.526a.75.75 0 0 1 .583-.65c.717-.159 1.45-.243 2.201-.252Zm0 1.5a9.135 9.135 0 0 0-1.354.117l-.109.977A2.886 2.886 0 0 1 6.525 7.17l-.898-.394a8.293 8.293 0 0 0-1.348 2.317l.798.587a2.881 2.881 0 0 1 0 4.643l-.799.588c.32.842.776 1.626 1.348 2.322l.905-.397a2.882 2.882 0 0 1 4.017 2.318l.11.984c.889.15 1.798.15 2.687 0l.11-.984a2.881 2.881 0 0 1 4.018-2.322l.905.396a8.296 8.296 0 0 0 1.347-2.318l-.798-.588a2.881 2.881 0 0 1 0-4.643l.796-.587a8.293 8.293 0 0 0-1.348-2.317l-.896.393a2.884 2.884 0 0 1-4.023-2.324l-.11-.976a8.988 8.988 0 0 0-1.333-.117ZM12 8.25a3.75 3.75 0 1 1 0 7.5 3.75 3.75 0 0 1 0-7.5Zm0 1.5a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.012 2.25c.734.008 1.465.093 2.182.253a.75.75 0 0 1 .582.649l.17 1.527a1.384 1.384 0 0 0 1.927 1.116l1.401-.615a.75.75 0 0 1 .85.174 9.792 9.792 0 0 1 2.204 3.792.75.75 0 0 1-.271.825l-1.242.916a1.381 1.381 0 0 0 0 2.226l1.243.915a.75.75 0 0 1 .272.826 9.797 9.797 0 0 1-2.204 3.792.75.75 0 0 1-.848.175l-1.407-.617a1.38 1.38 0 0 0-1.926 1.114l-.169 1.526a.75.75 0 0 1-.572.647 9.518 9.518 0 0 1-4.406 0 .75.75 0 0 1-.572-.647l-.168-1.524a1.382 1.382 0 0 0-1.926-1.11l-1.406.616a.75.75 0 0 1-.849-.175 9.798 9.798 0 0 1-2.204-3.796.75.75 0 0 1 .272-.826l1.243-.916a1.38 1.38 0 0 0 0-2.226l-1.243-.914a.75.75 0 0 1-.271-.826 9.793 9.793 0 0 1 2.204-3.792.75.75 0 0 1 .85-.174l1.4.615a1.387 1.387 0 0 0 1.93-1.118l.17-1.526a.75.75 0 0 1 .583-.65c.717-.159 1.45-.243 2.201-.252Zm0 1.5a9.135 9.135 0 0 0-1.354.117l-.109.977A2.886 2.886 0 0 1 6.525 7.17l-.898-.394a8.293 8.293 0 0 0-1.348 2.317l.798.587a2.881 2.881 0 0 1 0 4.643l-.799.588c.32.842.776 1.626 1.348 2.322l.905-.397a2.882 2.882 0 0 1 4.017 2.318l.11.984c.889.15 1.798.15 2.687 0l.11-.984a2.881 2.881 0 0 1 4.018-2.322l.905.396a8.296 8.296 0 0 0 1.347-2.318l-.798-.588a2.881 2.881 0 0 1 0-4.643l.796-.587a8.293 8.293 0 0 0-1.348-2.317l-.896.393a2.884 2.884 0 0 1-4.023-2.324l-.11-.976a8.988 8.988 0 0 0-1.333-.117ZM12 8.25a3.75 3.75 0 1 1 0 7.5 3.75 3.75 0 0 1 0-7.5Zm0 1.5a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-privacy]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3 5.75A.75.75 0 0 1 3.75 5c2.663 0 5.258-.943 7.8-2.85a.75.75 0 0 1 .9 0C14.992 4.057 17.587 5 20.25 5a.75.75 0 0 1 .75.75V11c0 .338-.014.67-.04.996a6.467 6.467 0 0 0-1.465-.684c.003-.103.005-.207.005-.312V6.478c-2.577-.152-5.08-1.09-7.5-2.8-2.42 1.71-4.923 2.648-7.5 2.8V11c0 4.149 2.332 7.221 7.125 9.285a6.506 6.506 0 0 0 1.005 1.52l-.355.143a.75.75 0 0 1-.55 0C5.958 19.676 3 16 3 11V5.75ZM23 17.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0Zm-2.146-2.354a.5.5 0 0 0-.708 0L16.5 18.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.708Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M3 5.75A.75.75 0 0 1 3.75 5c2.663 0 5.258-.943 7.8-2.85a.75.75 0 0 1 .9 0C14.992 4.057 17.587 5 20.25 5a.75.75 0 0 1 .75.75V11c0 .338-.014.67-.04.996a6.467 6.467 0 0 0-1.465-.684c.003-.103.005-.207.005-.312V6.478c-2.577-.152-5.08-1.09-7.5-2.8-2.42 1.71-4.923 2.648-7.5 2.8V11c0 4.149 2.332 7.221 7.125 9.285a6.506 6.506 0 0 0 1.005 1.52l-.355.143a.75.75 0 0 1-.55 0C5.958 19.676 3 16 3 11V5.75ZM23 17.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0Zm-2.146-2.354a.5.5 0 0 0-.708 0L16.5 18.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.708Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-change-nickname]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-leave-guild]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M8.502 11.5a1.002 1.002 0 1 1 0 2.004 1.002 1.002 0 0 1 0-2.004Z" /><path d="M12 4.354v6.651l7.442-.001L17.72 9.28a.75.75 0 0 1-.073-.976l.073-.084a.75.75 0 0 1 .976-.073l.084.073 2.997 2.997a.75.75 0 0 1 .073.976l-.073.084-2.996 3.004a.75.75 0 0 1-1.134-.975l.072-.085 1.713-1.717-7.431.001L12 19.25a.75.75 0 0 1-.88.739l-8.5-1.502A.75.75 0 0 1 2 17.75V5.75a.75.75 0 0 1 .628-.74l8.5-1.396a.75.75 0 0 1 .872.74Zm-1.5.883-7 1.15V17.12l7 1.236V5.237Z" /><path d="M13 18.501h.765l.102-.006a.75.75 0 0 0 .648-.745l-.007-4.25H13v5.001ZM13.002 10 13 8.725V5h.745a.75.75 0 0 1 .743.647l.007.102.007 4.251h-1.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M8.502 11.5a1.002 1.002 0 1 1 0 2.004 1.002 1.002 0 0 1 0-2.004Z" /><path d="M12 4.354v6.651l7.442-.001L17.72 9.28a.75.75 0 0 1-.073-.976l.073-.084a.75.75 0 0 1 .976-.073l.084.073 2.997 2.997a.75.75 0 0 1 .073.976l-.073.084-2.996 3.004a.75.75 0 0 1-1.134-.975l.072-.085 1.713-1.717-7.431.001L12 19.25a.75.75 0 0 1-.88.739l-8.5-1.502A.75.75 0 0 1 2 17.75V5.75a.75.75 0 0 1 .628-.74l8.5-1.396a.75.75 0 0 1 .872.74Zm-1.5.883-7 1.15V17.12l7 1.236V5.237Z" /><path d="M13 18.501h.765l.102-.006a.75.75 0 0 0 .648-.745l-.007-4.25H13v5.001ZM13.002 10 13 8.725V5h.745a.75.75 0 0 1 .743.647l.007.102.007 4.251h-1.5Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-devmode-copy-id]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-create-channel]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m11.066 8.004.184-.005h7.5a3.25 3.25 0 0 1 3.245 3.065l.005.185v7.5a3.25 3.25 0 0 1-3.066 3.245l-.184.005h-7.5a3.25 3.25 0 0 1-3.245-3.066L8 18.75v-7.5a3.25 3.25 0 0 1 3.066-3.245Zm7.684 1.495h-7.5a1.75 1.75 0 0 0-1.744 1.606l-.006.144v7.5a1.75 1.75 0 0 0 1.607 1.744l.143.006h7.5a1.75 1.75 0 0 0 1.744-1.607l.006-.143v-7.5a1.75 1.75 0 0 0-1.75-1.75ZM15 11a.75.75 0 0 1 .75.75v2.498h2.5a.75.75 0 0 1 0 1.5h-2.5v2.502a.75.75 0 0 1-1.5 0v-2.502h-2.5a.75.75 0 1 1 0-1.5h2.5V11.75A.75.75 0 0 1 15 11Zm.582-6.767.052.177.693 2.588h-1.553l-.588-2.2a1.75 1.75 0 0 0-2.144-1.238L4.798 5.502a1.75 1.75 0 0 0-1.27 1.995l.032.148 1.942 7.244A1.75 1.75 0 0 0 7 16.176v1.506a3.252 3.252 0 0 1-2.895-2.228l-.052-.176-1.941-7.245a3.25 3.25 0 0 1 2.12-3.928l.178-.052 7.244-1.941a3.25 3.25 0 0 1 3.928 2.12Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m11.066 8.004.184-.005h7.5a3.25 3.25 0 0 1 3.245 3.065l.005.185v7.5a3.25 3.25 0 0 1-3.066 3.245l-.184.005h-7.5a3.25 3.25 0 0 1-3.245-3.066L8 18.75v-7.5a3.25 3.25 0 0 1 3.066-3.245Zm7.684 1.495h-7.5a1.75 1.75 0 0 0-1.744 1.606l-.006.144v7.5a1.75 1.75 0 0 0 1.607 1.744l.143.006h7.5a1.75 1.75 0 0 0 1.744-1.607l.006-.143v-7.5a1.75 1.75 0 0 0-1.75-1.75ZM15 11a.75.75 0 0 1 .75.75v2.498h2.5a.75.75 0 0 1 0 1.5h-2.5v2.502a.75.75 0 0 1-1.5 0v-2.502h-2.5a.75.75 0 1 1 0-1.5h2.5V11.75A.75.75 0 0 1 15 11Zm.582-6.767.052.177.693 2.588h-1.553l-.588-2.2a1.75 1.75 0 0 0-2.144-1.238L4.798 5.502a1.75 1.75 0 0 0-1.27 1.995l.032.148 1.942 7.244A1.75 1.75 0 0 0 7 16.176v1.506a3.252 3.252 0 0 1-2.895-2.228l-.052-.176-1.941-7.245a3.25 3.25 0 0 1 2.12-3.928l.178-.052 7.244-1.941a3.25 3.25 0 0 1 3.928 2.12Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-create-category]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m11.066 8.004.184-.005h7.5a3.25 3.25 0 0 1 3.245 3.065l.005.185v1.56a6.518 6.518 0 0 0-1.5-1.077v-.483a1.75 1.75 0 0 0-1.75-1.75h-7.5a1.75 1.75 0 0 0-1.744 1.606l-.006.144v7.5a1.75 1.75 0 0 0 1.607 1.744l.143.006h.482c.287.55.65 1.055 1.076 1.5H11.25a3.25 3.25 0 0 1-3.245-3.066L8 18.75v-7.5a3.25 3.25 0 0 1 3.066-3.245Z" /><path d="m15.582 4.233.052.177.693 2.588h-1.553l-.588-2.2a1.75 1.75 0 0 0-2.144-1.238L4.798 5.502a1.75 1.75 0 0 0-1.27 1.995l.032.148 1.942 7.244A1.75 1.75 0 0 0 7 16.176v1.506a3.252 3.252 0 0 1-2.895-2.228l-.052-.176-1.941-7.245a3.25 3.25 0 0 1 2.12-3.928l.178-.052 7.244-1.941a3.25 3.25 0 0 1 3.928 2.12ZM23 17.5a5.5 5.5 0 1 0-11 0 5.5 5.5 0 0 0 11 0Zm-5.59-3.493L17.5 14l.09.008a.5.5 0 0 1 .402.402l.008.09V17l2.505.001.09.008a.5.5 0 0 1 .402.402l.008.09-.008.09a.5.5 0 0 1-.403.402l-.09.008h-2.503v2.503l-.008.09a.5.5 0 0 1-.402.402l-.09.008-.09-.008a.5.5 0 0 1-.402-.402l-.008-.09V18L14.498 18l-.09-.008a.5.5 0 0 1-.402-.402l-.008-.09.008-.09a.5.5 0 0 1 .402-.402l.09-.008H17v-2.5l.008-.09a.5.5 0 0 1 .402-.403Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m11.066 8.004.184-.005h7.5a3.25 3.25 0 0 1 3.245 3.065l.005.185v1.56a6.518 6.518 0 0 0-1.5-1.077v-.483a1.75 1.75 0 0 0-1.75-1.75h-7.5a1.75 1.75 0 0 0-1.744 1.606l-.006.144v7.5a1.75 1.75 0 0 0 1.607 1.744l.143.006h.482c.287.55.65 1.055 1.076 1.5H11.25a3.25 3.25 0 0 1-3.245-3.066L8 18.75v-7.5a3.25 3.25 0 0 1 3.066-3.245Z" /><path d="m15.582 4.233.052.177.693 2.588h-1.553l-.588-2.2a1.75 1.75 0 0 0-2.144-1.238L4.798 5.502a1.75 1.75 0 0 0-1.27 1.995l.032.148 1.942 7.244A1.75 1.75 0 0 0 7 16.176v1.506a3.252 3.252 0 0 1-2.895-2.228l-.052-.176-1.941-7.245a3.25 3.25 0 0 1 2.12-3.928l.178-.052 7.244-1.941a3.25 3.25 0 0 1 3.928 2.12ZM23 17.5a5.5 5.5 0 1 0-11 0 5.5 5.5 0 0 0 11 0Zm-5.59-3.493L17.5 14l.09.008a.5.5 0 0 1 .402.402l.008.09V17l2.505.001.09.008a.5.5 0 0 1 .402.402l.008.09-.008.09a.5.5 0 0 1-.403.402l-.09.008h-2.503v2.503l-.008.09a.5.5 0 0 1-.402.402l-.09.008-.09-.008a.5.5 0 0 1-.402-.402l-.008-.09V18L14.498 18l-.09-.008a.5.5 0 0 1-.402-.402l-.008-.09.008-.09a.5.5 0 0 1 .402-.402l.09-.008H17v-2.5l.008-.09a.5.5 0 0 1 .402-.403Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=guild-context-create-event]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm1.75 5.5h-15v9.25c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V8.5Zm-11.75 6a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm-4.25-4a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm1.5-6H6.25A1.75 1.75 0 0 0 4.5 6.25V7h15v-.75a1.75 1.75 0 0 0-1.75-1.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h11.5Zm1.75 5.5h-15v9.25c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V8.5Zm-11.75 6a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm-4.25-4a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm4.25 0a1.25 1.25 0 1 1 0 2.5 1.25 1.25 0 0 1 0-2.5Zm1.5-6H6.25A1.75 1.75 0 0 0 4.5 6.25V7h15v-.75a1.75 1.75 0 0 0-1.75-1.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-reply]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.277 16.221a.75.75 0 0 1-1.061 1.06l-4.997-5.003a.75.75 0 0 1 0-1.06L8.217 6.22a.75.75 0 0 1 1.061 1.06L5.557 11h7.842c1.595 0 2.81.242 3.889.764l.246.126a6.203 6.203 0 0 1 2.576 2.576c.61 1.14.89 2.418.89 4.135a.75.75 0 0 1-1.5 0c0-1.484-.228-2.52-.713-3.428a4.702 4.702 0 0 0-1.96-1.96c-.838-.448-1.786-.676-3.094-.709L13.4 12.5H5.562l3.715 3.721Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.277 16.221a.75.75 0 0 1-1.061 1.06l-4.997-5.003a.75.75 0 0 1 0-1.06L8.217 6.22a.75.75 0 0 1 1.061 1.06L5.557 11h7.842c1.595 0 2.81.242 3.889.764l.246.126a6.203 6.203 0 0 1 2.576 2.576c.61 1.14.89 2.418.89 4.135a.75.75 0 0 1-1.5 0c0-1.484-.228-2.52-.713-3.428a4.702 4.702 0 0 0-1.96-1.96c-.838-.448-1.786-.676-3.094-.709L13.4 12.5H5.562l3.715 3.721Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-mark-unread]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 3a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2V3Zm2.5 1a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1h-6Zm0 3a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1h-6ZM5.25 3H11v1.5H5.25A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75h6.236a1.75 1.75 0 0 0 1.75-1.75V12h.5c.35 0 .687-.06 1-.17v2.92A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3Z"/></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 3a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2V3Zm2.5 1a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1h-6Zm0 3a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1h-6ZM5.25 3H11v1.5H5.25A1.75 1.75 0 0 0 3.5 6.25v8.5c0 .966.784 1.75 1.75 1.75h2.249v3.75l5.015-3.75h6.236a1.75 1.75 0 0 0 1.75-1.75V12h.5c.35 0 .687-.06 1-.17v2.92A3.25 3.25 0 0 1 18.75 18h-5.738L8 21.75a1.25 1.25 0 0 1-1.999-1V18h-.75A3.25 3.25 0 0 1 2 14.75v-8.5A3.25 3.25 0 0 1 5.25 3Z"/></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-copy-link]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.25 7a.75.75 0 0 1 .11 1.492l-.11.008H7a3.5 3.5 0 0 0-.206 6.994L7 15.5h2.25a.75.75 0 0 1 .11 1.492L9.25 17H7a5 5 0 0 1-.25-9.994L7 7h2.25ZM17 7a5 5 0 0 1 .25 9.994L17 17h-2.25a.75.75 0 0 1-.11-1.492l.11-.008H17a3.5 3.5 0 0 0 .206-6.994L17 8.5h-2.25a.75.75 0 0 1-.11-1.492L14.75 7H17ZM7 11.25h10a.75.75 0 0 1 .102 1.493L17 12.75H7a.75.75 0 0 1-.102-1.493L7 11.25h10H7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9.25 7a.75.75 0 0 1 .11 1.492l-.11.008H7a3.5 3.5 0 0 0-.206 6.994L7 15.5h2.25a.75.75 0 0 1 .11 1.492L9.25 17H7a5 5 0 0 1-.25-9.994L7 7h2.25ZM17 7a5 5 0 0 1 .25 9.994L17 17h-2.25a.75.75 0 0 1-.11-1.492l.11-.008H17a3.5 3.5 0 0 0 .206-6.994L17 8.5h-2.25a.75.75 0 0 1-.11-1.492L14.75 7H17ZM7 11.25h10a.75.75 0 0 1 .102 1.493L17 12.75H7a.75.75 0 0 1-.102-1.493L7 11.25h10H7Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-tts]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15 4.25c0-1.079-1.274-1.65-2.08-.934L8.427 7.309a.75.75 0 0 1-.498.19H4.25A2.25 2.25 0 0 0 2 9.749v4.497a2.25 2.25 0 0 0 2.25 2.25h3.68a.75.75 0 0 1 .498.19l4.491 3.994c.806.716 2.081.144 2.081-.934V4.25ZM9.425 8.43 13.5 4.807v14.382l-4.075-3.624a2.25 2.25 0 0 0-1.495-.569H4.25a.75.75 0 0 1-.75-.75V9.75a.75.75 0 0 1 .75-.75h3.68a2.25 2.25 0 0 0 1.495-.569ZM18.992 5.897a.75.75 0 0 1 1.049.157A9.959 9.959 0 0 1 22 12a9.96 9.96 0 0 1-1.96 5.946.75.75 0 0 1-1.205-.892A8.459 8.459 0 0 0 20.5 12a8.459 8.459 0 0 0-1.665-5.054.75.75 0 0 1 .157-1.049Z" /><path d="M17.143 8.37a.75.75 0 0 1 1.017.302c.536.99.84 2.125.84 3.328a6.973 6.973 0 0 1-.84 3.328.75.75 0 0 1-1.32-.714c.42-.777.66-1.666.66-2.614s-.24-1.837-.66-2.614a.75.75 0 0 1 .303-1.017Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15 4.25c0-1.079-1.274-1.65-2.08-.934L8.427 7.309a.75.75 0 0 1-.498.19H4.25A2.25 2.25 0 0 0 2 9.749v4.497a2.25 2.25 0 0 0 2.25 2.25h3.68a.75.75 0 0 1 .498.19l4.491 3.994c.806.716 2.081.144 2.081-.934V4.25ZM9.425 8.43 13.5 4.807v14.382l-4.075-3.624a2.25 2.25 0 0 0-1.495-.569H4.25a.75.75 0 0 1-.75-.75V9.75a.75.75 0 0 1 .75-.75h3.68a2.25 2.25 0 0 0 1.495-.569ZM18.992 5.897a.75.75 0 0 1 1.049.157A9.959 9.959 0 0 1 22 12a9.96 9.96 0 0 1-1.96 5.946.75.75 0 0 1-1.205-.892A8.459 8.459 0 0 0 20.5 12a8.459 8.459 0 0 0-1.665-5.054.75.75 0 0 1 .157-1.049Z" /><path d="M17.143 8.37a.75.75 0 0 1 1.017.302c.536.99.84 2.125.84 3.328a6.973 6.973 0 0 1-.84 3.328.75.75 0 0 1-1.32-.714c.42-.777.66-1.666.66-2.614s-.24-1.837-.66-2.614a.75.75 0 0 1 .303-1.017Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-copy-id]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-copy-text]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-report]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.907 5.622c.062.208.093.424.093.641V17.74a2.25 2.25 0 0 1-2.891 2.156l-5.514-1.64a4.002 4.002 0 0 1-7.59-1.556L6 16.5l-.001-.5-2.39-.711A2.25 2.25 0 0 1 2 13.131V10.87a2.25 2.25 0 0 1 1.61-2.156l15.5-4.606a2.25 2.25 0 0 1 2.797 1.515ZM7.499 16.445l.001.054a2.5 2.5 0 0 0 4.624 1.321l-4.625-1.375Zm12.037-10.9-15.5 4.605a.75.75 0 0 0-.536.72v2.261a.75.75 0 0 0 .536.72l15.5 4.607a.75.75 0 0 0 .964-.72V6.264a.75.75 0 0 0-.964-.719Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.907 5.622c.062.208.093.424.093.641V17.74a2.25 2.25 0 0 1-2.891 2.156l-5.514-1.64a4.002 4.002 0 0 1-7.59-1.556L6 16.5l-.001-.5-2.39-.711A2.25 2.25 0 0 1 2 13.131V10.87a2.25 2.25 0 0 1 1.61-2.156l15.5-4.606a2.25 2.25 0 0 1 2.797 1.515ZM7.499 16.445l.001.054a2.5 2.5 0 0 0 4.624 1.321l-4.625-1.375Zm12.037-10.9-15.5 4.605a.75.75 0 0 0-.536.72v2.261a.75.75 0 0 0 .536.72l15.5 4.607a.75.75 0 0 0 .964-.72V6.264a.75.75 0 0 0-.964-.719Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=message-actions-devmode-copy-id]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.503 4.627 5.5 6.75v10.504a3.25 3.25 0 0 0 3.25 3.25h8.616a2.251 2.251 0 0 1-2.122 1.5H8.75A4.75 4.75 0 0 1 4 17.254V6.75c0-.98.627-1.815 1.503-2.123ZM17.75 2A2.25 2.25 0 0 1 20 4.25v13a2.25 2.25 0 0 1-2.25 2.25h-9a2.25 2.25 0 0 1-2.25-2.25v-13A2.25 2.25 0 0 1 8.75 2h9Zm0 1.5h-9a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75v-13a.75.75 0 0 0-.75-.75Z" /></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=account-set-custom-status]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 3a8.98 8.98 0 0 1 3.164.572l-1.183 1.192a7.5 7.5 0 1 0 5.276 5.335l1.194-1.203C20.806 9.864 21 10.91 21 12a9 9 0 1 1-9-9Zm9.06-.328.146.136a2.763 2.763 0 0 1 .008 3.9l-6.304 6.354a1.5 1.5 0 0 1-.652.385l-4.212 1.209a.5.5 0 0 1-.618-.619l1.21-4.22a1.5 1.5 0 0 1 .377-.642l6.309-6.36a2.74 2.74 0 0 1 3.736-.143Zm-2.671 1.2-6.31 6.36-.712 2.484 2.478-.71 6.304-6.355c.457-.461.486-1.186.088-1.68l-.095-.107a1.24 1.24 0 0 0-1.753.007Z"/></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 3a8.98 8.98 0 0 1 3.164.572l-1.183 1.192a7.5 7.5 0 1 0 5.276 5.335l1.194-1.203C20.806 9.864 21 10.91 21 12a9 9 0 1 1-9-9Zm9.06-.328.146.136a2.763 2.763 0 0 1 .008 3.9l-6.304 6.354a1.5 1.5 0 0 1-.652.385l-4.212 1.209a.5.5 0 0 1-.618-.619l1.21-4.22a1.5 1.5 0 0 1 .377-.642l6.309-6.36a2.74 2.74 0 0 1 3.736-.143Zm-2.671 1.2-6.31 6.36-.712 2.484 2.478-.71 6.304-6.355c.457-.461.486-1.186.088-1.68l-.095-.107a1.24 1.24 0 0 0-1.753.007Z"/></svg>');
}
.item-5ApiZt:not(#account-status-picker, [role=menuitemcheckbox], [role=menuitemradio])[id^=account-switch-account]::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15.75 13.997c.981 0 1.815.628 2.123 1.503h-2.056a.738.738 0 0 0-.066-.003H4.249a.749.749 0 0 0-.749.75v.577c0 .535.191 1.054.539 1.46 1.253 1.469 3.22 2.214 5.957 2.214h.168c.086.183.203.352.35.498l.934.933a14.6 14.6 0 0 1-1.452.07c-3.145 0-5.531-.906-7.098-2.74A3.75 3.75 0 0 1 2 16.824v-.578a2.249 2.249 0 0 1 2.249-2.249H15.75ZM9.996 2.002a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z"/><path d="M14.78 17.784a.75.75 0 0 0-1.06-1.06l-2.5 2.5a.75.75 0 0 0 0 1.06l2.5 2.5a.75.75 0 0 0 1.06-1.061l-1.22-1.22h6.88l-1.22 1.22a.75.75 0 0 0 1.06 1.06l2.5-2.498a.75.75 0 0 0 0-1.06l-2.5-2.502a.75.75 0 1 0-1.06 1.06l1.218 1.22h-6.877l1.22-1.22Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15.75 13.997c.981 0 1.815.628 2.123 1.503h-2.056a.738.738 0 0 0-.066-.003H4.249a.749.749 0 0 0-.749.75v.577c0 .535.191 1.054.539 1.46 1.253 1.469 3.22 2.214 5.957 2.214h.168c.086.183.203.352.35.498l.934.933a14.6 14.6 0 0 1-1.452.07c-3.145 0-5.531-.906-7.098-2.74A3.75 3.75 0 0 1 2 16.824v-.578a2.249 2.249 0 0 1 2.249-2.249H15.75ZM9.996 2.002a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z"/><path d="M14.78 17.784a.75.75 0 0 0-1.06-1.06l-2.5 2.5a.75.75 0 0 0 0 1.06l2.5 2.5a.75.75 0 0 0 1.06-1.061l-1.22-1.22h6.88l-1.22 1.22a.75.75 0 0 0 1.06 1.06l2.5-2.498a.75.75 0 0 0 0-1.06l-2.5-2.502a.75.75 0 1 0-1.06 1.06l1.218 1.22h-6.877l1.22-1.22Z" /></svg>');
}

#app-mount #guild-header-popout .item-1OdjEX:not([role=menuitemcheckbox]) {
  flex-direction: row;
}
#app-mount #guild-header-popout .item-1OdjEX:not([role=menuitemcheckbox]) .iconContainer-1-SsTR {
  display: none;
}

#app-mount .container-2McqkF {
  border: 1px solid var(--border);
  background: var(--bg-menu);
  border-radius: var(--rounded);
  overflow: hidden;
  box-shadow: none;
  min-width: 248px;
}
#app-mount .container-2McqkF:empty {
  display: none;
}
#app-mount .option-ayUoaq {
  color: var(--text-secondary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height-lg);
  height: auto;
  border-radius: var(--rounded);
  padding: 8px 12px;
  cursor: var(--cursor);
  margin: 0;
}
#app-mount .option-ayUoaq::before, #app-mount .option-ayUoaq::after {
  content: none;
}
#app-mount .option-ayUoaq:hover {
  background: var(--bg-menu-item);
}
#app-mount .plusIcon-1RVszG {
  display: none;
}
#app-mount .header-1BR0Ro {
  padding: 8px 12px;
}
#app-mount .resultsGroup-cfY57t {
  padding: 4px;
  margin: 0;
}
#app-mount .resultsGroup-cfY57t::before {
  content: none;
}
#app-mount .resultsGroup-cfY57t ~ .resultsGroup-cfY57t {
  padding-top: 0;
}
#app-mount .filter-2QaH9y,
#app-mount .displayedNick-1atSpT {
  color: var(--text-primary);
}
#app-mount .answer-14OVbQ,
#app-mount .displayUsername-UTerwm {
  color: var(--text-tertiary);
}

#app-mount .container-18GwIk {
  background: var(--bg-main);
  border-radius: var(--rounded);
  border: 1px solid var(--border-high);
  box-shadow: var(--shadow-flyout);
  width: var(--popout-width, 650px);
  max-width: var(--popout-width, 650px);
  max-height: calc(100vh - var(--toolbar-height) - var(--win-btn-height) - 16px) !important;
  box-sizing: border-box;
}
#app-mount .header-3_zmOb {
  border-bottom: 1px solid var(--border-high);
  background: var(--bg-alt);
  padding: 0 12px;
  gap: 0 12px;
}
#app-mount .header-3_zmOb > * {
  margin: 0;
}
#app-mount .divider-2xk5N2 {
  background: var(--border-high);
  height: 100%;
}

#app-mount .messagesPopoutWrap-3zryHW {
  background: var(--bg-main);
  border-radius: var(--rounded);
  border: 1px solid var(--border-high);
  box-shadow: var(--shadow-flyout);
  width: var(--popout-width, 650px);
  max-width: var(--popout-width, 650px);
  max-height: calc(100vh - var(--toolbar-height) - var(--win-btn-height) - 16px) !important;
  box-sizing: border-box;
}
#app-mount .messagesPopoutWrap-3zryHW .messageGroupWrapper-1jf_7C {
  background: transparent;
}
#app-mount .messagesPopoutWrap-3zryHW .cozy-VmLDNB.wrapper-30-Nkg {
  padding: 8px 16px 8px 72px;
}
#app-mount .messagesPopoutWrap-3zryHW .cozy-VmLDNB.wrapper-30-Nkg img {
  left: 16px;
}
#app-mount .messagesPopoutWrap-3zryHW .cozy-VmLDNB.wrapper-30-Nkg .header-2jRmjb {
  margin-bottom: 6px;
}
#app-mount .messagesPopoutWrap-3zryHW .actionButtons-2mNSAB {
  top: 0;
  right: 0;
}

#app-mount .container-2ebMPP {
  background: var(--bg-main);
  border-radius: var(--rounded);
  border: 1px solid var(--border-high);
  box-shadow: var(--shadow-flyout);
  width: var(--popout-width, 650px);
  max-width: var(--popout-width, 650px);
  max-height: calc(100vh - var(--toolbar-height) - var(--win-btn-height) - 16px) !important;
  box-sizing: border-box;
}
#app-mount .container-iA3Qrz {
  padding: 0;
  margin: 0;
}
#app-mount .channelHeader-DFRX8q {
  background: var(--bg-main);
  padding: 0 12px;
}
#app-mount .messageContainer-3VTXBC {
  padding-top: 0;
  margin-left: 0;
  background: transparent;
}

#app-mount .autocomplete-3jLKb0j,
#app-mount .outerWrapper-3UdjNj,
#app-mount .autocomplete-3NRXG8 {
  background: var(--bg-menu);
  border: 1px solid var(--border-high);
  box-shadow: var(--shadow-flyout);
}
#app-mount .wrapper-3z7DuG,
#app-mount .wrapper-22rqw6 {
  background: var(--bg-main);
}
#app-mount .wrapper-1NNaWG {
  background: var(--bg-menu);
}
#app-mount .autocompleteRow-14iwvH {
  border-radius: var(--rounded);
  padding: 0 4px;
}
#app-mount .autocompleteRow-14iwvH .base-2v-uc0 {
  padding: 6px 16px;
  position: relative;
}
#app-mount .autocompleteRow-14iwvH .base-2v-uc0::before {
  content: "";
  position: absolute;
  left: 0;
  top: 50%;
  transform: translateY(-50%);
  width: var(--pill-width);
  height: 0;
  border-radius: 30px;
  background: rgb(var(--accent));
  opacity: 0;
  transition: var(--pill-transition);
}
#app-mount .autocompleteRow-14iwvH .selected-3H3-RC {
  background: var(--bg-menu-item);
}
#app-mount .autocompleteRow-14iwvH .selected-3H3-RC::before {
  height: var(--pill-height);
  opacity: 1;
}

#app-mount .contentWrapper-3vHNP2 {
  background: var(--bg-menu);
  border-radius: var(--rounded);
  border: 1px solid var(--border-high);
  box-shadow: var(--shadow-flyout);
  grid-template-rows: 40px auto;
  padding-top: 4px;
}
#app-mount .contentWrapper-3vHNP2 [class^=header-]:not([aria-expanded]) {
  border-bottom: 1px solid var(--border-high);
  box-shadow: none;
}
#app-mount .inspector-DFKXwB {
  border-top: 1px solid var(--border-high);
  background: var(--bg-alt);
  padding: 0 12px;
}
#app-mount .nav-1zWVQw {
  padding: 0 8px;
}
#app-mount .nav-1zWVQw .navButton-1XuvI- {
  margin: 0;
  border: none;
  padding: 10px 12px;
  height: auto;
  border-radius: var(--btn-radius);
  cursor: var(--cursor);
  background: transparent !important;
  color: var(--text-secondary) !important;
  text-transform: none;
  font-weight: var(--font-weight-normal);
}
#app-mount .nav-1zWVQw .navButton-1XuvI-::before {
  content: "";
  height: 2px;
  width: 0%;
  display: block;
  opacity: 0;
  border-radius: 30px;
  background: rgb(var(--accent));
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  transition: opacity 0.15s var(--transition), width 0.15s var(--transition);
}
#app-mount .nav-1zWVQw .navButton-1XuvI-:hover {
  color: var(--text-primary) !important;
}
#app-mount .nav-1zWVQw .navButton-1XuvI-[aria-selected=true] {
  color: var(--text-primary) !important;
}
#app-mount .nav-1zWVQw .navButton-1XuvI-[aria-selected=true]::before {
  width: 40%;
  opacity: 1;
}
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ),
#app-mount .container-1SX9VC {
  background: var(--textbox-bg-high);
  border: 1px solid var(--textbox-border);
  padding: 0;
  border-radius: var(--rounded);
  font-size: var(--font-size-sm);
  box-sizing: border-box;
  border-bottom-color: var(--textbox-underline);
  transition: none;
}
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ) [class^=input-],
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ) [class^=inner-],
#app-mount .container-1SX9VC [class^=input-],
#app-mount .container-1SX9VC [class^=inner-] {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ) [class^=input-]::-webkit-scrollbar,
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ) [class^=inner-]::-webkit-scrollbar,
#app-mount .container-1SX9VC [class^=input-]::-webkit-scrollbar,
#app-mount .container-1SX9VC [class^=inner-]::-webkit-scrollbar {
  display: none;
}
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ) [class^=input-],
#app-mount .container-1SX9VC [class^=input-] {
  padding: 0 8px;
}
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ)::-moz-placeholder, #app-mount .container-1SX9VC::-moz-placeholder {
  font-size: var(--font-size-sm);
  color: var(--text-muted);
}
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ)::placeholder,
#app-mount .container-1SX9VC::placeholder {
  font-size: var(--font-size-sm);
  color: var(--text-muted);
}
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ):hover,
#app-mount .container-1SX9VC:hover {
  background: var(--textbox-bg-high-hover);
}
#app-mount .container-2oNtJn:not(.searchBar-2aylmZ):focus-within,
#app-mount .container-1SX9VC:focus-within {
  background: var(--textbox-bg-high-active) !important;
  box-shadow: inset 0 -1px 0 rgb(var(--accent));
  border-bottom-color: rgb(var(--accent));
}
#app-mount .listWrapper-2DwCYS {
  border-left: 1px solid var(--border-high);
}

#app-mount .userProfileInnerThemedWithBanner-2624Yx {
  background: transparent;
}
#app-mount .userProfileInner-3F03PX:not(.userProfileInnerThemedNonPremium-2AJg-H) .role-2TIOKu {
  background: var(--bg-transparent);
}
#app-mount .userProfileInner-3F03PX:not(.userProfileInnerThemedNonPremium-2AJg-H) .discrimBase-KriZSj {
  color: #aaa;
}
#app-mount .userProfileInner-3F03PX:not(.userProfileInnerThemedNonPremium-2AJg-H) .inputDefault-3FGxgL {
  background: var(--bg-transparent);
  border-color: var(--bg-transparent);
}
#app-mount .userProfileInner-3F03PX:not(.userProfileInnerThemedNonPremium-2AJg-H) .inputDefault-3FGxgL:hover {
  background: var(--bg-transparent-hover);
}
#app-mount .userProfileInner-3F03PX:not(.userProfileInnerThemedNonPremium-2AJg-H) .inputDefault-3FGxgL:focus {
  background: var(--bg-transparent-active) !important;
  border-bottom-color: var(--profile-message-input-border-color);
  box-shadow: inset 0 -1px 0 var(--profile-message-input-border-color);
}
#app-mount .userProfileInnerThemedNonPremium-2AJg-H {
  background: var(--bg-main);
}
#app-mount .userProfileInnerThemedNonPremium-2AJg-H .overlayBackground-2aa7wt {
  margin: 0;
  background: transparent;
  padding: 0 8px 8px;
}
#app-mount .roles-3vQPxb {
  gap: 8px;
}
#app-mount .role-2TIOKu {
  color: var(--text-secondary);
  line-height: var(--line-height);
  background: var(--bg-content);
  margin: 0;
  padding: 6px 8px;
  height: unset;
  border-radius: 50px;
  border: none;
}
#app-mount .roleCircle-3TFUOr {
  margin: 0;
}
#app-mount .roleName-2ZJJYR {
  margin: 0 0 0 4px;
}

#app-mount .userPopoutOuter-1OHwPL {
  box-shadow: 0 0 0 1px var(--border-high), var(--shadow-flyout);
  padding: 0;
}
#app-mount .userPopoutOuter-1OHwPL .userProfileInnerThemedNonPremium-2AJg-H .bannerSVGWrapper-2CLfzN {
  min-height: 120px !important;
}
#app-mount .userPopoutOuter-1OHwPL .userProfileInnerThemedNonPremium-2AJg-H .bannerSVGWrapper-2CLfzN foreignObject {
  y: -30;
  -webkit-mask: none;
          mask: none;
}
#app-mount .userPopoutOuter-1OHwPL .avatarWrapperNormal-ahVUaC {
  position: absolute;
  top: 16px;
  right: 16px;
  left: unset;
  background: hsla(0, 0%, 100%, 0.2);
  border-color: transparent;
  box-shadow: 0 0 0 8px hsla(0, 0%, 100%, 0.2);
}
#app-mount .userPopoutOuter-1OHwPL .avatarWrapperNormal-ahVUaC circle[fill=black] {
  opacity: 0 !important;
}
#app-mount .userPopoutOuter-1OHwPL .overlayBackground-2aa7wt {
  overflow: visible;
  position: static;
  z-index: 2;
  margin-top: 0;
}
#app-mount .userPopoutOuter-1OHwPL .overlayBackground-2aa7wt > .section-28YDOf:first-of-type {
  padding: 0;
  position: absolute;
  top: 16px;
  left: 16px;
}
#app-mount .userPopoutOuter-1OHwPL .overlayBackground-2aa7wt > .divider-1tWBgZ {
  display: none;
}
#app-mount .userPopoutOuter-1OHwPL .overlayBackground-2aa7wt .section-28YDOf {
  padding-right: 0 !important;
}
#app-mount .userPopoutOuter-1OHwPL .profileBadges-2pItdR {
  position: absolute;
  right: unset;
  left: 16px;
  top: 66px;
  z-index: 2;
  background: transparent;
  padding: 0;
}
#app-mount .userPopoutOuter-1OHwPL .profileBadge22-3OAigE {
  filter: drop-shadow(var(--profile-premium-text-shadow));
}
#app-mount .userPopoutOuter-1OHwPL .banner-1YaD3N {
  -webkit-mask: linear-gradient(hsla(0, 0%, 0%, 0.5), transparent 90%);
          mask: linear-gradient(hsla(0, 0%, 0%, 0.5), transparent 90%);
  position: absolute;
  width: 100%;
  height: 120px;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  max-width: unset;
  pointer-events: none;
}
#app-mount .userPopoutOuter-1OHwPL .banner-1YaD3N [role=button] {
  display: none;
}
#app-mount .userPopoutOuter-1OHwPL .nickname-3P1RuO {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  max-width: 220px;
}
#app-mount .userPopoutInner-nv9Y92::before {
  content: none;
}
#app-mount .nameTag-H6kSJ0 {
  line-height: normal;
  text-shadow: var(--profile-premium-text-shadow);
}
#app-mount .messageInputContainer-2rGDH8 {
  border: none;
  border-radius: unset;
}

#app-mount .userProfileModalOuter-2wdWjU {
  padding: 0;
}
#app-mount .userProfileModalOuter-2wdWjU .bannerSVGWrapper-2CLfzN {
  overflow: visible;
  pointer-events: none;
}
#app-mount .userProfileModalOuter-2wdWjU .bannerSVGWrapper-2CLfzN foreignObject {
  -webkit-mask: none;
          mask: none;
}
#app-mount .userProfileModalOuter-2wdWjU .banner-1YaD3N {
  -webkit-mask: linear-gradient(hsla(0, 0%, 0%, 0.5), transparent 90%);
          mask: linear-gradient(hsla(0, 0%, 0%, 0.5), transparent 90%);
  position: absolute;
  width: 100%;
  height: 170px;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  max-width: unset;
}
#app-mount .userProfileModalOuter-2wdWjU .banner-1YaD3N [role=button] {
  display: none;
}
#app-mount .userProfileModalInner-3dx9L9::before {
  content: none;
}
#app-mount .userProfileModalInner-3dx9L9:not(.userProfileInnerThemedNonPremium-2AJg-H) .tabBarItem-3VvT2z::before {
  background: var(--profile-message-input-border-color);
}
#app-mount .userProfileModalInner-3dx9L9:not(.userProfileInnerThemedNonPremium-2AJg-H) .textarea-_59yqs:focus {
  border-bottom-color: var(--profile-message-input-border-color);
  box-shadow: inset 0 -1px 0 var(--profile-message-input-border-color);
}
#app-mount .userProfileModalInner-3dx9L9.userProfileInnerThemedNonPremium-2AJg-H .userProfileModalOverlayBackground-2dAaBg {
  padding: 0;
}
#app-mount .topSection-13QKHs {
  margin-bottom: 0;
  height: 180px;
  z-index: 0;
}
#app-mount .topSection-13QKHs .wrapper-3Un6-K {
  top: 24px;
  right: 24px;
  left: unset;
  background: hsla(0, 0%, 100%, 0.2);
  border-color: transparent;
  box-shadow: 0 0 0 8px hsla(0, 0%, 100%, 0.2);
}
#app-mount .topSection-13QKHs .wrapper-3Un6-K circle[fill=black] {
  fill: transparent;
}
#app-mount .header-S26rhB {
  position: unset;
}
#app-mount .headerTop-1PNKck {
  position: unset;
}
#app-mount .badgeList-2aoHPw {
  position: absolute;
  top: 104px;
  left: 24px;
  background: transparent;
  padding: 0;
  margin: 0;
}
#app-mount .profileBadge24-3UMhUO {
  filter: drop-shadow(var(--profile-premium-text-shadow));
}
#app-mount .actionButton-iarQTd {
  position: absolute;
  top: 24px;
  right: 24px;
  width: 120px !important;
  height: 120px !important;
  border-radius: 50% !important;
  background: hsla(0, 0%, 0%, 0.6) !important;
  margin: 0;
  color: #fff !important;
  opacity: 0;
  transition: opacity 0.15s var(--transition) !important;
}
#app-mount .actionButton-iarQTd .contents-3NembX {
  white-space: normal;
}
#app-mount .actionButton-iarQTd:hover {
  opacity: 1;
}
#app-mount .relationshipButtons-3ByBpj div[class][role=button] {
  position: absolute;
  top: 4px;
  right: 4px;
}
#app-mount .body-_QAKrE {
  overflow: visible;
  flex: none;
}
#app-mount .userProfileModalOverlayBackground-2dAaBg {
  position: unset;
  margin-top: 0;
}
#app-mount .container-3g15px {
  position: absolute;
  top: 24px;
  left: 24px;
  z-index: 1;
  padding: 0;
}
#app-mount .nameTag-2ysfG3 {
  text-shadow: var(--profile-premium-text-shadow);
  font-size: 24px;
}
#app-mount .customStatusText-3ca2B1 {
  font-weight: var(--font-weight-semibold);
  max-width: 400px;
  text-shadow: var(--profile-premium-text-shadow);
}
#app-mount .divider-1NpGam {
  display: none;
}
#app-mount .tabBarContainer-2UG0vy {
  margin: 8px;
  border: none;
}
#app-mount .tabBar-2StdUa {
  gap: 0;
}
#app-mount .listScroller-XCVa1H, #app-mount .infoScroller-3MqKC5 {
  max-height: 330px;
  height: 330px;
}

#app-mount .profilePanel-2VBkh8 {
  border-left: 1px solid var(--border-high);
  background: var(--bg-altuserPanelInner-3KPel3);
}
#app-mount .profilePanel-2VBkh8 .userPanelOuter-XfFELn:not(.userProfileOuterThemed-2BgJCM),
#app-mount .profilePanel-2VBkh8 .userPanelInner-3KPel3 {
  background: transparent;
}
#app-mount .profilePanel-2VBkh8 .bannerSVGWrapper-2CLfzN {
  overflow: visible;
  pointer-events: none;
}
#app-mount .profilePanel-2VBkh8 .bannerSVGWrapper-2CLfzN foreignObject {
  -webkit-mask: none;
          mask: none;
}
#app-mount .profilePanel-2VBkh8 .banner-1YaD3N {
  -webkit-mask: linear-gradient(hsla(0, 0%, 0%, 0.5), transparent 90%);
          mask: linear-gradient(hsla(0, 0%, 0%, 0.5), transparent 90%);
  position: absolute;
  width: 100%;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  max-width: unset;
}
#app-mount .profilePanel-2VBkh8 .banner-1YaD3N [role=button] {
  display: none;
}
#app-mount .profilePanel-2VBkh8 .gifTag-1TvtGO {
  display: none;
}
#app-mount .profilePanel-2VBkh8 .avatarWrapperNormal-ahVUaC {
  top: 24px;
  right: 24px;
  left: unset;
  background: hsla(0, 0%, 100%, 0.2);
  border-color: transparent;
  box-shadow: 0 0 0 8px hsla(0, 0%, 100%, 0.2);
}
#app-mount .profilePanel-2VBkh8 .avatarWrapperNormal-ahVUaC circle[fill=black] {
  fill: transparent;
}
#app-mount .profilePanel-2VBkh8 .badgelistGroup-_4Ddiq {
  position: absolute;
  top: 85px;
  left: 16px;
  padding: 0;
  margin: 0;
}
#app-mount .profilePanel-2VBkh8 .badgeList-2hF9ig {
  background: transparent;
  padding: 0;
}
#app-mount .profilePanel-2VBkh8 .overlayBackground-2aa7wt {
  position: unset;
  background: var(--bg-transparent);
}
#app-mount .profilePanel-2VBkh8 .overlayBackground-2aa7wt:nth-child(2) > .section-28YDOf:first-of-type {
  padding: 0;
  position: absolute;
  top: 16px;
  left: 16px;
}
#app-mount .profilePanel-2VBkh8 .overlayBackground-2aa7wt:nth-child(2) > .section-28YDOf:first-of-type + .divider-2dDziJ {
  display: none;
}
#app-mount .profilePanel-2VBkh8 .profilePanelConnections-1tVK8j {
  background: transparent;
}
#app-mount .profilePanel-2VBkh8 .profilePanelConnections-1tVK8j button {
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .profilePanel-2VBkh8 .profilePanelConnections-1tVK8j button:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .profilePanel-2VBkh8 .profilePanelConnections-1tVK8j button:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .profilePanel-2VBkh8 .mutualFriendsDivider-_X_dLc {
  border: none;
  margin-top: 12px;
}

#app-mount .peopleColumn-1wMU14 {
  position: relative;
}
#app-mount .peopleList-2VBrVI {
  padding-bottom: calc(var(--bottombar-height) * 1.5);
}
#app-mount .container-2cd8Mz {
  background: var(--bg-alt);
}
#app-mount .tabBody-2dgbAs::before {
  content: none;
}
#app-mount .searchBar-2aylmZ {
  margin: 0;
  position: absolute;
  bottom: 12px;
  right: 12px;
  left: 0;
  z-index: 1;
  height: var(--bottombar-height);
  background: var(--bg-main);
  padding: 10px 10px 10px 14px;
  border: 1px solid var(--border-high);
  border-left: none;
  border-radius: 0 var(--rounded) var(--rounded) 0;
}
#app-mount .searchBar-2aylmZ .inner-2pOSmK {
  background: var(--bg-alt);
  border-radius: var(--rounded);
  flex-direction: row-reverse;
  padding: 0 10px;
  overflow: hidden;
}
#app-mount .searchBar-2aylmZ .inner-2pOSmK::before {
  content: "";
  height: 1px;
  width: 100%;
  background: var(--textbox-underline);
  position: absolute;
  left: 0;
  bottom: 0;
}
#app-mount .searchBar-2aylmZ .inner-2pOSmK:focus-within {
  background: var(--bg-content-alt);
}
#app-mount .searchBar-2aylmZ .inner-2pOSmK:focus-within::before {
  height: 2px;
  background: rgb(var(--accent));
}
#app-mount .searchBar-2aylmZ .input-2m5SfJ {
  padding: 0 10px;
  margin: 0;
}
#app-mount .title-x4dI75 {
  margin: 16px;
}
#app-mount .peopleListItem-u6dGxF {
  height: auto !important;
  margin: 0 4px 4px 16px;
  padding: 8px 16px;
  border-radius: var(--rounded);
  cursor: var(--cursor);
  border: none;
  position: relative;
}
#app-mount .peopleListItem-u6dGxF::before {
  content: "";
  display: block;
  height: 0;
  width: var(--pill-width);
  background: rgb(var(--accent));
  border-radius: 50px;
  transition: var(--pill-transition);
  opacity: 0;
  position: absolute;
  left: 0;
  top: 50%;
  transform: translateY(-50%);
  z-index: 1;
}
#app-mount .peopleListItem-u6dGxF .actionButton-3-B2x- {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  width: auto;
  height: auto;
}
#app-mount .peopleListItem-u6dGxF .actionButton-3-B2x-:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .peopleListItem-u6dGxF .actionButton-3-B2x-:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .peopleListItem-u6dGxF:hover {
  background: var(--bg-interactive-high);
}
#app-mount .peopleListItem-u6dGxF.active-2UF8Zh {
  background: var(--bg-interactive-high);
}
#app-mount .peopleListItem-u6dGxF.active-2UF8Zh::before {
  height: var(--pill-height);
  opacity: 1;
}
#app-mount .addFriendInputWrapper-kkoSV9 {
  padding: 0;
  border: none;
  background: transparent;
  margin-top: 16px;
}

#app-mount .container-1oAagU {
  background: transparent;
}
#app-mount .nowPlayingColumn-1eCBCN {
  background: transparent;
}
#app-mount .scroller-hE2gWq {
  border-left: 1px solid var(--border-mid);
  margin: 0;
}
#app-mount .header-Imy05m {
  margin: 0 0 16px;
  color: var(--text-primary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-semibold);
  line-height: var(--line-height-md);
  margin-bottom: 12px;
  text-transform: none;
}
#app-mount .itemCard-3Etziu {
  border-radius: var(--rounded);
  border: 1px solid var(--border);
  background: var(--bg-content);
  cursor: var(--cursor);
  padding: 0;
}
#app-mount .itemCard-3Etziu .sectionTitle-2AR_TY {
  color: var(--text-secondary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height-lg);
}
#app-mount .itemCard-3Etziu .size14-3fJ-ot {
  color: var(--text-tertiary);
  font-size: var(--font-size-xs);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height);
}
#app-mount .itemCard-3Etziu:hover {
  background: var(--bg-content-alt);
}
#app-mount .header-3jUeHi {
  padding: 12px;
}
#app-mount .body-16rSsp {
  margin: 0;
  border-top: 1px solid var(--border);
  border-radius: 0;
  background: transparent;
}
#app-mount .section-3G9aLW {
  background: transparent;
}
#app-mount .voiceSectionDetails-3jGIB4 {
  cursor: var(--cursor);
}

#app-mount .perksModal-CLcR1c {
  background: var(--bg-main);
}
#app-mount .perksModal-CLcR1c .ctaBar-Nhk8yY {
  border-radius: var(--rounded);
  border: 1px solid var(--border);
  background: var(--bg-content);
}
#app-mount .perksModal-CLcR1c .tierWrapper-CsnudO {
  box-shadow: none !important;
}
#app-mount .perksModal-CLcR1c .tierWrapper-CsnudO[style*="box-shadow: rgba(0, 0, 0, 0.2)"] {
  box-shadow: var(--shadow-flyout) !important;
}
#app-mount .perksModal-CLcR1c .tier-lFqDUs {
  border: 1px solid var(--border-high);
}
#app-mount .perksModal-CLcR1c .tierHeaderLocked-3ItHYn {
  background: var(--bg-alt);
  box-shadow: inset 0 -1px 0 var(--border-high);
}
#app-mount .perksModal-CLcR1c .tierBody-3ju-rc {
  background: var(--bg-content);
  border-radius: 0 0 var(--rounded) var(--rounded);
}
#app-mount .perksModal-CLcR1c .perk-19D_HN {
  border-radius: var(--rounded);
  border: 1px solid var(--border);
  background: var(--bg-content);
}

#app-mount .sidebar-1tnWFu.hiddenOnMobileStore-2z5BJi .avatarWrapper-1B9FTW {
  display: none;
}
#app-mount .applicationStore-2nk7Lo {
  background: var(--bg-alt);
}
#app-mount .scroller-29cQFV {
  background: transparent;
}
#app-mount .featureGrid-SSlfD0 {
  grid-template-columns: 1fr;
}
#app-mount .feature-2IUcBI {
  min-height: 180px;
  padding: 24px;
  background: var(--bg-content);
  border: 1px solid var(--border-mid);
  border-radius: var(--rounded);
}
#app-mount .featureTitle-3N9Stg {
  text-align: left;
}
#app-mount .featureDescription-3U0QB3 {
  text-align: left;
  max-width: 50%;
}
#app-mount .featureImageWrapper-2ndc8N {
  position: absolute;
  left: unset;
  right: 24px;
  top: 50%;
  transform: translateY(-50%);
  bottom: unset;
}

#app-mount [role=slider] .bar-2H7Q9u {
  height: 4px;
}
#app-mount [role=slider] .barFill-3RgCsY {
  background: rgb(var(--accent));
}
#app-mount [role=slider] .track-3I-RwH {
  left: 10px;
}
#app-mount [role=slider] .grabber-3R-Rx9 {
  border: 4px solid var(--bg-highest);
  margin-top: 0;
  background: rgb(var(--accent));
  box-shadow: var(--shadow-flyout);
  width: 20px;
  height: 20px;
  border-radius: 50%;
  transform: translateY(-50%);
  margin-left: -10px;
  margin-top: -2px;
}
#app-mount [role=slider].mini-28oMa3 .grabber-3R-Rx9 {
  width: 12px;
  height: 12px;
  top: 100%;
}

#app-mount [role=menuitemcheckbox] .iconContainer-Ksy8Oj {
  border: 1px solid var(--text-muted);
  border-radius: var(--rounded);
  width: 18px;
  height: 18px;
  box-sizing: border-box;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}
#app-mount [role=menuitemcheckbox] .iconContainer-Ksy8Oj::before {
  content: "";
  width: 10px;
  height: 4px;
  border-left: 1px solid #000;
  border-bottom: 1px solid #000;
  transform: rotate(-45deg);
  margin-top: -2px;
  opacity: 0;
}
#app-mount [role=menuitemcheckbox] svg {
  display: none;
}
#app-mount [role=menuitemcheckbox][aria-checked=true] .iconContainer-Ksy8Oj {
  border-color: rgb(var(--accent));
  background: rgb(var(--accent));
}
#app-mount [role=menuitemcheckbox][aria-checked=true] .iconContainer-Ksy8Oj::before {
  opacity: 1;
}

#app-mount [role=menuitemradio] .iconContainer-Ksy8Oj {
  border: 1px solid var(--text-muted);
  box-sizing: border-box;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}
#app-mount [role=menuitemradio] .iconContainer-Ksy8Oj::before {
  content: "";
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #000;
  opacity: 0;
}
#app-mount [role=menuitemradio] svg {
  display: none;
}
#app-mount [role=menuitemradio][aria-checked=true] .iconContainer-Ksy8Oj {
  border-color: rgb(var(--accent));
  background: rgb(var(--accent));
}
#app-mount [role=menuitemradio][aria-checked=true] .iconContainer-Ksy8Oj::before {
  opacity: 1;
}

#app-mount .button-ejjZWC,
#app-mount .button-f2h6uQ {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  cursor: var(--cursor);
  margin: 1px;
  min-height: auto;
  height: auto;
}
#app-mount .button-ejjZWC [role=button],
#app-mount .button-f2h6uQ [role=button] {
  cursor: var(--cursor) !important;
}
#app-mount .button-ejjZWC [class*=shine],
#app-mount .button-f2h6uQ [class*=shine] {
  display: none;
}
#app-mount .button-ejjZWC .contents-3NembX,
#app-mount .button-f2h6uQ .contents-3NembX {
  display: flex;
  align-items: center;
  gap: 8px;
}
#app-mount .button-ejjZWC.buttonColor-3bP3fX,
#app-mount .button-f2h6uQ.buttonColor-3bP3fX {
  background: rgb(var(--accent));
  color: var(--accent-text);
}
#app-mount .button-ejjZWC.lookFilled-1H2Jvj,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj {
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  font-weight: var(--font-weight-semibold);
  transition: box-shadow 0.15s var(--transition);
}
#app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorBrand-2M3O3N, #app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorGreen-3y-Z79,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorBrand-2M3O3N,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorGreen-3y-Z79 {
  background: rgb(var(--accent));
  color: var(--accent-text);
}
#app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorRed-2VFhM4,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorRed-2VFhM4 {
  background: hsl(var(--discord-red));
}
#app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorGrey-2iAG-B, #app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorPrimary-2-Lusz,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorGrey-2iAG-B,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorPrimary-2-Lusz {
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
}
#app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorGrey-2iAG-B:hover, #app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorPrimary-2-Lusz:hover,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorGrey-2iAG-B:hover,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorPrimary-2-Lusz:hover {
  background: var(--btn-bg-hover) !important;
}
#app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorGrey-2iAG-B:active, #app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorPrimary-2-Lusz:active,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorGrey-2iAG-B:active,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorPrimary-2-Lusz:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active) !important;
}
#app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorBrand-2M3O3N:hover, #app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorGreen-3y-Z79:hover, #app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorRed-2VFhM4:hover,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorBrand-2M3O3N:hover,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorGreen-3y-Z79:hover,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorRed-2VFhM4:hover {
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.1);
  border-color: hsla(0, 0%, 0%, 0.1);
}
#app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorBrand-2M3O3N:active, #app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorGreen-3y-Z79:active, #app-mount .button-ejjZWC.lookFilled-1H2Jvj.colorRed-2VFhM4:active,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorBrand-2M3O3N:active,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorGreen-3y-Z79:active,
#app-mount .button-f2h6uQ.lookFilled-1H2Jvj.colorRed-2VFhM4:active {
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.2);
  border-color: hsla(0, 0%, 0%, 0.2);
}
#app-mount .button-ejjZWC.lookOutlined-3RTC7c,
#app-mount .button-f2h6uQ.lookOutlined-3RTC7c {
  cursor: pointer;
  border: none;
  background: transparent !important;
}
#app-mount .button-ejjZWC.lookOutlined-3RTC7c .contents-3NembX,
#app-mount .button-f2h6uQ.lookOutlined-3RTC7c .contents-3NembX {
  background: none;
}
#app-mount .button-ejjZWC.lookOutlined-3RTC7c::before,
#app-mount .button-f2h6uQ.lookOutlined-3RTC7c::before {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: currentColor;
  z-index: 1;
  border-radius: inherit;
  opacity: 0;
  pointer-events: none;
}
#app-mount .button-ejjZWC.lookOutlined-3RTC7c.sizeMin-DfpWCE,
#app-mount .button-f2h6uQ.lookOutlined-3RTC7c.sizeMin-DfpWCE {
  font-size: var(--font-size-xs);
}
#app-mount .button-ejjZWC.lookOutlined-3RTC7c:hover::before,
#app-mount .button-f2h6uQ.lookOutlined-3RTC7c:hover::before {
  opacity: 0.1;
}
#app-mount .button-ejjZWC.lookOutlined-3RTC7c:active::before,
#app-mount .button-f2h6uQ.lookOutlined-3RTC7c:active::before {
  opacity: 0.07;
}
#app-mount .button-ejjZWC.lookOutlined-3RTC7c.colorRed-2VFhM4,
#app-mount .button-f2h6uQ.lookOutlined-3RTC7c.colorRed-2VFhM4 {
  color: hsl(var(--discord-red));
}
#app-mount .button-ejjZWC.lookLink-13iF2K,
#app-mount .button-f2h6uQ.lookLink-13iF2K {
  cursor: pointer;
  color: rgb(var(--accent));
}
#app-mount .button-ejjZWC.lookLink-13iF2K .contents-3NembX,
#app-mount .button-f2h6uQ.lookLink-13iF2K .contents-3NembX {
  background: none;
}
#app-mount .button-ejjZWC.lookLink-13iF2K.sizeMin-3Yqxk5,
#app-mount .button-f2h6uQ.lookLink-13iF2K.sizeMin-3Yqxk5 {
  font-size: var(--font-size-xs);
}
#app-mount .button-ejjZWC.lookLink-13iF2K:hover,
#app-mount .button-f2h6uQ.lookLink-13iF2K:hover {
  background: var(--btn-bg);
}
#app-mount .button-ejjZWC.lookLink-13iF2K:active,
#app-mount .button-f2h6uQ.lookLink-13iF2K:active {
  background: var(--btn-bg-active);
}
#app-mount .applicationInstallButtonContent-2GoIj7 {
  display: flex;
  align-items: center;
  gap: 8px;
}
#app-mount .applicationInstallButtonContent-2GoIj7 .launchIcon-RTf7He {
  margin-left: 0;
}
#app-mount .component-ifCTxY {
  margin: 4px !important;
}

#app-mount .input-2g-os5:not(.multiInput-1VARjC, .multiInputField-1zyopx, .input-2yCVqe),
#app-mount .input-2g-os5.multiInput-1VARjC {
  background: var(--textbox-bg);
  border: 1px solid var(--textbox-border);
  height: 32px;
  padding: 0;
  border-radius: var(--rounded);
  padding: 8px 10px;
  font-size: var(--font-size-sm);
  box-sizing: border-box;
  border-bottom-color: var(--textbox-underline);
  transition: none;
  color: var(--text-secondary) !important;
  cursor: text;
}
#app-mount .input-2g-os5:not(.multiInput-1VARjC, .multiInputField-1zyopx, .input-2yCVqe)::-moz-placeholder, #app-mount .input-2g-os5.multiInput-1VARjC::-moz-placeholder {
  font-size: var(--font-size-sm);
  color: var(--text-muted);
}
#app-mount .input-2g-os5:not(.multiInput-1VARjC, .multiInputField-1zyopx, .input-2yCVqe)::placeholder,
#app-mount .input-2g-os5.multiInput-1VARjC::placeholder {
  font-size: var(--font-size-sm);
  color: var(--text-muted);
}
#app-mount .input-2g-os5:not(.multiInput-1VARjC, .multiInputField-1zyopx, .input-2yCVqe):hover,
#app-mount .input-2g-os5.multiInput-1VARjC:hover {
  background: var(--textbox-bg-hover);
}
#app-mount .input-2g-os5:not(.multiInput-1VARjC, .multiInputField-1zyopx, .input-2yCVqe):focus, #app-mount .input-2g-os5:not(.multiInput-1VARjC, .multiInputField-1zyopx, .input-2yCVqe):focus-within,
#app-mount .input-2g-os5.multiInput-1VARjC:focus,
#app-mount .input-2g-os5.multiInput-1VARjC:focus-within {
  background: var(--textbox-bg-active) !important;
  box-shadow: inset 0 -1px 0 rgb(var(--accent));
  border-bottom-color: rgb(var(--accent));
}
#app-mount .input-2g-os5.textArea-3WXAeD {
  height: auto !important;
}
#app-mount .multiInput-1VARjC .inputWrapper-1YNMmM::before {
  content: none;
}
#app-mount .multiInput-1VARjC input {
  padding: 0;
}
#app-mount .multiInput-1VARjC .multiInputLast-35zVz0 input {
  padding-left: 36px;
}
#app-mount .inputWrapper-1YNMmM > svg {
  width: 18px;
  height: 18px;
  left: 8px;
  top: 8px;
}
#app-mount .inputWrapper-1YNMmM > svg + .input-2g-os5 {
  padding-left: 32px;
}

#app-mount .buttonsContainer-3rygH4 {
  margin: 0;
  gap: 16px;
}
#app-mount .colorSwatch-3KbHGH {
  margin-right: 0;
  position: relative;
}
#app-mount .swatch-35F5kl {
  width: 75px;
  height: 35px;
}
#app-mount .swatchDescription--ZWxV0 {
  text-align: left;
  font-size: var(--font-size-xs);
  margin-top: 0;
}

#app-mount .container-1QtPKm {
  background: transparent !important;
  width: 40px;
  height: 20px;
}
#app-mount .container-1QtPKm svg {
  display: none;
}
#app-mount .container-1QtPKm input {
  display: inline-flex;
  align-items: center;
  opacity: 1;
  -webkit-appearance: none;
     -moz-appearance: none;
          appearance: none;
  border: 1px solid var(--switch-border);
  width: 40px;
  height: 20px;
  border-radius: 20px;
  margin: 0;
  padding: 0 4px;
  cursor: var(--cursor);
  transition: background 0.15s var(--transition), border-color 0.15s var(--transition);
}
#app-mount .container-1QtPKm input::before {
  content: "";
  width: 12px;
  height: 12px;
  border-radius: 7px;
  display: block;
  background: var(--text-secondary);
  transition: background 0.15s var(--transition), transform 0.15s var(--transition), width 0.15s var(--transition), height 0.15s var(--transition);
}
#app-mount .container-1QtPKm input:hover:not(:checked) {
  background: hsla(0, 0%, 100%, 0.05) !important;
}
#app-mount .container-1QtPKm input:hover::before {
  width: 14px;
  height: 14px;
}
#app-mount .container-1QtPKm input:active::before {
  width: 18px;
}
#app-mount .container-1QtPKm input:checked {
  background: rgb(var(--accent));
  border-color: rgb(var(--accent));
}
#app-mount .container-1QtPKm input:checked::before {
  background: var(--accent-text);
  transform: translateX(18px);
}
#app-mount .container-1QtPKm input:checked:hover {
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.12);
  border-color: hsla(0, 0%, 0%, 0.12);
}
#app-mount .container-1QtPKm input:checked:active::before {
  transform: translateX(13px);
}

#app-mount [role=radiogroup] {
  border: 1px solid var(--border);
  background: var(--bg-content);
  border-radius: var(--rounded);
  overflow: hidden;
}
#app-mount [role=radiogroup] .item-1TA5qI {
  background: transparent;
  margin: 0;
  border-radius: 0;
}
#app-mount [role=radiogroup] .item-1TA5qI:not(:last-child) {
  border-bottom: 1px solid var(--border);
}
#app-mount [role=radiogroup] .item-1TA5qI:hover {
  background: var(--bg-content-alt);
}
#app-mount [role=radiogroup] .item-1TA5qI[aria-checked=true] .radioBar-1XgZqD > div:first-child {
  background: var(--radio-bar-accent-color, var(--accent-solid));
  border-color: var(--radio-bar-accent-color, var(--accent-solid));
}
#app-mount [role=radiogroup] .item-1TA5qI[aria-checked=true] .radioBar-1XgZqD > div:first-child::before {
  background: var(--accent-text);
}
#app-mount [role=radiogroup] .radioBar-1XgZqD {
  border-radius: 0;
  padding: 16px !important;
  display: flex;
  flex-direction: row-reverse;
  align-items: center;
  border: none;
  cursor: var(--cursor);
}
#app-mount [role=radiogroup] .radioBar-1XgZqD > div:first-child {
  display: flex;
  align-items: center;
  justify-content: center;
  min-width: 20px;
  min-height: 20px;
  max-width: 20px;
  max-height: 20px;
  border-radius: 50%;
  border: 1px solid var(--text-muted);
}
#app-mount [role=radiogroup] .radioBar-1XgZqD > div:first-child::before {
  content: "";
  width: 12px;
  height: 12px;
  border-radius: 50%;
}
#app-mount [role=radiogroup] .radioBar-1XgZqD svg {
  display: none;
}
#app-mount [role=radiogroup] .info-2FZci4 {
  gap: 0;
}
#app-mount [role=radiogroup] .title-1yyp9V {
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
}
#app-mount [role=radiogroup] .size14-3fJ-ot {
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
}

#app-mount .select-1Ia3hD {
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-normal);
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  border-radius: var(--btn-radius);
  cursor: var(--cursor);
  transition: box-shadow 0.15s var(--transition);
  padding: 6px 6px 6px 12px;
}
#app-mount .select-1Ia3hD .value-26hJ01 {
  color: var(--text-secondary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height-lg);
}
#app-mount .select-1Ia3hD .icons-2dXYop {
  width: 18px;
  height: 18px;
}
#app-mount .select-1Ia3hD:hover {
  background: var(--btn-bg-hover);
}
#app-mount .select-1Ia3hD:active {
  background: var(--btn-bg-active);
  border-color: var(--btn-border-active);
}
#app-mount .popout-1KHNAq {
  background: var(--bg-menu);
  border-radius: var(--rounded);
  border: 1px solid var(--border);
  box-shadow: var(--shadow-flyout);
  margin-top: 6px;
  padding: 6px !important;
  display: flex;
  flex-direction: column;
  gap: 4px;
  max-height: 350px !important;
}
#app-mount .option-2eIyOn {
  border-radius: var(--rounded);
  font-size: var(--font-size-sm);
  padding: 10px 14px;
  position: relative;
  cursor: var(--cursor);
}
#app-mount .option-2eIyOn:hover, #app-mount .option-2eIyOn:focus, #app-mount .option-2eIyOn.focused-ODgjnC {
  background: var(--bg-menu-item-hover);
}
#app-mount .option-2eIyOn[aria-selected=true] {
  background: var(--bg-menu-item-hover);
}
#app-mount .option-2eIyOn[aria-selected=true]::before {
  content: "";
  position: absolute;
  top: 50%;
  left: 0;
  transform: translateY(-50%);
  width: 3px;
  height: var(--pill-height);
  background: rgb(var(--accent));
  border-radius: 30%;
}
#app-mount .selectedIcon-19TbzU {
  display: none;
}
#app-mount .optionLabel-1h0MHL {
  margin: 0;
}

#app-mount .container-2uPlB3 .selectedProgressBar-11z5d9 {
  background: rgb(var(--accent));
}
#app-mount .container-2uPlB3 .colorBrand-21Le_q {
  color: rgb(var(--accent));
}

#app-mount .layer-86YKbF ~ .layer-86YKbF .contentColumn-1C7as6 > .heading-lg-semibold-14ouVv:first-child, #app-mount .layer-86YKbF ~ .layer-86YKbF .contentColumn-1C7as6 > div > div:first-child > .sectionTitle-LdcnyP:first-child .title-lXcL8p, #app-mount .layer-86YKbF ~ .layer-86YKbF .contentColumn-1C7as6 > div:first-child > .sectionTitle-LdcnyP:first-child .title-lXcL8p {
  color: var(--header-primary);
  font-size: var(--font-size-xl);
  line-height: var(--line-height-2xl);
  font-weight: var(--font-weight-semibold);
  margin-bottom: 48px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .title-2dsDLn {
  cursor: var(--cursor);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF [class^=margin] > .title-lXcL8p,
#app-mount .layer-86YKbF ~ .layer-86YKbF .marginTop40-Q4o1tS > .sectionTitle-LdcnyP > .title-lXcL8p,
#app-mount .layer-86YKbF ~ .layer-86YKbF .title-lXcL8p.marginBottom8-emkd0_,
#app-mount .layer-86YKbF ~ .layer-86YKbF .sectionTitle-LdcnyP .title-lXcL8p:not(h1) {
  color: var(--text-primary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-semibold);
  line-height: var(--line-height-md);
  margin-bottom: 12px;
  text-transform: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF [class*=divider-] {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .children-1xdcWE > .description-30xx7u.formText-2ngGjI {
  color: var(--text-tertiary);
  font-size: var(--font-size-xs);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .title-lXcL8p.marginBottom8-emkd0_ + .description-30xx7u.formText-2ngGjI,
#app-mount .layer-86YKbF ~ .layer-86YKbF .title-lXcL8p.defaultMarginh3-2aILfT + .description-30xx7u.formText-2ngGjI {
  background: var(--bg-content);
  border-radius: var(--rounded);
  border: 1px solid var(--border);
  padding: 16px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .children-1xdcWE > .divider-_0um2u + div {
  margin-top: 40px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-31PmuA {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 0 18px;
  position: relative;
  margin-top: 0;
  margin-bottom: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-31PmuA .title-2yADjX {
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-31PmuA .note-3SS3a9 {
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-31PmuA + .title-lXcL8p, #app-mount .layer-86YKbF ~ .layer-86YKbF .container-31PmuA + div[class^=margin]:not(.container-31PmuA) {
  margin-top: 40px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .contentRegionScroller-2_GT_N {
  margin-top: calc(var(--win-btn-height) + 16px);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF [class^=margin] + [class^=margin] {
  margin-top: 40px;
  margin-bottom: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .children-1xdcWE > [class^=marginBottom]:not(:only-child):first-child {
  margin-bottom: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .title-lXcL8p.defaultMarginh3-2aILfT {
  margin-top: 40px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .noticeRegion-qjyUVg {
  max-width: 980px;
  right: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-20TyK0 {
  box-shadow: var(--shadow-flyout);
  padding: 16px;
  background: var(--bg-content-alt) !important;
  border: 1px solid var(--border);
  border-radius: var(--rounded);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-20TyK0 .flex-2S1XBF {
  gap: 8px;
}

#app-mount .layer-86YKbF {
  background: var(--bg-main);
}
#app-mount .layer-86YKbF .toolsContainer-25FL6V {
  margin: 0;
  padding: 0;
  flex: none;
  width: auto;
  position: fixed;
  top: 5px;
  left: 5px;
  z-index: 2;
  width: auto;
  -webkit-user-drag: none;
  -webkit-app-region: none;
}
#app-mount .layer-86YKbF .tools-kIrEGr {
  position: static;
}
#app-mount .layer-86YKbF .container-O54IuJ {
  flex-direction: row;
  align-items: center;
  width: 100%;
  gap: 8px;
}
#app-mount .layer-86YKbF .closeButton-PCZcma {
  border-radius: var(--btn-radius);
  width: 42px;
  flex: 0 0 42px;
  border: none;
  cursor: var(--cursor);
}
#app-mount .layer-86YKbF .closeButton-PCZcma svg {
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M10.733 19.79a.75.75 0 0 0 1.034-1.086L5.516 12.75H20.25a.75.75 0 0 0 0-1.5H5.516l6.251-5.955a.75.75 0 0 0-1.034-1.086l-7.42 7.067a.995.995 0 0 0-.3.58.754.754 0 0 0 .001.289.995.995 0 0 0 .3.579l7.419 7.067Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M10.733 19.79a.75.75 0 0 0 1.034-1.086L5.516 12.75H20.25a.75.75 0 0 0 0-1.5H5.516l6.251-5.955a.75.75 0 0 0-1.034-1.086l-7.42 7.067a.995.995 0 0 0-.3.58.754.754 0 0 0 .001.289.995.995 0 0 0 .3.579l7.419 7.067Z" /></svg>') center/cover;
  width: 16px;
  height: 16px;
  background: var(--text-primary);
}
#app-mount .layer-86YKbF .closeButton-PCZcma path {
  display: none;
}
#app-mount .layer-86YKbF .closeButton-PCZcma:hover {
  background: var(--btn-bg-hover);
}
#app-mount .layer-86YKbF .closeButton-PCZcma:active {
  background: var(--btn-bg-active);
  transform: none;
}
#app-mount .layer-86YKbF .keybind-13vtq8 {
  margin-top: 0;
  font-size: 0;
  color: var(--text-primary);
}
#app-mount .layer-86YKbF .keybind-13vtq8::before {
  content: "Settings";
  font-size: var(--font-size-xs);
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .standardSidebarView-E9Pc3j {
  background: var(--bg-main);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebarRegion-1VBisG {
  flex: 0;
  margin-top: 46px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebarRegionScroller-FXiQOh {
  background: var(--bg-main);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN {
  width: 270px;
  padding: 0 16px 16px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy {
  font-size: var(--font-size-sm);
  border-radius: var(--rounded);
  padding: 8px 12px;
  display: flex;
  align-items: center;
  gap: 12px;
  position: relative;
  cursor: var(--cursor);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy:not(:last-child) {
  margin-bottom: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy svg {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy .selectedBackground-1qyzak {
  background: rgb(var(--accent));
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy::after {
  content: "";
  position: absolute;
  left: 0;
  height: 0;
  width: 4px;
  border-radius: 4px;
  background: rgb(var(--accent));
  opacity: 0;
  transition: 0.15s var(--transition);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy:hover {
  background: var(--bg-interactive);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy.selected-1sf9UK {
  background: var(--bg-interactive);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy.selected-1sf9UK .premiumLabel-V52REm {
  color: var(--accent-text);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy.selected-1sf9UK .selectedIcon-3rJcYb {
  fill: var(--accent-text);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy.selected-1sf9UK::after {
  height: 16px;
  opacity: 1;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .item-2GWPIy.selected-1sf9UK:hover {
  background: var(--bg-interactive-hover);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .header-2F5_LB {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-nqHbhN .separator-2N511j {
  height: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .contentRegion-3HkfJJ {
  background: var(--bg-main);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .contentRegionScroller-2_GT_N {
  background: var(--bg-main);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .contentColumn-1C7as6:not(.contentColumnMinimal-32PuDO) {
  padding: 0 32px 32px;
  max-width: 1000px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .contentColumn-1C7as6:not(.contentColumnMinimal-32PuDO) > div {
  animation: settingsIn 0.25s ease forwards;
}

#app-mount .layer-86YKbF ~ .layer-86YKbF .accountProfileCard-lbN7n- {
  background: transparent;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .banner-2boKnS,
#app-mount .layer-86YKbF ~ .layer-86YKbF .bannerSVGWrapper-2CLfzN {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W {
  padding: 18px;
  margin: 0 0 4px 0;
  height: auto;
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0 18px;
  position: relative;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W .avatar-3mTjvZ {
  width: 22px !important;
  height: 22px !important;
  background: var(--text-primary);
  border: none;
  position: relative;
  z-index: 1;
  top: 0;
  left: 0;
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M21.03 2.97a3.578 3.578 0 0 1 0 5.06L9.062 20a2.25 2.25 0 0 1-.999.58l-5.116 1.395a.75.75 0 0 1-.92-.921l1.395-5.116a2.25 2.25 0 0 1 .58-.999L15.97 2.97a3.578 3.578 0 0 1 5.06 0ZM15 6.06 5.062 16a.75.75 0 0 0-.193.333l-1.05 3.85 3.85-1.05A.75.75 0 0 0 8 18.938L17.94 9 15 6.06Zm2.03-2.03-.97.97L19 7.94l.97-.97a2.079 2.079 0 0 0-2.94-2.94Z" /></svg>') center/cover;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W .avatar-3mTjvZ svg {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W > div:nth-child(2) {
  position: relative;
  z-index: 1;
  flex: 1;
  pointer-events: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W > div:nth-child(2) > div {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W > div:nth-child(2)::before {
  content: "Profile";
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W > div:nth-child(2)::after {
  content: "Avatar, banner, about me, profile colour";
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W > button {
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0;
  background: transparent !important;
  border: none !important;
  box-shadow: none !important;
  display: flex;
  color: var(--text-primary);
  padding: 0 0 0 60px;
  z-index: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W > button div {
  width: 100%;
  font-size: 0;
  padding-right: 18px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W > button div::before {
  content: "";
  width: 16px;
  height: 16px;
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M8.47 4.22a.75.75 0 0 0 0 1.06L15.19 12l-6.72 6.72a.75.75 0 1 0 1.06 1.06l7.25-7.25a.75.75 0 0 0 0-1.06L9.53 4.22a.75.75 0 0 0-1.06 0Z" /></svg>') center/cover;
          mask: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M8.47 4.22a.75.75 0 0 0 0 1.06L15.19 12l-6.72 6.72a.75.75 0 1 0 1.06 1.06l7.25-7.25a.75.75 0 0 0 0-1.06L9.53 4.22a.75.75 0 0 0-1.06 0Z" /></svg>') center/cover;
  background: var(--text-primary);
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userInfo-regn9W:hover > button {
  background: var(--bg-content-alt) !important;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .background-3d_SjE {
  margin: 0;
  background: transparent;
  padding: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .fieldList-in8WkP {
  background: transparent;
  border-radius: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .fieldList-in8WkP .field-21XZwa:first-child::before, #app-mount .layer-86YKbF ~ .layer-86YKbF .fieldList-in8WkP .field-21XZwa:nth-child(2)::before {
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.754 14a2.249 2.249 0 0 1 2.25 2.249v.575c0 .894-.32 1.76-.902 2.438-1.57 1.834-3.957 2.739-7.102 2.739-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h11.501Zm0 1.5H6.253a.749.749 0 0 0-.75.749v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214s4.706-.746 5.962-2.214a2.25 2.25 0 0 0 .541-1.463v-.575a.749.749 0 0 0-.749-.75ZM12 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.754 14a2.249 2.249 0 0 1 2.25 2.249v.575c0 .894-.32 1.76-.902 2.438-1.57 1.834-3.957 2.739-7.102 2.739-3.146 0-5.532-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577a2.249 2.249 0 0 1 2.249-2.25h11.501Zm0 1.5H6.253a.749.749 0 0 0-.75.749v.577c0 .536.192 1.054.54 1.461 1.253 1.468 3.219 2.214 5.957 2.214s4.706-.746 5.962-2.214a2.25 2.25 0 0 0 .541-1.463v-.575a.749.749 0 0 0-.749-.75ZM12 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .fieldList-in8WkP .field-21XZwa:nth-child(3)::before {
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.25 4h13.5a3.25 3.25 0 0 1 3.245 3.066L22 7.25v9.5a3.25 3.25 0 0 1-3.066 3.245L18.75 20H5.25a3.25 3.25 0 0 1-3.245-3.066L2 16.75v-9.5a3.25 3.25 0 0 1 3.066-3.245L5.25 4h13.5-13.5ZM20.5 9.373l-8.15 4.29a.75.75 0 0 1-.603.043l-.096-.042L3.5 9.374v7.376a1.75 1.75 0 0 0 1.606 1.744l.144.006h13.5a1.75 1.75 0 0 0 1.744-1.607l.006-.143V9.373ZM18.75 5.5H5.25a1.75 1.75 0 0 0-1.744 1.606L3.5 7.25v.429l8.5 4.473 8.5-4.474V7.25a1.75 1.75 0 0 0-1.607-1.744L18.75 5.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M5.25 4h13.5a3.25 3.25 0 0 1 3.245 3.066L22 7.25v9.5a3.25 3.25 0 0 1-3.066 3.245L18.75 20H5.25a3.25 3.25 0 0 1-3.245-3.066L2 16.75v-9.5a3.25 3.25 0 0 1 3.066-3.245L5.25 4h13.5-13.5ZM20.5 9.373l-8.15 4.29a.75.75 0 0 1-.603.043l-.096-.042L3.5 9.374v7.376a1.75 1.75 0 0 0 1.606 1.744l.144.006h13.5a1.75 1.75 0 0 0 1.744-1.607l.006-.143V9.373ZM18.75 5.5H5.25a1.75 1.75 0 0 0-1.744 1.606L3.5 7.25v.429l8.5 4.473 8.5-4.474V7.25a1.75 1.75 0 0 0-1.607-1.744L18.75 5.5Z" /></svg>');
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .fieldList-in8WkP .field-21XZwa:last-child::before {
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15.75 2A2.25 2.25 0 0 1 18 4.25v15.5A2.25 2.25 0 0 1 15.75 22h-7.5A2.25 2.25 0 0 1 6 19.75V4.25A2.25 2.25 0 0 1 8.25 2h7.5Zm0 1.5h-7.5a.75.75 0 0 0-.75.75v15.5c0 .414.336.75.75.75h7.5a.75.75 0 0 0 .75-.75V4.25a.75.75 0 0 0-.75-.75Zm-2.501 14a.75.75 0 0 1 .002 1.5l-2.5.004a.75.75 0 0 1-.002-1.5l2.5-.004Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M15.75 2A2.25 2.25 0 0 1 18 4.25v15.5A2.25 2.25 0 0 1 15.75 22h-7.5A2.25 2.25 0 0 1 6 19.75V4.25A2.25 2.25 0 0 1 8.25 2h7.5Zm0 1.5h-7.5a.75.75 0 0 0-.75.75v15.5c0 .414.336.75.75.75h7.5a.75.75 0 0 0 .75-.75V4.25a.75.75 0 0 0-.75-.75Zm-2.501 14a.75.75 0 0 1 .002 1.5l-2.5.004a.75.75 0 0 1-.002-1.5l2.5-.004Z" /></svg>');
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0 18px;
  position: relative;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa .sizeMin-1mJd1x {
  margin-left: 8px;
  padding: 0;
  background: transparent;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa .sizeMin-1mJd1x:hover {
  text-decoration: underline;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa .fieldButtonList-28BYbB {
  gap: 18px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa .fieldButtonList-28BYbB button {
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa .usernameInnerRow-1-STdK {
  display: flex;
  align-items: center;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa .text-md-normal-2rFCH3 {
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
  line-height: normal;
  color: var(--text-muted) !important;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa .text-md-normal-2rFCH3 > span {
  font-size: inherit;
  line-height: inherit;
  color: inherit !important;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa .text-md-normal-2rFCH3 button {
  padding: 0;
  margin-left: 12px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa::before {
  content: "";
  width: 22px;
  height: 22px;
  -webkit-mask-size: cover;
          mask-size: cover;
  -webkit-mask-position: center;
          mask-position: center;
  background: var(--text-primary);
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .field-21XZwa:not(:first-child) {
  margin-top: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .constrainedRow-3y91Xf {
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .constrainedRow-3y91Xf .size16-rrJ6ag {
  font-size: var(--font-size-xs);
  color: var(--text-muted);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .fieldTitle-2g5r_V {
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN .h1-34Txb0 {
  color: var(--text-primary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-semibold);
  line-height: var(--line-height-md);
  margin-bottom: 12px;
  text-transform: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div:first-child {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0 18px;
  position: relative;
  margin-bottom: 40px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div:first-child button {
  margin: 0;
  order: 1;
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div:first-child button:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div:first-child button:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div:first-child::before {
  content: "";
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M11.78 10.22a.75.75 0 0 0-1.06 1.06l.72.72-.72.72a.75.75 0 1 0 1.06 1.06l.72-.72.72.72a.75.75 0 0 0 1.06-1.062L13.561 12l.72-.72a.75.75 0 1 0-1.061-1.06l-.72.72-.72-.72ZM5.22 10.22a.75.75 0 0 1 1.06 0l.72.72.72-.72a.75.75 0 1 1 1.06 1.06l-.719.72.72.718A.75.75 0 1 1 7.72 13.78L7 13.06l-.72.72a.75.75 0 0 1-1.06-1.06l.72-.72-.72-.72a.75.75 0 0 1 0-1.06ZM16.5 13.5a.75.75 0 0 0 0 1.5h1.75a.75.75 0 0 0 0-1.5H16.5Z" /><path d="M5.25 5A3.25 3.25 0 0 0 2 8.25v7.5A3.25 3.25 0 0 0 5.25 19h13.5A3.25 3.25 0 0 0 22 15.75v-7.5A3.25 3.25 0 0 0 18.75 5H5.25ZM3.5 8.25c0-.967.783-1.75 1.75-1.75h13.5c.967 0 1.75.783 1.75 1.75v7.5a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-7.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M11.78 10.22a.75.75 0 0 0-1.06 1.06l.72.72-.72.72a.75.75 0 1 0 1.06 1.06l.72-.72.72.72a.75.75 0 0 0 1.06-1.062L13.561 12l.72-.72a.75.75 0 1 0-1.061-1.06l-.72.72-.72-.72ZM5.22 10.22a.75.75 0 0 1 1.06 0l.72.72.72-.72a.75.75 0 1 1 1.06 1.06l-.719.72.72.718A.75.75 0 1 1 7.72 13.78L7 13.06l-.72.72a.75.75 0 0 1-1.06-1.06l.72-.72-.72-.72a.75.75 0 0 1 0-1.06ZM16.5 13.5a.75.75 0 0 0 0 1.5h1.75a.75.75 0 0 0 0-1.5H16.5Z" /><path d="M5.25 5A3.25 3.25 0 0 0 2 8.25v7.5A3.25 3.25 0 0 0 5.25 19h13.5A3.25 3.25 0 0 0 22 15.75v-7.5A3.25 3.25 0 0 0 18.75 5H5.25ZM3.5 8.25c0-.967.783-1.75 1.75-1.75h13.5c.967 0 1.75.783 1.75 1.75v7.5a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-7.5Z" /></svg>');
  width: 22px;
  height: 22px;
  -webkit-mask-size: cover;
          mask-size: cover;
  -webkit-mask-position: center;
          mask-position: center;
  background: var(--text-primary);
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div:first-child::after {
  content: "Password";
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
  flex: 1;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .h5-2feg8J:first-child {
  color: var(--text-primary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-semibold);
  line-height: var(--line-height-md);
  margin-bottom: 12px;
  text-transform: none;
  color: transparent;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .h5-2feg8J:first-child::before {
  content: "Security";
  color: var(--text-primary);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .h5-2feg8J:first-child img {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .modeDefault-3Warim {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 0 18px;
  position: relative;
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
  padding-left: 60px !important;
  gap: 4px;
  border-radius: var(--rounded) var(--rounded) 0 0;
  margin-bottom: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .modeDefault-3Warim::before {
  content: "Two-factor authentication";
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .modeDefault-3Warim::after {
  content: "";
  width: 22px;
  height: 22px;
  -webkit-mask-size: cover;
          mask-size: cover;
  -webkit-mask-position: center;
          mask-position: center;
  background: var(--text-primary);
  display: block;
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2a4 4 0 0 1 4 4v2h1.75A2.25 2.25 0 0 1 20 10.25v9.5A2.25 2.25 0 0 1 17.75 22H6.25A2.25 2.25 0 0 1 4 19.75v-9.5A2.25 2.25 0 0 1 6.25 8H8V6a4 4 0 0 1 4-4Zm5.75 7.5H6.25a.75.75 0 0 0-.75.75v9.5c0 .414.336.75.75.75h11.5a.75.75 0 0 0 .75-.75v-9.5a.75.75 0 0 0-.75-.75Zm-5.75 4a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Zm0-10A2.5 2.5 0 0 0 9.5 6v2h5V6A2.5 2.5 0 0 0 12 3.5Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2a4 4 0 0 1 4 4v2h1.75A2.25 2.25 0 0 1 20 10.25v9.5A2.25 2.25 0 0 1 17.75 22H6.25A2.25 2.25 0 0 1 4 19.75v-9.5A2.25 2.25 0 0 1 6.25 8H8V6a4 4 0 0 1 4-4Zm5.75 7.5H6.25a.75.75 0 0 0-.75.75v9.5c0 .414.336.75.75.75h11.5a.75.75 0 0 0 .75-.75v-9.5a.75.75 0 0 0-.75-.75Zm-5.75 4a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3Zm0-10A2.5 2.5 0 0 0 9.5 6v2h5V6A2.5 2.5 0 0 0 12 3.5Z" /></svg>');
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  left: 18px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .modeDefault-3Warim + div {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0 18px;
  position: relative;
  margin-top: 0;
  border-top: none;
  border-radius: 0 0 var(--rounded) var(--rounded);
  justify-content: flex-start;
  flex-direction: row-reverse;
  margin-bottom: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .modeDefault-3Warim + div > div {
  flex: none !important;
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .modeDefault-3Warim + div .button-38aScr.lookFilled-1Gx00P.colorBrand-3pXr91 {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .modeDefault-3Warim + div .button-38aScr.lookFilled-1Gx00P.colorBrand-3pXr91:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .modeDefault-3Warim + div .button-38aScr.lookFilled-1Gx00P.colorBrand-3pXr91:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS {
  margin-top: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS .sectionTitle-LdcnyP {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS .marginBottom8-emkd0_ {
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS .children-2C96Ex {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 0 18px;
  position: relative;
  padding-left: 60px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS .children-2C96Ex::before {
  content: "";
  width: 22px;
  height: 22px;
  -webkit-mask-size: cover;
          mask-size: cover;
  -webkit-mask-position: center;
          mask-position: center;
  background: var(--text-primary);
  display: block;
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M13.75 2A2.25 2.25 0 0 1 16 4.25v6.587a3.515 3.515 0 0 0-1.5 1.36V4.25a.75.75 0 0 0-.75-.75h-7.5a.75.75 0 0 0-.75.75v15.5c0 .414.336.75.75.75H12v1c0 .171.017.338.05.5h-5.8A2.25 2.25 0 0 1 4 19.75V4.25A2.25 2.25 0 0 1 6.25 2h7.5ZM15 14a2.496 2.496 0 0 1 2.5-2.5A2.5 2.5 0 0 1 20 14v1h.5a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5v-5a1.5 1.5 0 0 1 1.5-1.5h.5v-1Zm1.5 0v1h2v-1a1 1 0 1 0-2 0Zm2 5a1 1 0 1 0-2 0 1 1 0 0 0 2 0Zm-6.5-.751v.001a.75.75 0 0 1-.749.75l-2.5.004a.75.75 0 0 1-.002-1.5l2.5-.004a.75.75 0 0 1 .751.749Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M13.75 2A2.25 2.25 0 0 1 16 4.25v6.587a3.515 3.515 0 0 0-1.5 1.36V4.25a.75.75 0 0 0-.75-.75h-7.5a.75.75 0 0 0-.75.75v15.5c0 .414.336.75.75.75H12v1c0 .171.017.338.05.5h-5.8A2.25 2.25 0 0 1 4 19.75V4.25A2.25 2.25 0 0 1 6.25 2h7.5ZM15 14a2.496 2.496 0 0 1 2.5-2.5A2.5 2.5 0 0 1 20 14v1h.5a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5v-5a1.5 1.5 0 0 1 1.5-1.5h.5v-1Zm1.5 0v1h2v-1a1 1 0 1 0-2 0Zm2 5a1 1 0 1 0-2 0 1 1 0 0 0 2 0Zm-6.5-.751v.001a.75.75 0 0 1-.749.75l-2.5.004a.75.75 0 0 1-.002-1.5l2.5-.004a.75.75 0 0 1 .751.749Z" /></svg>');
  position: absolute;
  top: calc(50% - 35px);
  transform: translateY(-50%);
  left: 18px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS .children-2C96Ex .modeDefault-2fEh7a:first-child::before {
  content: "SMS backup";
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
  margin-bottom: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS .children-2C96Ex .flex-2S1XBF {
  padding: 18px;
  border-top: 1px solid var(--border);
  margin: 16px -60px -18px;
  width: calc(100% + 78px);
  flex-direction: row-reverse;
  gap: 18px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS .children-2C96Ex .flex-2S1XBF .lookFilled-1Gx00P.colorBrand-3pXr91 {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS .children-2C96Ex .flex-2S1XBF .lookFilled-1Gx00P.colorBrand-3pXr91:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN > .children-2C96Ex > div.flex-2S1XBF > div > div > .marginTop40-Q4o1tS .children-2C96Ex .flex-2S1XBF .lookFilled-1Gx00P.colorBrand-3pXr91:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN ~ .marginTop40-Q4o1tS .h5-2feg8J {
  color: var(--text-primary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-semibold);
  line-height: var(--line-height-md);
  margin-bottom: 12px;
  text-transform: none;
  color: transparent;
  -webkit-user-select: none;
     -moz-user-select: none;
          user-select: none;
  font-size: 0 !important;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN ~ .marginTop40-Q4o1tS .h5-2feg8J::before {
  content: "Danger zone";
  font-size: var(--font-size);
  color: var(--text-primary);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN ~ .marginTop40-Q4o1tS .children-2C96Ex {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0 18px;
  position: relative;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN ~ .marginTop40-Q4o1tS .children-2C96Ex::before {
  content: "";
  width: 22px;
  height: 22px;
  -webkit-mask-size: cover;
          mask-size: cover;
  -webkit-mask-position: center;
          mask-position: center;
  background: var(--text-primary);
  display: block;
  -webkit-mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm3.071.966-.07.058-.057.07a.5.5 0 0 0 0 .568l.058.069 1.77 1.77-1.768 1.766-.057.07a.5.5 0 0 0 0 .568l.058.07.069.057a.5.5 0 0 0 .568 0l.07-.058 1.766-1.767 1.77 1.77.069.058a.5.5 0 0 0 .568 0l.07-.058.058-.07a.5.5 0 0 0 0-.568l-.058-.07-1.77-1.768 1.772-1.77.058-.07a.5.5 0 0 0 0-.568l-.058-.069-.069-.058a.5.5 0 0 0-.569 0l-.069.058-1.771 1.77-1.77-1.77-.07-.058a.5.5 0 0 0-.492-.043l-.076.043ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
          mask-image: url('data:image/svg+xml; utf-8,<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.5 12a5.5 5.5 0 1 1 0 11 5.5 5.5 0 0 1 0-11Zm-5.478 2a6.474 6.474 0 0 0-.708 1.5h-7.06a.75.75 0 0 0-.75.75v.907c0 .656.286 1.279.783 1.706C5.545 19.945 7.44 20.501 10 20.501c.599 0 1.162-.03 1.688-.091.25.5.563.964.93 1.38-.803.141-1.676.21-2.618.21-2.89 0-5.128-.656-6.691-2a3.75 3.75 0 0 1-1.305-2.843v-.907A2.25 2.25 0 0 1 4.254 14h7.768Zm3.071.966-.07.058-.057.07a.5.5 0 0 0 0 .568l.058.069 1.77 1.77-1.768 1.766-.057.07a.5.5 0 0 0 0 .568l.058.07.069.057a.5.5 0 0 0 .568 0l.07-.058 1.766-1.767 1.77 1.77.069.058a.5.5 0 0 0 .568 0l.07-.058.058-.07a.5.5 0 0 0 0-.568l-.058-.07-1.77-1.768 1.772-1.77.058-.07a.5.5 0 0 0 0-.568l-.058-.069-.069-.058a.5.5 0 0 0-.569 0l-.069.058-1.771 1.77-1.77-1.77-.07-.058a.5.5 0 0 0-.492-.043l-.076.043ZM10 2.004a5 5 0 1 1 0 10 5 5 0 0 1 0-10Zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7Z" /></svg>');
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN ~ .marginTop40-Q4o1tS .description-foE_WP {
  margin-bottom: 0;
  flex: 1;
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN ~ .marginTop40-Q4o1tS .description-foE_WP::before {
  content: "Disable account";
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN ~ .marginTop40-Q4o1tS .buttonContainer-cmXa0P {
  flex-direction: row-reverse;
  gap: 16px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .userSettingsSecurity-2kODPN ~ .marginTop40-Q4o1tS .buttonContainer-cmXa0P button {
  margin: 0;
}

#app-mount #profile-customization-tab .top-K_jibn {
  border: none;
}
#app-mount #profile-customization-tab .baseLayoutProfileThemes-1Jj-oN {
  flex-direction: column;
}
#app-mount #profile-customization-tab .customizationSection-IGy2fS {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0 18px;
  position: relative;
  justify-content: space-between;
}
#app-mount #profile-customization-tab .customizationSection-IGy2fS .description-foE_WP {
  display: none;
}
#app-mount #profile-customization-tab .customizationSection-IGy2fS:last-child {
  flex-direction: column;
  align-items: flex-start;
}
#app-mount #profile-customization-tab .customizationSection-IGy2fS.withDivider-14SSKx:not(.section-2ZF4mt) .buttonsContainer-12kYno {
  flex-direction: row-reverse;
  gap: 8px;
}
#app-mount #profile-customization-tab .title-1HgbhV {
  margin: 0;
}
#app-mount #profile-customization-tab .tryItOutSection-W9qeGH {
  display: none;
}

#app-mount .layer-86YKbF ~ .layer-86YKbF .formNotice-1JW4h2 {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0 18px;
  position: relative;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .formNotice-1JW4h2 .h5-2feg8J {
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .formNotice-1JW4h2 .formNoticeBody-xYQk5u {
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .authedApp-8q3NA9 {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: column;
  align-items: stretch;
  gap: 0 18px;
  position: relative;
  margin-bottom: 4px;
}

#app-mount .layer-86YKbF ~ .layer-86YKbF .accountList-305sx3 {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: column;
  align-items: stretch;
  gap: 0 18px;
  position: relative;
  margin-bottom: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .accountList-305sx3 .title-3hptVQ {
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .accountList-305sx3 .formText-2ngGjI {
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
  margin-bottom: 16px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .accountList-305sx3 + .container-1zDvAE {
  padding: 16px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .connectedAccounts-26X_gr {
  display: flex;
  gap: 8px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .accountBtn-1YkMgV {
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .connectionList-11Q_X- {
  margin-top: 40px;
  gap: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .connection-YOVI9j {
  background: var(--bg-content);
  border-radius: var(--rounded);
  border: 1px solid var(--border);
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .connection-YOVI9j .container-1zDvAE {
  border: none;
  padding: 0;
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .connectionHeader-Ixbb1s {
  padding: 16px;
  background: transparent;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .connectionOptionsWrapper-3aVWcp {
  padding: 16px;
  border-top: 1px solid var(--border);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .connectionOptions-JJ1YEi {
  display: flex;
  gap: 16px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .subEnabledTitle-2MHkAH {
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .integrationsWrapper-1V-5L9 {
  padding: 0;
  margin: 0 16px 16px;
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  background: var(--bg-alt);
  overflow: hidden;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .integrationsWrapper-1V-5L9 .title-3hptVQ {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .integration-1qC-fv {
  margin: 0;
  border-radius: 0;
  background: transparent;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .integration-1qC-fv:not(:last-child) {
  border-bottom: 1px solid var(--border);
}

#app-mount .layer-86YKbF ~ .layer-86YKbF .customColumn-2n-oKU {
  padding: 0 32px 32px;
  max-width: 1000px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .customColumn-2n-oKU > div {
  animation: settingsIn 0.25s ease forwards;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .customColumn-2n-oKU div[aria-hidden=true][style="height: 60px;"] {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-3EtAkD {
  background: var(--bg-content);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
  padding: 18px;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0 18px;
  position: relative;
  cursor: var(--cursor);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-3EtAkD .icon-2DGsye {
  width: 22px;
  height: 22px;
  background: transparent;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-3EtAkD .icon-2DGsye svg {
  width: 100%;
  height: 100%;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-3EtAkD .description-18M4UD {
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-3EtAkD .label-2Pe5f1 {
  color: var(--text-primary);
  font-size: var(--font-size-sm);
  font-weight: var(--font-weight-regular);
  margin: 0;
  text-transform: none;
  display: block;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-3EtAkD .size12-oc4dx4 {
  display: block;
  font-size: var(--font-size-xs);
  color: var(--text-muted);
  margin-top: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .container-3EtAkD:hover {
  background: var(--bg-content-alt);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .searchContainer-16qhPt {
  gap: 16px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .tableHeader-2h-wc8 {
  margin: 0;
  padding: 16px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .tableHeader-2h-wc8 .tableTitle-3zdrSx {
  color: var(--text-tertiary);
  font-size: var(--font-size-xs);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .tableHeader-2h-wc8 .dragSpacing-2GB_1h {
  display: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .tableHeader-2h-wc8 .memberSpacing-1RRW7k {
  margin-left: 28px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6 {
  margin: 0;
  position: relative;
  padding: 0 16px;
  cursor: var(--cursor);
  border-radius: 0;
  border-left: 1px solid var(--border);
  border-right: 1px solid var(--border);
  background: var(--bg-content);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6 + .roleRow-3LoHQ6 {
  border-top: 1px solid var(--border);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6:not(.roleRow-3LoHQ6 + .roleRow-3LoHQ6) {
  border-radius: var(--rounded-high) var(--rounded-high) 0 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6:first-of-type {
  border-top: 1px solid var(--border);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6:last-of-type {
  border-bottom: 1px solid var(--border);
  border-radius: 0 0 var(--rounded-high) var(--rounded-high);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6::before, #app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6::after {
  content: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6 .dragIcon-kQZ0Jv {
  position: absolute;
  left: 10px;
  background: var(--bg-content-alt);
  z-index: 1;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6 .circleButton-33AIyY {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6 .circleButton-33AIyY:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6 .circleButton-33AIyY:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .roleRow-3LoHQ6:hover {
  background: var(--bg-content-alt);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .sidebar-3K3Z4C {
  border: none;
  width: 240px;
  flex: 0 0 240px !important;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .list-1AJFv_ {
  padding: 0 16px 16px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .list-1AJFv_ .item-3XjbnG {
  margin: 0 0 4px;
  height: auto;
  padding: 8px 16px;
  cursor: var(--cursor);
  border-radius: var(--rounded);
  position: relative;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .list-1AJFv_ .item-3XjbnG::before {
  content: "";
  position: absolute;
  left: 0;
  top: 50%;
  transform: translateY(-50%);
  background: rgb(var(--accent));
  width: var(--pill-width);
  height: 0;
  opacity: 0;
  border-radius: 30px;
  transition: var(--pill-transition);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .list-1AJFv_ .item-3XjbnG:hover {
  background: var(--bg-interactive);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .list-1AJFv_ .item-3XjbnG.selected-g-kMVV {
  background: var(--bg-interactive);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .list-1AJFv_ .item-3XjbnG.selected-g-kMVV::before {
  height: var(--pill-height);
  opacity: 1;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .list-1AJFv_ .item-3XjbnG.selected-g-kMVV:hover {
  background: var(--bg-interactive-hover);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .titleContainer-3fPic2 {
  padding: 16px;
  margin: 0;
  background: var(--bg-main);
  box-shadow: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .title-JU0E7C {
  cursor: var(--cursor);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .title-JU0E7C:hover .left-2jjm9w {
  background: var(--bg-interactive);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .titleText-3LapIU {
  color: var(--text-tertiary);
  font-size: var(--font-size-xs);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height);
  margin-left: 4px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .left-2jjm9w {
  width: 32px;
  height: 32px;
  padding: 8px;
  box-sizing: border-box;
  border-radius: var(--btn-radius);
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .contentWidth-3aWel5 {
  width: 100%;
  max-width: 760px;
  padding: 0 32px;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .header-JUTO-g {
  background: var(--bg-main);
  margin: 0;
  padding-left: 0;
  padding-right: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .header-JUTO-g .tabBar-3DfKkN {
  border: none;
  margin: 0;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .permissionsForm-xrzuUy > h5 {
  color: var(--text-primary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-semibold);
  line-height: var(--line-height-md);
  margin-bottom: 12px;
  text-transform: none;
}
#app-mount .layer-86YKbF ~ .layer-86YKbF .permissionsForm-xrzuUy + .permissionsForm-xrzuUy {
  margin-top: 40px;
}

#app-mount #permissions-tab .scroller-3_YDR2 {
  background: transparent;
}
#app-mount #permissions-tab .button-f2h6uQ {
  margin-top: 40px;
}

#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) {
  border: 1px solid var(--border-high);
  border-radius: var(--rounded);
  background: var(--bg-content);
  box-shadow: var(--shadow-dialog);
  transform: none !important;
  animation: fadeInFromBottom 0.15s var(--transition) forwards !important;
  width: 548px;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) [class^=modalCloseButton-],
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) [class^=closeButton-] {
  display: none;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .input-2g-os5:not(.multiInput-1VARjC):not(.multiInputField-1zyopx),
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .input-2g-os5.multiInput-1VARjC {
  background: var(--bg-high);
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .input-2g-os5:not(.multiInput-1VARjC):not(.multiInputField-1zyopx):hover,
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .input-2g-os5.multiInput-1VARjC:hover {
  background: var(--bg-higher);
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .header-1kWa4s,
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .header-1R3myj,
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .header-1zd7se {
  padding: 24px;
  align-items: center;
  height: auto;
  overflow: hidden;
  box-shadow: none;
  background: var(--bg-content);
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .header-1kWa4s .size24-17l95E,
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .header-1R3myj .size24-17l95E,
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .header-1zd7se .size24-17l95E {
  font-weight: var(--font-weight-semibold);
  font-size: var(--font-size-lg);
  margin-bottom: 12px;
  color: var(--text-primary);
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .header-1kWa4s button[type=button].button-f2h6uQ:not(.lookFilled-yCfaCM),
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .header-1R3myj button[type=button].button-f2h6uQ:not(.lookFilled-yCfaCM),
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .header-1zd7se button[type=button].button-f2h6uQ:not(.lookFilled-yCfaCM) {
  display: none;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .content-2hZxGK {
  padding: 0 24px 24px !important;
  display: flex;
  flex-direction: column;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .content-2hZxGK .marginBottom20-315RVT {
  margin-bottom: 0;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .content-2hZxGK .marginBottom20-315RVT + * {
  margin-top: 20px;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .content-2hZxGK div[class][style^="position: absolute;"]:not(.file-input) {
  display: none;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .content-2hZxGK .title-3hptVQ {
  text-transform: none;
  color: var(--text-tertiary);
  font-size: var(--font-size-xs);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height);
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .content-2hZxGK .optionHeader-27AHfD {
  color: var(--text-secondary) !important;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .size16-rrJ6ag {
  color: var(--text-secondary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height-lg);
  margin: 0;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .footer-IubaaS {
  padding: 24px;
  background: var(--bg-main);
  box-shadow: none;
  border-radius: 0 0 var(--rounded) var(--rounded);
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 8px;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .footer-IubaaS button:only-child {
  grid-column: 2/3;
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .footer-IubaaS button[type=button]:not(.lookFilled-yCfaCM) {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .footer-IubaaS button[type=button]:not(.lookFilled-yCfaCM):hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .footer-IubaaS button[type=button]:not(.lookFilled-yCfaCM):active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .root-1CAIjD:not(.modal-3Crloo, .carouselModal-1eUFoq, .root-2uUafN) .buttonsRight-21z8KV {
  gap: 8px;
}

#app-mount .content-2hZxGK .message-G6O-Wv {
  background: transparent;
  box-shadow: none;
}
#app-mount .content-2hZxGK .cozy-VmLDNB {
  padding-left: 54px;
}
#app-mount .content-2hZxGK .cozy-VmLDNB .avatar-2e8lTP {
  left: 0;
}

#app-mount .container-qBnZJg {
  max-height: 500px;
  height: 50vh;
}
#app-mount .quickswitcher-pKcM9U {
  height: 100%;
  padding: 16px 16px 0;
  border-radius: var(--rounded);
  box-shadow: none;
  background: var(--bg-main);
}
#app-mount .scroller-2qwVWY {
  margin: 0 -12px 0 0;
  max-height: none;
  background: transparent;
}
#app-mount .scroller-2qwVWY div[style="height: 15px;"] {
  height: 16px !important;
}
#app-mount .input-3r5zZY {
  background: var(--textbox-bg);
  border: 1px solid var(--textbox-border);
  height: 32px;
  padding: 0;
  border-radius: var(--rounded);
  padding: 8px 10px;
  font-size: var(--font-size-sm);
  box-sizing: border-box;
  border-bottom-color: var(--textbox-underline);
  transition: none;
  box-shadow: none;
}
#app-mount .input-3r5zZY::-moz-placeholder {
  font-size: var(--font-size-sm);
  color: var(--text-muted);
}
#app-mount .input-3r5zZY::placeholder {
  font-size: var(--font-size-sm);
  color: var(--text-muted);
}
#app-mount .input-3r5zZY:hover {
  background: var(--textbox-bg-hover);
}
#app-mount .input-3r5zZY:focus, #app-mount .input-3r5zZY:focus-within {
  background: var(--textbox-bg-active) !important;
  box-shadow: inset 0 -1px 0 rgb(var(--accent));
  border-bottom-color: rgb(var(--accent));
}
#app-mount div:not([class]) > .content-vQY7Mf {
  height: auto;
  line-height: normal;
  padding: 12px 12px 6px;
}
#app-mount .header-1ZpMzy {
  margin: 0;
  color: var(--text-tertiary);
  font-size: var(--font-size-xs);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height);
  text-transform: none;
}
#app-mount .result-u66Ywh {
  border-radius: var(--rounded);
}
#app-mount .result-u66Ywh .content-vQY7Mf {
  position: relative;
  padding: 0 16px;
  cursor: var(--cursor);
}
#app-mount .result-u66Ywh .content-vQY7Mf::before {
  content: "";
  position: absolute;
  top: 50%;
  left: 0;
  transform: translateY(-50%);
  width: var(--pill-width);
  height: 0;
  background: rgb(var(--accent));
  border-radius: 30px;
  opacity: 0;
  transition: var(--pill-transition);
}
#app-mount .result-u66Ywh[aria-selected=true] {
  background: var(--bg-interactive);
}
#app-mount .result-u66Ywh[aria-selected=true] .content-vQY7Mf::before {
  height: var(--pill-height);
  opacity: 1;
}
#app-mount .result-u66Ywh[aria-selected=true]:hover {
  background: var(--bg-interactive-hover);
}

#app-mount .art-2Y6Pk3 {
  display: none;
}
#app-mount .header-VCOMen {
  font-weight: var(--font-weight-semibold);
  font-size: var(--font-size-lg);
  margin-bottom: 12px;
  color: var(--text-primary);
  padding-top: 0;
  align-items: flex-start;
}
#app-mount .emojiButtonContainer-gCE6AT {
  margin: 0;
}
#app-mount .emojiButtonContainer-gCE6AT .sprite-2lxwfc {
  width: 20px;
  height: 20px;
}
#app-mount .emojiButtonContainer-gCE6AT + .inputWrapper-1YNMmM .input-2g-os5 {
  padding-left: 42px;
}

#app-mount .root-g14mjS .content-Lj791F {
  gap: 24px;
}
#app-mount .root-g14mjS .content-Lj791F > div[style*=relative]:not([class]) {
  width: 100% !important;
}
#app-mount .root-g14mjS .content-Lj791F > div[style*=relative]:not([class]) > div {
  width: 100% !important;
}
#app-mount .root-g14mjS .content-Lj791F + .footerSeparator-VzAYwb {
  grid-template-columns: 1fr;
}
#app-mount .root-g14mjS .content-Lj791F + .footerSeparator-VzAYwb .inline-3eaUwP {
  flex-direction: row-reverse;
  width: 100%;
  flex: 1;
  gap: 8px;
}
#app-mount .root-g14mjS .content-Lj791F + .footerSeparator-VzAYwb .inline-3eaUwP button {
  flex: 1;
}

#app-mount .card-14SgW5 {
  width: 100%;
  background: transparent;
  padding: 24px;
}
#app-mount .card-14SgW5 .title-3FQ39e {
  font-weight: var(--font-weight-semibold);
  font-size: var(--font-size-lg);
  margin-bottom: 12px;
  color: var(--text-primary);
  text-align: left;
}
#app-mount .card-14SgW5 .colorHeaderSecondary-g5teka.subtitle-N87Vzb {
  font-weight: var(--font-weight-normal);
  font-size: var(--font-size-sm);
  margin-bottom: 6px;
  color: var(--text-secondary);
  text-align: left;
  padding: 0;
}
#app-mount .accountCard-2lki2x {
  background: var(--bg-high);
  border: 1px solid var(--border);
  border-radius: var(--rounded);
}
#app-mount .navRow-dG-XX8 {
  padding: 16px;
  gap: 8px;
}
#app-mount .navRow-dG-XX8 button {
  flex: 1;
}
#app-mount .navRow-dG-XX8 button.backButton-2rLJZw {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .navRow-dG-XX8 button.backButton-2rLJZw:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .navRow-dG-XX8 button.backButton-2rLJZw:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}

#app-mount .container-2E0bff {
  width: 748px !important;
}
#app-mount .guildSidebar-UHnQqs {
  background: var(--bg-alt);
  border-right: 1px solid var(--border-high);
}
#app-mount .modal-2TOYtq {
  background: transparent;
}
#app-mount .formFieldWrapper-2LV3S6 {
  background: var(--bg-alt);
  border: 1px solid var(--border-high);
  border-radius: var(--rounded);
}

#app-mount .container-1Lk8p7 {
  width: 100%;
}
#app-mount .container-1Lk8p7 > div, #app-mount .container-1Lk8p7 > div > div {
  width: 100% !important;
}
#app-mount .container-1Lk8p7 [class*=subtitle-],
#app-mount .container-1Lk8p7 .title-1_TkpU {
  text-align: left;
}
#app-mount .container-1Lk8p7 .header-1zd7se {
  align-items: flex-start !important;
}
#app-mount .container-1Lk8p7 .heading-xl-medium-_XBxHT {
  font-weight: var(--font-weight-semibold);
  font-size: var(--font-size-lg);
  margin-bottom: 12px;
  color: var(--text-primary);
}
#app-mount .container-1Lk8p7 [class*=subtitle-] {
  font-weight: var(--font-weight-normal);
  font-size: var(--font-size-sm);
  margin-bottom: 6px;
  color: var(--text-secondary);
  margin-top: 0;
  color: var(--text-secondary) !important;
}
#app-mount .container-1Lk8p7 .content-2hZxGK {
  margin-top: 0;
  flex-direction: column !important;
}
#app-mount .container-1Lk8p7 .container-x8Y1ix {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
}
#app-mount .container-1Lk8p7 .container-x8Y1ix:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .container-1Lk8p7 .container-x8Y1ix:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .container-1Lk8p7 .container-x8Y1ix .icon-AynerZ {
  margin: 0 10px 0 0;
}
#app-mount .container-1Lk8p7 .container-x8Y1ix .text-md-normal-304U3g {
  color: var(--text-primary);
  font-weight: var(--font-weight-normal);
  font-size: var(--font-size-sm);
}
#app-mount .container-1Lk8p7 .container-x8Y1ix .arrow-2yY1Tm {
  margin-right: 10px;
  filter: invert(1);
}
#app-mount .container-1Lk8p7 .container-x8Y1ix .text-PdAsFQ {
  color: var(--text-primary);
}
#app-mount .container-1Lk8p7 .skip-2hTIXL {
  color: var(--text-tertiary);
  font-size: var(--font-size-xs);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height);
  color: var(--text-muted) !important;
}
#app-mount .container-1Lk8p7 .footerTitle-3Bslxi {
  color: var(--text-tertiary);
  font-size: var(--font-size-xs);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height);
  margin: 0;
}

@keyframes fadeInFromBottom {
  from {
    opacity: 0;
    transform: translateY(6px);
  }
  to {
    opacity: 1;
    transform: translateY(0px);
  }
}
@keyframes settingsIn {
  from {
    transform: translateY(100px);
    opacity: 0;
  }
  to {
    transform: translateY(0%);
    opacity: 1;
  }
}
.platform-win #app-mount .typeWindows-2-g3UY + div .layer-86YKbF {
  top: 0;
  padding-top: 0;
}
.platform-win #app-mount .typeWindows-2-g3UY + div .layer-86YKbF.baseLayer-W6S8cY {
  padding-top: calc(var(--win-btn-height) + 4px) !important;
}
.platform-win #app-mount .typeWindows-2-g3UY + div .standardSidebarView-E9Pc3j {
  top: 0;
}

.typeWindows-2-g3UY {
  height: var(--win-btn-height);
  z-index: 2;
  background: transparent;
  position: fixed;
  width: calc(100% - 72px - var(--server-size));
  -webkit-user-select: none;
     -moz-user-select: none;
          user-select: none;
  pointer-events: none;
  right: 0;
}

.winButton-3UMjdg {
  height: calc(var(--win-btn-height) + 4px);
  width: var(--win-btn-width);
  cursor: var(--cursor);
}

.wordmarkWindows-2dq6rw {
  display: none;
}

.platform-osx #app-mount .layer-86YKbF .toolsContainer-25FL6V {
  left: 70px;
}

#app-mount .bd-sidebar-header {
  display: none;
}

#app-mount .bd-switch {
  background: transparent !important;
  width: 40px;
  height: 20px;
}
#app-mount .bd-switch svg {
  display: none;
}
#app-mount .bd-switch input {
  display: inline-flex;
  align-items: center;
  opacity: 1;
  -webkit-appearance: none;
     -moz-appearance: none;
          appearance: none;
  border: 1px solid var(--switch-border);
  width: 40px;
  height: 20px;
  border-radius: 20px;
  margin: 0;
  padding: 0 4px;
  cursor: var(--cursor);
  transition: background 0.15s var(--transition), border-color 0.15s var(--transition);
}
#app-mount .bd-switch input::before {
  content: "";
  width: 12px;
  height: 12px;
  border-radius: 7px;
  display: block;
  background: var(--text-secondary);
  transition: background 0.15s var(--transition), transform 0.15s var(--transition), width 0.15s var(--transition), height 0.15s var(--transition);
}
#app-mount .bd-switch input:hover:not(:checked) {
  background: hsla(0, 0%, 100%, 0.05) !important;
}
#app-mount .bd-switch input:hover::before {
  width: 14px;
  height: 14px;
}
#app-mount .bd-switch input:active::before {
  width: 18px;
}
#app-mount .bd-switch input:checked {
  background: rgb(var(--accent));
  border-color: rgb(var(--accent));
}
#app-mount .bd-switch input:checked::before {
  background: var(--accent-text);
  transform: translateX(18px);
}
#app-mount .bd-switch input:checked:hover {
  box-shadow: inset 0 0 0 100vmax hsla(0, 0%, 0%, 0.12);
  border-color: hsla(0, 0%, 0%, 0.12);
}
#app-mount .bd-switch input:checked:active::before {
  transform: translateX(13px);
}
#app-mount .bd-switch-body {
  display: none;
}

#app-mount .bd-addon-card {
  border-radius: var(--rounded);
  border: 1px solid var(--border);
  background: var(--bg-content);
}
#app-mount .bd-addon-header {
  background: transparent;
  padding: 16px 16px 8px;
}
#app-mount .bd-title {
  color: var(--text-secondary);
  font-size: var(--font-size);
  font-weight: var(--font-weight-regular);
  line-height: var(--line-height-lg);
}
#app-mount .bd-description-wrap {
  padding: 0 16px 16px;
}
#app-mount .bd-footer {
  padding: 16px 16px;
  border-top: 1px solid var(--border);
}
#app-mount .bd-footer .bd-controls {
  gap: 8px;
}
#app-mount .bd-footer .bd-button {
  border-radius: var(--btn-radius);
  padding: 4px 10px;
  line-height: 20px;
  font-size: var(--font-size-sm);
  display: inline-flex;
  align-items: center;
  box-sizing: border-box;
  text-decoration: none;
  background: var(--btn-bg);
  font-weight: var(--font-weight-regular);
  color: var(--text-primary);
  box-shadow: none !important;
  border: 1px solid var(--btn-border-x);
  border-top-color: var(--btn-border-t);
  border-bottom-color: var(--btn-border-b);
  cursor: var(--cursor);
  min-width: 50px;
}
#app-mount .bd-footer .bd-button:hover {
  background: var(--btn-bg-hover);
  border-color: var(--btn-border-t) var(--btn-border-x) var(--btn-border-b);
}
#app-mount .bd-footer .bd-button:active {
  background: var(--btn-bg-active) !important;
  border-color: var(--btn-border-active);
}
#app-mount .bd-footer .bd-button svg {
  fill: var(--text-secondary);
}
#app-mount .bd-footer .bd-button.bd-button-danger svg {
  fill: hsl(var(--discord-red));
}

#Fluent-card {
  position: relative;
  z-index: -1;
}
#Fluent-card::before {
  content: "";
  background: url("https://i.imgur.com/HQVfRQy.jpg") center/cover;
  position: absolute;
  inset: 0;
  z-index: 0;
  opacity: 0.1;
  pointer-events: none;
}
#Fluent-card > div {
  position: relative;
  z-index: 1;
}
