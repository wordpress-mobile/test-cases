
# Social Icons - Test Cases

--------------------------------------------------------------------------------

##### TC001

### Active icon gets product color

-   Add `Social Icons` block
-   Press an inactive icon e.g. Facebook icon
-   Press `link` icon in mobile toolbar above the keyboard or tap the social icon
-   Fill `Label` field and add link into `URL` field e.g. facebook.com
-   Close the bottom sheet
-   Expect Facebook social icons to be active (has product color)
-   Expect icon color to be animated when closing bottom sheet

<img src="../resources/social-icons-animate-color.gif" width=300 />

--------------------------------------------------------------------------------

##### TC002

### Social icon forwarding to the link

-   Add `Social Icons` block
-   Press an inserter or inline appender
-   Add new icon e.g. Amazon
-   Add link into `URL` field e.g. amazon.com
-   Close the bottom sheet
-   Open post preview
-   Press Amazon icon
-   Expect to be forwarded to the added link