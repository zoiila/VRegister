# Installation

VRegister **2.2.0** targets **Folia 1.21.11** and is compiled for **Java 21**.

## Dependencies

| Plugin | Requirement |
| --- | --- |
| FastLoginPlusFolia | **VRegister-specific** `0.7.0-vregister.1-2c5808e` build; plugin ID: `FastLoginPlus` |
| ProtocolLib | Required by FastLoginPlusFolia; version `5.4.0` used in staging |
| Floodgate + Geyser | Optional Bedrock integration |
| ViaVersion | Optional older Java-client support |

The stock FastLoginPlusFolia 0.7.0 JAR lacks the required configuration-phase integration. **Do not substitute the stock JAR.**

## Server installation

1. Set up a clean **Folia 1.21.11** staging server and accept the Minecraft EULA.
2. Obtain VRegister and the matching bridge from an authorized VACK STUDIO source.
3. Place ProtocolLib, the matching FastLoginPlusFolia bridge and `VRegister-2.2.0.jar` in `plugins/`.
4. Start the server. Successful bridge initialization should log: `FastLoginPlus bridge ready; pre-world configuration authentication enabled.`
5. Adjust `plugins/VRegister/config.yml` and test registration and login with test accounts.
6. Test Premium connections and optional Floodgate Bedrock integration separately.

**Before an upgrade**, stop the server and back up `plugins/VRegister/data.db`. Keep only one VRegister JAR and one matching bridge JAR. Avoid the server-wide `/reload`.

## Validation

The 2.2.0 build and unit tests passed in the reported test package. Real Java screenshots show the Register Dialog, Login Dialog and automatic-login message. Complete Premium, legacy and Bedrock authentication coverage remains unverified.

The executable plugin and companion bridge are not distributed in this public repository.
