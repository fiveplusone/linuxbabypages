# linux baby pages

linux baby pages (<code>lbp</code>) is an attempt to make concise "common uses" man pages.

It shares this goal with at least two other projects: [<code>tldr</code>](https://github.com/rprieto/tldr) and [<code>bro</code>](http://bropages.org). <code>lbp</code> is distinguished from these projects by its rules.

# Rules

## Code

1. The <code>lbp</code> command shall be a shell script.
2. The code shall be as simple as possible.
3. The code shall have as few dependencies as possible.
4. Installation shall be as simple as possible.

## Text

1. Entries shall be no more than 2000 characters.
2. The corpus shall total no more than 100,000 characters.
3. Spaces count, but not line breaks.
4. Entries shall hard wrap at 72 characters.

# Install

1. In the directory of your choice (e.g., <code>/usr/local/lbp</code>):
        ```
        $ curl http://linuxbabypages.info/install | bash
        ```
2. If you did not install to a directory already in your PATH, either:
    * add the install directory to your PATH, or
    * make an alias in your <code>.bashrc</code>, <code>.bash_profile</code> or similar file, e.g.:
        ```
        alias lbp='/path/to/install/dir/lbp'
        ```

# Web

A copy of the corpus is kept at [linuxbabypages.info](http://linuxbabypages.info).

# Contribute

<code>lbp</code> code and text is managed by two co-autocrats.

To suggest a change, make a pull request to the [appropriate repository](https://github.com/fiveplusone/linuxbabypages).

# Legal

The script (such as it is) is released under the [GNU General Public License, version 3](http://www.gnu.org/licenses/gpl-3.0.html).

The corpus is released under the [GNU Free Documentation License, version 1.3](http://www.gnu.org/copyleft/fdl.html).

The site code is released under the [GNU Affero General Public License, version 3](http://www.gnu.org/licenses/agpl-3.0.txt).

# Maintainers

<code>lbp</code> is maintained by [Ankita Raturi](http://sudokita.com) and [Six Silberman](http://wtf.tw).
