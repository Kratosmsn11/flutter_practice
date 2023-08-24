## To install flutter:

### For macOS (Silicon & higher)

Reference Link - https://docs.flutter.dev/get-started/install/macos

- Install Rosetta translation enviroment

```sudo softwareupdate --install-rosetta --agree-to-license```

- Download the Flutter SDK from the reference link provided.

- Place the unzip file preferably in the the desktop.

- Now, in the terminal type the following command

`nano .zprofile`

& type the following comand to the path

`export PATH="$PATH:[set this to where your flutter bin folder is located]"`

once done press 'ctrl + o' & enter to save the path, and press 'ctrl + x' to exit.

Now you have your path setup

- To check the zprofile type the following command

`cat .zprofile`

- Once you see that all of you changes are correctly saved, type the following command to referesh the enviroment with the recent changes made

`source .zprofile`

- Once done run the following command to check if there is need to intall or upgrade any packages, framework, etc.

`flutter doctor`
