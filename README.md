# Money Manager Ex packaged for subuser

Why - there is no ability to launch latest MMEX on Linux except building it from source.
In addition, there is no sign that this situation will change in future.

One important thing - this image is packed without network enabled. I care about my privacy and
do not want to share any piece of information with Google. Side effect of that is
that you won't be able to update currencies rate.

## Prerequisites:
* [Subuser](http://subuser.org/installation.html)

## Usage:

1. Install

    ```bash
    $ subuser subuser add mmex mmex@https://github.com/akovalyov/subuser-mmex.git
    ```

2. Run

    ```bash
    $ subuser run mmex
    ```

3. Enjoy!

## Known issues

* Locales support is buggy
