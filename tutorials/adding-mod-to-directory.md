# Adding Mod to Directory

Before adding a mod to the directory, ensure you understand [how to contribute](../meta/contributing.md).

1. In your fork of the repo, navigate to **mod-directory/mod-template.md** and create a copy.
2. Rename the file to your mods name ensuring that it matches the naming convention of the other mods. An example of this is (yourname-mod-name-v1.md)
3. Fill out the template following the instructions found inside the file.
4. Head to **mod-directory/README.md** and open it.
5. Once again following the conventions inside the file, copy the following template and paste it at the end of the **mod-directory/README.md** file.

```md
### Mod Name

Short description of your mod\
For more information, see [yourname-mod-name-v1.md](yourname-mod-name-v1.md "mention")
```

6. Edit the contents of this template to match your mod **MAKING SURE** that the .md file mentioned in line 4 is the exact same name as the file you created in step 2.
7. Navigate to the root of the repo and find **SUMMARY.md**
8. Copy and paste the following line near the end of the file under the **Mod Directory** section.

```md
  * [Mod Name](mod-directory/yourname-mod-name-v1.md)
```
_Please copy and paste this exactly, including the whitespace_

9. Edit the contents of the template to match your mod.
10. Once again following the [contribution guide](../meta/contributing.md), create a pull request and wait for it to be accepted.