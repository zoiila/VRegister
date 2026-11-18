# Commands and permissions

These commands are registered in the [VRegister 2.2.0 plugin.yml](../src/main/resources/plugin.yml).

## Administrator commands

| Command | Permission | Function |
| --- | --- | --- |
| `/vregister reload` | `vregister.admin` | Reload VRegister configuration and messages |
| `/vregister reset <player>` | `vregister.admin` | Delete the specified account registration |

`vregister.admin` defaults to operators. **A reset deletes the account registration.** Confirm account ownership through a trusted staff channel before using it.

## Legacy Java-client commands

| Command | Function |
| --- | --- |
| `/register <password> <confirm-password>` | Register an offline-mode account |
| `/reg <password> <confirm-password>` | Alias for registration |
| `/login <password>` | Log in to an existing offline-mode account |

Supported clients from Minecraft **1.21.6** onward use the native Dialog experience instead. Older clients may use these commands when compatible ViaVersion support is installed.

Never post registration passwords, command history or account data in support tickets.
