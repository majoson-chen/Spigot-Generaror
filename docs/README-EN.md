# Spigot-Generaror

**[简体中文](../README.md)|English**

**If this project helped you, please click a star⭐⭐⭐~~**

**This document is translated using Google**

This project uses the `Actions` function of `Github` to automatically build the core of `Spigot`.
Save yourself the trouble of `Build`, and solve the problem of build failure caused by unsmooth network.

## Automatic build time:
"18:30" on the "1st" and "16th" of each month

## download link:
This project [Release](https://github.com/Youkii-Chen/Spigot-Generaror/releases) page

## Help update this item
Since the version of `Minecraft` is iterated very quickly, if you find that the latest version of the core is not in the `release`. You can assist in updating this project by following the steps below:
1. Go to [Spigot Document](https://www.spigotmc.org/wiki/buildtools/) to check whether a new version has been launched
   ![](../docs/versions.png)
   As shown in the figure above, if the corresponding latest version is not found in `release`, go to the second step.
2. <del>star this project (</del>
`fork` this project
3. Modify `.github/workflows/Build.yml`  
Find `jobs`> `build_on_java16`> `strategy`  
Just add the latest version option in `ver`  
![](../docs/ver.png)  
Then, go to the top of the file and modify `env.latest`
4. Submit a `pull request` and wait for my approval.