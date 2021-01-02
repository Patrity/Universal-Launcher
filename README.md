![Image](https://i.imgur.com/ppbXR3M.png)
# Universal Launcher
This launcher is meant to provide a simple and non-intrusive means of serving jars to clients that are frequently updated so that the client does not need to repeatedly download new files. The configuration is simple and located in `Config.java` for ease of use.

# Configuration
Configuring Universal Launcher is simple. Just open the configuration file and modify the necessary fields.
![Image](https://i.imgur.com/C0cN3B9.png)

# Distribution
A Gradle task has been created to jar the necessary files for distribution.
The `fatJar` task will create a jar for you to distribute with all necessary dependencies.

![Image](https://i.imgur.com/qvP37Wh.png)

# Credits
[ReverendDread](https://github.com/ReverendDread) is the original creator of this launcher, it was created for our previous project.
It was bundled and simplified by myself and is covered under the GNU GPL V3 License