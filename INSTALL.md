### [ranger](https://github.com/ranger/ranger)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/ranger.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/ranger/archive/master.zip) option and unzip them.

#### Activating theme

1. Install the Dracula color theme for your terminal application ([Kitty](https://draculatheme.com/kitty), [Wezterm](https://draculatheme.com/wezterm), [Alacritty](https://draculatheme.com/alacritty), etc.)

2. Find your ranger colorschemes directory. Usually, it is located in
`~/.config/ranger/colorschemes`.

    * If you don't have a `~/.config/ranger` directory:
    1. Run `ranger --copy-config=(rc)`
    2. Go to `~/.config/ranger` and create a directory called `colorschemes`

3. Go back to the cloned or downloaded directory

4. Copy or link `dracula.py` to your `~/.config/ranger/colorschemes` directory

    * Copy: `cp dracula.py ~/.config/ranger/colorschemes/dracula.py`
    * Link: `ln -s dracula.py ~/.config/ranger/colorschemes/dracula.py`

5. Go to your `rc.conf` file located in `~/.config/ranger/rc.conf`

6. Change the line `set colorscheme ...` to `set colorscheme dracula`
