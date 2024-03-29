---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Start ^b2ngU1Vx

Ask the user what they want to do
    A. Collect new Baseline
        or
    B. Begin monitoring files with saved Baseline ^6xTXEUPA

Collect new Baseline
    1. Calculate HASH value from target files
    2. Store the file | hash pairs in baseline.txt ^CN3onIj4

Begin monitoring files with saved Baseline
    1. Load file : hash pairs from baseline.txt ^XyXeTLH9

Continuously monitor file integrity
    1. Loop through each target file, calculate
the hash, and com[are the file | hash to what
is baseline.txt ^ezmStPAZ

Notify user if a file is changed or deleted
    1. If a file's actual hash is different than
what is recorded in baseline, a file has been
changed or deleted (Integrity Compromise), print
to the screen (color). ^swpHMgAd

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.9.17",
	"elements": [
		{
			"type": "diamond",
			"version": 279,
			"versionNonce": 2123403338,
			"isDeleted": false,
			"id": "1OTfDX7Sexx5HJdufQasv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -107.75,
			"y": -362.28125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 127,
			"height": 129.4780487804878,
			"seed": 1553667402,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694476872202,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 44,
			"versionNonce": 730479178,
			"isDeleted": false,
			"id": "b2ngU1Vx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -69.75,
			"y": -308.28125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.699951171875,
			"height": 25,
			"seed": 1762077322,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1694477170124,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Start",
			"rawText": "Start",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Start",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 547,
			"versionNonce": 520077706,
			"isDeleted": false,
			"id": "XCZkb7ODaJL56xz1HEMrO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -44.75,
			"y": -234.28125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.4722330265538872,
			"height": 62,
			"seed": 1303152074,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694477013257,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "WNlvodR5JFlJWfuT7yZtS",
				"gap": 14,
				"focus": -0.005893909626719057
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-0.4722330265538872,
					62
				]
			]
		},
		{
			"type": "rectangle",
			"version": 531,
			"versionNonce": 1321043606,
			"isDeleted": false,
			"id": "WNlvodR5JFlJWfuT7yZtS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -296.75,
			"y": -158.28125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 504.8035714285714,
			"height": 133.91355599214143,
			"seed": 1141603594,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "XCZkb7ODaJL56xz1HEMrO",
					"type": "arrow"
				},
				{
					"id": "D2ODLxsOdpr9Suo5tGnRs",
					"type": "arrow"
				}
			],
			"updated": 1694477033827,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1594780106,
			"isDeleted": false,
			"id": "6xTXEUPA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -284.75,
			"y": -142.28125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 476.89959716796875,
			"height": 100,
			"seed": 1219529930,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "akrokK2oMv8wKwN2ZntOp",
					"type": "arrow"
				}
			],
			"updated": 1694477280884,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Ask the user what they want to do\n    A. Collect new Baseline\n        or\n    B. Begin monitoring files with saved Baseline",
			"rawText": "Ask the user what they want to do\n    A. Collect new Baseline\n        or\n    B. Begin monitoring files with saved Baseline",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Ask the user what they want to do\n    A. Collect new Baseline\n        or\n    B. Begin monitoring files with saved Baseline",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "arrow",
			"version": 169,
			"versionNonce": 1464096406,
			"isDeleted": false,
			"id": "D2ODLxsOdpr9Suo5tGnRs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -287.95325506995977,
			"y": -23.36769400785856,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.51649465304365,
			"height": 59.08644400785856,
			"seed": 1303858634,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1694477265276,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WNlvodR5JFlJWfuT7yZtS",
				"gap": 1,
				"focus": 0.4926066768823343
			},
			"endBinding": {
				"elementId": "TugLSEdKa70aYWD0nF5Hq",
				"gap": 11,
				"focus": -0.24702140126677646
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-69.51649465304365,
					59.08644400785856
				]
			]
		},
		{
			"type": "text",
			"version": 210,
			"versionNonce": 1907790474,
			"isDeleted": false,
			"id": "CN3onIj4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -596.75,
			"y": 60.71875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 478.8396301269531,
			"height": 75,
			"seed": 1237074902,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1694477266846,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Collect new Baseline\n    1. Calculate HASH value from target files\n    2. Store the file | hash pairs in baseline.txt",
			"rawText": "Collect new Baseline\n    1. Calculate HASH value from target files\n    2. Store the file | hash pairs in baseline.txt",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Collect new Baseline\n    1. Calculate HASH value from target files\n    2. Store the file | hash pairs in baseline.txt",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 124,
			"versionNonce": 166323222,
			"isDeleted": false,
			"id": "TugLSEdKa70aYWD0nF5Hq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -609.75,
			"y": 46.71875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 511,
			"height": 106,
			"seed": 748833046,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "D2ODLxsOdpr9Suo5tGnRs",
					"type": "arrow"
				}
			],
			"updated": 1694477265275,
			"link": null,
			"locked": false
		},
		{
			"id": "XyXeTLH9",
			"type": "text",
			"x": 116.25,
			"y": 57.71875,
			"width": 451.4196472167969,
			"height": 50,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 525920138,
			"version": 131,
			"versionNonce": 646545878,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1694477351769,
			"link": null,
			"locked": false,
			"text": "Begin monitoring files with saved Baseline\n    1. Load file : hash pairs from baseline.txt",
			"rawText": "Begin monitoring files with saved Baseline\n    1. Load file : hash pairs from baseline.txt",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 43,
			"containerId": null,
			"originalText": "Begin monitoring files with saved Baseline\n    1. Load file : hash pairs from baseline.txt",
			"lineHeight": 1.25
		},
		{
			"id": "qlaY6PqkUYUfCxsrv6U4m",
			"type": "rectangle",
			"x": 80.25,
			"y": 34.71875,
			"width": 521,
			"height": 93,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"seed": 1415457302,
			"version": 89,
			"versionNonce": 360420054,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "akrokK2oMv8wKwN2ZntOp",
					"type": "arrow"
				},
				{
					"id": "w2Pns6_e_mHfRiCBJNuji",
					"type": "arrow"
				}
			],
			"updated": 1694477383989,
			"link": null,
			"locked": false
		},
		{
			"id": "akrokK2oMv8wKwN2ZntOp",
			"type": "arrow",
			"x": 211.25,
			"y": -70.28125,
			"width": 81,
			"height": 96,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1523278550,
			"version": 37,
			"versionNonce": 972202122,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1694477280884,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					81,
					96
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "6xTXEUPA",
				"focus": -0.8515892314452829,
				"gap": 19.10040283203125
			},
			"endBinding": {
				"elementId": "qlaY6PqkUYUfCxsrv6U4m",
				"focus": -0.005577855392795705,
				"gap": 9
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "ezmStPAZ",
			"type": "text",
			"x": 115.25,
			"y": 221.71875,
			"width": 463.0396728515625,
			"height": 100,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 439564182,
			"version": 241,
			"versionNonce": 1906452682,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1694477378876,
			"link": null,
			"locked": false,
			"text": "Continuously monitor file integrity\n    1. Loop through each target file, calculate\nthe hash, and com[are the file | hash to what\nis baseline.txt",
			"rawText": "Continuously monitor file integrity\n    1. Loop through each target file, calculate\nthe hash, and com[are the file | hash to what\nis baseline.txt",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 93,
			"containerId": null,
			"originalText": "Continuously monitor file integrity\n    1. Loop through each target file, calculate\nthe hash, and com[are the file | hash to what\nis baseline.txt",
			"lineHeight": 1.25
		},
		{
			"id": "5c5fWJumcVA0wlx1c4rpl",
			"type": "rectangle",
			"x": 87.25,
			"y": 211.71875,
			"width": 516,
			"height": 121,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"seed": 509112522,
			"version": 116,
			"versionNonce": 815270230,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "w2Pns6_e_mHfRiCBJNuji",
					"type": "arrow"
				},
				{
					"id": "MznZseAwUXBbe6OpgnEnH",
					"type": "arrow"
				}
			],
			"updated": 1694477578307,
			"link": null,
			"locked": false
		},
		{
			"id": "w2Pns6_e_mHfRiCBJNuji",
			"type": "arrow",
			"x": 328.25,
			"y": 133.71875,
			"width": 2,
			"height": 69,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1653734986,
			"version": 46,
			"versionNonce": 1330217546,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1694477387303,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2,
					69
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "qlaY6PqkUYUfCxsrv6U4m",
				"focus": 0.05354919053549191,
				"gap": 6
			},
			"endBinding": {
				"elementId": "5c5fWJumcVA0wlx1c4rpl",
				"focus": -0.049991630865368515,
				"gap": 9
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "swpHMgAd",
			"type": "text",
			"x": 108.25,
			"y": 443.71875,
			"width": 471.59954833984375,
			"height": 125,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1856750742,
			"version": 453,
			"versionNonce": 1538473482,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "MznZseAwUXBbe6OpgnEnH",
					"type": "arrow"
				}
			],
			"updated": 1694477584306,
			"link": null,
			"locked": false,
			"text": "Notify user if a file is changed or deleted\n    1. If a file's actual hash is different than\nwhat is recorded in baseline, a file has been\nchanged or deleted (Integrity Compromise), print\nto the screen (color).",
			"rawText": "Notify user if a file is changed or deleted\n    1. If a file's actual hash is different than\nwhat is recorded in baseline, a file has been\nchanged or deleted (Integrity Compromise), print\nto the screen (color).",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 118,
			"containerId": null,
			"originalText": "Notify user if a file is changed or deleted\n    1. If a file's actual hash is different than\nwhat is recorded in baseline, a file has been\nchanged or deleted (Integrity Compromise), print\nto the screen (color).",
			"lineHeight": 1.25
		},
		{
			"id": "jJ42HsbWKsbDMjjcuBen7",
			"type": "rectangle",
			"x": 83.25,
			"y": 429.71875,
			"width": 527,
			"height": 156,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"seed": 993756490,
			"version": 185,
			"versionNonce": 1251253654,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "MznZseAwUXBbe6OpgnEnH",
					"type": "arrow"
				}
			],
			"updated": 1694477587443,
			"link": null,
			"locked": false
		},
		{
			"id": "MznZseAwUXBbe6OpgnEnH",
			"type": "arrow",
			"x": 338.9344405667301,
			"y": 343.71875,
			"width": 0.604548398899226,
			"height": 75,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1224683018,
			"version": 142,
			"versionNonce": 1925987670,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1694477587759,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.604548398899226,
					75
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "5c5fWJumcVA0wlx1c4rpl",
				"focus": 0.02666237658106597,
				"gap": 11
			},
			"endBinding": {
				"elementId": "jJ42HsbWKsbDMjjcuBen7",
				"focus": -0.024585033187332017,
				"gap": 11
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"type": "text",
			"version": 2,
			"versionNonce": 225546442,
			"isDeleted": true,
			"id": "tBSyklVi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 176.25,
			"y": 22.71875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 10,
			"height": 25,
			"seed": 2022464330,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1694477208147,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "",
			"rawText": "",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.25,
			"baseline": 18
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 707.25,
		"scrollY": 405.71875,
		"zoom": {
			"value": 1
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%