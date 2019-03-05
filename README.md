### What is this?
O2system OS is an icon pack &mdash; designed to integrate with most
desktop environments. The set of icons takes inspiration from the latest
iterations of macOS and Google's Material Design through the use of
visually pleasing gradients, shadowing, and simple icon geometry.

Every image in this theme is a _scalable vector graphic_ so it will look
great at any size, on any screen. In my spare time, I work on adding new
icons, updating old ones, and making this theme more complete. Since
this theme is updated often, you should clone this git repository and
pull regularly to make sure you're always up-to-date:

```
cd ~/.icons
git clone https://github.com/o2system/o2system-icon-theme.git
```

### Configuration
O2System OS comes with a configuration script which attempts to
determine your distribution and desktop environment. Using this
information, O2System OS updates several system icons and icons used
for mime-types.

For best integration with your distro/desktop environment, please run
`./configure` and follow the prompts.

#### Use a dark GTK+ theme?
O2System OS doesn't ship with two distinct variants, because I wanted
to keep the size of this project to a minimum.

You'll need to run the configuration script to tell O2System OS to
update its directory structure to use the dark variant.

### Troubleshooting
If something does not work as expected with O2System OS, take a look at
[`SUPPORT`](.github/SUPPORT.md). There you'll find the most common
traps, their solutions and known issues. Please read this doc before
submitting an issue.

### License
O2System OS is fully free software that is dual-licensed under the MIT
and GPLv3 licenses.

Much of the artwork in O2System OS is based on Numix Circle and El
General GNOME (now known as Antu), with significant additions and
changes. This art is to be treated as a GPLv3 licensed library.

The included configuration script is licensed under the permissive MIT
license.

See the `LICENSE` and `COPYING` files for more details.