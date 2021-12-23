# ElapseAnalyzer
Simple WCL Analyzer for fight report

### Scenario 1
Calculate parse% + bracket% Per DPS Character Per Encounter

### Scenario 2

Calculate DPS Character Fight Potion

### [TODO]Scenario 3 

Get Healer Casts durning Entire Raid

### [TODO]Scenario 4 

Get Healer Overhealed Volume % during Entire Raid

### [TODO]Scenario 5 

Get Healer Potion during Entire Raid

### Usage 1:
```sh
# Windows
set WCL_CLIENT_TOKEN=your_wcl_api_v2_client_id_and_secrect_base64_string
# Linux/Unix
export WCL_CLIENT_TOKEN=your_wcl_api_v2_client_id_and_secrect_base64_string
# invoke py directly with -l and your wcl fight report link
python elapse_wcl_analyzer.py -l https://cn.classic.warcraftlogs.com/reports/rwG81bzxZvg3mDN9
```

Output:
`elapse_score.csv`
`elapse_dps_potion.csv`
//TODO 下次会更新 命令行 -opt potion / dps / healer 选项和输出 csv filename 参数

### [TODO]Usage 2:
```sh
# invoke py directly with -l and your wcl fight report link
python elapse_wcl_analyzer.py -o html -l https://cn.classic.warcraftlogs.com/reports/rwG81bzxZvg3mDN9
```

Output:
html web content

