---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Requirements
- sending & receiving messages
- joining groups

Out of Scope
- presence indicator ^bUd3Xk8R

Client - Sender ^kzgtATHS

Client - Receiving ^WHGCFdPW

Messaging Service ^mfPYs3ub

Messaging Service ^t9OkGbO6

Messaging DB ^xFRQAWxz

Short Polling ^NbghfFO5

Client - Sender ^TzXMch6D

Client - Receiving ^m0wcbtxP

Client - Connections ^UVDsfzEa

Messaging Service ^hw4BM0MB

Messaging Service ^ebj6LF0M

Messaging DB ^QBs9We2F

WebSockets ^w8sUO8C3

Persistant Connection ^3NjB1wJz

WS ^Sm1Mj4VB

WS ^0WKBDHQo

Client - Sender ^CmeBt27R

Client - Receiving ^jWoRhNv5

Client - Connections ^llwEFLPp

Messaging Service ^ZR0vEbTp

Messaging Service ^GhqR8wjz

Messaging DB ^MotPd2fS

WebSockets ^DcVJKsRr

Persistant Connection ^N89ObKtk

WS ^5ysMs64n

WS ^IdeH3HLN

Client - Connections ^oJPFrLFB

Messaging Service ^tMWE0piW

Messaging Service ^SRBgaZTe

Messaging DB ^yQGcMSW4

WebSockets ^zIAkr89z

Persistant Connection ^fg1KcnrB

WS ^TZ5cIah7

WS ^AqhNa2wx

Connection DB ^YczYdsya

Messaging Service ^2HicTMiH

Messaging Service ^pB9uWOcY

Messaging Service ^NVMCoDk4

Messaging Worker ^lYMEXADU

{
    sebder: {send}
    user_id: {rec}
    message: {msg}
} ^yH1oG5jb

{
    user_id: {rec}
    machine_id: {}
} ^pVOSVUEi

User
Socket
Cache ^fmqEIHgZ

User
Socket
Cache ^lA9wL69B

Stateful! ^AtpDOMzK

User
Socket
Cache ^bww0yBWS

WS ^tfcsCDWz

Client - Sender ^ytijRGDL

Client - Receiving ^yPTDDPf9

Client - Connections ^FXF77hil

Messaging Service ^CKTFiSLg

Messaging Service ^T5F3kLAD

Messaging DB ^2bamgdA0

WebSockets - Change Data Capture (DB Triggers) ^Vn0Hcl1h

Persistant Connection ^oDKjLcNC

WS ^65NX4PQl

WS ^98rVwHSq

Connection DB ^MIZphPfH

Messaging Service ^ZgrtClUv

Messaging Service ^R2uuLIuD

Messaging Service ^ETOeFIrp

Messaging Worker ^vBp9lGus

{
    sebder: {send}
    user_id: {rec}
    message: {msg}
} ^js4vY8qP

{
    user_id: {rec}
    machine_id: {}
} ^nVm5JSu1

User
Socket
Cache ^qZMGjzCB

User
Socket
Cache ^Rr0Zoc4N

Stateful! ^S1iiARlW

User
Socket
Cache ^ZVqpVkEk

WS ^PHTokAvB

Messaging Service ^h8ZJRA8m

Messaging Service ^ua1rzZhN

Group Worker ^jNbRUxH8

Group
DB ^879vdG6O

{
    group_id: {send}
    user_id: [{rec}, {}]
} ^1ImYYPot

Client - Sender ^6rBTIXIf

Client - Receiving ^eJolWrD0

Client - Connections ^d5tzzYtG

Send Service ^1PtwBLQU

Receive Service ^thi4UGsH

Messaging DB ^3YhJcgHt

WebSockets - Change Data Capture (DB Triggers) ^uzjTTuDb

Persistant Connection ^kUsXcFbd

WS ^VEH8JJzm

Connection DB ^yXaMCB8S

Receive Service ^DKaH4n2D

Messaging Service ^kTL6R4ew

Messaging Service ^LVuDnD2l

Messaging Worker ^D9Zu6wQc

{
    sebder: {send}
    user_id: {rec}
    message: {msg}
} ^5lH4QHhT

{
    user_id: {rec}
    machine_id: {}
} ^sW5g690p

User
Socket
Cache ^tClgBJ2Z

User
Socket
Cache ^einG2DQF

Stateful! due to keeping websocket ^2i1GfBlX

User
Socket
Cache ^9KNM7lT9

WS ^p3qO00r1

Messaging Service ^Ily8wCkK

Messaging Service ^rZZrAJrs

Group Worker ^5SuwbhUW

Group
DB ^fZGNDLe0

{
    group_id: {send}
    user_id: [{rec}, {}]
} ^Aqq3NyES

read heavy
- dynamodb ^WWpEw1Fi

Client - Join a group ^UN5ErxRQ

Group Service ^BaFNgKwX

Write Heavy ^QKPYgqoS

Save connection info on join ^5vEq58ax

Send info to clients ^sXxOkOln

Client - Sender ^vu3PKaIj

Client - Receiving ^1CtCww9i

Client - Connections ^2nWT0Z7j

Send Service ^ggFBM8QI

Receive Service ^uHNqNU1f

Messaging DB ^llAJy4wO

WebSockets - Change Data Capture ^K29ndCf2

Persistant Connection ^jjlS1xZm

WS ^zLPTplUE

Connection DB ^yMy1CemG

Receive Service ^WnHay2un

Messaging Service ^NqkKxWpy

Messaging Service ^qenPLvBh

Messaging Worker ^2aetfaZW

{
    sebder: {send}
    user_id: {rec}
    message: {msg}
} ^Nfb9qtJQ

{
    user_id: {rec}
    machine_id: {}
} ^AzrNT6bJ

User
Socket
Cache ^7gb4bvWs

User
Socket
Cache ^6eZmAk6N

Stateful! due to keeping websocket ^rWTIFLtE

User
Socket
Cache ^PWc2M19T

WS ^SBPECtMJ

Group
DB ^ZfVEwY95

{
    group_id: {send}
    user_id: [{rec}, {}]
} ^1wDDL3pL

read heavy
- dynamodb ^m4MKVQmI

Client - Join a group ^IykyFCT2

Group Service ^oblNPO05

Write Heavy ^pLzcpIoQ

Save connection info on join ^QXFS8gvv

Send info to clients ^3mo0yfvE

Extensions
- how would you handle large groups
  - could probably change to polling as you will be receiving lots of messages at once and therefore takes load off the servers
- mentions might want to sned notifications ^Idz2FIN8

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.24",
	"elements": [
		{
			"type": "rectangle",
			"version": 86,
			"versionNonce": 1538521749,
			"isDeleted": false,
			"id": "V-8TcXFoWOwLqD-C4DHEZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 265.82421875,
			"y": -223.666259765625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 199.48828125,
			"height": 359.421875,
			"seed": 1774066069,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 103,
			"versionNonce": 1703830843,
			"isDeleted": false,
			"id": "bUd3Xk8R",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -475.5703125,
			"y": -427.03515625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 298.4397277832031,
			"height": 150,
			"seed": 1777866171,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Requirements\n- sending & receiving messages\n- joining groups\n\nOut of Scope\n- presence indicator",
			"rawText": "Requirements\n- sending & receiving messages\n- joining groups\n\nOut of Scope\n- presence indicator",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Requirements\n- sending & receiving messages\n- joining groups\n\nOut of Scope\n- presence indicator",
			"lineHeight": 1.25,
			"baseline": 143
		},
		{
			"type": "rectangle",
			"version": 85,
			"versionNonce": 1289871349,
			"isDeleted": false,
			"id": "EAJOyEwuXRdm-i2MS2L2u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -69.25,
			"y": -192.765380859375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 2020162261,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "kzgtATHS"
				},
				{
					"id": "yoHXn7wk2GnUdznOtjPl-",
					"type": "arrow"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 1386481115,
			"isDeleted": false,
			"id": "kzgtATHS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -40.91777801513672,
			"y": -164.974365234375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.31993103027344,
			"height": 50,
			"seed": 170170485,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nSender",
			"rawText": "Client - Sender",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "EAJOyEwuXRdm-i2MS2L2u",
			"originalText": "Client - Sender",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 127,
			"versionNonce": 502012245,
			"isDeleted": false,
			"id": "WniOmuDcbRpMzUxukBRp-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -73.46484375,
			"y": -35.060302734375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 994607163,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "WHGCFdPW"
				},
				{
					"id": "Iq4Bf2Ctt49bMsZITJ8iO",
					"type": "arrow"
				},
				{
					"id": "k8Qj8S0-Qca_dam8ECbE_",
					"type": "arrow"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 116,
			"versionNonce": 427594363,
			"isDeleted": false,
			"id": "WHGCFdPW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -51.00261688232422,
			"y": -7.269287109375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.05992126464844,
			"height": 50,
			"seed": 1080213723,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nReceiving",
			"rawText": "Client - Receiving",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "WniOmuDcbRpMzUxukBRp-",
			"originalText": "Client - Receiving",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 240,
			"versionNonce": 942155445,
			"isDeleted": false,
			"id": "SUTfFYG63ogEFMI1rozLH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 294.57421875,
			"y": -185.406494140625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 46453525,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "mfPYs3ub"
				},
				{
					"id": "yoHXn7wk2GnUdznOtjPl-",
					"type": "arrow"
				},
				{
					"id": "ZMeMxCHpbZb1nU90gg9HC",
					"type": "arrow"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 236,
			"versionNonce": 1524271899,
			"isDeleted": false,
			"id": "mfPYs3ub",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 311.52645111083984,
			"y": -157.615478515625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 2101586037,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "SUTfFYG63ogEFMI1rozLH",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 303,
			"versionNonce": 1044088853,
			"isDeleted": false,
			"id": "6BTlo-7FOpV5JrJSMw_6b",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 295.23046875,
			"y": 0.366943359375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1576374587,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "t9OkGbO6"
				},
				{
					"id": "Iq4Bf2Ctt49bMsZITJ8iO",
					"type": "arrow"
				},
				{
					"id": "k8Qj8S0-Qca_dam8ECbE_",
					"type": "arrow"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 302,
			"versionNonce": 2066771899,
			"isDeleted": false,
			"id": "t9OkGbO6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 312.18270111083984,
			"y": 28.157958984375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 222671323,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "6BTlo-7FOpV5JrJSMw_6b",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 298,
			"versionNonce": 1645985141,
			"isDeleted": false,
			"id": "Ics636Me-5x31PwT3mwsR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 585.39453125,
			"y": -118.840087890625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 7602837,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "xFRQAWxz"
				},
				{
					"id": "ZMeMxCHpbZb1nU90gg9HC",
					"type": "arrow"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 296,
			"versionNonce": 748732507,
			"isDeleted": false,
			"id": "xFRQAWxz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 602.3467636108398,
			"y": -91.049072265625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1818290165,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nDB",
			"rawText": "Messaging DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Ics636Me-5x31PwT3mwsR",
			"originalText": "Messaging DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 39,
			"versionNonce": 2064533205,
			"isDeleted": false,
			"id": "NbghfFO5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 198.41796875,
			"y": -314.888916015625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 121.57987976074219,
			"height": 25,
			"seed": 39019797,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Short Polling",
			"rawText": "Short Polling",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Short Polling",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 183,
			"versionNonce": 2071537781,
			"isDeleted": false,
			"id": "yoHXn7wk2GnUdznOtjPl-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 65.09765625000001,
			"y": -131.974853515625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 222.046875,
			"height": 4.42578125,
			"seed": 2081844443,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354605,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "EAJOyEwuXRdm-i2MS2L2u",
				"gap": 5.36328125,
				"focus": 0.1221820140084977
			},
			"endBinding": {
				"elementId": "SUTfFYG63ogEFMI1rozLH",
				"gap": 7.4296875,
				"focus": -0.12019897198010214
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
					222.046875,
					4.42578125
				]
			]
		},
		{
			"type": "arrow",
			"version": 299,
			"versionNonce": 277530101,
			"isDeleted": false,
			"id": "Iq4Bf2Ctt49bMsZITJ8iO",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 58.748681078758096,
			"y": 18.332366952858877,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 233.06249999999997,
			"height": 5.5820312499999964,
			"seed": 729046805,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354605,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WniOmuDcbRpMzUxukBRp-",
				"gap": 3.2291498287580964,
				"focus": -0.01877819545291292
			},
			"endBinding": {
				"elementId": "6BTlo-7FOpV5JrJSMw_6b",
				"gap": 3.419287671241932,
				"focus": 0.5082671307240502
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
					233.06249999999997,
					5.5820312499999964
				]
			]
		},
		{
			"type": "arrow",
			"version": 575,
			"versionNonce": 659524789,
			"isDeleted": false,
			"id": "k8Qj8S0-Qca_dam8ECbE_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 290.7316348543111,
			"y": 56.573308311617,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 229.20703125,
			"height": 5.136718750000007,
			"seed": 1660279227,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354605,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "6BTlo-7FOpV5JrJSMw_6b",
				"gap": 4.498833895688904,
				"focus": -0.03446404453338455
			},
			"endBinding": {
				"elementId": "WniOmuDcbRpMzUxukBRp-",
				"gap": 6.005072354311096,
				"focus": 0.8400127475064771
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
					-229.20703125,
					5.136718750000007
				]
			]
		},
		{
			"type": "arrow",
			"version": 306,
			"versionNonce": 253862773,
			"isDeleted": false,
			"id": "ZMeMxCHpbZb1nU90gg9HC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 426.8814935787581,
			"y": -132.98794554714115,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 152.45703124999994,
			"height": 54.074218749999986,
			"seed": 140976795,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354605,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "SUTfFYG63ogEFMI1rozLH",
				"gap": 3.322899828758068,
				"focus": -0.32280872730972915
			},
			"endBinding": {
				"elementId": "Ics636Me-5x31PwT3mwsR",
				"gap": 6.056006421241932,
				"focus": -0.16067748182656452
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
					152.45703124999994,
					54.074218749999986
				]
			]
		},
		{
			"type": "rectangle",
			"version": 215,
			"versionNonce": 2084125243,
			"isDeleted": false,
			"id": "Ea2jAa9JB5ujaq19khGkD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 256.556640625,
			"y": 574.0872802734375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 199.48828125,
			"height": 437.28906249999994,
			"seed": 1298656181,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 157,
			"versionNonce": 1790630645,
			"isDeleted": false,
			"id": "uuhGzqY2hPL7-RqgozUqb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -79.255859375,
			"y": 605.2303466796875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 20622613,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "TzXMch6D"
				},
				{
					"id": "gpwUnDhLEijucXTaazzJ2",
					"type": "arrow"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 131,
			"versionNonce": 1462516443,
			"isDeleted": false,
			"id": "TzXMch6D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -50.92363739013672,
			"y": 633.0213623046875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.31993103027344,
			"height": 50,
			"seed": 602817141,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nSender",
			"rawText": "Client - Sender",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "uuhGzqY2hPL7-RqgozUqb",
			"originalText": "Client - Sender",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 301,
			"versionNonce": 753775701,
			"isDeleted": false,
			"id": "o-HSacmMUKXVUJ51gYY8P",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -78.263671875,
			"y": 876.6854248046875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1246243797,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "m0wcbtxP"
				},
				{
					"id": "BPxhdBla82e20QVBoWmdL",
					"type": "arrow"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 288,
			"versionNonce": 691414907,
			"isDeleted": false,
			"id": "m0wcbtxP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -55.80144500732422,
			"y": 904.4764404296875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.05992126464844,
			"height": 50,
			"seed": 1415440693,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nReceiving",
			"rawText": "Client - Receiving",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "o-HSacmMUKXVUJ51gYY8P",
			"originalText": "Client - Receiving",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 336,
			"versionNonce": 1245602229,
			"isDeleted": false,
			"id": "lSpaXJqBerOBz3PT_49IM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -74.279296875,
			"y": 1033.5423583984375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 60095125,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "UVDsfzEa"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 354,
			"versionNonce": 1218019355,
			"isDeleted": false,
			"id": "UVDsfzEa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -65.07705688476562,
			"y": 1061.3333740234375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.57989501953125,
			"height": 50,
			"seed": 1352851445,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nConnections",
			"rawText": "Client - Connections",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "lSpaXJqBerOBz3PT_49IM",
			"originalText": "Client - Connections",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 311,
			"versionNonce": 1204970261,
			"isDeleted": false,
			"id": "UWfVlTA2JA1K0OMBNXaM8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 285.306640625,
			"y": 612.3470458984375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 26024277,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "hw4BM0MB"
				},
				{
					"id": "gpwUnDhLEijucXTaazzJ2",
					"type": "arrow"
				},
				{
					"id": "-HvwDYTReTDepsBPjx99-",
					"type": "arrow"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 304,
			"versionNonce": 524862651,
			"isDeleted": false,
			"id": "hw4BM0MB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 302.25887298583984,
			"y": 640.1380615234375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 2141791925,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "UWfVlTA2JA1K0OMBNXaM8",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 447,
			"versionNonce": 1780430965,
			"isDeleted": false,
			"id": "RPOE3FVGOGjIOqECOHm5g",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 291.306640625,
			"y": 877.9759521484375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1838974997,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ebj6LF0M"
				},
				{
					"id": "BPxhdBla82e20QVBoWmdL",
					"type": "arrow"
				},
				{
					"id": "CuKp-yx4kx2cLHGX8ZR42",
					"type": "arrow"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 443,
			"versionNonce": 887518555,
			"isDeleted": false,
			"id": "ebj6LF0M",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 308.25887298583984,
			"y": 905.7669677734375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 2103229813,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "RPOE3FVGOGjIOqECOHm5g",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 484,
			"versionNonce": 1256874453,
			"isDeleted": false,
			"id": "gip9ECHeUarEBcgDmI7FP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 611.650390625,
			"y": 626.6790771484375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 103761621,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "QBs9We2F"
				}
			],
			"updated": 1710340482151,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 481,
			"versionNonce": 2026181115,
			"isDeleted": false,
			"id": "QBs9We2F",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 628.6026229858398,
			"y": 654.4700927734375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1521067061,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482151,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nDB",
			"rawText": "Messaging DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "gip9ECHeUarEBcgDmI7FP",
			"originalText": "Messaging DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 18,
			"versionNonce": 793337653,
			"isDeleted": false,
			"id": "w8sUO8C3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 163.4296875,
			"y": 459.9708251953125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 112.139892578125,
			"height": 25,
			"seed": 323996629,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WebSockets",
			"rawText": "WebSockets",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "WebSockets",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 185,
			"versionNonce": 790611893,
			"isDeleted": false,
			"id": "gpwUnDhLEijucXTaazzJ2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 56.238281250000014,
			"y": 660.4200439453125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 226.43359375,
			"height": 0.80859375,
			"seed": 1277463131,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354605,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "uuhGzqY2hPL7-RqgozUqb",
				"gap": 6.509765625,
				"focus": 0.04045795120895698
			},
			"endBinding": {
				"elementId": "UWfVlTA2JA1K0OMBNXaM8",
				"gap": 2.634765625,
				"focus": 0.06921204270979184
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
					226.43359375,
					0.80859375
				]
			]
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 497135765,
			"isDeleted": false,
			"id": "3NjB1wJz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 47.7421875,
			"y": 554.9825439453125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 213.85980224609375,
			"height": 25,
			"seed": 1305724341,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Persistant Connection",
			"rawText": "Persistant Connection",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Persistant Connection",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 286,
			"versionNonce": 1564984629,
			"isDeleted": false,
			"id": "BPxhdBla82e20QVBoWmdL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 58.484375000000014,
			"y": 930.2258780736511,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 231.822265625,
			"height": 0.5890685363144712,
			"seed": 226589147,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354605,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "o-HSacmMUKXVUJ51gYY8P",
				"gap": 7.763671875,
				"focus": 0.010685187618235972
			},
			"endBinding": {
				"elementId": "RPOE3FVGOGjIOqECOHm5g",
				"gap": 1,
				"focus": -0.0040486682112330745
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
					231.822265625,
					0.5890685363144712
				]
			]
		},
		{
			"type": "rectangle",
			"version": 130,
			"versionNonce": 866702837,
			"isDeleted": false,
			"id": "amgxlzYQgo5bLm77G0Usm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 512.61328125,
			"y": 678.5762939453125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 49.41015625,
			"height": 275.01953125,
			"seed": 2137481845,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "-HvwDYTReTDepsBPjx99-",
					"type": "arrow"
				},
				{
					"id": "CuKp-yx4kx2cLHGX8ZR42",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 112,
			"versionNonce": 1717509749,
			"isDeleted": false,
			"id": "-HvwDYTReTDepsBPjx99-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 420.4921875,
			"y": 661.8497314453125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 86.765625,
			"height": 38.17578125,
			"seed": 775562805,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354605,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "UWfVlTA2JA1K0OMBNXaM8",
				"gap": 6.201171875,
				"focus": -0.4237265954055913
			},
			"endBinding": {
				"elementId": "amgxlzYQgo5bLm77G0Usm",
				"gap": 5.35546875,
				"focus": 0.6930482613648037
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
					86.765625,
					38.17578125
				]
			]
		},
		{
			"type": "arrow",
			"version": 102,
			"versionNonce": 365280245,
			"isDeleted": false,
			"id": "CuKp-yx4kx2cLHGX8ZR42",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 423.58203125,
			"y": 940.3497314453125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 80.7421875,
			"height": 41.72265625,
			"seed": 784434779,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354605,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "RPOE3FVGOGjIOqECOHm5g",
				"gap": 3.291015625,
				"focus": 0.5180066738093457
			},
			"endBinding": {
				"elementId": "amgxlzYQgo5bLm77G0Usm",
				"gap": 8.2890625,
				"focus": -0.4358095405025586
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
					80.7421875,
					-41.72265625
				]
			]
		},
		{
			"type": "rectangle",
			"version": 156,
			"versionNonce": 1716173947,
			"isDeleted": false,
			"id": "0GUr2ctMzV3H00rV_z3lF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 21.81640625,
			"y": 641.8028564453125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 968302005,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Sm1Mj4VB"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 103390389,
			"isDeleted": false,
			"id": "Sm1Mj4VB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 58.56156921386719,
			"y": 646.8028564453125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 1237225685,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "0GUr2ctMzV3H00rV_z3lF",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 243,
			"versionNonce": 5469467,
			"isDeleted": false,
			"id": "B_VRxwhZZcBC_Qn8Fl7xd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 30.671875,
			"y": 914.0645751953125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 787106683,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "0WKBDHQo"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 184,
			"versionNonce": 2023636501,
			"isDeleted": false,
			"id": "0WKBDHQo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 67.41703796386719,
			"y": 919.0645751953125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 1277764635,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "B_VRxwhZZcBC_Qn8Fl7xd",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 473,
			"versionNonce": 368843195,
			"isDeleted": false,
			"id": "2SpzfsDbckzcwN6cTL0q6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 215.0677712774559,
			"y": 1679.2623736983405,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 199.48828125,
			"height": 808.1123352329179,
			"seed": 1804853115,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 379,
			"versionNonce": 1790423925,
			"isDeleted": false,
			"id": "g9gr6rDbQ8isMgXNK9ozB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -120.7447287225441,
			"y": 1710.4054401045905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1719679003,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "CmeBt27R"
				},
				{
					"id": "OHTwtYtd4M7tNw7Y98djy",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 353,
			"versionNonce": 73869915,
			"isDeleted": false,
			"id": "CmeBt27R",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -92.41250673768081,
			"y": 1738.1964557295905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.31993103027344,
			"height": 50,
			"seed": 1066958011,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nSender",
			"rawText": "Client - Sender",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "g9gr6rDbQ8isMgXNK9ozB",
			"originalText": "Client - Sender",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 523,
			"versionNonce": 951811285,
			"isDeleted": false,
			"id": "oA73V2cRL6fVsIjBipROA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -119.7525412225441,
			"y": 1981.8605182295905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 578760027,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "jWoRhNv5"
				},
				{
					"id": "JiSmpbNACqkMaOf_AK6vS",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 510,
			"versionNonce": 1617372923,
			"isDeleted": false,
			"id": "jWoRhNv5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -97.29031435486831,
			"y": 2009.6515338545905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.05992126464844,
			"height": 50,
			"seed": 579258875,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nReceiving",
			"rawText": "Client - Receiving",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "oA73V2cRL6fVsIjBipROA",
			"originalText": "Client - Receiving",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 664,
			"versionNonce": 440343093,
			"isDeleted": false,
			"id": "dIlG5YT7TAIOZfW21ho-B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -117.43466878574088,
			"y": 2263.5332033224504,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1152504475,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "llwEFLPp"
				},
				{
					"id": "N-SVnggIFUGxNME3KdPvB",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 681,
			"versionNonce": 8294299,
			"isDeleted": false,
			"id": "llwEFLPp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -108.23242879550651,
			"y": 2291.3242189474504,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.57989501953125,
			"height": 50,
			"seed": 1236453179,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nConnections",
			"rawText": "Client - Connections",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "dIlG5YT7TAIOZfW21ho-B",
			"originalText": "Client - Connections",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 534,
			"versionNonce": 942148501,
			"isDeleted": false,
			"id": "uhiSgaF3hJs-xQWpTIery",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 243.8177712774559,
			"y": 1717.5221393233405,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 938223579,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ZR0vEbTp"
				},
				{
					"id": "OHTwtYtd4M7tNw7Y98djy",
					"type": "arrow"
				},
				{
					"id": "aSdGT1QxBNgX9kIAD9GH_",
					"type": "arrow"
				},
				{
					"id": "feGDR9Nl12AX8XQVm9007",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 526,
			"versionNonce": 1189078075,
			"isDeleted": false,
			"id": "ZR0vEbTp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 260.77000363829575,
			"y": 1745.3131549483405,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 628126843,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "uhiSgaF3hJs-xQWpTIery",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 671,
			"versionNonce": 44814581,
			"isDeleted": false,
			"id": "JT-d8QYpDPlvf1xfTPqK7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 249.8177712774559,
			"y": 1983.1510455733405,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1107438875,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "GhqR8wjz"
				},
				{
					"id": "JiSmpbNACqkMaOf_AK6vS",
					"type": "arrow"
				},
				{
					"id": "RroquzPyEqF7hRsFDVwqy",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 665,
			"versionNonce": 728605915,
			"isDeleted": false,
			"id": "GhqR8wjz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 266.77000363829575,
			"y": 2010.9420611983405,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 554947003,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "JT-d8QYpDPlvf1xfTPqK7",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1036,
			"versionNonce": 1196419669,
			"isDeleted": false,
			"id": "YJKxcGnYvToduJhocR0bR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 548.5587102730533,
			"y": 1715.9209952733581,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1137173083,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "MotPd2fS"
				},
				{
					"id": "feGDR9Nl12AX8XQVm9007",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1032,
			"versionNonce": 96096635,
			"isDeleted": false,
			"id": "MotPd2fS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 565.5109426338931,
			"y": 1743.7120108983581,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1659952891,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nDB",
			"rawText": "Messaging DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "YJKxcGnYvToduJhocR0bR",
			"originalText": "Messaging DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 240,
			"versionNonce": 115988405,
			"isDeleted": false,
			"id": "DcVJKsRr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 121.9408181524559,
			"y": 1565.1459186202155,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 112.139892578125,
			"height": 25,
			"seed": 2031175579,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WebSockets",
			"rawText": "WebSockets",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "WebSockets",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 855,
			"versionNonce": 1828894453,
			"isDeleted": false,
			"id": "OHTwtYtd4M7tNw7Y98djy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 14.749411902455904,
			"y": 1765.5951373702158,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 226.43359375,
			"height": 0.8085937499997726,
			"seed": 207330363,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354606,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "g9gr6rDbQ8isMgXNK9ozB",
				"gap": 6.509765625,
				"focus": 0.04045795120895698
			},
			"endBinding": {
				"elementId": "uhiSgaF3hJs-xQWpTIery",
				"gap": 2.634765625,
				"focus": 0.06921204270979184
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
					226.43359375,
					0.8085937499997726
				]
			]
		},
		{
			"type": "text",
			"version": 357,
			"versionNonce": 194976021,
			"isDeleted": false,
			"id": "N89ObKtk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -26.397787622769556,
			"y": 1820.8516900843924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 213.85980224609375,
			"height": 25,
			"seed": 951213275,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Persistant Connection",
			"rawText": "Persistant Connection",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Persistant Connection",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 956,
			"versionNonce": 1268323445,
			"isDeleted": false,
			"id": "JiSmpbNACqkMaOf_AK6vS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 16.99550565245592,
			"y": 2035.400971498315,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 231.822265625,
			"height": 0.589068536501145,
			"seed": 2041055611,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354606,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "oA73V2cRL6fVsIjBipROA",
				"gap": 7.763671875000014,
				"focus": 0.010685187612612572
			},
			"endBinding": {
				"elementId": "JT-d8QYpDPlvf1xfTPqK7",
				"gap": 1,
				"focus": -0.004048668211233235
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
					231.822265625,
					0.589068536501145
				]
			]
		},
		{
			"type": "rectangle",
			"version": 589,
			"versionNonce": 1055207029,
			"isDeleted": false,
			"id": "sLLyvOxLsUEb8RfECl0nL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 457.9819670852878,
			"y": 1888.145869364755,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 321.49094774503965,
			"height": 32.33619766870607,
			"seed": 880747035,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "aSdGT1QxBNgX9kIAD9GH_",
					"type": "arrow"
				},
				{
					"id": "Ro-n7QO9lnSk1wXeH0t9R",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 1360,
			"versionNonce": 460990901,
			"isDeleted": false,
			"id": "aSdGT1QxBNgX9kIAD9GH_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 377.87183541193554,
			"y": 1801.0626244840928,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 119.31167252876668,
			"height": 79.25985577653319,
			"seed": 36316859,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "jgdZZ-B1ZDSWixgTD7V4G",
				"gap": 19.79044476476122,
				"focus": -1.226021605393976
			},
			"endBinding": {
				"elementId": "sLLyvOxLsUEb8RfECl0nL",
				"gap": 7.823389104129092,
				"focus": -0.4615695811453458
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
					119.31167252876668,
					79.25985577653319
				]
			]
		},
		{
			"type": "rectangle",
			"version": 378,
			"versionNonce": 1065457621,
			"isDeleted": false,
			"id": "1PfSQuoGo-UeL17OHMwGB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -19.672463097544096,
			"y": 1746.9779498702155,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 943059963,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "5ysMs64n"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 317,
			"versionNonce": 618937339,
			"isDeleted": false,
			"id": "5ysMs64n",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 17.07269986632309,
			"y": 1751.9779498702155,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 1860943003,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "1PfSQuoGo-UeL17OHMwGB",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 465,
			"versionNonce": 931779893,
			"isDeleted": false,
			"id": "Q5ROayVkV8jatSTihxZz-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -10.816994347544096,
			"y": 2019.2396686202155,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 689926459,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "IdeH3HLN"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 406,
			"versionNonce": 1049691291,
			"isDeleted": false,
			"id": "IdeH3HLN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 25.92816861632309,
			"y": 2024.2396686202155,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 406032859,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Q5ROayVkV8jatSTihxZz-",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 268,
			"versionNonce": 1919116949,
			"isDeleted": false,
			"id": "47ipp19G7DN2A4bxYbQXa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 229.49033569030712,
			"y": -1461.343687788598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 199.48828125,
			"height": 437.28906249999994,
			"seed": 490380923,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 389,
			"versionNonce": 1692121403,
			"isDeleted": false,
			"id": "TrGWQ32-KkTfWvhNmnb-C",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -101.34560180969288,
			"y": -1001.8886096635979,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1391925019,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "oJPFrLFB"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 407,
			"versionNonce": 851692533,
			"isDeleted": false,
			"id": "oJPFrLFB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -92.1433618194585,
			"y": -974.0975940385979,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.57989501953125,
			"height": 50,
			"seed": 1474001851,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nConnections",
			"rawText": "Client - Connections",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "TrGWQ32-KkTfWvhNmnb-C",
			"originalText": "Client - Connections",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 364,
			"versionNonce": 623303131,
			"isDeleted": false,
			"id": "svEuikDKQccOeEBK6nqRY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 258.2403356903071,
			"y": -1423.083922163598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1477069915,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "tMWE0piW"
				},
				{
					"id": "QXbCe_uNlXA5PK1HNknWC",
					"type": "arrow"
				},
				{
					"id": "yrZjTmHKNUzWQwx_GNj_y",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 357,
			"versionNonce": 1219528021,
			"isDeleted": false,
			"id": "tMWE0piW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 275.19256805114696,
			"y": -1395.292906538598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1465256187,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "svEuikDKQccOeEBK6nqRY",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 500,
			"versionNonce": 1015342715,
			"isDeleted": false,
			"id": "FA4KtyXOBrvp1pnHUI4iT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 264.2403356903071,
			"y": -1157.455015913598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 994128283,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "SRBgaZTe"
				},
				{
					"id": "0qxJc3CglarZx2eInrBsy",
					"type": "arrow"
				},
				{
					"id": "hor8QIv_uAhCdNVKPZ20J",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 496,
			"versionNonce": 1736381109,
			"isDeleted": false,
			"id": "SRBgaZTe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 281.19256805114696,
			"y": -1129.664000288598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 352208443,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FA4KtyXOBrvp1pnHUI4iT",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 537,
			"versionNonce": 565731099,
			"isDeleted": false,
			"id": "m_WBBI1T5y0sTYybtcGNp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 584.5840856903071,
			"y": -1408.751890913598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 728745691,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "yQGcMSW4"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 534,
			"versionNonce": 1003811861,
			"isDeleted": false,
			"id": "yQGcMSW4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 601.536318051147,
			"y": -1380.960875288598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1160262523,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nDB",
			"rawText": "Messaging DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "m_WBBI1T5y0sTYybtcGNp",
			"originalText": "Messaging DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 1328792507,
			"isDeleted": false,
			"id": "zIAkr89z",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 136.36338256530712,
			"y": -1575.460142866723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 112.139892578125,
			"height": 25,
			"seed": 845810715,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WebSockets",
			"rawText": "WebSockets",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "WebSockets",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 216,
			"versionNonce": 1419316373,
			"isDeleted": false,
			"id": "QXbCe_uNlXA5PK1HNknWC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 29.17197631530712,
			"y": -1375.010924116723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 226.43359375,
			"height": 0.80859375,
			"seed": 388485307,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354606,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "svEuikDKQccOeEBK6nqRY",
				"gap": 2.634765625,
				"focus": 0.06921204270979184
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
					226.43359375,
					0.80859375
				]
			]
		},
		{
			"type": "text",
			"version": 153,
			"versionNonce": 1293522011,
			"isDeleted": false,
			"id": "fg1KcnrB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 20.67588256530712,
			"y": -1480.448424116723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 213.85980224609375,
			"height": 25,
			"seed": 1963196763,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Persistant Connection",
			"rawText": "Persistant Connection",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Persistant Connection",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 317,
			"versionNonce": 294549685,
			"isDeleted": false,
			"id": "0qxJc3CglarZx2eInrBsy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 31.41807006530712,
			"y": -1105.205121273535,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 231.822265625,
			"height": 0.5890929514389427,
			"seed": 1968250363,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354606,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "FA4KtyXOBrvp1pnHUI4iT",
				"gap": 1,
				"focus": -0.00404866821122397
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
					231.822265625,
					0.5890929514389427
				]
			]
		},
		{
			"type": "rectangle",
			"version": 183,
			"versionNonce": 2067550459,
			"isDeleted": false,
			"id": "fwoTiga5pEusZdggxSIZ5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 485.5469763153071,
			"y": -1356.854674116723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 49.41015625,
			"height": 275.01953125,
			"seed": 1930536603,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "yrZjTmHKNUzWQwx_GNj_y",
					"type": "arrow"
				},
				{
					"id": "hor8QIv_uAhCdNVKPZ20J",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 265,
			"versionNonce": 708094805,
			"isDeleted": false,
			"id": "yrZjTmHKNUzWQwx_GNj_y",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 393.4258825653071,
			"y": -1373.581236616723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 86.76562500000011,
			"height": 38.175781250000455,
			"seed": 1157110587,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354606,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "svEuikDKQccOeEBK6nqRY",
				"gap": 6.201171875,
				"focus": -0.42372659540559376
			},
			"endBinding": {
				"elementId": "fwoTiga5pEusZdggxSIZ5",
				"gap": 5.355468749999886,
				"focus": 0.6930482613647996
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
					86.76562500000011,
					38.175781250000455
				]
			]
		},
		{
			"type": "arrow",
			"version": 255,
			"versionNonce": 261459829,
			"isDeleted": false,
			"id": "hor8QIv_uAhCdNVKPZ20J",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 396.5157263153071,
			"y": -1095.081236616723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 80.7421875,
			"height": 41.72265625,
			"seed": 1197931483,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354606,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "FA4KtyXOBrvp1pnHUI4iT",
				"gap": 3.291015625,
				"focus": 0.5180066738093457
			},
			"endBinding": {
				"elementId": "fwoTiga5pEusZdggxSIZ5",
				"gap": 8.2890625,
				"focus": -0.4358095405025586
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
					80.7421875,
					-41.72265625
				]
			]
		},
		{
			"type": "rectangle",
			"version": 209,
			"versionNonce": 122929557,
			"isDeleted": false,
			"id": "Wb8WWqATCe7pgRHS3nDwl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -5.24989868469288,
			"y": -1393.628111616723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 644925563,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "TZ5cIah7"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 148,
			"versionNonce": 435326523,
			"isDeleted": false,
			"id": "TZ5cIah7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 31.495264279174307,
			"y": -1388.628111616723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 1742209307,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Wb8WWqATCe7pgRHS3nDwl",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 296,
			"versionNonce": 519096053,
			"isDeleted": false,
			"id": "uIMtCRslcyieREyNlPG5v",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3.60557006530712,
			"y": -1121.366392866723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 890185147,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "AqhNa2wx"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 237,
			"versionNonce": 446369499,
			"isDeleted": false,
			"id": "AqhNa2wx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 40.35073302917431,
			"y": -1116.366392866723,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 1698215515,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482152,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "uIMtCRslcyieREyNlPG5v",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 956,
			"versionNonce": 998645845,
			"isDeleted": false,
			"id": "pTAH00c58KHxKo-V6ZAQp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 858.4184030794902,
			"y": 2082.0605239458223,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 2072503195,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "YczYdsya"
				},
				{
					"id": "QxDBXzJydwR5nhPOHc0_H",
					"type": "arrow"
				},
				{
					"id": "52KxeeB_2jfVpUdsgP7qX",
					"type": "arrow"
				},
				{
					"id": "xXF5V5epUJ1g3V3OjKeT0",
					"type": "arrow"
				}
			],
			"updated": 1710340482152,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 963,
			"versionNonce": 1068137339,
			"isDeleted": false,
			"id": "YczYdsya",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 873.0506357455058,
			"y": 2109.8515395708223,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 99.71990966796875,
			"height": 50,
			"seed": 1033812027,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Connection\nDB",
			"rawText": "Connection DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "pTAH00c58KHxKo-V6ZAQp",
			"originalText": "Connection DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 757,
			"versionNonce": 1122586037,
			"isDeleted": false,
			"id": "M_lnoaoqwAdhjwOaSCOC1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 247.29692344964258,
			"y": 2262.0957056143493,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 425672373,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "2HicTMiH"
				},
				{
					"id": "N-SVnggIFUGxNME3KdPvB",
					"type": "arrow"
				},
				{
					"id": "xXF5V5epUJ1g3V3OjKeT0",
					"type": "arrow"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 753,
			"versionNonce": 895702043,
			"isDeleted": false,
			"id": "2HicTMiH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 264.2491558104824,
			"y": 2289.8867212393493,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 416260117,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "M_lnoaoqwAdhjwOaSCOC1",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 980,
			"versionNonce": 1145032469,
			"isDeleted": false,
			"id": "tXggqRfTthtGIutERt7OE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 838.2352053696632,
			"y": 1823.6688606484704,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1141739253,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "pB9uWOcY"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 975,
			"versionNonce": 2075662523,
			"isDeleted": false,
			"id": "pB9uWOcY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 855.187437730503,
			"y": 1851.4598762734704,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 835315797,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "tXggqRfTthtGIutERt7OE",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1050,
			"versionNonce": 1308566645,
			"isDeleted": false,
			"id": "xEKUjb60YWJdUIXx3wiTi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 850.8045143846737,
			"y": 1842.5162110655774,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1820679515,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "NVMCoDk4"
				},
				{
					"id": "Ro-n7QO9lnSk1wXeH0t9R",
					"type": "arrow"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1044,
			"versionNonce": 1883982171,
			"isDeleted": false,
			"id": "NVMCoDk4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 867.7567467455135,
			"y": 1870.3072266905774,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 742849019,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "xEKUjb60YWJdUIXx3wiTi",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1095,
			"versionNonce": 65850837,
			"isDeleted": false,
			"id": "h_sM3q_7yzrvmUXIr4XoI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 866.1028315653421,
			"y": 1868.9730414405608,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1968855003,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "lYMEXADU"
				},
				{
					"id": "QxDBXzJydwR5nhPOHc0_H",
					"type": "arrow"
				},
				{
					"id": "52KxeeB_2jfVpUdsgP7qX",
					"type": "arrow"
				},
				{
					"id": "RroquzPyEqF7hRsFDVwqy",
					"type": "arrow"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1093,
			"versionNonce": 409953787,
			"isDeleted": false,
			"id": "lYMEXADU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 883.0550639261819,
			"y": 1896.7640570655608,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1972937851,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nWorker",
			"rawText": "Messaging Worker",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "h_sM3q_7yzrvmUXIr4XoI",
			"originalText": "Messaging Worker",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 220,
			"versionNonce": 1964919605,
			"isDeleted": false,
			"id": "yH1oG5jb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 814.6805074474341,
			"y": 1682.1095257618229,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 189.37986755371094,
			"height": 125,
			"seed": 250803189,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"rawText": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"lineHeight": 1.25,
			"baseline": 118
		},
		{
			"type": "arrow",
			"version": 250,
			"versionNonce": 154642421,
			"isDeleted": false,
			"id": "Ro-n7QO9lnSk1wXeH0t9R",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 782.3468307318649,
			"y": 1906.7787602076091,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 47.76866474136784,
			"height": 1.983931622853106,
			"seed": 1799767067,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "sLLyvOxLsUEb8RfECl0nL",
				"gap": 2.87391590153743,
				"focus": 0.4053653775806926
			},
			"endBinding": {
				"elementId": "xEKUjb60YWJdUIXx3wiTi",
				"gap": 20.68901891144094,
				"focus": -0.10726343028734056
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
					47.76866474136784,
					-1.983931622853106
				]
			]
		},
		{
			"type": "arrow",
			"version": 268,
			"versionNonce": 531361461,
			"isDeleted": false,
			"id": "QxDBXzJydwR5nhPOHc0_H",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 960.7595972065916,
			"y": 1984.6061934036736,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 21.505818791729894,
			"height": 91.30053328370855,
			"seed": 928451765,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "h_sM3q_7yzrvmUXIr4XoI",
				"gap": 10.051120713112596,
				"focus": -0.58454080741492
			},
			"endBinding": {
				"elementId": "pTAH00c58KHxKo-V6ZAQp",
				"gap": 6.153797258440136,
				"focus": 0.0319620952097888
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
					-21.505818791729894,
					91.30053328370855
				]
			]
		},
		{
			"type": "arrow",
			"version": 251,
			"versionNonce": 21857653,
			"isDeleted": false,
			"id": "52KxeeB_2jfVpUdsgP7qX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 915.7640280002788,
			"y": 2071.105612160077,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 15.104332755322957,
			"height": 92.82154752789575,
			"seed": 868889979,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "pTAH00c58KHxKo-V6ZAQp",
				"gap": 10.95491178574548,
				"focus": 0.04414809781134893
			},
			"endBinding": {
				"elementId": "h_sM3q_7yzrvmUXIr4XoI",
				"gap": 3.7289919416202792,
				"focus": 0.5354560838413329
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
					-15.104332755322957,
					-92.82154752789575
				]
			]
		},
		{
			"type": "arrow",
			"version": 287,
			"versionNonce": 516465397,
			"isDeleted": false,
			"id": "RroquzPyEqF7hRsFDVwqy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 851.8241161641874,
			"y": 1972.6276551385797,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 470.28490909574293,
			"height": 90.54498216956358,
			"seed": 1864017883,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "h_sM3q_7yzrvmUXIr4XoI",
				"gap": 14.278715401154727,
				"focus": -0.5474443746654334
			},
			"endBinding": {
				"elementId": "IQeWcG72GUbZsNv8rI4N7",
				"gap": 16.58007608366495,
				"focus": -0.7069426771241228
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
					-470.28490909574293,
					90.54498216956358
				]
			]
		},
		{
			"type": "text",
			"version": 302,
			"versionNonce": 1623868379,
			"isDeleted": false,
			"id": "pVOSVUEi",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 655.4554823476308,
			"y": 2072.0693804066836,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 179.83987426757812,
			"height": 100,
			"seed": 1772574043,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"rawText": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "rectangle",
			"version": 1039,
			"versionNonce": 449887061,
			"isDeleted": false,
			"id": "IQeWcG72GUbZsNv8rI4N7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 262.3042639922924,
			"y": 2067.10167950951,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 1994560411,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "fmqEIHgZ"
				},
				{
					"id": "RroquzPyEqF7hRsFDVwqy",
					"type": "arrow"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1138,
			"versionNonce": 1143672955,
			"isDeleted": false,
			"id": "fmqEIHgZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 281.23786368085865,
			"y": 2084.60167950951,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 1512269883,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "IQeWcG72GUbZsNv8rI4N7",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 1119,
			"versionNonce": 875071669,
			"isDeleted": false,
			"id": "WsxVqFZgTxNnz6qYyn8AL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 255.46851736732816,
			"y": 2350.6670235641764,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 771409019,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "lA9wL69B"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1222,
			"versionNonce": 1728661787,
			"isDeleted": false,
			"id": "lA9wL69B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 274.4021170558944,
			"y": 2368.1670235641764,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 1690467611,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "WsxVqFZgTxNnz6qYyn8AL",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "arrow",
			"version": 265,
			"versionNonce": 52890229,
			"isDeleted": false,
			"id": "N-SVnggIFUGxNME3KdPvB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 16.549224310495276,
			"y": 2323.8673183854658,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 223.27166483590918,
			"height": 2.7290081656587972,
			"seed": 99865467,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "dIlG5YT7TAIOZfW21ho-B",
				"gap": 4.999518096236159,
				"focus": 0.1566367043961917
			},
			"endBinding": {
				"elementId": "M_lnoaoqwAdhjwOaSCOC1",
				"gap": 7.476034303238123,
				"focus": -0.10026139913206318
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
					223.27166483590918,
					-2.7290081656587972
				]
			]
		},
		{
			"type": "arrow",
			"version": 271,
			"versionNonce": 1107603765,
			"isDeleted": false,
			"id": "xXF5V5epUJ1g3V3OjKeT0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 386.06310217232993,
			"y": 2321.8128469715775,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 475.9981011657788,
			"height": 125.58728046355282,
			"seed": 109565877,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "M_lnoaoqwAdhjwOaSCOC1",
				"gap": 9.781803722687357,
				"focus": 0.37994339208693256
			},
			"endBinding": {
				"elementId": "pTAH00c58KHxKo-V6ZAQp",
				"gap": 8.583011312202416,
				"focus": -0.6492153310018839
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
					475.9981011657788,
					-125.58728046355282
				]
			]
		},
		{
			"type": "text",
			"version": 74,
			"versionNonce": 1055629173,
			"isDeleted": false,
			"id": "AtpDOMzK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 236.64218981289952,
			"y": 1639.8738258797464,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 91.29991149902344,
			"height": 25,
			"seed": 1545419739,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Stateful!",
			"rawText": "Stateful!",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Stateful!",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 268,
			"versionNonce": 1761360693,
			"isDeleted": false,
			"id": "feGDR9Nl12AX8XQVm9007",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 381.1605866954125,
			"y": 1766.0871469887325,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 160.9409419827985,
			"height": 3.4476322868260922,
			"seed": 1551695131,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354606,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "uhiSgaF3hJs-xQWpTIery",
				"gap": 8.358440417956615,
				"focus": -0.1068178256072861
			},
			"endBinding": {
				"elementId": "YJKxcGnYvToduJhocR0bR",
				"gap": 6.457181594842268,
				"focus": -0.04324378561439553
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
					160.9409419827985,
					3.4476322868260922
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1086,
			"versionNonce": 932309205,
			"isDeleted": false,
			"id": "jgdZZ-B1ZDSWixgTD7V4G",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 256.7382336059543,
			"y": 1809.2741273722108,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 2078190325,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "bww0yBWS"
				},
				{
					"id": "aSdGT1QxBNgX9kIAD9GH_",
					"type": "arrow"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1185,
			"versionNonce": 830307067,
			"isDeleted": false,
			"id": "bww0yBWS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 275.6718332945205,
			"y": 1826.7741273722108,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 152536149,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "jgdZZ-B1ZDSWixgTD7V4G",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 520,
			"versionNonce": 1265108533,
			"isDeleted": false,
			"id": "xA54xn5it8fU4oDoyUue9",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -7.543625780901664,
			"y": 2307.751661784522,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 740525621,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "tfcsCDWz"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 461,
			"versionNonce": 61498267,
			"isDeleted": false,
			"id": "tfcsCDWz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 29.201537182965524,
			"y": 2312.751661784522,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 1788802965,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "xA54xn5it8fU4oDoyUue9",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 679,
			"versionNonce": 2143142357,
			"isDeleted": false,
			"id": "pZ_MunjKKiappXCIlMljA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 204.10647746177222,
			"y": 2853.886039475744,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 199.48828125,
			"height": 1083.2081945178898,
			"seed": 1200579515,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710340504808,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 443,
			"versionNonce": 493959227,
			"isDeleted": false,
			"id": "eDx_lEDm_o6_tIPMn6kNz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -134.31386595795766,
			"y": 2874.463805864829,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 2030122075,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ytijRGDL"
				},
				{
					"id": "kQZiTt8EoxtuHr-ysWGoE",
					"type": "arrow"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 417,
			"versionNonce": 394902773,
			"isDeleted": false,
			"id": "ytijRGDL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -105.98164397309438,
			"y": 2902.254821489829,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.31993103027344,
			"height": 50,
			"seed": 154136827,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nSender",
			"rawText": "Client - Sender",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "eDx_lEDm_o6_tIPMn6kNz",
			"originalText": "Client - Sender",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 687,
			"versionNonce": 1704167995,
			"isDeleted": false,
			"id": "4p8rLOAFl7BIbrVQyIdiC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -126.20870182668301,
			"y": 3502.2113060123543,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1771968923,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "yPTDDPf9"
				},
				{
					"id": "vMfWIOdXhcoPq7L9qO8ca",
					"type": "arrow"
				}
			],
			"updated": 1710340541527,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 674,
			"versionNonce": 1086098139,
			"isDeleted": false,
			"id": "yPTDDPf9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -103.74647495900723,
			"y": 3530.0023216373543,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.05992126464844,
			"height": 50,
			"seed": 931016251,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340541527,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nReceiving",
			"rawText": "Client - Receiving",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "4p8rLOAFl7BIbrVQyIdiC",
			"originalText": "Client - Receiving",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 815,
			"versionNonce": 805868987,
			"isDeleted": false,
			"id": "Dsga98o_eXU8uAAvWn_D5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -113.85007419751048,
			"y": 3721.072538467954,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1169338075,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "FXF77hil"
				},
				{
					"id": "L8kIOEydevjFQucMYjhNT",
					"type": "arrow"
				}
			],
			"updated": 1710340513544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 832,
			"versionNonce": 528754267,
			"isDeleted": false,
			"id": "FXF77hil",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -104.6478342072761,
			"y": 3748.863554092954,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.57989501953125,
			"height": 50,
			"seed": 1724783483,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340513544,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nConnections",
			"rawText": "Client - Connections",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Dsga98o_eXU8uAAvWn_D5",
			"originalText": "Client - Connections",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 598,
			"versionNonce": 1269448219,
			"isDeleted": false,
			"id": "xhxo5bFg5tDWzaKQS3J7g",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 230.24863404204234,
			"y": 2881.580505083579,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1997730843,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "CKTFiSLg"
				},
				{
					"id": "kQZiTt8EoxtuHr-ysWGoE",
					"type": "arrow"
				},
				{
					"id": "LU5QtBgIsGCw7ZhK95xqn",
					"type": "arrow"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 590,
			"versionNonce": 1236567317,
			"isDeleted": false,
			"id": "CKTFiSLg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 247.20086640288218,
			"y": 2909.371520708579,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 645118139,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "xhxo5bFg5tDWzaKQS3J7g",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 835,
			"versionNonce": 643158043,
			"isDeleted": false,
			"id": "XyUAFfJa6FurCwUrzx-bl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 243.361610673317,
			"y": 3503.5018333561043,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 43182427,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "T5F3kLAD"
				},
				{
					"id": "vMfWIOdXhcoPq7L9qO8ca",
					"type": "arrow"
				},
				{
					"id": "07UFXHEuXjFH2keKAcGDo",
					"type": "arrow"
				}
			],
			"updated": 1710340541527,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 829,
			"versionNonce": 553325755,
			"isDeleted": false,
			"id": "T5F3kLAD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 260.31384303415683,
			"y": 3531.2928489811043,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1086522875,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340541527,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "XyUAFfJa6FurCwUrzx-bl",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1102,
			"versionNonce": 1367611771,
			"isDeleted": false,
			"id": "53baJjARnf26T6BGy0EW_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 534.9895730376397,
			"y": 2880.210011949464,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1208389275,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "2bamgdA0"
				},
				{
					"id": "LU5QtBgIsGCw7ZhK95xqn",
					"type": "arrow"
				},
				{
					"id": "4jQn9m_UiWYekcNDt5VKy",
					"type": "arrow"
				}
			],
			"updated": 1710340648765,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1097,
			"versionNonce": 315417531,
			"isDeleted": false,
			"id": "2bamgdA0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 551.9418053984796,
			"y": 2908.001027574464,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 2064646971,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340642967,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nDB",
			"rawText": "Messaging DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "53baJjARnf26T6BGy0EW_",
			"originalText": "Messaging DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 340,
			"versionNonce": 2070319099,
			"isDeleted": false,
			"id": "Vn0Hcl1h",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 108.37168091704234,
			"y": 2729.204284380454,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 503.319580078125,
			"height": 25,
			"seed": 1111614427,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WebSockets - Change Data Capture (DB Triggers)",
			"rawText": "WebSockets - Change Data Capture (DB Triggers)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "WebSockets - Change Data Capture (DB Triggers)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1045,
			"versionNonce": 152921269,
			"isDeleted": false,
			"id": "kQZiTt8EoxtuHr-ysWGoE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1.1802746670423545,
			"y": 2929.653503130454,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 226.43359375,
			"height": 0.8085937499995453,
			"seed": 1437511803,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "eDx_lEDm_o6_tIPMn6kNz",
				"gap": 6.509765625,
				"focus": 0.04045795120895977
			},
			"endBinding": {
				"elementId": "xhxo5bFg5tDWzaKQS3J7g",
				"gap": 2.634765625,
				"focus": 0.06921204270980312
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
					226.43359375,
					0.8085937499995453
				]
			]
		},
		{
			"type": "text",
			"version": 421,
			"versionNonce": 967366811,
			"isDeleted": false,
			"id": "oDKjLcNC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -39.96692485818312,
			"y": 2984.9100558446307,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 213.85980224609375,
			"height": 25,
			"seed": 1192814875,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Persistant Connection",
			"rawText": "Persistant Connection",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Persistant Connection",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1462,
			"versionNonce": 1091494453,
			"isDeleted": false,
			"id": "vMfWIOdXhcoPq7L9qO8ca",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 10.539345048317003,
			"y": 3555.751759281078,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 231.822265625,
			"height": 0.5890685365015997,
			"seed": 1274219963,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "4p8rLOAFl7BIbrVQyIdiC",
				"gap": 7.763671875,
				"focus": 0.010685187612612574
			},
			"endBinding": {
				"elementId": "XyUAFfJa6FurCwUrzx-bl",
				"gap": 1,
				"focus": -0.004048668211233235
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
					231.822265625,
					0.5890685365015997
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1019,
			"versionNonce": 128041109,
			"isDeleted": false,
			"id": "HeRNJaNFiTUySC2j5uhWX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 889.4909737772125,
			"y": 3055.831406785816,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 33.8134530170904,
			"height": 393.5764538542,
			"seed": 1197448795,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "AU4ACXphJow2ZhFiL1Zcc",
					"type": "arrow"
				},
				{
					"id": "1BZeMWSdAXDh7IyiKbXnG",
					"type": "arrow"
				},
				{
					"id": "tyuALMhwC1cbPFzq8P56D",
					"type": "arrow"
				},
				{
					"id": "eiYgUj4Z_pZb3c7EqVhp1",
					"type": "arrow"
				}
			],
			"updated": 1710340749306,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 442,
			"versionNonce": 861515227,
			"isDeleted": false,
			"id": "pnkpVbviieFUBc103UlqP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -33.24160033295766,
			"y": 2911.036315630454,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 250217371,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "65NX4PQl"
				}
			],
			"updated": 1710340482153,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 381,
			"versionNonce": 180678997,
			"isDeleted": false,
			"id": "65NX4PQl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3.503562630909528,
			"y": 2916.036315630454,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 1606211643,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482153,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "pnkpVbviieFUBc103UlqP",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 629,
			"versionNonce": 16476827,
			"isDeleted": false,
			"id": "m2LZaBctvDbXKuSYCmKID",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -17.27315495168301,
			"y": 3539.5904564029793,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 76290267,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "98rVwHSq"
				}
			],
			"updated": 1710340541527,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 570,
			"versionNonce": 2030657339,
			"isDeleted": false,
			"id": "98rVwHSq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 19.472008012184176,
			"y": 3544.5904564029793,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 451560827,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340541527,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "m2LZaBctvDbXKuSYCmKID",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1251,
			"versionNonce": 623260533,
			"isDeleted": false,
			"id": "IJrk4umU3qwl_ZnFsYgm7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1034.9502626318044,
			"y": 3717.584242443875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1780080155,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "MIZphPfH"
				},
				{
					"id": "XGXoIjCyQNLm2lQ4DHB8k",
					"type": "arrow"
				},
				{
					"id": "6k_d291ZD3UReSJGpdWGv",
					"type": "arrow"
				},
				{
					"id": "Ot-y_owCCuHNPKDxmgs-r",
					"type": "arrow"
				}
			],
			"updated": 1710340565134,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1258,
			"versionNonce": 559545557,
			"isDeleted": false,
			"id": "MIZphPfH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1049.58249529782,
			"y": 3745.375258068875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 99.71990966796875,
			"height": 50,
			"seed": 755851963,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340565134,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Connection\nDB",
			"rawText": "Connection DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "IJrk4umU3qwl_ZnFsYgm7",
			"originalText": "Connection DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 904,
			"versionNonce": 856770267,
			"isDeleted": false,
			"id": "82_AxCEklCTxQaim8LCvb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 244.80647052800316,
			"y": 3716.937913114626,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 476533595,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ZgrtClUv"
				},
				{
					"id": "L8kIOEydevjFQucMYjhNT",
					"type": "arrow"
				},
				{
					"id": "Ot-y_owCCuHNPKDxmgs-r",
					"type": "arrow"
				}
			],
			"updated": 1710340508611,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 900,
			"versionNonce": 1553576827,
			"isDeleted": false,
			"id": "ZgrtClUv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 261.758702888843,
			"y": 3744.728928739626,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 947531771,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340508611,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "82_AxCEklCTxQaim8LCvb",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1277,
			"versionNonce": 2050845205,
			"isDeleted": false,
			"id": "cxhJkTrdVyccRn5UlhE0f",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1014.7670649219776,
			"y": 3459.192579146523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1397258395,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "R2uuLIuD"
				},
				{
					"id": "eiYgUj4Z_pZb3c7EqVhp1",
					"type": "arrow"
				},
				{
					"id": "07UFXHEuXjFH2keKAcGDo",
					"type": "arrow"
				}
			],
			"updated": 1710340799699,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1269,
			"versionNonce": 190683413,
			"isDeleted": false,
			"id": "R2uuLIuD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1031.7192972828175,
			"y": 3486.983594771523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1518644539,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340565134,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "cxhJkTrdVyccRn5UlhE0f",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1322,
			"versionNonce": 1121169013,
			"isDeleted": false,
			"id": "jtb-zVnceiUjXkQFjMXo_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1027.336373936988,
			"y": 3478.03992956363,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1636912603,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ETOeFIrp"
				},
				{
					"id": "eiYgUj4Z_pZb3c7EqVhp1",
					"type": "arrow"
				}
			],
			"updated": 1710340565134,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1316,
			"versionNonce": 1101010901,
			"isDeleted": false,
			"id": "ETOeFIrp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1044.2886062978278,
			"y": 3505.83094518863,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1803606651,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340565134,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "jtb-zVnceiUjXkQFjMXo_",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1389,
			"versionNonce": 1591862933,
			"isDeleted": false,
			"id": "fUyb0i0AK_lZOYm52tXT0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1042.6346911176565,
			"y": 3504.4967599386136,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1964364571,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "vBp9lGus"
				},
				{
					"id": "XGXoIjCyQNLm2lQ4DHB8k",
					"type": "arrow"
				},
				{
					"id": "6k_d291ZD3UReSJGpdWGv",
					"type": "arrow"
				},
				{
					"id": "07UFXHEuXjFH2keKAcGDo",
					"type": "arrow"
				}
			],
			"updated": 1710340565134,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1387,
			"versionNonce": 192039925,
			"isDeleted": false,
			"id": "vBp9lGus",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1059.5869234784964,
			"y": 3532.2877755636136,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1052948411,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340565134,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nWorker",
			"rawText": "Messaging Worker",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "fUyb0i0AK_lZOYm52tXT0",
			"originalText": "Messaging Worker",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 492,
			"versionNonce": 1884029179,
			"isDeleted": false,
			"id": "js4vY8qP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 991.2123669997486,
			"y": 3317.633244259875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 189.37986755371094,
			"height": 125,
			"seed": 1453983835,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "eiYgUj4Z_pZb3c7EqVhp1",
					"type": "arrow"
				}
			],
			"updated": 1710340670974,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"rawText": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"lineHeight": 1.25,
			"baseline": 118
		},
		{
			"type": "arrow",
			"version": 1582,
			"versionNonce": 1281972277,
			"isDeleted": false,
			"id": "eiYgUj4Z_pZb3c7EqVhp1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 999.2463207370886,
			"y": 3510.5555735659686,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 87.87225323517328,
			"height": 53.0108021355004,
			"seed": 1654539515,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "cxhJkTrdVyccRn5UlhE0f",
				"gap": 15.520744184889054,
				"focus": -0.5108272545190039
			},
			"endBinding": {
				"elementId": "HeRNJaNFiTUySC2j5uhWX",
				"gap": 8.136910790452475,
				"focus": 0.9755322018974788
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
					-87.87225323517328,
					-53.0108021355004
				]
			]
		},
		{
			"type": "arrow",
			"version": 1164,
			"versionNonce": 184882613,
			"isDeleted": false,
			"id": "XGXoIjCyQNLm2lQ4DHB8k",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1137.291456758906,
			"y": 3620.1299119017262,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 21.505818791730007,
			"height": 91.30053328370877,
			"seed": 706866587,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "fUyb0i0AK_lZOYm52tXT0",
				"gap": 10.051120713112596,
				"focus": -0.5845408074149211
			},
			"endBinding": {
				"elementId": "IJrk4umU3qwl_ZnFsYgm7",
				"gap": 6.153797258440136,
				"focus": 0.03196209520978681
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
					-21.505818791730007,
					91.30053328370877
				]
			]
		},
		{
			"type": "arrow",
			"version": 1147,
			"versionNonce": 130608245,
			"isDeleted": false,
			"id": "6k_d291ZD3UReSJGpdWGv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1092.2958875525933,
			"y": 3706.6293306581297,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 15.104332755322957,
			"height": 92.82154752789575,
			"seed": 1617396283,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "IJrk4umU3qwl_ZnFsYgm7",
				"gap": 10.95491178574548,
				"focus": 0.044148097811352045
			},
			"endBinding": {
				"elementId": "fUyb0i0AK_lZOYm52tXT0",
				"gap": 3.7289919416202792,
				"focus": 0.5354560838413329
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
					-15.104332755322957,
					-92.82154752789575
				]
			]
		},
		{
			"type": "arrow",
			"version": 1227,
			"versionNonce": 219550517,
			"isDeleted": false,
			"id": "07UFXHEuXjFH2keKAcGDo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 994.5927256183185,
			"y": 3540.9628117737393,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 631.1859641428107,
			"height": 21.172282158491726,
			"seed": 777093851,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "cxhJkTrdVyccRn5UlhE0f",
				"gap": 20.174339303659167,
				"focus": -0.47565310499843727
			},
			"endBinding": {
				"elementId": "frAoyge_lFBAudH214v_X",
				"gap": 25.702291917096318,
				"focus": -1.3826829660678186
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
					-631.1859641428107,
					21.172282158491726
				]
			]
		},
		{
			"type": "text",
			"version": 596,
			"versionNonce": 1407492181,
			"isDeleted": false,
			"id": "nVm5JSu1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 831.9873418999452,
			"y": 3707.5930989047365,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 179.83987426757812,
			"height": 100,
			"seed": 2087874427,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340565134,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"rawText": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "rectangle",
			"version": 1203,
			"versionNonce": 1890566107,
			"isDeleted": false,
			"id": "frAoyge_lFBAudH214v_X",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 255.84810338815345,
			"y": 3587.452467292274,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 2097989659,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "qZMGjzCB"
				},
				{
					"id": "07UFXHEuXjFH2keKAcGDo",
					"type": "arrow"
				}
			],
			"updated": 1710340541527,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1303,
			"versionNonce": 335164981,
			"isDeleted": false,
			"id": "qZMGjzCB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 274.7817030767197,
			"y": 3604.952467292274,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 1980959931,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340583270,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "frAoyge_lFBAudH214v_X",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 1267,
			"versionNonce": 865281691,
			"isDeleted": false,
			"id": "hG3vedIZ-BTqv3HyVMRrc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 252.9780644456888,
			"y": 3805.509231064453,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 1260895579,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Rr0Zoc4N"
				}
			],
			"updated": 1710340508611,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1371,
			"versionNonce": 69183381,
			"isDeleted": false,
			"id": "Rr0Zoc4N",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 271.91166413425503,
			"y": 3823.009231064453,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 1201494523,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340583270,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "hG3vedIZ-BTqv3HyVMRrc",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "arrow",
			"version": 784,
			"versionNonce": 635624117,
			"isDeleted": false,
			"id": "L8kIOEydevjFQucMYjhNT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 20.133818898725735,
			"y": 3780.9430412749657,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 217.19661732603936,
			"height": 4.350245616549728,
			"seed": 678847131,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Dsga98o_eXU8uAAvWn_D5",
				"gap": 4.999518096236216,
				"focus": 0.1566367043962002
			},
			"endBinding": {
				"elementId": "82_AxCEklCTxQaim8LCvb",
				"gap": 7.476034303238066,
				"focus": -0.10026139913206321
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
					217.19661732603936,
					-4.350245616549728
				]
			]
		},
		{
			"type": "arrow",
			"version": 1078,
			"versionNonce": 2142859637,
			"isDeleted": false,
			"id": "Ot-y_owCCuHNPKDxmgs-r",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 383.57264925069046,
			"y": 3791.6861366140092,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 642.7946020689116,
			"height": 12.361730653327868,
			"seed": 1717917499,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "82_AxCEklCTxQaim8LCvb",
				"gap": 9.7818037226873,
				"focus": 0.37994339208693956
			},
			"endBinding": {
				"elementId": "IJrk4umU3qwl_ZnFsYgm7",
				"gap": 8.583011312202416,
				"focus": -0.649215331001883
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
					642.7946020689116,
					12.361730653327868
				]
			]
		},
		{
			"type": "text",
			"version": 138,
			"versionNonce": 1976154619,
			"isDeleted": false,
			"id": "S1iiARlW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 223.0730525774859,
			"y": 2803.932191639985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 91.29991149902344,
			"height": 25,
			"seed": 1070381019,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340482154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Stateful!",
			"rawText": "Stateful!",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Stateful!",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 460,
			"versionNonce": 2116655349,
			"isDeleted": false,
			"id": "LU5QtBgIsGCw7ZhK95xqn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 367.591449459999,
			"y": 2930.197075033486,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 160.94094198279868,
			"height": 3.573439854631488,
			"seed": 46072955,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354607,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "xhxo5bFg5tDWzaKQS3J7g",
				"gap": 8.358440417956672,
				"focus": -0.10681782560728609
			},
			"endBinding": {
				"elementId": "53baJjARnf26T6BGy0EW_",
				"gap": 6.457181594842041,
				"focus": -0.04324378561439541
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
					160.94094198279868,
					3.573439854631488
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1178,
			"versionNonce": 303481499,
			"isDeleted": false,
			"id": "vzYAwCCnCJDnPlVSdmOPp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 245.14450985966596,
			"y": 2960.378840083234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 385793307,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ZVqpVkEk"
				}
			],
			"updated": 1710340482154,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1277,
			"versionNonce": 625994997,
			"isDeleted": false,
			"id": "ZVqpVkEk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 264.0781095482322,
			"y": 2977.878840083234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 1207853499,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340583270,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "vzYAwCCnCJDnPlVSdmOPp",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 670,
			"versionNonce": 1758355515,
			"isDeleted": false,
			"id": "kqCNM0jEBEnMDPZFgvUWF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3.9590311926712047,
			"y": 3765.290996930026,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 1323332187,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "PHTokAvB"
				}
			],
			"updated": 1710340513544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 611,
			"versionNonce": 36479195,
			"isDeleted": false,
			"id": "PHTokAvB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 32.78613177119598,
			"y": 3770.290996930026,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 477589243,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340513544,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "kqCNM0jEBEnMDPZFgvUWF",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1581,
			"versionNonce": 1762914747,
			"isDeleted": false,
			"id": "nEtaOs5n1RWBSYTQ_jl_O",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 807.5508743075839,
			"y": 2855.339685706672,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1115409819,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "h8ZJRA8m"
				}
			],
			"updated": 1710340590246,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1575,
			"versionNonce": 1455686235,
			"isDeleted": false,
			"id": "h8ZJRA8m",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 824.5031066684237,
			"y": 2883.130701331672,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 310731323,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340590246,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "nEtaOs5n1RWBSYTQ_jl_O",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1629,
			"versionNonce": 2118268603,
			"isDeleted": false,
			"id": "meLfgkXndnLUFWNHZo9sh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 820.1201833225941,
			"y": 2874.187036123779,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 565404379,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ua1rzZhN"
				},
				{
					"id": "4jQn9m_UiWYekcNDt5VKy",
					"type": "arrow"
				}
			],
			"updated": 1710340648765,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1622,
			"versionNonce": 1401251739,
			"isDeleted": false,
			"id": "ua1rzZhN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 837.072415683434,
			"y": 2901.978051748779,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1754812283,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340590246,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "meLfgkXndnLUFWNHZo9sh",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1700,
			"versionNonce": 963815003,
			"isDeleted": false,
			"id": "9O1E5u6g1f-PCdKjMhcR9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 835.4185005032627,
			"y": 2900.6438664987627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 695642139,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "jNbRUxH8"
				},
				{
					"id": "vvlTzgMHNiB7f8kgW54wm",
					"type": "arrow"
				},
				{
					"id": "ARjQ_OhB4r1tssLEsuBVt",
					"type": "arrow"
				},
				{
					"id": "AU4ACXphJow2ZhFiL1Zcc",
					"type": "arrow"
				},
				{
					"id": "1BZeMWSdAXDh7IyiKbXnG",
					"type": "arrow"
				},
				{
					"id": "tyuALMhwC1cbPFzq8P56D",
					"type": "arrow"
				}
			],
			"updated": 1710340711721,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1700,
			"versionNonce": 2006587643,
			"isDeleted": false,
			"id": "jNbRUxH8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 867.9707160794346,
			"y": 2928.4348821237627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 63.87994384765625,
			"height": 50,
			"seed": 977333435,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340652631,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Group\nWorker",
			"rawText": "Group Worker",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "9O1E5u6g1f-PCdKjMhcR9",
			"originalText": "Group Worker",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1202,
			"versionNonce": 1418183707,
			"isDeleted": false,
			"id": "l83FczhU1a8AIOegDNVgN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1075.356942254506,
			"y": 2872.6012409883256,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1638848117,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "879vdG6O"
				},
				{
					"id": "vvlTzgMHNiB7f8kgW54wm",
					"type": "arrow"
				},
				{
					"id": "ARjQ_OhB4r1tssLEsuBVt",
					"type": "arrow"
				}
			],
			"updated": 1710340660985,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1209,
			"versionNonce": 1547480053,
			"isDeleted": false,
			"id": "879vdG6O",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1111.509156304799,
			"y": 2900.3922566133256,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.67994689941406,
			"height": 50,
			"seed": 718684117,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340612671,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Group\nDB",
			"rawText": "Group\nDB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "l83FczhU1a8AIOegDNVgN",
			"originalText": "Group\nDB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 88,
			"versionNonce": 1691912693,
			"isDeleted": false,
			"id": "4jQn9m_UiWYekcNDt5VKy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 675.4260703027809,
			"y": 2936.9434032870213,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 123.76281724332932,
			"height": 2.3920732081114693,
			"seed": 461939093,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "53baJjARnf26T6BGy0EW_",
				"gap": 11.452122265141156,
				"focus": 0.10011967823059706
			},
			"endBinding": {
				"elementId": "meLfgkXndnLUFWNHZo9sh",
				"gap": 20.93129577648392,
				"focus": -0.10959466738559986
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
					123.76281724332932,
					-2.3920732081114693
				]
			]
		},
		{
			"type": "arrow",
			"version": 69,
			"versionNonce": 2024202869,
			"isDeleted": false,
			"id": "vvlTzgMHNiB7f8kgW54wm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 973.4902965969011,
			"y": 2934.4992476140364,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 96.99615047448992,
			"height": 2.1763029964936322,
			"seed": 1602115131,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "9O1E5u6g1f-PCdKjMhcR9",
				"gap": 9.08742109363834,
				"focus": -0.3186828408520803
			},
			"endBinding": {
				"elementId": "l83FczhU1a8AIOegDNVgN",
				"gap": 4.870495183115054,
				"focus": -0.09908909889874554
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
					96.99615047448992,
					-2.1763029964936322
				]
			]
		},
		{
			"type": "arrow",
			"version": 70,
			"versionNonce": 191793461,
			"isDeleted": false,
			"id": "ARjQ_OhB4r1tssLEsuBVt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1068.7677257305704,
			"y": 2960.5181589943368,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 97.53929617959773,
			"height": 1.7150011647581778,
			"seed": 472576437,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "l83FczhU1a8AIOegDNVgN",
				"gap": 6.589216523935647,
				"focus": -0.6282081862932514
			},
			"endBinding": {
				"elementId": "9O1E5u6g1f-PCdKjMhcR9",
				"gap": 6.825554047709943,
				"focus": 0.1864115282712291
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
					-97.53929617959773,
					1.7150011647581778
				]
			]
		},
		{
			"type": "arrow",
			"version": 63,
			"versionNonce": 420990517,
			"isDeleted": false,
			"id": "AU4ACXphJow2ZhFiL1Zcc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 906.5606090585839,
			"y": 3016.503088557126,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0.2752930286162609,
			"height": 37.030632524952125,
			"seed": 775975579,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "9O1E5u6g1f-PCdKjMhcR9",
				"gap": 10.27719080836323,
				"focus": -0.10971443860528153
			},
			"endBinding": {
				"elementId": "HeRNJaNFiTUySC2j5uhWX",
				"gap": 2.2976857037378977,
				"focus": -0.08668781546191687
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
					-0.2752930286162609,
					37.030632524952125
				]
			]
		},
		{
			"type": "arrow",
			"version": 123,
			"versionNonce": 31950069,
			"isDeleted": false,
			"id": "1BZeMWSdAXDh7IyiKbXnG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 894.5556009052766,
			"y": 3016.9123079239876,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0.2752930286162609,
			"height": 37.030632524952125,
			"seed": 519188635,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "9O1E5u6g1f-PCdKjMhcR9",
				"gap": 10.686410175224864,
				"focus": 0.07525945915550264
			},
			"endBinding": {
				"elementId": "HeRNJaNFiTUySC2j5uhWX",
				"gap": 1.888466336876263,
				"focus": -0.7400448715215723
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
					-0.2752930286162609,
					37.030632524952125
				]
			]
		},
		{
			"type": "arrow",
			"version": 117,
			"versionNonce": 164137909,
			"isDeleted": false,
			"id": "tyuALMhwC1cbPFzq8P56D",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 921.0134930609385,
			"y": 3015.855777922271,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0.2752930286162609,
			"height": 37.030632524952125,
			"seed": 1701959835,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354608,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "9O1E5u6g1f-PCdKjMhcR9",
				"gap": 9.629880173508354,
				"focus": -0.33238763766587404
			},
			"endBinding": {
				"elementId": "HeRNJaNFiTUySC2j5uhWX",
				"gap": 2.944996338592773,
				"focus": 0.6998291340255278
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
					-0.2752930286162609,
					37.030632524952125
				]
			]
		},
		{
			"type": "text",
			"version": 576,
			"versionNonce": 133143317,
			"isDeleted": false,
			"id": "1ImYYPot",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 990.3051999378258,
			"y": 2756.551023870131,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 236.1798553466797,
			"height": 100,
			"seed": 1988636245,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710340736099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    group_id: {send}\n    user_id: [{rec}, {}]\n}",
			"rawText": "{\n    group_id: {send}\n    user_id: [{rec}, {}]\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    group_id: {send}\n    user_id: [{rec}, {}]\n}",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "rectangle",
			"version": 980,
			"versionNonce": 1319777819,
			"isDeleted": false,
			"id": "gKFY14YRNyFzJXzNy0YPB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 177.25318011760362,
			"y": 5312.872048896727,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 199.48828125,
			"height": 505.5207262086258,
			"seed": 1123896123,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710347292866,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 683,
			"versionNonce": 698080373,
			"isDeleted": false,
			"id": "TpUOWnankyEZ1rcjG7qKP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -161.16716330212626,
			"y": 4755.7623469765485,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 759573467,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "6rBTIXIf"
				},
				{
					"id": "kWKyt8Ixk4Mh_IX9ryLVd",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 657,
			"versionNonce": 993166805,
			"isDeleted": false,
			"id": "6rBTIXIf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -132.83494131726297,
			"y": 4783.5533626015485,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.31993103027344,
			"height": 50,
			"seed": 1760163963,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nSender",
			"rawText": "Client - Sender",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "TpUOWnankyEZ1rcjG7qKP",
			"originalText": "Client - Sender",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 927,
			"versionNonce": 758174869,
			"isDeleted": false,
			"id": "69TfVdKYw4D5dueEhFEoO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -153.0619991708516,
			"y": 5383.509847124074,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1672163611,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "eJolWrD0"
				},
				{
					"id": "ITh7Blt9fY0AU6CFYh6XB",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 914,
			"versionNonce": 1303607797,
			"isDeleted": false,
			"id": "eJolWrD0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -130.59977230317583,
			"y": 5411.300862749074,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.05992126464844,
			"height": 50,
			"seed": 788288955,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nReceiving",
			"rawText": "Client - Receiving",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "69TfVdKYw4D5dueEhFEoO",
			"originalText": "Client - Receiving",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1055,
			"versionNonce": 282804405,
			"isDeleted": false,
			"id": "UXu_Ako2t1TBflS5XvAAK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -140.70337154167908,
			"y": 5602.371079579674,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 167765595,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "d5tzzYtG"
				},
				{
					"id": "lwGcFXa_HeILcqRnb0A6s",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1072,
			"versionNonce": 91972117,
			"isDeleted": false,
			"id": "d5tzzYtG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -131.5011315514447,
			"y": 5630.162095204674,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.57989501953125,
			"height": 50,
			"seed": 730358523,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nConnections",
			"rawText": "Client - Connections",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "UXu_Ako2t1TBflS5XvAAK",
			"originalText": "Client - Connections",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 838,
			"versionNonce": 60793045,
			"isDeleted": false,
			"id": "KJaiXe56W0d690g45W6W4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 203.39533669787374,
			"y": 4762.8790461952985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1276660635,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "1PtwBLQU"
				},
				{
					"id": "kWKyt8Ixk4Mh_IX9ryLVd",
					"type": "arrow"
				},
				{
					"id": "2tSp7E2kLD5CA--dcMgdy",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 836,
			"versionNonce": 1015850709,
			"isDeleted": false,
			"id": "1PtwBLQU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 234.12756020861593,
			"y": 4790.6700618202985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 67.51992797851562,
			"height": 50,
			"seed": 1877090363,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347302303,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Send\nService",
			"rawText": "Send Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "KJaiXe56W0d690g45W6W4",
			"originalText": "Send Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1075,
			"versionNonce": 1023544917,
			"isDeleted": false,
			"id": "8FDuax6UPCOJNDZSVfCv6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 216.5083133291484,
			"y": 5384.800374467824,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1892180187,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "thi4UGsH"
				},
				{
					"id": "ITh7Blt9fY0AU6CFYh6XB",
					"type": "arrow"
				},
				{
					"id": "_GICeX7jkhDppsX2gvQ1L",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1078,
			"versionNonce": 531810907,
			"isDeleted": false,
			"id": "thi4UGsH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 245.37053409330855,
			"y": 5412.591390092824,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 71.25993347167969,
			"height": 50,
			"seed": 1214090619,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347309053,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Receive\nService",
			"rawText": "Receive Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "8FDuax6UPCOJNDZSVfCv6",
			"originalText": "Receive Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1342,
			"versionNonce": 513397365,
			"isDeleted": false,
			"id": "1H6AUMJ1Mm7Al0IdwdIF7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 508.13627569347113,
			"y": 4761.508553061183,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 434382363,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "3YhJcgHt"
				},
				{
					"id": "2tSp7E2kLD5CA--dcMgdy",
					"type": "arrow"
				},
				{
					"id": "q_S3Qhsh370TcpOknwkk0",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1337,
			"versionNonce": 151108565,
			"isDeleted": false,
			"id": "3YhJcgHt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 525.088508054311,
			"y": 4789.299568686183,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 2085530299,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nDB",
			"rawText": "Messaging DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "1H6AUMJ1Mm7Al0IdwdIF7",
			"originalText": "Messaging DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 609,
			"versionNonce": 216369211,
			"isDeleted": false,
			"id": "uzjTTuDb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -69.83093754113781,
			"y": 4406.462186231343,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 503.319580078125,
			"height": 25,
			"seed": 71277403,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347797224,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WebSockets - Change Data Capture (DB Triggers)",
			"rawText": "WebSockets - Change Data Capture (DB Triggers)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "WebSockets - Change Data Capture (DB Triggers)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1767,
			"versionNonce": 2132427829,
			"isDeleted": false,
			"id": "kWKyt8Ixk4Mh_IX9ryLVd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -25.673022677126255,
			"y": 4810.952044242174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 226.43359375,
			"height": 0.80859375,
			"seed": 235501563,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "TpUOWnankyEZ1rcjG7qKP",
				"gap": 6.509765625000014,
				"focus": 0.04045795120897413
			},
			"endBinding": {
				"elementId": "KJaiXe56W0d690g45W6W4",
				"gap": 2.634765625,
				"focus": 0.06921204270977468
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
					226.43359375,
					0.80859375
				]
			]
		},
		{
			"type": "text",
			"version": 661,
			"versionNonce": 251570517,
			"isDeleted": false,
			"id": "kUsXcFbd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -66.82022220235172,
			"y": 4866.20859695635,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 213.85980224609375,
			"height": 25,
			"seed": 1202634907,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Persistant Connection",
			"rawText": "Persistant Connection",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Persistant Connection",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 2184,
			"versionNonce": 1474298293,
			"isDeleted": false,
			"id": "ITh7Blt9fY0AU6CFYh6XB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -16.313952295851593,
			"y": 5437.050300392799,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 231.822265625,
			"height": 0.589068536501145,
			"seed": 2061628731,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "69TfVdKYw4D5dueEhFEoO",
				"gap": 7.763671875000014,
				"focus": 0.010685187612612572
			},
			"endBinding": {
				"elementId": "8FDuax6UPCOJNDZSVfCv6",
				"gap": 1,
				"focus": -0.004048668211233235
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
					231.822265625,
					0.589068536501145
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1259,
			"versionNonce": 1474959381,
			"isDeleted": false,
			"id": "cgcwOGOyWw-dn1Sp-ucnT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 862.6376764330439,
			"y": 4937.129947897536,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 33.8134530170904,
			"height": 393.5764538542,
			"seed": 386242011,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "lXXcrSOlhRGC3t7RYLGLt",
					"type": "arrow"
				},
				{
					"id": "e8ur6VscEjurejeoQfuZJ",
					"type": "arrow"
				},
				{
					"id": "IBEOx62fd-ZYoGsCqrLuj",
					"type": "arrow"
				},
				{
					"id": "LtVsgDxiWmnLM2kwbSpGs",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 869,
			"versionNonce": 1693381045,
			"isDeleted": false,
			"id": "YCrjPBMHE_mhPCSIN2U2c",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -44.12645229585161,
			"y": 5420.888997514699,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 1111228347,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "VEH8JJzm"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 810,
			"versionNonce": 1576071957,
			"isDeleted": false,
			"id": "VEH8JJzm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -7.381289331984419,
			"y": 5425.888997514699,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 733630555,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "YCrjPBMHE_mhPCSIN2U2c",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1493,
			"versionNonce": 1325636885,
			"isDeleted": false,
			"id": "aPu0vnOtenHZRkF9tlYBz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1008.0969652876361,
			"y": 5598.882783555595,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1046842619,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "yXaMCB8S"
				},
				{
					"id": "Phd7rFMN3RKa-INKRN7TX",
					"type": "arrow"
				},
				{
					"id": "2ChkXMnzWmbFk9RP8oojE",
					"type": "arrow"
				},
				{
					"id": "5QUGgGiwXsc2M4YBxZksL",
					"type": "arrow"
				}
			],
			"updated": 1710347269622,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1499,
			"versionNonce": 852873205,
			"isDeleted": false,
			"id": "yXaMCB8S",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1022.7291979536517,
			"y": 5626.673799180595,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 99.71990966796875,
			"height": 50,
			"seed": 499135899,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347269622,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Connection\nDB",
			"rawText": "Connection DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "aPu0vnOtenHZRkF9tlYBz",
			"originalText": "Connection DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1144,
			"versionNonce": 1420649973,
			"isDeleted": false,
			"id": "uvHtpvPlDjlDSnbPowvfR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 217.95317318383456,
			"y": 5598.236454226346,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1492961851,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "DKaH4n2D"
				},
				{
					"id": "lwGcFXa_HeILcqRnb0A6s",
					"type": "arrow"
				},
				{
					"id": "5QUGgGiwXsc2M4YBxZksL",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1141,
			"versionNonce": 749483957,
			"isDeleted": false,
			"id": "DKaH4n2D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 246.81539394799472,
			"y": 5626.027469851346,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 71.25993347167969,
			"height": 50,
			"seed": 1962789595,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347312808,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Receive\nService",
			"rawText": "Receive Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "uvHtpvPlDjlDSnbPowvfR",
			"originalText": "Receive Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1519,
			"versionNonce": 2056009429,
			"isDeleted": false,
			"id": "KjrLca8qoZWtYqytFfdLP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 987.9137675778093,
			"y": 5340.4911202582425,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 911587195,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "kTL6R4ew"
				},
				{
					"id": "LtVsgDxiWmnLM2kwbSpGs",
					"type": "arrow"
				},
				{
					"id": "_GICeX7jkhDppsX2gvQ1L",
					"type": "arrow"
				}
			],
			"updated": 1710347269622,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1511,
			"versionNonce": 755388853,
			"isDeleted": false,
			"id": "kTL6R4ew",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1004.8659999386491,
			"y": 5368.2821358832425,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 726077467,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347269622,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "KjrLca8qoZWtYqytFfdLP",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1564,
			"versionNonce": 1813795605,
			"isDeleted": false,
			"id": "gT_9kRaKnYwMI1vK8SMPE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1000.4830765928195,
			"y": 5359.3384706753495,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1975801019,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "LVuDnD2l"
				},
				{
					"id": "LtVsgDxiWmnLM2kwbSpGs",
					"type": "arrow"
				}
			],
			"updated": 1710347269622,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1558,
			"versionNonce": 1336617077,
			"isDeleted": false,
			"id": "LVuDnD2l",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1017.4353089536594,
			"y": 5387.1294863003495,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1433404763,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347269622,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "gT_9kRaKnYwMI1vK8SMPE",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1631,
			"versionNonce": 2037928405,
			"isDeleted": false,
			"id": "Xk80Spw4D2_ovufP1XFmX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1015.7813937734882,
			"y": 5385.795301050333,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1906090491,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "D9Zu6wQc"
				},
				{
					"id": "Phd7rFMN3RKa-INKRN7TX",
					"type": "arrow"
				},
				{
					"id": "2ChkXMnzWmbFk9RP8oojE",
					"type": "arrow"
				},
				{
					"id": "_GICeX7jkhDppsX2gvQ1L",
					"type": "arrow"
				}
			],
			"updated": 1710347269622,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1627,
			"versionNonce": 1251846421,
			"isDeleted": false,
			"id": "D9Zu6wQc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1032.733626134328,
			"y": 5413.586316675333,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1665968795,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nWorker",
			"rawText": "Messaging Worker",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Xk80Spw4D2_ovufP1XFmX",
			"originalText": "Messaging Worker",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 732,
			"versionNonce": 1112696117,
			"isDeleted": false,
			"id": "5lH4QHhT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 964.35906965558,
			"y": 5198.931785371595,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 189.37986755371094,
			"height": 125,
			"seed": 2134023995,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "LtVsgDxiWmnLM2kwbSpGs",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"rawText": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"lineHeight": 1.25,
			"baseline": 118
		},
		{
			"type": "arrow",
			"version": 2302,
			"versionNonce": 1296791477,
			"isDeleted": false,
			"id": "LtVsgDxiWmnLM2kwbSpGs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 972.3930233929201,
			"y": 5391.854114677688,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 87.87225323517339,
			"height": 53.010802135499944,
			"seed": 1605435355,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "KjrLca8qoZWtYqytFfdLP",
				"gap": 15.52074418488911,
				"focus": -0.5108272545189985
			},
			"endBinding": {
				"elementId": "cgcwOGOyWw-dn1Sp-ucnT",
				"gap": 8.136910790452475,
				"focus": 0.9755322018974778
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
					-87.87225323517339,
					-53.010802135499944
				]
			]
		},
		{
			"type": "arrow",
			"version": 1884,
			"versionNonce": 1880847669,
			"isDeleted": false,
			"id": "Phd7rFMN3RKa-INKRN7TX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1110.4381594147376,
			"y": 5501.428453013446,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 21.505818791730007,
			"height": 91.30053328370832,
			"seed": 786058363,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Xk80Spw4D2_ovufP1XFmX",
				"gap": 10.05112071311305,
				"focus": -0.5845408074149229
			},
			"endBinding": {
				"elementId": "aPu0vnOtenHZRkF9tlYBz",
				"gap": 6.153797258440136,
				"focus": 0.03196209520978591
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
					-21.505818791730007,
					91.30053328370832
				]
			]
		},
		{
			"type": "arrow",
			"version": 1867,
			"versionNonce": 1802333173,
			"isDeleted": false,
			"id": "2ChkXMnzWmbFk9RP8oojE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1065.442590208425,
			"y": 5587.92787176985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 15.104332755322957,
			"height": 92.82154752789575,
			"seed": 812713243,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "aPu0vnOtenHZRkF9tlYBz",
				"gap": 10.954911785745026,
				"focus": 0.04414809781135104
			},
			"endBinding": {
				"elementId": "Xk80Spw4D2_ovufP1XFmX",
				"gap": 3.728991941620734,
				"focus": 0.5354560838413339
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
					-15.104332755322957,
					-92.82154752789575
				]
			]
		},
		{
			"type": "arrow",
			"version": 1947,
			"versionNonce": 2051060405,
			"isDeleted": false,
			"id": "_GICeX7jkhDppsX2gvQ1L",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 967.7394282741502,
			"y": 5422.261352885459,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 634.4297005990916,
			"height": 21.28108892448654,
			"seed": 199731643,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "KjrLca8qoZWtYqytFfdLP",
				"gap": 20.17433930365911,
				"focus": -0.4756531049984398
			},
			"endBinding": {
				"elementId": "nAQuLoI8m33cK-nzOCBd2",
				"gap": 25.236534467271667,
				"focus": -1.3826829660678261
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
					-634.4297005990916,
					21.28108892448654
				]
			]
		},
		{
			"type": "text",
			"version": 887,
			"versionNonce": 691755483,
			"isDeleted": false,
			"id": "sW5g690p",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 993.4778632190379,
			"y": 5745.3189907648275,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 179.83987426757812,
			"height": 100,
			"seed": 1449179739,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "5QUGgGiwXsc2M4YBxZksL",
					"type": "arrow"
				}
			],
			"updated": 1710347544113,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"rawText": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "rectangle",
			"version": 1443,
			"versionNonce": 122110677,
			"isDeleted": false,
			"id": "nAQuLoI8m33cK-nzOCBd2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 228.99480604398485,
			"y": 5468.751008403993,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 1554953979,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "tClgBJ2Z"
				},
				{
					"id": "_GICeX7jkhDppsX2gvQ1L",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1544,
			"versionNonce": 1868701749,
			"isDeleted": false,
			"id": "tClgBJ2Z",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 247.92840573255108,
			"y": 5486.251008403993,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 760487835,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "nAQuLoI8m33cK-nzOCBd2",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 1507,
			"versionNonce": 1128617717,
			"isDeleted": false,
			"id": "nRJ2afkHm_s75aa9W2dwE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 226.1247671015202,
			"y": 5686.807772176173,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 1652782139,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "einG2DQF"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1612,
			"versionNonce": 113815637,
			"isDeleted": false,
			"id": "einG2DQF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 245.05836679008644,
			"y": 5704.307772176173,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 740242651,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "nRJ2afkHm_s75aa9W2dwE",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "arrow",
			"version": 1506,
			"versionNonce": 1450228277,
			"isDeleted": false,
			"id": "lwGcFXa_HeILcqRnb0A6s",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -6.71947844544286,
			"y": 5662.241582386686,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 217.19661732603936,
			"height": 4.350245616550637,
			"seed": 431612283,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "UXu_Ako2t1TBflS5XvAAK",
				"gap": 4.999518096236216,
				"focus": 0.15663670439619978
			},
			"endBinding": {
				"elementId": "uvHtpvPlDjlDSnbPowvfR",
				"gap": 7.476034303238066,
				"focus": -0.10026139913205499
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
					217.19661732603936,
					-4.350245616550637
				]
			]
		},
		{
			"type": "arrow",
			"version": 1963,
			"versionNonce": 1458925813,
			"isDeleted": false,
			"id": "5QUGgGiwXsc2M4YBxZksL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 356.71935190652187,
			"y": 5693.169188688604,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 638.69653208637,
			"height": 25.37594539499969,
			"seed": 613808667,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "uvHtpvPlDjlDSnbPowvfR",
				"gap": 9.7818037226873,
				"focus": 0.8146334649468194
			},
			"endBinding": {
				"elementId": "aPu0vnOtenHZRkF9tlYBz",
				"gap": 12.681081294744217,
				"focus": -0.2358174756046635
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
					638.69653208637,
					-25.37594539499969
				]
			]
		},
		{
			"type": "text",
			"version": 488,
			"versionNonce": 1867302811,
			"isDeleted": false,
			"id": "2i1GfBlX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 92.85631178837002,
			"y": 5266.72822566237,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 349.8196716308594,
			"height": 25,
			"seed": 2040921787,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347508180,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Stateful! due to keeping websocket",
			"rawText": "Stateful! due to keeping websocket",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Stateful! due to keeping websocket",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1182,
			"versionNonce": 1943591029,
			"isDeleted": false,
			"id": "2tSp7E2kLD5CA--dcMgdy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 340.7381521158304,
			"y": 4811.495613260105,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 160.94094198279868,
			"height": 3.57344188137904,
			"seed": 59535195,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "KJaiXe56W0d690g45W6W4",
				"gap": 8.358440417956672,
				"focus": -0.1068178941347873
			},
			"endBinding": {
				"elementId": "1H6AUMJ1Mm7Al0IdwdIF7",
				"gap": 6.457181594842041,
				"focus": -0.043243785614394396
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
					160.94094198279868,
					3.57344188137904
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1418,
			"versionNonce": 348576565,
			"isDeleted": false,
			"id": "v73Rv0t9ZdimKmTTeLgD1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 218.29121251549736,
			"y": 4841.677381194953,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 882625531,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "9KNM7lT9"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1518,
			"versionNonce": 1846520981,
			"isDeleted": false,
			"id": "9KNM7lT9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 237.2248122040636,
			"y": 4859.177381194953,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 282498203,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "v73Rv0t9ZdimKmTTeLgD1",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 910,
			"versionNonce": 1022841333,
			"isDeleted": false,
			"id": "FJMD98csS9N8t0yo-I-vD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -30.8123285368398,
			"y": 5646.589538041746,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 2012170555,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "p3qO00r1"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 851,
			"versionNonce": 243485525,
			"isDeleted": false,
			"id": "p3qO00r1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 5.932834427027387,
			"y": 5651.589538041746,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 793274843,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FJMD98csS9N8t0yo-I-vD",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1821,
			"versionNonce": 856234165,
			"isDeleted": false,
			"id": "KEKEFjumFH15tmd_1oZNV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 780.6975769634153,
			"y": 4736.638226818392,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 737441403,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Ily8wCkK"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1815,
			"versionNonce": 1412315669,
			"isDeleted": false,
			"id": "Ily8wCkK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 797.6498093242551,
			"y": 4764.429242443392,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 481685275,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "KEKEFjumFH15tmd_1oZNV",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1869,
			"versionNonce": 1256730485,
			"isDeleted": false,
			"id": "Mdu5zXmTHqa06xknwY1ya",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 793.2668859784255,
			"y": 4755.485577235499,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 872371131,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "rZZrAJrs"
				},
				{
					"id": "q_S3Qhsh370TcpOknwkk0",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1862,
			"versionNonce": 897349845,
			"isDeleted": false,
			"id": "rZZrAJrs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 810.2191183392654,
			"y": 4783.276592860499,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 838018139,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Mdu5zXmTHqa06xknwY1ya",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1940,
			"versionNonce": 2111440789,
			"isDeleted": false,
			"id": "04b_0ZZbz3MhYh0Q1U2O3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 808.5652031590942,
			"y": 4781.942407610482,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 778297595,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "5SuwbhUW"
				},
				{
					"id": "0dSdjCOT391xP2uBbryos",
					"type": "arrow"
				},
				{
					"id": "DrkLSNjNd6KFjLlKbMGsC",
					"type": "arrow"
				},
				{
					"id": "lXXcrSOlhRGC3t7RYLGLt",
					"type": "arrow"
				},
				{
					"id": "e8ur6VscEjurejeoQfuZJ",
					"type": "arrow"
				},
				{
					"id": "IBEOx62fd-ZYoGsCqrLuj",
					"type": "arrow"
				}
			],
			"updated": 1710347265517,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1940,
			"versionNonce": 951995637,
			"isDeleted": false,
			"id": "5SuwbhUW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 841.117418735266,
			"y": 4809.733423235482,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 63.87994384765625,
			"height": 50,
			"seed": 584321435,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Group\nWorker",
			"rawText": "Group Worker",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "04b_0ZZbz3MhYh0Q1U2O3",
			"originalText": "Group Worker",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1443,
			"versionNonce": 614699419,
			"isDeleted": false,
			"id": "vqyec1pou_Wv-U2hp6bkF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1048.5036449103377,
			"y": 4753.899782100045,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 880156219,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "fZGNDLe0"
				},
				{
					"id": "0dSdjCOT391xP2uBbryos",
					"type": "arrow"
				},
				{
					"id": "DrkLSNjNd6KFjLlKbMGsC",
					"type": "arrow"
				},
				{
					"id": "CdK_HiPoiJRoo_A7w82QC",
					"type": "arrow"
				}
			],
			"updated": 1710347334994,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1449,
			"versionNonce": 693723797,
			"isDeleted": false,
			"id": "fZGNDLe0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1084.6558589606307,
			"y": 4781.690797725045,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.67994689941406,
			"height": 50,
			"seed": 1043111643,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Group\nDB",
			"rawText": "Group\nDB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "vqyec1pou_Wv-U2hp6bkF",
			"originalText": "Group\nDB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 808,
			"versionNonce": 142690677,
			"isDeleted": false,
			"id": "q_S3Qhsh370TcpOknwkk0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 648.5727729586123,
			"y": 4818.241944398741,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 123.76281724332932,
			"height": 2.3920732081114693,
			"seed": 445254523,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354609,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "1H6AUMJ1Mm7Al0IdwdIF7",
				"gap": 11.452122265141156,
				"focus": 0.10011967823060547
			},
			"endBinding": {
				"elementId": "Mdu5zXmTHqa06xknwY1ya",
				"gap": 20.93129577648392,
				"focus": -0.10959466738559986
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
					123.76281724332932,
					-2.3920732081114693
				]
			]
		},
		{
			"type": "arrow",
			"version": 789,
			"versionNonce": 60580341,
			"isDeleted": false,
			"id": "0dSdjCOT391xP2uBbryos",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 946.6369992527326,
			"y": 4815.797788725757,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 96.99615047449004,
			"height": 2.1763029964931775,
			"seed": 768664603,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "04b_0ZZbz3MhYh0Q1U2O3",
				"gap": 9.087421093638454,
				"focus": -0.3186828408520801
			},
			"endBinding": {
				"elementId": "vqyec1pou_Wv-U2hp6bkF",
				"gap": 4.870495183115054,
				"focus": -0.0990890988987773
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
					96.99615047449004,
					-2.1763029964931775
				]
			]
		},
		{
			"type": "arrow",
			"version": 790,
			"versionNonce": 1068116149,
			"isDeleted": false,
			"id": "DrkLSNjNd6KFjLlKbMGsC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1041.914428386402,
			"y": 4841.8167001060565,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 97.53929617959773,
			"height": 1.7150011647581778,
			"seed": 804497595,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "vqyec1pou_Wv-U2hp6bkF",
				"gap": 6.589216523935647,
				"focus": -0.6282081862932514
			},
			"endBinding": {
				"elementId": "04b_0ZZbz3MhYh0Q1U2O3",
				"gap": 6.82555404771017,
				"focus": 0.18641152827122068
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
					-97.53929617959773,
					1.7150011647581778
				]
			]
		},
		{
			"type": "arrow",
			"version": 783,
			"versionNonce": 1108012469,
			"isDeleted": false,
			"id": "lXXcrSOlhRGC3t7RYLGLt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 879.7073117144153,
			"y": 4897.801629668846,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0.2752930286163746,
			"height": 37.030632524952125,
			"seed": 915724635,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "04b_0ZZbz3MhYh0Q1U2O3",
				"gap": 10.27719080836323,
				"focus": -0.10971443860528426
			},
			"endBinding": {
				"elementId": "cgcwOGOyWw-dn1Sp-ucnT",
				"gap": 2.2976857037378977,
				"focus": -0.08668781546195349
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
					-0.2752930286163746,
					37.030632524952125
				]
			]
		},
		{
			"type": "arrow",
			"version": 843,
			"versionNonce": 1765327989,
			"isDeleted": false,
			"id": "e8ur6VscEjurejeoQfuZJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 867.702303561108,
			"y": 4898.210849035708,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0.2752930286163746,
			"height": 37.030632524951216,
			"seed": 2131162619,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "04b_0ZZbz3MhYh0Q1U2O3",
				"gap": 10.686410175225319,
				"focus": 0.07525945915549923
			},
			"endBinding": {
				"elementId": "cgcwOGOyWw-dn1Sp-ucnT",
				"gap": 1.8884663368767178,
				"focus": -0.740044871521588
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
					-0.2752930286163746,
					37.030632524951216
				]
			]
		},
		{
			"type": "arrow",
			"version": 837,
			"versionNonce": 107998005,
			"isDeleted": false,
			"id": "IBEOx62fd-ZYoGsCqrLuj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 894.1601957167699,
			"y": 4897.154319033991,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0.2752930286162609,
			"height": 37.030632524952125,
			"seed": 2018279067,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "04b_0ZZbz3MhYh0Q1U2O3",
				"gap": 9.629880173508354,
				"focus": -0.33238763766587404
			},
			"endBinding": {
				"elementId": "cgcwOGOyWw-dn1Sp-ucnT",
				"gap": 2.944996338592773,
				"focus": 0.6998291340255278
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
					-0.2752930286162609,
					37.030632524952125
				]
			]
		},
		{
			"type": "text",
			"version": 904,
			"versionNonce": 887621301,
			"isDeleted": false,
			"id": "Aqq3NyES",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1012.5675667375846,
			"y": 4909.424993628398,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 236.1798553466797,
			"height": 100,
			"seed": 219673403,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347327548,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    group_id: {send}\n    user_id: [{rec}, {}]\n}",
			"rawText": "{\n    group_id: {send}\n    user_id: [{rec}, {}]\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    group_id: {send}\n    user_id: [{rec}, {}]\n}",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "text",
			"version": 87,
			"versionNonce": 1584471125,
			"isDeleted": false,
			"id": "WWpEw1Fi",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1223.6769771872996,
			"y": 4777.866939632295,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 108.25991821289062,
			"height": 50,
			"seed": 879701275,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347265517,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "read heavy\n- dynamodb",
			"rawText": "read heavy\n- dynamodb",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "read heavy\n- dynamodb",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 809,
			"versionNonce": 186949627,
			"isDeleted": false,
			"id": "A7Lh03FVJA7o5OX1iePqs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -168.13403320139315,
			"y": 4554.658451378701,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1651062549,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "UN5ErxRQ"
				},
				{
					"id": "j2qewu1X4TENPVqyGludZ",
					"type": "arrow"
				}
			],
			"updated": 1710347339734,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 797,
			"versionNonce": 255708955,
			"isDeleted": false,
			"id": "UN5ErxRQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -139.80181121652987,
			"y": 4569.949467003701,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.31993103027344,
			"height": 75,
			"seed": 851151989,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347330049,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nJoin a\ngroup",
			"rawText": "Client - Join a group",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "A7Lh03FVJA7o5OX1iePqs",
			"originalText": "Client - Join a group",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 949,
			"versionNonce": 2035490107,
			"isDeleted": false,
			"id": "fG0eJ2nkV-y1nfw8h-PRw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 204.19671479387443,
			"y": 4545.475931519176,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1513291867,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "BaFNgKwX"
				},
				{
					"id": "CdK_HiPoiJRoo_A7w82QC",
					"type": "arrow"
				},
				{
					"id": "j2qewu1X4TENPVqyGludZ",
					"type": "arrow"
				}
			],
			"updated": 1710347339734,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 955,
			"versionNonce": 1275266139,
			"isDeleted": false,
			"id": "BaFNgKwX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 234.92893830461662,
			"y": 4573.266947144176,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 67.51992797851562,
			"height": 50,
			"seed": 2051554555,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347330049,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Group\nService",
			"rawText": "Group Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "fG0eJ2nkV-y1nfw8h-PRw",
			"originalText": "Group Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 79,
			"versionNonce": 1028873461,
			"isDeleted": false,
			"id": "CdK_HiPoiJRoo_A7w82QC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 341.90267156653687,
			"y": 4599.793360785746,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 760.1660125072799,
			"height": 144.7388683355548,
			"seed": 2044023189,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "fG0eJ2nkV-y1nfw8h-PRw",
				"gap": 8.72158177266249,
				"focus": -0.19077434471372967
			},
			"endBinding": {
				"elementId": "vqyec1pou_Wv-U2hp6bkF",
				"gap": 9.367552978744243,
				"focus": 0.9232739270726134
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
					760.1660125072799,
					144.7388683355548
				]
			]
		},
		{
			"type": "arrow",
			"version": 55,
			"versionNonce": 236872629,
			"isDeleted": false,
			"id": "j2qewu1X4TENPVqyGludZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -22.8801412562392,
			"y": 4611.241463097525,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 221.48622509342908,
			"height": 1.0035869218199878,
			"seed": 1632289013,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "A7Lh03FVJA7o5OX1iePqs",
				"gap": 16.269516945153953,
				"focus": 0.07832866655456847
			},
			"endBinding": {
				"elementId": "fG0eJ2nkV-y1nfw8h-PRw",
				"gap": 5.590630956684549,
				"focus": -0.2195301859402202
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
					221.48622509342908,
					-1.0035869218199878
				]
			]
		},
		{
			"type": "text",
			"version": 165,
			"versionNonce": 1718100469,
			"isDeleted": false,
			"id": "QKPYgqoS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 513.6458743974048,
			"y": 4904.54678338523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 115.2799072265625,
			"height": 25,
			"seed": 1429040027,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347490400,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Write Heavy",
			"rawText": "Write Heavy",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Write Heavy",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 29,
			"versionNonce": 1118345205,
			"isDeleted": false,
			"id": "5vEq58ax",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 596.6034171204439,
			"y": 5728.97287589401,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 270.07977294921875,
			"height": 25,
			"seed": 1383261115,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347556690,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Save connection info on join",
			"rawText": "Save connection info on join",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Save connection info on join",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 128,
			"versionNonce": 118712123,
			"isDeleted": false,
			"id": "sXxOkOln",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 625.6529971146882,
			"y": 5454.674907857052,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 192.83982849121094,
			"height": 25,
			"seed": 1272791061,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347569857,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Send info to clients",
			"rawText": "Send info to clients",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Send info to clients",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1040,
			"versionNonce": 1590053941,
			"isDeleted": false,
			"id": "qFB5ODCcSSn19JjBcoJdR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 161.76342544868294,
			"y": 6984.715439787557,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 199.48828125,
			"height": 505.5207262086258,
			"seed": 104360699,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 846,
			"versionNonce": 607002971,
			"isDeleted": false,
			"id": "FnJ-yguadaYsdYf_eLLsj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -168.20755741967514,
			"y": 6704.301262665965,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1669813147,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "vu3PKaIj"
				},
				{
					"id": "J0-rHicpQUOQ2FsBpSKGY",
					"type": "arrow"
				}
			],
			"updated": 1710348119908,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 820,
			"versionNonce": 2050440699,
			"isDeleted": false,
			"id": "vu3PKaIj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -139.87533543481186,
			"y": 6732.092278290965,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.31993103027344,
			"height": 50,
			"seed": 1412442171,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348119908,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nSender",
			"rawText": "Client - Sender",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FnJ-yguadaYsdYf_eLLsj",
			"originalText": "Client - Sender",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 987,
			"versionNonce": 491260341,
			"isDeleted": false,
			"id": "7tFJDlNWqZBQOmdmNGqGA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -168.55175383977235,
			"y": 7055.353238014904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 773155035,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "1CtCww9i"
				},
				{
					"id": "kF46FqfR95SvIBHp7jebR",
					"type": "arrow"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 974,
			"versionNonce": 1533479701,
			"isDeleted": false,
			"id": "1CtCww9i",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -146.08952697209656,
			"y": 7083.144253639904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.05992126464844,
			"height": 50,
			"seed": 1724487035,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nReceiving",
			"rawText": "Client - Receiving",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "7tFJDlNWqZBQOmdmNGqGA",
			"originalText": "Client - Receiving",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1115,
			"versionNonce": 796199381,
			"isDeleted": false,
			"id": "C_UyOyCiqENaZjQm-ti7J",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -156.19312621059976,
			"y": 7274.214470470503,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 495922715,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "2nWT0Z7j"
				},
				{
					"id": "3hTWj6vNQaVw0nIJty6-B",
					"type": "arrow"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1132,
			"versionNonce": 2084505397,
			"isDeleted": false,
			"id": "2nWT0Z7j",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -146.99088622036538,
			"y": 7302.005486095503,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.57989501953125,
			"height": 50,
			"seed": 1700311739,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nConnections",
			"rawText": "Client - Connections",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "C_UyOyCiqENaZjQm-ti7J",
			"originalText": "Client - Connections",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1001,
			"versionNonce": 517356347,
			"isDeleted": false,
			"id": "UuCCMsvGwZxHo7lbF9FEJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 196.35494258032486,
			"y": 6711.417961884715,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1321771867,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ggFBM8QI"
				},
				{
					"id": "J0-rHicpQUOQ2FsBpSKGY",
					"type": "arrow"
				},
				{
					"id": "eCiAROpJUg35UbHTwNA6x",
					"type": "arrow"
				}
			],
			"updated": 1710348119908,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 999,
			"versionNonce": 8461275,
			"isDeleted": false,
			"id": "ggFBM8QI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 227.08716609106705,
			"y": 6739.208977509715,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 67.51992797851562,
			"height": 50,
			"seed": 842104827,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348119908,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Send\nService",
			"rawText": "Send Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "UuCCMsvGwZxHo7lbF9FEJ",
			"originalText": "Send Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1135,
			"versionNonce": 2102352757,
			"isDeleted": false,
			"id": "4e62gfv1WFl4eb8LqlHEe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 201.0185586602277,
			"y": 7056.643765358654,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 966117531,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "uHNqNU1f"
				},
				{
					"id": "kF46FqfR95SvIBHp7jebR",
					"type": "arrow"
				},
				{
					"id": "-wwDyAJ_rSyEqE6nyUeIA",
					"type": "arrow"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1138,
			"versionNonce": 1780360405,
			"isDeleted": false,
			"id": "uHNqNU1f",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 229.88077942438787,
			"y": 7084.434780983654,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 71.25993347167969,
			"height": 50,
			"seed": 715652411,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Receive\nService",
			"rawText": "Receive Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "4e62gfv1WFl4eb8LqlHEe",
			"originalText": "Receive Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1540,
			"versionNonce": 81837781,
			"isDeleted": false,
			"id": "yTfUllYo_e8ewV4kIDza2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 957.9382635924862,
			"y": 6796.710504676157,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1892326875,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "llAJy4wO"
				},
				{
					"id": "eCiAROpJUg35UbHTwNA6x",
					"type": "arrow"
				},
				{
					"id": "4QlXtxZtGeeB5wZnFX525",
					"type": "arrow"
				},
				{
					"id": "QLbcaIX-vOKFwubffdV3-",
					"type": "arrow"
				}
			],
			"updated": 1710348354610,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1534,
			"versionNonce": 1573137493,
			"isDeleted": false,
			"id": "llAJy4wO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 974.8904959533261,
			"y": 6824.501520301157,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1729112699,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nDB",
			"rawText": "Messaging DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "yTfUllYo_e8ewV4kIDza2",
			"originalText": "Messaging DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 699,
			"versionNonce": 1065130901,
			"isDeleted": false,
			"id": "K29ndCf2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -106.67846418699708,
			"y": 6415.564868376469,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 358.61968994140625,
			"height": 25,
			"seed": 1648042779,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348128014,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WebSockets - Change Data Capture",
			"rawText": "WebSockets - Change Data Capture",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "WebSockets - Change Data Capture",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 2256,
			"versionNonce": 1214750389,
			"isDeleted": false,
			"id": "J0-rHicpQUOQ2FsBpSKGY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -32.71341679467514,
			"y": 6759.4909599315915,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 226.43359375,
			"height": 0.8085937499990905,
			"seed": 2059274171,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "FnJ-yguadaYsdYf_eLLsj",
				"gap": 6.509765625,
				"focus": 0.04045795120897413
			},
			"endBinding": {
				"elementId": "UuCCMsvGwZxHo7lbF9FEJ",
				"gap": 2.634765625,
				"focus": 0.06921204270977468
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
					226.43359375,
					0.8085937499990905
				]
			]
		},
		{
			"type": "text",
			"version": 824,
			"versionNonce": 517817787,
			"isDeleted": false,
			"id": "jjlS1xZm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -73.8606163199006,
			"y": 6814.7475126457675,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 213.85980224609375,
			"height": 25,
			"seed": 381376603,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348119908,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Persistant Connection",
			"rawText": "Persistant Connection",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Persistant Connection",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 2362,
			"versionNonce": 316487029,
			"isDeleted": false,
			"id": "kF46FqfR95SvIBHp7jebR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -31.80370696477233,
			"y": 7108.893691283628,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 231.82226562500006,
			"height": 0.589068536501145,
			"seed": 872781051,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "7tFJDlNWqZBQOmdmNGqGA",
				"gap": 7.763671875,
				"focus": 0.010685187612612574
			},
			"endBinding": {
				"elementId": "4e62gfv1WFl4eb8LqlHEe",
				"gap": 1,
				"focus": -0.004048668211233233
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
					231.82226562500006,
					0.589068536501145
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1562,
			"versionNonce": 1297337589,
			"isDeleted": false,
			"id": "z5xrkHJaQJK86Q4eq11nd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 636.3405826591637,
			"y": 6967.746649085274,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 214.25477585883405,
			"height": 22.98846159143434,
			"seed": 1914650011,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "9z_ww882uUzOnkuF-LweM",
					"type": "arrow"
				},
				{
					"id": "eCiAROpJUg35UbHTwNA6x",
					"type": "arrow"
				}
			],
			"updated": 1710348054880,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 929,
			"versionNonce": 1542410613,
			"isDeleted": false,
			"id": "aSgx_k1nSMrodq1E8FBGc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -59.616206964772346,
			"y": 7092.732388405529,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 1547358779,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "zLPTplUE"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 871,
			"versionNonce": 491739861,
			"isDeleted": false,
			"id": "zLPTplUE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -22.871044000905158,
			"y": 7097.732388405529,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 1933234907,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "aSgx_k1nSMrodq1E8FBGc",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1553,
			"versionNonce": 1017591861,
			"isDeleted": false,
			"id": "AO1JPis5j5mmYhpU7vo4b",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 992.6072106187155,
			"y": 7270.726174446424,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 2008137595,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "yMy1CemG"
				},
				{
					"id": "NuT0qdAyoNxVi02wq1b8h",
					"type": "arrow"
				},
				{
					"id": "G7yoNWPo6Lumd_ByowFIY",
					"type": "arrow"
				},
				{
					"id": "vCwKynQO--l58OahJiFUA",
					"type": "arrow"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1559,
			"versionNonce": 1406953877,
			"isDeleted": false,
			"id": "yMy1CemG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1007.2394432847311,
			"y": 7298.517190071424,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 99.71990966796875,
			"height": 50,
			"seed": 1944197147,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Connection\nDB",
			"rawText": "Connection DB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "AO1JPis5j5mmYhpU7vo4b",
			"originalText": "Connection DB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1204,
			"versionNonce": 1395947285,
			"isDeleted": false,
			"id": "dP_Z1VBaJ-YIkqm63nJtt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 202.46341851491388,
			"y": 7270.079845117175,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 96361659,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "WnHay2un"
				},
				{
					"id": "3hTWj6vNQaVw0nIJty6-B",
					"type": "arrow"
				},
				{
					"id": "vCwKynQO--l58OahJiFUA",
					"type": "arrow"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1201,
			"versionNonce": 1746848885,
			"isDeleted": false,
			"id": "WnHay2un",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 231.32563927907404,
			"y": 7297.870860742175,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 71.25993347167969,
			"height": 50,
			"seed": 1760103771,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Receive\nService",
			"rawText": "Receive Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "dP_Z1VBaJ-YIkqm63nJtt",
			"originalText": "Receive Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1580,
			"versionNonce": 1799720155,
			"isDeleted": false,
			"id": "htSHOZu2JJHo-UC4WNAaz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 972.4240129088887,
			"y": 7012.334511149072,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1085581819,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "NqkKxWpy"
				},
				{
					"id": "9z_ww882uUzOnkuF-LweM",
					"type": "arrow"
				},
				{
					"id": "-wwDyAJ_rSyEqE6nyUeIA",
					"type": "arrow"
				},
				{
					"id": "QLbcaIX-vOKFwubffdV3-",
					"type": "arrow"
				}
			],
			"updated": 1710348066879,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1571,
			"versionNonce": 2067687925,
			"isDeleted": false,
			"id": "NqkKxWpy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 989.3762452697285,
			"y": 7040.125526774072,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 572764827,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "htSHOZu2JJHo-UC4WNAaz",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1624,
			"versionNonce": 833376789,
			"isDeleted": false,
			"id": "FSZOU0ucvopPZE4SsHKy6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 984.993321923899,
			"y": 7031.181861566179,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1575528251,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "qenPLvBh"
				},
				{
					"id": "9z_ww882uUzOnkuF-LweM",
					"type": "arrow"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1618,
			"versionNonce": 14894965,
			"isDeleted": false,
			"id": "qenPLvBh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1001.9455542847388,
			"y": 7058.972877191179,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 174458843,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nService",
			"rawText": "Messaging Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FSZOU0ucvopPZE4SsHKy6",
			"originalText": "Messaging Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 1693,
			"versionNonce": 241390139,
			"isDeleted": false,
			"id": "NIoxDhyNs85wUJsaQ4YTX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1000.2916391045676,
			"y": 7057.6386919411625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1303270523,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "2aetfaZW"
				},
				{
					"id": "NuT0qdAyoNxVi02wq1b8h",
					"type": "arrow"
				},
				{
					"id": "G7yoNWPo6Lumd_ByowFIY",
					"type": "arrow"
				},
				{
					"id": "-wwDyAJ_rSyEqE6nyUeIA",
					"type": "arrow"
				},
				{
					"id": "N2YlVisV2lcbOEHFKHR_V",
					"type": "arrow"
				},
				{
					"id": "dp0CdV89VNcqITIanrG9s",
					"type": "arrow"
				}
			],
			"updated": 1710348110543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1687,
			"versionNonce": 1637199413,
			"isDeleted": false,
			"id": "2aetfaZW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1017.2438714654074,
			"y": 7085.4297075661625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.07991027832031,
			"height": 50,
			"seed": 1736707355,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Messaging\nWorker",
			"rawText": "Messaging Worker",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "NIoxDhyNs85wUJsaQ4YTX",
			"originalText": "Messaging Worker",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 888,
			"versionNonce": 2119734203,
			"isDeleted": false,
			"id": "Nfb9qtJQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 724.4985286808133,
			"y": 6793.048270592833,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 189.37986755371094,
			"height": 125,
			"seed": 2069475771,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "9z_ww882uUzOnkuF-LweM",
					"type": "arrow"
				}
			],
			"updated": 1710348071054,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"rawText": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    sebder: {send}\n    user_id: {rec}\n    message: {msg}\n}",
			"lineHeight": 1.25,
			"baseline": 118
		},
		{
			"type": "arrow",
			"version": 3023,
			"versionNonce": 312341717,
			"isDeleted": false,
			"id": "9z_ww882uUzOnkuF-LweM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 956.9032687239994,
			"y": 7068.856748870649,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 99.70917895026378,
			"height": 85.76434884933678,
			"seed": 441565787,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354611,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "htSHOZu2JJHo-UC4WNAaz",
				"gap": 15.520744184889281,
				"focus": -0.670203348810832
			},
			"endBinding": {
				"elementId": "z5xrkHJaQJK86Q4eq11nd",
				"gap": 6.598731255737903,
				"focus": -0.9066967448609314
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
					-99.70917895026378,
					-85.76434884933678
				]
			]
		},
		{
			"type": "arrow",
			"version": 2062,
			"versionNonce": 1732743445,
			"isDeleted": false,
			"id": "NuT0qdAyoNxVi02wq1b8h",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1094.948404745817,
			"y": 7173.271843904276,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 21.505818791730007,
			"height": 91.30053328370832,
			"seed": 222215931,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354611,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "NIoxDhyNs85wUJsaQ4YTX",
				"gap": 10.05112071311305,
				"focus": -0.5845408074149229
			},
			"endBinding": {
				"elementId": "AO1JPis5j5mmYhpU7vo4b",
				"gap": 6.153797258440136,
				"focus": 0.03196209520978591
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
					-21.505818791730007,
					91.30053328370832
				]
			]
		},
		{
			"type": "arrow",
			"version": 2045,
			"versionNonce": 896274389,
			"isDeleted": false,
			"id": "G7yoNWPo6Lumd_ByowFIY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1049.9528355395041,
			"y": 7259.771262660681,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 15.104332755322957,
			"height": 92.82154752789756,
			"seed": 1587750811,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354611,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "AO1JPis5j5mmYhpU7vo4b",
				"gap": 10.954911785744116,
				"focus": 0.04414809781134456
			},
			"endBinding": {
				"elementId": "NIoxDhyNs85wUJsaQ4YTX",
				"gap": 3.728991941620734,
				"focus": 0.5354560838413363
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
					-15.104332755322957,
					-92.82154752789756
				]
			]
		},
		{
			"type": "arrow",
			"version": 2125,
			"versionNonce": 226847765,
			"isDeleted": false,
			"id": "-wwDyAJ_rSyEqE6nyUeIA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 952.2496736052294,
			"y": 7094.10474377629,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 634.8127400260729,
			"height": 21.293937465623458,
			"seed": 615611451,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354611,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "htSHOZu2JJHo-UC4WNAaz",
				"gap": 20.17433930365928,
				"focus": -0.47565310499845637
			},
			"endBinding": {
				"elementId": "GTgXObaEOB6knGrMJKP3j",
				"gap": 25.208566594046715,
				"focus": -1.3826829660678113
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
					-634.8127400260729,
					21.293937465623458
				]
			]
		},
		{
			"type": "text",
			"version": 947,
			"versionNonce": 269248821,
			"isDeleted": false,
			"id": "AzrNT6bJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 977.9881085501172,
			"y": 7417.162381655658,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 179.83987426757812,
			"height": 100,
			"seed": 189545691,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "vCwKynQO--l58OahJiFUA",
					"type": "arrow"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"rawText": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    user_id: {rec}\n    machine_id: {}\n}",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "rectangle",
			"version": 1503,
			"versionNonce": 1165195925,
			"isDeleted": false,
			"id": "GTgXObaEOB6knGrMJKP3j",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 213.50505137506417,
			"y": 7140.594399294822,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 503703931,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "7gb4bvWs"
				},
				{
					"id": "-wwDyAJ_rSyEqE6nyUeIA",
					"type": "arrow"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1605,
			"versionNonce": 1387356149,
			"isDeleted": false,
			"id": "7gb4bvWs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 232.4386510636304,
			"y": 7158.094399294822,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 1377894939,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "GTgXObaEOB6knGrMJKP3j",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 1567,
			"versionNonce": 806856373,
			"isDeleted": false,
			"id": "XJ-aDyYmtQ069vXR_pigb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 210.63501243259952,
			"y": 7358.651163067002,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 1351616187,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "6eZmAk6N"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1673,
			"versionNonce": 205195285,
			"isDeleted": false,
			"id": "6eZmAk6N",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 229.56861212116576,
			"y": 7376.151163067002,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 2146793307,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "XJ-aDyYmtQ069vXR_pigb",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "arrow",
			"version": 1684,
			"versionNonce": 1430439765,
			"isDeleted": false,
			"id": "3hTWj6vNQaVw0nIJty6-B",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -22.209233114363542,
			"y": 7334.084973277515,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 217.19661732603936,
			"height": 4.350245616550637,
			"seed": 1319359483,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354611,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "C_UyOyCiqENaZjQm-ti7J",
				"gap": 4.999518096236216,
				"focus": 0.15663670439619978
			},
			"endBinding": {
				"elementId": "dP_Z1VBaJ-YIkqm63nJtt",
				"gap": 7.476034303238066,
				"focus": -0.10026139913205499
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
					217.19661732603936,
					-4.350245616550637
				]
			]
		},
		{
			"type": "arrow",
			"version": 2141,
			"versionNonce": 1446950421,
			"isDeleted": false,
			"id": "vCwKynQO--l58OahJiFUA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 341.2295972376012,
			"y": 7365.012579579433,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 638.6965320863701,
			"height": 25.37594539499969,
			"seed": 1016962203,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354611,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "dP_Z1VBaJ-YIkqm63nJtt",
				"gap": 9.7818037226873,
				"focus": 0.8146334649468194
			},
			"endBinding": {
				"elementId": "AO1JPis5j5mmYhpU7vo4b",
				"gap": 12.681081294744217,
				"focus": -0.23581747560466343
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
					638.6965320863701,
					-25.37594539499969
				]
			]
		},
		{
			"type": "text",
			"version": 548,
			"versionNonce": 534258741,
			"isDeleted": false,
			"id": "rWTIFLtE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 77.36655711944934,
			"y": 6938.5716165532,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 349.8196716308594,
			"height": 25,
			"seed": 630542651,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Stateful! due to keeping websocket",
			"rawText": "Stateful! due to keeping websocket",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Stateful! due to keeping websocket",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 2169,
			"versionNonce": 1680812757,
			"isDeleted": false,
			"id": "eCiAROpJUg35UbHTwNA6x",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 327.9591210859218,
			"y": 6775.73001533034,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 294.36556823529276,
			"height": 211.22199457074385,
			"seed": 1257075163,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354611,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ivw47wjgtyhRpOYdTtCQA",
				"gap": 14.486281554030029,
				"focus": -1.263386937345997
			},
			"endBinding": {
				"elementId": "z5xrkHJaQJK86Q4eq11nd",
				"gap": 14.015893337949194,
				"focus": -1.0710022116466216
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
					294.36556823529276,
					211.22199457074385
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1582,
			"versionNonce": 809686619,
			"isDeleted": false,
			"id": "ivw47wjgtyhRpOYdTtCQA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 211.25081839794848,
			"y": 6790.21629688437,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 103.12713284881217,
			"height": 110,
			"seed": 498630267,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "PWc2M19T"
				},
				{
					"id": "eCiAROpJUg35UbHTwNA6x",
					"type": "arrow"
				}
			],
			"updated": 1710348119908,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1682,
			"versionNonce": 1810715387,
			"isDeleted": false,
			"id": "PWc2M19T",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 230.1844180865147,
			"y": 6807.71629688437,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.25993347167969,
			"height": 75,
			"seed": 1220081435,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348119908,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "User\nSocket\nCache",
			"rawText": "User\nSocket\nCache",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ivw47wjgtyhRpOYdTtCQA",
			"originalText": "User\nSocket\nCache",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 970,
			"versionNonce": 984474037,
			"isDeleted": false,
			"id": "HiXT-RZR08xDrS0N3cahN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -46.30208320576048,
			"y": 7318.432928932575,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 100.5703125,
			"height": 35,
			"seed": 2053200827,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "SBPECtMJ"
				}
			],
			"updated": 1710347954067,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 911,
			"versionNonce": 2119295765,
			"isDeleted": false,
			"id": "SBPECtMJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -9.556920241893295,
			"y": 7323.432928932575,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 27.079986572265625,
			"height": 25,
			"seed": 1859398747,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954067,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "WS",
			"rawText": "WS",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "HiXT-RZR08xDrS0N3cahN",
			"originalText": "WS",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1627,
			"versionNonce": 2119046395,
			"isDeleted": false,
			"id": "jXyb2jjOodI7F1k-LJD_w",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1209.0442382291728,
			"y": 7040.839794523673,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1842196667,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ZfVEwY95"
				},
				{
					"id": "BusN94DxFfvKWsV_Xsgf3",
					"type": "arrow"
				},
				{
					"id": "N2YlVisV2lcbOEHFKHR_V",
					"type": "arrow"
				},
				{
					"id": "dp0CdV89VNcqITIanrG9s",
					"type": "arrow"
				}
			],
			"updated": 1710348110543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1630,
			"versionNonce": 1803262523,
			"isDeleted": false,
			"id": "ZfVEwY95",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1245.1964522794658,
			"y": 7068.630810148673,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.67994689941406,
			"height": 50,
			"seed": 1005445467,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348044609,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Group\nDB",
			"rawText": "Group\nDB",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "jXyb2jjOodI7F1k-LJD_w",
			"originalText": "Group\nDB",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 1362,
			"versionNonce": 1953242165,
			"isDeleted": false,
			"id": "4QlXtxZtGeeB5wZnFX525",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1098.1317084816205,
			"y": 6795.120609192968,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 6.280050377178895,
			"height": 7.634865336894109,
			"seed": 67042811,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354610,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "yTfUllYo_e8ewV4kIDza2",
				"gap": 11.32126386173212,
				"focus": 0.2869868623210617
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					6.280050377178895,
					-7.634865336894109
				]
			]
		},
		{
			"type": "text",
			"version": 1054,
			"versionNonce": 20225691,
			"isDeleted": false,
			"id": "1wDDL3pL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1361.1875606085425,
			"y": 7051.554023686159,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 236.1798553466797,
			"height": 100,
			"seed": 534054331,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348050745,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "{\n    group_id: {send}\n    user_id: [{rec}, {}]\n}",
			"rawText": "{\n    group_id: {send}\n    user_id: [{rec}, {}]\n}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "{\n    group_id: {send}\n    user_id: [{rec}, {}]\n}",
			"lineHeight": 1.25,
			"baseline": 93
		},
		{
			"type": "text",
			"version": 192,
			"versionNonce": 505414939,
			"isDeleted": false,
			"id": "m4MKVQmI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1525.4168418539537,
			"y": 6542.3708499694985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 108.25991821289062,
			"height": 50,
			"seed": 1010996827,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348009560,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "read heavy\n- dynamodb",
			"rawText": "read heavy\n- dynamodb",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "read heavy\n- dynamodb",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 956,
			"versionNonce": 344277211,
			"isDeleted": false,
			"id": "LqviRqDsQ3gxjr3CKBdv9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -161.93549325445258,
			"y": 6507.1576292326645,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 1643451131,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "IykyFCT2"
				},
				{
					"id": "6JuzEAaD9cKXHVhXv-LmP",
					"type": "arrow"
				}
			],
			"updated": 1710348125952,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 942,
			"versionNonce": 390905397,
			"isDeleted": false,
			"id": "IykyFCT2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -133.6032712695893,
			"y": 6522.4486448576645,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.31993103027344,
			"height": 75,
			"seed": 1903098779,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348125695,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Client -\nJoin a\ngroup",
			"rawText": "Client - Join a group",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "LqviRqDsQ3gxjr3CKBdv9",
			"originalText": "Client - Join a group",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 1078,
			"versionNonce": 968965307,
			"isDeleted": false,
			"id": "I4AXwZ6rTG1PClEe0sKDU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 201.05648781561456,
			"y": 6507.025420177099,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 128.984375,
			"height": 105.58203125,
			"seed": 383963195,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "oblNPO05"
				},
				{
					"id": "BusN94DxFfvKWsV_Xsgf3",
					"type": "arrow"
				},
				{
					"id": "6JuzEAaD9cKXHVhXv-LmP",
					"type": "arrow"
				}
			],
			"updated": 1710348122817,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1082,
			"versionNonce": 535421685,
			"isDeleted": false,
			"id": "oblNPO05",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 231.78871132635675,
			"y": 6534.816435802099,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 67.51992797851562,
			"height": 50,
			"seed": 1412632795,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348122578,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Group\nService",
			"rawText": "Group Service",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "I4AXwZ6rTG1PClEe0sKDU",
			"originalText": "Group Service",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 682,
			"versionNonce": 434587093,
			"isDeleted": false,
			"id": "BusN94DxFfvKWsV_Xsgf3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 338.762444588277,
			"y": 6571.754307309471,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 976.0667651342915,
			"height": 591.6582230942458,
			"seed": 1257389435,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354612,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "I4AXwZ6rTG1PClEe0sKDU",
				"gap": 8.72158177266249,
				"focus": 0.3704842972967702
			},
			"endBinding": {
				"elementId": "jXyb2jjOodI7F1k-LJD_w",
				"gap": 9.367552978744243,
				"focus": 0.7179181812083238
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
					853.941556580693,
					-131.94028885878834
				],
				[
					976.0667651342915,
					459.7179342354575
				]
			]
		},
		{
			"type": "arrow",
			"version": 340,
			"versionNonce": 1974834325,
			"isDeleted": false,
			"id": "6JuzEAaD9cKXHVhXv-LmP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -29.92053537378814,
			"y": 6559.780378786944,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 221.48622509342914,
			"height": 1.0035869218218068,
			"seed": 1180882459,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354612,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "LqviRqDsQ3gxjr3CKBdv9",
				"gap": 3.03058288066444,
				"focus": 0.0025938434457016624
			},
			"endBinding": {
				"elementId": "I4AXwZ6rTG1PClEe0sKDU",
				"gap": 9.49079809597356,
				"focus": 0.025900299818444984
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
					221.48622509342914,
					-1.0035869218218068
				]
			]
		},
		{
			"type": "text",
			"version": 345,
			"versionNonce": 594354427,
			"isDeleted": false,
			"id": "pLzcpIoQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 946.4830366658914,
			"y": 6751.374868824312,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 115.2799072265625,
			"height": 25,
			"seed": 91708091,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710348071054,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Write Heavy",
			"rawText": "Write Heavy",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Write Heavy",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 89,
			"versionNonce": 246979733,
			"isDeleted": false,
			"id": "QXFS8gvv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 581.1136624515232,
			"y": 7400.816266784838,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 270.07977294921875,
			"height": 25,
			"seed": 1154632539,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954068,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Save connection info on join",
			"rawText": "Save connection info on join",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Save connection info on join",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 188,
			"versionNonce": 990003701,
			"isDeleted": false,
			"id": "3mo0yfvE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 610.1632424457675,
			"y": 7126.518298747881,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 192.83982849121094,
			"height": 25,
			"seed": 147204091,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710347954068,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Send info to clients",
			"rawText": "Send info to clients",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Send info to clients",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 153,
			"versionNonce": 1077305941,
			"isDeleted": false,
			"id": "QLbcaIX-vOKFwubffdV3-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1023.2032495110456,
			"y": 6997.610033399317,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 2.426060417880649,
			"height": 86.78923547859904,
			"seed": 113989589,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354611,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "htSHOZu2JJHo-UC4WNAaz",
				"gap": 14.724477749754442,
				"focus": -0.17939940143282784
			},
			"endBinding": {
				"elementId": "yTfUllYo_e8ewV4kIDza2",
				"gap": 8.528261994560125,
				"focus": 0.05104527680362504
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
					-2.426060417880649,
					-86.78923547859904
				]
			]
		},
		{
			"type": "arrow",
			"version": 39,
			"versionNonce": 2069249781,
			"isDeleted": false,
			"id": "N2YlVisV2lcbOEHFKHR_V",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1135.030805428205,
			"y": 7073.101404129284,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 68.98307949445052,
			"height": 0.1742755732502701,
			"seed": 717743451,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354611,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "NIoxDhyNs85wUJsaQ4YTX",
				"gap": 5.7547913236373915,
				"focus": -0.7082715296217559
			},
			"endBinding": {
				"elementId": "jXyb2jjOodI7F1k-LJD_w",
				"gap": 5.030353306517327,
				"focus": 0.38107626856463295
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
					68.98307949445052,
					0.1742755732502701
				]
			]
		},
		{
			"type": "arrow",
			"version": 26,
			"versionNonce": 1850787253,
			"isDeleted": false,
			"id": "dp0CdV89VNcqITIanrG9s",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1200.2038603212545,
			"y": 7118.286853621294,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 68.27996769892388,
			"height": 0.06610452778477338,
			"seed": 745950037,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710348354612,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "jXyb2jjOodI7F1k-LJD_w",
				"gap": 8.84037790791831,
				"focus": -0.46784151632167015
			},
			"endBinding": {
				"elementId": "NIoxDhyNs85wUJsaQ4YTX",
				"gap": 2.647878517763047,
				"focus": 0.14617853965919556
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
					-68.27996769892388,
					-0.06610452778477338
				]
			]
		},
		{
			"id": "Idz2FIN8",
			"type": "text",
			"x": -38.91566543675003,
			"y": 7828.6424906832635,
			"width": 1272.638916015625,
			"height": 100,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 664812021,
			"version": 237,
			"versionNonce": 1323534171,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1710348395291,
			"link": null,
			"locked": false,
			"text": "Extensions\n- how would you handle large groups\n  - could probably change to polling as you will be receiving lots of messages at once and therefore takes load off the servers\n- mentions might want to sned notifications",
			"rawText": "Extensions\n- how would you handle large groups\n  - could probably change to polling as you will be receiving lots of messages at once and therefore takes load off the servers\n- mentions might want to sned notifications",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 93,
			"containerId": null,
			"originalText": "Extensions\n- how would you handle large groups\n  - could probably change to polling as you will be receiving lots of messages at once and therefore takes load off the servers\n- mentions might want to sned notifications",
			"lineHeight": 1.25
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "#ffec99",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 0.5,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1154.8679374011067,
		"scrollY": -5820.861966407271,
		"zoom": {
			"value": 0.40001220703124996
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
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