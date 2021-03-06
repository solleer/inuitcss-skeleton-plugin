# inuitcss-skeleton-plugin
A plugin to give default skeleton styling to inuitcss

## Differences between this and Skeleton
* It does not include the skeleton grid system in order to favor the inuit grid system because this is a plugin for inuitcss
* This uses the default example button component for inuit but rewritten to allow setting your own values for the colors. To make a button look like a skeleton button use the modifier `.c-btn--skel`.
    * To get the same formatting as the button class in skeleton use `class="c-btn c-btn--skel c-btn--secondary c-btn--ghost"`
    It seems like a lot of classes for a commonly used style so please create an issue if you would like to see this
    changed because if there is enough support then I will change it

## Use
Just import the `_inuit-skeleton.scss` file in your `main.scss` file after the elements section. Because of the way the plugin does responsive headers, there is no need for importing inuit's header file because inuit-skeleton does the exact same thing but has to do it on its own for it to be responsive.
