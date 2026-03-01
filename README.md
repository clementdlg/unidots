# Unidots
dotfiles for various environements :
- cosmic desktop
- hyprland
- macos

# usage 
I use stow. It takes care of provisionning the ~/.config directory with appropriate dotfiles depending on the environement.
```bash
stow -t ~/.config common # add the common dotfiles
stow -t ~/.config hyprland # add the hyprland dotfiles
```
