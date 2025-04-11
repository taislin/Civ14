# Contributing to the Wiki

This wiki is hosted and deployed on GitHub from the main [Civ14 repository](https://github.com/Civ13/Civ14). To contribute, you will need to do it through there. Check below for guidance according to your skill level:

## I am barely sentient

1. Access the Civ14 repository [here](https://github.com/Civ13/Civ14). Create a GitHub account if you haven't already. Then, press the Fork button on the top right. this will create a copy of the game files on your account.
2. Go to your repositories, open `Civ14`, and open the `Wiki` folder. You will see a bunch of .md files. Edit them through GitHub. Use [markdown](https://www.markdownguide.org/).
3. When done, create a pull request on your repository to the Civ14 repository. You will figure this out.

```admonish note
If this still sounds too complicated, you are probably not qualified enough to write a wiki article anyway.
```

## I understand GitHub

1. Fork the Civ14 repository. Go on GitHub desktop and clone your fork into your computer.
2. Open the `Wiki/` folder and edit the markdown files. Create new ones if needed. Do not forget to add them to the SUMMARY.md file under the right section!
3. You can run the included `mdbook.exe` in the command line to preview the changes locally. Run it as `./mdbook.exe build`, then open `book/index.html` to view. You can run `./mdbook.exe watch` to enable it to automatically update while you make changes.
4. Commit and pull request to the main repository.

## Best Practices

-   You can add your screenshots to the `images` folder and reference them on the md files. You can also directly use sprites from the game by using GitHub links like `https://raw.githubusercontent.com/Civ13/Civ14/refs/heads/master/Resources/Textures/<someimage.png>`.

-   Avoid using HTML where possible.
