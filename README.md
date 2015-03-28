# The Shmowzow Esoteric Language

![Shmowzow](https://raw.githubusercontent.com/shmowzow/shmowzow-lang/master/shmowzow.gif)

Shmowzow's syntax highlighting support for [Atom](https://atom.io/). 

## Using

### Install using APM

From the command line, just do:

`apm install language-shmowzow`

### Install directly from Atom

1. While inside Atom, go `File -> Settings`
2. On the Settings tab go to `Install` and search for `language-shmowzow`
3. Then just hit `Install`
4. Have fun!

### Install using Git

You can install the syntax highlighting and keep up to date by cloning the repo directly into your `packages` subdirectory
in your `atom` directory. Just go through:

```sh
$ cd ~/.atom/packages
$ git clone git://github.com/shmowzow/atom-support
```

### Download Manually

1. Download the files using the [GitHub .zip download](https://github.com/shmowzow/atom-support/archive/master.zip) option
2. Unzip the files
3. Go to `~/.atom/packages`
4. Copy the folder into your Atom `packages` directory
5. On the Settings tab go to `Install` and search for `language-shmowzow`
6. Then just hit `Install`
7. Have fun!

## Commands/Scopes

Command     		      | Scope																																														
---						  | ---  																																															
`Shmowzow` / `shmowzoW`   | `keyword.control`  																														   
`SHMOWZOW` / `shmowzow`   | `constant.numeric`																															
`ShMoWzOw` / `sHmOwZoW`	  | `storage.type`																																			 
`ShmoWzow` / `sHMOwZOW`   | `entity.name.function`																																		
`c:` 					  | `comment`																																							

> *Remember*: The `c:` command is not actually used for comments if you intend to build your `.finn` program - since as
said before Shmowzow doesn't support commenting yet -, it just makes the things *more beautiful*.  