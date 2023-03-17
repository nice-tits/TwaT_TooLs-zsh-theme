# thy-god-zsh-theme
Personal Oh-My-ZSH theme, features include changing the prompt to a red cross upon invalid command and the usual git-status plugin implementation.<br>
<br>Code was based off **gnzh**/**bira**'s code, while being inspired by **spaceship prompt**'s looks and features.<br>
<br>To install the theme, simply use the command:<br>
```git clone https://github.com/Thy-GoD/thy-god-zsh-theme.git "$ZSH_CUSTOM/themes/Thy-GoD" && cp "$ZSH_CUSTOM/themes/Thy-GoD/ThyGoD.zsh-theme" "$ZSH_CUSTOM/themes/"```
<br><br>Lastly, you'll have to enable the theme in ~/.zshrc as `ThyGoD`, and enable `git-status` as a plugin.

## Screenshots
Note: Screenshots were taken with Kali Dark on Konsole.

This is the base version of the prompt, with the error code (if any) displayed on the right-side.
![Base Prompt](/screenshots/prompt-ss-4.png)
Root ver of the prompt.
![Root_Prompt](/screenshots/prompt-ss-1.png)
Root ver of the prompt with Error Code.
![Root_Prompt_All](/screenshots/prompt-ss-2.png)
Prompt with Git-Status implementation.
<br>(For the most part, left as default, though I have added all default values in the file to allow for customization.)
![Root_Prompt_Git_Status](/screenshots/prompt-ss-3.png)
<br>
<br>Yes, I will continue update and fix this prompt as time goes by.
