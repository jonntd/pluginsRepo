GPU implementation of delta mush for Maya 2016, 2016.5, 2017.

The file jsDelta.cl MUST be in the same folder alongside the compiled plugin for GPU override to work.

Loading plugin adds command "jsDeltaCmd()" to maya.cmds. Select target mesh and run command from the script editor. You can also create a bare node with deformer(type="jsDelta").
