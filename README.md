# WinUIEdit WinUI3 Demo

## IMPORTANT!

- This project uses Git submodules. This project isn't for beginners, if you can't figure out how to use submodules, then you can't figure out how to use this project.

- Due to an upstream issue (BreeceW/WinUIEdit#2), you'll need to manually modify one of the submodules once you clone the repo. Open [`Deps/WinUIEdit/MicaEditor/MicaEditor.vcxproj`](./Deps/WinUIEdit/MicaEditor/MicaEditor.vcxproj) in a text editor, and do a find and replace, replacing `..\packages` with `$(SolutionDir)packages`.
  - You also need to change `MicaEditorUseWinUI3` to true, but that's not an issue, it's intended behaviour.
    - All of these changes is because I don't want to fork the project. Deal with it.
