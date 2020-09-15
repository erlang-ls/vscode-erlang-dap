# vscode-erlang-dap
VS Code extension for Erlang Debugger

Experiment with a daptoy launch config (in `.vscode/launch.json`) of


```json
{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "type": "erlang",
            "request": "launch",
            "name": "Run baby run",
            "cwd": "${workspaceRoot}",
            "stopOnEntry": true,
            "module": "daptoy_fact",
            "function": "fact",
            "args": "[5]"

        }
    ]
}
```