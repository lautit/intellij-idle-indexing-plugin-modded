# Modded Intellij Idle Indexing Plugin
Based on Andrev's Idle Indexing but modded to support newer IDE versions.

## Instructions

1. [Download the latest plugin build available at JetBrains Plugin Marketplace](https://plugins.jetbrains.com/plugin/download?rel=true&updateId=116910)
2. Extract the `inin.zip` contents
3. Find the `inin.jar` package under `lib` folder and extract it's content
4. Locate the `plugin.xml` file under `META-INF` folder and edit it
5. Update the `<idea-version>` property `until-build` to desired build number:

```
...
  <idea-version since-build="202.0" until-build="222.*"/> // update until-build to desired build number
...
```

6. Repack the `com` and `META-INF` folders back to `inin.jar` (you can safely use a `.zip` archive and rename it)
7. Repack the whole content back to a `.zip` file
8. In your preferred JB IDE Plugin menu, click on the 3 dots and select "Install plugin from Disk...":

![image](https://user-images.githubusercontent.com/14226299/181104805-d0bd4b10-d5a5-4670-b139-2c75345859a2.png)

9. Success! Enjoy a great working tool, once again :)
