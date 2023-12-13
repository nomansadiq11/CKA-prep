

- secrets are uses to storee password information sensitive inforatmion
- create secrete and inject to deployment
- secrets are store encoded format as base64
- do not checkin secrets files in github
- secrets are not encrypted at ectd,
- we can enable the secrete encrytion to use kind:encryptionconfiguration
- anyone creating the secrets on same namespace they can see the secrets which other applciations uses
- we can use external secrets providers
