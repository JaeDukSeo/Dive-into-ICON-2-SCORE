# Dive-into-ICON-2-SCORE

## Prerequisite
1. install Docker : https://docs.docker.com
2. Linux (Ubuntu 18.04 recommended) or OS X
3. Python 3.6, Python IDE (Pycharm recommended.)
4. T-Bears installation
5. Python experience, Basic knowledge about ICON dev tools (PythonSDK recommended)
6. Git (clone this repo)
7. Create directory for `icon-workshop-score` & Run Docker container (T-Bears container)  
 * ```$ cd ~ && mkdir icon-workshop && cd icon-workshop-score```
 * ```$ docker run -it -p 9000:9000 -v ${PWD}:/tbears/icon-workshop --name icon-workshop-score iconloop/tbears``` 

## Goal 

**Learn how to develop SCORE by following SCORE Guide and inspecting sample SCORE**

### SCORE Guide

1. Token & Crowdsale
2. IconScoreBase abstract methods
3. DB abstraction
4. Decorator, fallback
5. Type hints, exception handling  
6. InterfaceScore

### Sample SCORE
1. ICON Dice roll 
2. SampleGame (simple blackjack)

**\+ Development Resources**
 
 
## Links

#### 1. ICON official Github
https://github.com/icon-project

* ICON T-Bears Guide  
https://github.com/icon-project/t-bears
* ICON icon-rpc-server Guide  
https://github.com/icon-project/icon-rpc-server
* ICON SCORE Guide  
https://icon-project.github.io/score-guide


#### 2. ICON Developer portal
https://icondev.io/

#### 3. Tracker
* Mainnet : https://tracker.icon.foundation
* Testnet : https://bicon.tracker.solidwallet.io


#### 4. ICONex (ICON wallet chrome web store)
https://chrome.google.com/webstore/detail/iconex/flpiciilemghbmfalicajoolhkkenfel?hl=ko

#### 5. Faucet (Testnet)
http://52.88.70.222
