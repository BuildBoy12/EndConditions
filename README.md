# EndConditions
- Grants the ability to set custom round end conditions using [EXILED](https://github.com/galaxy119/EXILED/).
- Requires the included Newtonsoft.Json.dll as a dependency.

## EXILED Configs:
| Config Option | Value Type | Default Value | Description |
|:------------------------:|:----------:|:-------------:|:------------------------------------------:|
| `is_enabled` | bool | true | Enables/Disables the plugin. |
| `uses_global_config` | bool | true | Determines if the server reads from the central config file, otherwise it makes a new one. |
| `allow_debug` | bool | false | Enables/Disables printing of various debug messages. |
| `allow_default_end_conditions` | bool | false | Enables/Disables the use of base game round end conditions. |
| `end_on_detonation` | bool | false | Enables/Disables the round ending when the warhead detonates.. |
| `detonation_winner` | LeadingTeam | FacilityForces | Determines who will win when the warhead detonates using LeadingTeam names. |
| `ignore_tutorials` | bool | true | Determines if tutorials are calculated as a player. |
| `round_end_ff` | bool | false | Determines if FriendlyFire should be enabled when the round ends. |

- The configs file for EndConditions, used for win conditions and not the above configs, is located at __/EXILED/Configs/EndConditions/config.yml__ by default.

## Leading team names:
- FacilityForces
- ChaosInsurgency
- Anomalies
- Draw

## Class names
- Scp173
- Scp106
- Scp049
- Scp079
- Scp096
- Scp0492
- Scp93953
- Scp93989
- NtfScientist
- ChaosInsurgency
- NtfLieutenant
- NtfCommander
- NtfCadet
- FacilityGuard
- Scientist
- ClassD
- Tutorial