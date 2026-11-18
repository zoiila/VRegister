# Configuration

The shipped [VRegister 2.2.0 config.yml](../src/main/resources/config.yml) contains `settings` and `messages` sections. The runtime configuration is written to `plugins/VRegister/config.yml`.

## Authentication settings

| Key under `settings` | Default | Description |
| --- | --- | --- |
| `minimum-password-length` | `6` | Minimum registration password length |
| `failed-login-cooldown-seconds` | `3` | Failed-login cooldown |
| `maximum-failed-login-attempts` | `5` | Maximum failed attempts |
| `kick-after-maximum-failed-attempts` | `true` | Disconnect on the failed-attempt limit |
| `dialog-reopen-delay-seconds` | `2` | Dialog reopen delay |
| `minimum-dialog-client-version` | `"1.21.6"` | Minimum configured Dialog client version |
| `pre-world-authentication-timeout-seconds` | `120` | Connection authentication timeout |
| `maximum-concurrent-pre-world-authentications` | `100` | Pre-world connection authentication capacity |
| `block-chat-before-authentication` | `true` | Restrict unauthenticated chat |
| `block-movement-before-authentication` | `true` | Restrict unauthenticated movement |
| `send-chat-authentication-messages` | `false` | Chat-message setting |

## Messages

The `messages` section provides Register and Login Dialog labels, password feedback, disconnect text and legacy-client command responses. See the linked configuration for every message key and its shipped value.

To edit a running installation, back up `plugins/VRegister/config.yml`, preserve YAML formatting, and use `/vregister reload` for supported settings and messages. Dependency changes require a full server restart, not a server-wide `/reload`.

Account data is stored separately in `plugins/VRegister/data.db`. Keep it private.
