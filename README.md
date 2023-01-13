# Settings for Windows Terminal
This is so that I can manage all my settings for windows terminal and profile settings from same repository.

## Usage
### Windows Terminal
- Install the Windows Terminal from the Microsoft Store or using winget
`winget install --id Microsoft.WindowsTerminal -e`

- Delete the LocalState folder

- Create a symlink to LocalState from windows-terminal folder

### Starship Prompt
- Install startship prompt
`winget install --id Starship.Starship`

- Create a symlink to ~/.config/startship.toml from startship-promp/startship.toml

### Windows Powershell
- Create symlink to WindowsPowerShell folder from windows-powershell