# pulumi-scripts

## Project & Stack Management Commands:
| Command                      | Description                                  |
| ---------------------------- | -------------------------------------------- |
| `pulumi new`                 | Create a new Pulumi project.                 |
| `pulumi stack`               | Manage stacks (create, select, rename, etc). |
| `pulumi stack init <name>`   | Create a new stack.                          |
| `pulumi stack select <name>` | Switch to an existing stack.                 |
| `pulumi stack ls`            | List all stacks.                             |

## Infrastructure Deployment Commands:
| Command          | Description                                                   |
| ---------------- | ------------------------------------------------------------- |
| `pulumi up`      | Deploy infrastructure (shows preview, then prompts to apply). |
| `pulumi preview` | Show a preview of changes without applying them.              |
| `pulumi destroy` | Tear down all resources in the current stack.                 |
| `pulumi refresh` | Refresh stack state with actual cloud provider state.         |

## State & Secrets Commands
| Command                           | Description                                 |
| --------------------------------- | ------------------------------------------- |
| `pulumi config`                   | Manage config settings and secrets.         |
| `pulumi config set <key> <value>` | Set a config value.                         |
| `pulumi config get <key>`         | Retrieve a config value.                    |
| `pulumi config rm <key>`          | Remove a config value.                      |
| `pulumi state`                    | Low-level access to stack state (advanced). |
| `pulumi stack export`             | Export the stack state to a file.           |
| `pulumi stack import`             | Import stack state from a file.             |

## Authentication & Accounts Commands
| Command         | Description                                          |
| --------------- | ---------------------------------------------------- |
| `pulumi login`  | Log in to the Pulumi service or self-hosted backend. |
| `pulumi logout` | Log out of the current session.                      |
| `pulumi whoami` | Show the currently logged-in user.                   |


## Utilities & Info Commands
| Command          | Description                                    |
| ---------------- | ---------------------------------------------- |
| `pulumi version` | Show the current Pulumi CLI version.           |
| `pulumi about`   | Show information about the Pulumi environment. |
| `pulumi plugin`  | Manage language/runtime plugins.               |
| `pulumi cancel`  | Cancel a currently running update.             |

