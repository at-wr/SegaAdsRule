# SegaAdsRule
This repository contains lists of SEGA Mobile Games' Ads domain.

# Contribute to this project
If you know how to fetch ads domains from Sega mobile games, please feel free to [create issues](https://github.com/AlanYe-Dev/SegaAdsRule/issues) or [pull requests](https://github.com/AlanYe-Dev/SegaAdsRule/pulls)! Such actions can help building this project and provide a better experience for Sega mobile gamers who use this project. 😉

# To-do List
## Automation
- [ ] Distribute rules via automated actions
## Platforms
### Apple
- [x] [Shadowrocket](https://apps.apple.com/ca/app/shadowrocket/id932747118) (iOS/iPadOS)
- [x] [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) (macOS/iOS/iPadOS/tvOS)
- [ ] [Surge](https://apps.apple.com/us/app/surge-5/id1442620678) (iOS/iPadOS/tvOS)
- [ ] [Surge](https://nssurge.com/) (macOS)
### Android
- [ ] WIP...


## Rules
### Sonic Franchise
#### HARDlight Games
- [x] Sonic Dash
- [x] Sonic Dash 2: Sonic Boom (iOS)
- [ ] Sonic Forces: Racing Battle (UNTESTED)

#### SEGA Forever Games
- [x] Sonic the Hedgehog Classic
- [x] Sonic CD Classic
- [x] Sonic the Hedgehog 2
- [x] Sonic the Hedgehog 4 Ep. II


### Other Sega Mobile Games
- [ ] WIP...

## User Instructions
### Apple
#### Quantumult X
**Quick Method**: [Click here](https://aka.wrye.dev/segaqx)

**Manual Method**:
1. Click the **Quantumult X logo** (Settings) on bottom-right
2. Turn to **Filter** > **Resources**
3. Click the **add link button** on top-right
4. Please fill in with the following details
    * **Tag**: SegaAdsRule (You can type in whatever you like)
    * **Resource URL**: https://raw.githubusercontent.com/AlanYe-Dev/SegaAdsRule/main/rules/QuantumultX.list
    * (Other options are optional)

#### Shadowrocket
1. Turn to **Config** page on the bottom menu
2. Click the **information button** of your current configuration
3. Click the **+** button on top-right > **Add Rule**
4. There're 2 rule-sets, please fill in with the following details
    * Reject Rule
        * **Type**: RULE-SET
        * **Policy**: REJECT
        * **Rule Set**: https://raw.githubusercontent.com/AlanYe-Dev/SegaAdsRule/main/rules/Shadowrocket/reject.list
    * Direct Rule
        * **Type**: RULE-SET
        * **Policy**: REJECT
        * **Rule Set**: https://raw.githubusercontent.com/AlanYe-Dev/SegaAdsRule/main/rules/Shadowrocket/direct.list
5. Save your edits, and reload the app. After that, the ads should disappear.

## DISCLAIMER
* All content shared in this repository SHOULD NOT be used in violation of the platform ToS and the laws of the country or region where the user is located.
* All content shared in this repository is for studing and research purposes only. Legality, accuracy, completeness and validity cannot be guaranteed. Please make your own judgment based on the actual situation.
* If the content included in this repository may be suspected of infringing its rights, you should promptly notify and provide proof of identity and ownership, and I will delete the relevant scripts after receiving the certification documents if there's any proper reason.
