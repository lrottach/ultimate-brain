- **Tags:** #development #keyboard-shortcuts #vscode
- #### Switch focus between Terminal and Editor
	- ```json
	      {
	          "key": "cmd+j",
	          "command": "workbench.action.terminal.focus"
	      },
	      {
	          "key": "cmd+j",
	          "command": "workbench.action.focusActiveEditorGroup",
	          "when": "terminalFocus"
	      }
	  ```
- #### Toggle integrated Terminal visibility
	- ```json
	      {
	          "key": "shift+cmd+j",
	          "command": "workbench.action.terminal.toggleTerminal"
	      }
	  ```
- #### Toggle Activity Bar visibility
	- ```json
	      {
	          "key": "cmd+k cmd+a",
	          "command": "workbench.action.toggleActivityBarVisibility",
	          "when": "editorTextFocus"
	      }
	  ```
- #### Toggle Status Bar visibility
	- ```json
	      {
	          "key": "cmd+k cmd+s",
	          "command": "workbench.action.toggleStatusbarVisibility",
	          "when": "editorTextFocus"
	      }
	  ```
-