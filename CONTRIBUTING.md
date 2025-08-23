# Contributing

## Tools

We use the following tools for development:

- [OpenJDK](https://openjdk.org/install/)
- [Gradle](https://gradle.org/install/)
- [Git](https://git-scm.com/downloads)
- [Vscode](https://code.visualstudio.com/download) (recommended)
  - [Language Support for Java(TM) by Red Hat for Vscode](https://marketplace.visualstudio.com/items?itemName=redhat.java)
  - [IntelliCode for Vscode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
  - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) (recommended)
  - [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) (recommended)

## Installation Guide

### Requirements

To build and run this plugin, you will need:

- Git
- JDK (Java Development Kit) 21.0.4 or higher
- Gradle 8.10.1 or higher

### Build from Source

1. **Clone the Repository**  
   Clone the project repository from GitHub:
   ```bash
   git clone https://github.com/beduality/metachickens
   cd metachickens
   ```

2. **Build the Plugin**  
   Run the following command to build the plugin:
   ```bash
   gradle build
   ```

3. **Locate the Built Plugin**  
   The compiled plugin will be located at `build/libs/metachickens-*.jar`.

4. **Add to Your Server**  
   Move the `metachickens-*.jar` file into the `plugins` folder of your Minecraft server.

5. **Start the Server**  
   Restart your server if it's already running. The plugin will automatically enable itself.

6. **Verify Installation**  
   Check your server logs for the message:  
   ```
   [Metachickens] Metachickens Plugin Enabled
   ```

## Useful Commands for Testing

```
/summon minecraft:chicken ~ ~ ~ {Age:-6000}

/data merge entity @e[type=chicken,limit=1,sort=nearest] {Age:0}

/execute as @e[type=chicken,distance=..10] run data merge entity @s {EggLayTime:1}
```

## Committing

- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
  - [Angular Commit Convention](https://github.com/angular/angular/blob/main/CONTRIBUTING.md#commit)

## Releasing

- [Semver](https://semver.org/)
- [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)
