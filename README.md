[Original README](https://github.com/CleverPumpkin/Generamba/blob/develop/ORIGINAL-README.md)

### Installation

> Ruby 2.2 or later version is required. To check your current Ruby version run this command in terminal:
```bash
$ ruby --version
```

Since current version from Gems is not compatible with Xcode 9/10 - install fixed version from this repo:

* `sudo gem uninstall generamba`
* `sudo gem install specific_install`
* `sudo gem specific_install git@github.com:CleverPumpkin/Generamba.git`


### Usage
1. \***Only if starting from scratch and there is no `Rambafile` file in a project directory.**
	
	Run `generamba setup` in the project root folder. This command helps to create [Rambafile](https://github.com/rambler-digital-solutions/Generamba/wiki/Rambafile-Structure) that define all configuration needed to generate code. You can modify this file directly in future.
2. \***Only if starting from scratch and there is no `Rambafile` file in a project directory.**

	Add all templates planned to use in the project to the generated [Rambafile](https://github.com/rambler-digital-solutions/Generamba/wiki/Rambafile-Structure). You can begin with one of the templates from our catalog: `{name: 'rviper_controller'}`.
3. Run `generamba template install`. All the templates will be placed in the '/Templates' folder of your current project.
4. Run `generamba gen [MODULE_NAME] [TEMPLATE_NAME]` - It creates module with specific name from specific template.

### Additional info

Run `generamba help` to learn more about each of the Generamba features.

**Wiki:**
- [Command list](https://github.com/rambler-digital-solutions/Generamba/wiki/Available-Commands)
- [Understanding the Rambafile](https://github.com/rambler-digital-solutions/Generamba/wiki/Rambafile-Structure)
- [Understanding templates](https://github.com/rambler-digital-solutions/Generamba/wiki/Template-Structure)

**Other materials:**
- [Russian] Rambler.iOS V: Generamba and Code Generation ([Slides](http://www.slideshare.net/Rambler-iOS/viper-56423582) | [Video](http://www.youtube.com/watch?v=NXNiN9FaUnY))
- [Introduction to Generamba](http://etolstoy.com/2016/02/10/generamba/)

### Authors

- Egor Tolstoy, Beniamin Sarkisyan, Andrey Zarembo and the rest of [Rambler.iOS team](https://github.com/orgs/rambler-digital-solutions/teams/ios-team).

### License

MIT
