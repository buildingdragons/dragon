_Most of the content of this page will be eventually moved to a GitHub Pages
website. Hopefully._

# About Building Dragons
In May 2019, I decided to create a JavaFX application written entirely
in Scala. Being new to Scala and not very proficient in JavaFX, I knew
I quickly would become quite a pain in the backside of those who know way
better than me and are willing to offer help and guidance. 

To give something back to the community, I decided to make my work open so
everyone interested can follow my endeavor.

If there is anything you want to know and not addressed here, feel free to
open an issue, and I do my best to come back to you as soon as possible.

## Tools and Libs
Before starting on the Dragon, I had to decide which tools I will work with
and what libraries I will use.

Usually, I would go all-in on bleeding edge software, but in this case, I
decided to make more conservative decisions.

### The IDE
* IntelliJ IDEA Ultimate (kept up-to-date)
* IntelliJ IDEA for Scala plugin (kept up-to-date)

Being Java developer for more than one and a half decade, I gave most of the
widely known IDEs offering Java support a try. If leaving BlueJ aside, where
I did my very first steps with Java, my Java journey began with Eclipse. After
a short detour to NetBeans, I came back to Eclipse and got more and more
annoyed by it. Eventually, I tried IntelliJ and never stopped using it.

### Development Kits
* Java 8/OpenJDK 8u212 (ZuluFX 8 by Azul Systems)
* Scala 2.12.8

Choosing what JDK to use was more painful than I would have expected and
certainly more painful than it should be.

But even Java 8 gave me a hard time: Since Oracle changed their JDK licensing
I wanted to use OpenJDK, but most OpenJDK builds do not include JavaFX. On
*Stack Overflow* I was pointed to *ZuluFX* 8, an OpenJDK build by
*Azul Systems* which contains JavaFX 8 and so my day, and most likely the
whole project was saved.