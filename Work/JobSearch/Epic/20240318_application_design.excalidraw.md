---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Design a system taht would help devs sepeed up new serveices
- reduce boilerplate code when creating new services
- follow a golden path to production
- implement cross cutting concerns


Replacing an existing system
- current is embedded and linked to a service catalog
- is being depricated
- new service creation has been reported as frustration
  - large cubersome webform / lots of data fields / collect data


Languages
- variation of languages Java/NodeJS etc.
- focus on languages
- out of scope supporting services

Code Level
- bootstrapping
- health endpoints
- cli input
- Invesion of control < expanded scope

Deployment
- deployable in the end
- click run and will be able to go
- developer has no code at the moment
- new API
- CI/CD


CrossCutting Concerns
- Observability
  - metrics
  - logs
  - tracing
- Security
  - HTTPs
  - limit who can call it
- Scalability
  - will be dependant on the service
- Analytics
- Secret management / Config ^u82hntyy

Container (containerd) ^TqFfU9Ci

cmd/main.go ^1J8KdZKY

pkg/base/ ^UOdIP46e

ENV_VARS
- HTTP
- gRPC
- Event Driven
- Tracing
Endpoint ^KrfymSjb

Logs >> stdout ^6VePojqL

SideCar
- service disco
- vault ^Um8Qyac2

Metrics >>
port ^twu2dpAq

Deployment Manifest
- k8s yaml
- kustomize inject config ^hpI5sgQ3

Logger ^2MIriZKu

Trace ^2Mm0WCjJ

Creation of service

- UI backstage
  - cli
  - data

- CLI
  - would ask same questions as above


Would point off to template repos 
- auto create the repo
- would be able to take over the needed files and folders

Final Output
- git command
- git clone <>
- repo

Service Name
- injected into correct places
- templating engine
  - ginger
  - ^FeOvwObD

CICD
- run all tests
- Jenksins
- make  ^59yKZCML

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.24",
	"elements": [
		{
			"type": "text",
			"version": 1127,
			"versionNonce": 1128038798,
			"isDeleted": false,
			"id": "u82hntyy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1603.4267481965835,
			"y": -708.7907183785837,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 1175.1116943359375,
			"height": 1980,
			"seed": 864782482,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Design a system taht would help devs sepeed up new serveices\n- reduce boilerplate code when creating new services\n- follow a golden path to production\n- implement cross cutting concerns\n\n\nReplacing an existing system\n- current is embedded and linked to a service catalog\n- is being depricated\n- new service creation has been reported as frustration\n  - large cubersome webform / lots of data fields / collect data\n\n\nLanguages\n- variation of languages Java/NodeJS etc.\n- focus on languages\n- out of scope supporting services\n\nCode Level\n- bootstrapping\n- health endpoints\n- cli input\n- Invesion of control < expanded scope\n\nDeployment\n- deployable in the end\n- click run and will be able to go\n- developer has no code at the moment\n- new API\n- CI/CD\n\n\nCrossCutting Concerns\n- Observability\n  - metrics\n  - logs\n  - tracing\n- Security\n  - HTTPs\n  - limit who can call it\n- Scalability\n  - will be dependant on the service\n- Analytics\n- Secret management / Config",
			"rawText": "Design a system taht would help devs sepeed up new serveices\n- reduce boilerplate code when creating new services\n- follow a golden path to production\n- implement cross cutting concerns\n\n\nReplacing an existing system\n- current is embedded and linked to a service catalog\n- is being depricated\n- new service creation has been reported as frustration\n  - large cubersome webform / lots of data fields / collect data\n\n\nLanguages\n- variation of languages Java/NodeJS etc.\n- focus on languages\n- out of scope supporting services\n\nCode Level\n- bootstrapping\n- health endpoints\n- cli input\n- Invesion of control < expanded scope\n\nDeployment\n- deployable in the end\n- click run and will be able to go\n- developer has no code at the moment\n- new API\n- CI/CD\n\n\nCrossCutting Concerns\n- Observability\n  - metrics\n  - logs\n  - tracing\n- Security\n  - HTTPs\n  - limit who can call it\n- Scalability\n  - will be dependant on the service\n- Analytics\n- Secret management / Config",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Design a system taht would help devs sepeed up new serveices\n- reduce boilerplate code when creating new services\n- follow a golden path to production\n- implement cross cutting concerns\n\n\nReplacing an existing system\n- current is embedded and linked to a service catalog\n- is being depricated\n- new service creation has been reported as frustration\n  - large cubersome webform / lots of data fields / collect data\n\n\nLanguages\n- variation of languages Java/NodeJS etc.\n- focus on languages\n- out of scope supporting services\n\nCode Level\n- bootstrapping\n- health endpoints\n- cli input\n- Invesion of control < expanded scope\n\nDeployment\n- deployable in the end\n- click run and will be able to go\n- developer has no code at the moment\n- new API\n- CI/CD\n\n\nCrossCutting Concerns\n- Observability\n  - metrics\n  - logs\n  - tracing\n- Security\n  - HTTPs\n  - limit who can call it\n- Scalability\n  - will be dependant on the service\n- Analytics\n- Secret management / Config",
			"lineHeight": 1.25,
			"baseline": 1967
		},
		{
			"type": "rectangle",
			"version": 274,
			"versionNonce": 328277966,
			"isDeleted": false,
			"id": "jbn93Df-XwcQ3_csKLFkB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 171.5308990161011,
			"y": -256.7867854501119,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 838.7681772240666,
			"height": 835.1840927373611,
			"seed": 2112923218,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 86,
			"versionNonce": 607647246,
			"isDeleted": false,
			"id": "TqFfU9Ci",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 396.5150546428408,
			"y": 533.3973073636093,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 388.79986572265625,
			"height": 45,
			"seed": 23858194,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Container (containerd)",
			"rawText": "Container (containerd)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Container (containerd)",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "rectangle",
			"version": 110,
			"versionNonce": 506070094,
			"isDeleted": false,
			"id": "r2f7vU7gcRBAXR1e0TOky",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 249.24798040515998,
			"y": 206.3962402937882,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 242.32503429737608,
			"height": 240.7343082857201,
			"seed": 1408547282,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 44,
			"versionNonce": 591415950,
			"isDeleted": false,
			"id": "1J8KdZKY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 271.0685249880685,
			"y": 304.2633944101226,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 198.68394470214844,
			"height": 45,
			"seed": 883011474,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "cmd/main.go",
			"rawText": "cmd/main.go",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "cmd/main.go",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "rectangle",
			"version": 171,
			"versionNonce": 842254542,
			"isDeleted": false,
			"id": "y58E2hP008cGSY3PZww3t",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 249.2479807025352,
			"y": -177.02940552352175,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 242.32503399999996,
			"height": 306.48212701883193,
			"seed": 1739189586,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 178093838,
			"isDeleted": false,
			"id": "UOdIP46e",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 284.98252695958263,
			"y": -110.55408493993218,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 170.85594177246094,
			"height": 45,
			"seed": 308572946,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "pkg/base/",
			"rawText": "pkg/base/",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "pkg/base/",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "rectangle",
			"version": 106,
			"versionNonce": 284585294,
			"isDeleted": false,
			"id": "b1grSxR0C7xEgVY9XKShL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -241.25885351412853,
			"y": 555.8973071779697,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 278.0734720818464,
			"height": 280,
			"seed": 390611154,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "KrfymSjb"
				}
			],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 133,
			"versionNonce": 1840616910,
			"isDeleted": false,
			"id": "KrfymSjb",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -230.97605424078347,
			"y": 560.8973071779697,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 257.50787353515625,
			"height": 270,
			"seed": 1911314066,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297046,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "ENV_VARS\n- HTTP\n- gRPC\n- Event Driven\n- Tracing\nEndpoint",
			"rawText": "ENV_VARS\n- HTTP\n- gRPC\n- Event Driven\n- Tracing\nEndpoint",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "b1grSxR0C7xEgVY9XKShL",
			"originalText": "ENV_VARS\n- HTTP\n- gRPC\n- Event Driven\n- Tracing\nEndpoint",
			"lineHeight": 1.25,
			"baseline": 257
		},
		{
			"type": "rectangle",
			"version": 111,
			"versionNonce": 1127914386,
			"isDeleted": false,
			"id": "F3jnF9UTbkEh3PRgDZAfY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 303.020349536303,
			"y": 726.9380173842187,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 259.9422071662325,
			"height": 125.73998061096086,
			"seed": 319272018,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710776731391,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 64,
			"versionNonce": 24545294,
			"isDeleted": false,
			"id": "6VePojqL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 303.56537044381366,
			"y": 768.3973072439958,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 271.1159362792969,
			"height": 45,
			"seed": 1014061586,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Logs >> stdout",
			"rawText": "Logs >> stdout",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Logs >> stdout",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "rectangle",
			"version": 52,
			"versionNonce": 969299534,
			"isDeleted": false,
			"id": "nnNAsbHPTgxpDyNUh5BW_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1027.401446567429,
			"y": -256.78678510263126,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 487.4618922877007,
			"height": 835.1840920000001,
			"seed": 1562396626,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 132,
			"versionNonce": 1803705486,
			"isDeleted": false,
			"id": "Um8Qyac2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1185.51699664416,
			"y": -207.82291256040162,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 255.9238739013672,
			"height": 135,
			"seed": 1831566738,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "SideCar\n- service disco\n- vault",
			"rawText": "SideCar\n- service disco\n- vault",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SideCar\n- service disco\n- vault",
			"lineHeight": 1.25,
			"baseline": 122
		},
		{
			"type": "rectangle",
			"version": 77,
			"versionNonce": 207854286,
			"isDeleted": false,
			"id": "eQlVW4fqnxsWbYnEa-qNN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 590.9149880494929,
			"y": 728.0273165140811,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 259.9422071662325,
			"height": 125.73998061096086,
			"seed": 1237973842,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "twu2dpAq"
				}
			],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 1851632654,
			"isDeleted": false,
			"id": "twu2dpAq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 630.1301330754802,
			"y": 745.8973068195615,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 181.5119171142578,
			"height": 90,
			"seed": 290636050,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297046,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Metrics >>\nport",
			"rawText": "Metrics >>\nport",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "eQlVW4fqnxsWbYnEa-qNN",
			"originalText": "Metrics >>\nport",
			"lineHeight": 1.25,
			"baseline": 77
		},
		{
			"type": "rectangle",
			"version": 411,
			"versionNonce": 987348814,
			"isDeleted": false,
			"id": "eCDYRN7bS3kPvxHMJIzUP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 82.22920689174134,
			"y": -342.84890179158356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1463.1975413048417,
			"height": 1030.1701697572244,
			"seed": 2134691538,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 155,
			"versionNonce": 675325326,
			"isDeleted": false,
			"id": "LIHubVl3yaHaDK9zPW2qE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 927.5715057475227,
			"y": -756.069803057957,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 617.8552419550136,
			"height": 368.4742476434067,
			"seed": 1210000530,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 159,
			"versionNonce": 208716750,
			"isDeleted": false,
			"id": "hpI5sgQ3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 989.9456393152886,
			"y": -706.832679367295,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 430.41583251953125,
			"height": 135,
			"seed": 1974518354,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Deployment Manifest\n- k8s yaml\n- kustomize inject config",
			"rawText": "Deployment Manifest\n- k8s yaml\n- kustomize inject config",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Deployment Manifest\n- k8s yaml\n- kustomize inject config",
			"lineHeight": 1.25,
			"baseline": 122
		},
		{
			"type": "rectangle",
			"version": 202,
			"versionNonce": 696457742,
			"isDeleted": false,
			"id": "bN6CBuFUJgBr5PYMapcko",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 518.8465486363834,
			"y": -172.5561850352883,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 242.32503399999996,
			"height": 84.50209993265753,
			"seed": 1120446482,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "2MIriZKu"
				}
			],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 12,
			"versionNonce": 1177090638,
			"isDeleted": false,
			"id": "2MIriZKu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 583.6330814444889,
			"y": -152.80513506895954,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 112.75196838378906,
			"height": 45,
			"seed": 2002638290,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297047,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Logger",
			"rawText": "Logger",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "bN6CBuFUJgBr5PYMapcko",
			"originalText": "Logger",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "rectangle",
			"version": 229,
			"versionNonce": 588410510,
			"isDeleted": false,
			"id": "7RXvqrsTVfBXgM0jBFSfu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 518.8465488918027,
			"y": -80.50967476533924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 242.32503399999996,
			"height": 84.50209993265753,
			"seed": 1149717394,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "2Mm0WCjJ"
				}
			],
			"updated": 1710775297045,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 468746382,
			"isDeleted": false,
			"id": "2Mm0WCjJ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 586.9090826764707,
			"y": -60.75862479901048,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 106.19996643066406,
			"height": 45,
			"seed": 544999762,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297047,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Trace",
			"rawText": "Trace",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "7RXvqrsTVfBXgM0jBFSfu",
			"originalText": "Trace",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "text",
			"version": 559,
			"versionNonce": 1328980750,
			"isDeleted": false,
			"id": "FeOvwObD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -349.7129367625771,
			"y": -1989.0999066214172,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1042.4876708984375,
			"height": 1080,
			"seed": 580062994,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775297045,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "Creation of service\n\n- UI backstage\n  - cli\n  - data\n\n- CLI\n  - would ask same questions as above\n\n\nWould point off to template repos \n- auto create the repo\n- would be able to take over the needed files and folders\n\nFinal Output\n- git command\n- git clone <>\n- repo\n\nService Name\n- injected into correct places\n- templating engine\n  - ginger\n  -",
			"rawText": "Creation of service\n\n- UI backstage\n  - cli\n  - data\n\n- CLI\n  - would ask same questions as above\n\n\nWould point off to template repos \n- auto create the repo\n- would be able to take over the needed files and folders\n\nFinal Output\n- git command\n- git clone <>\n- repo\n\nService Name\n- injected into correct places\n- templating engine\n  - ginger\n  -",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Creation of service\n\n- UI backstage\n  - cli\n  - data\n\n- CLI\n  - would ask same questions as above\n\n\nWould point off to template repos \n- auto create the repo\n- would be able to take over the needed files and folders\n\nFinal Output\n- git command\n- git clone <>\n- repo\n\nService Name\n- injected into correct places\n- templating engine\n  - ginger\n  -",
			"lineHeight": 1.25,
			"baseline": 1067
		},
		{
			"type": "rectangle",
			"version": 255,
			"versionNonce": 666309070,
			"isDeleted": false,
			"id": "2oOyvALqnayJELRVIrY2F",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 129.67536591841645,
			"y": -755.7036758805586,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 617.8552419550136,
			"height": 368.4742476434067,
			"seed": 1598250194,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "59yKZCML"
				}
			],
			"updated": 1710775311864,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 107,
			"versionNonce": 1657776142,
			"isDeleted": false,
			"id": "59yKZCML",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 306.62703474748577,
			"y": -661.4665520588553,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 263.951904296875,
			"height": 180,
			"seed": 1143206546,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710775311864,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "CICD\n- run all tests\n- Jenksins\n- make ",
			"rawText": "CICD\n- run all tests\n- Jenksins\n- make ",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "2oOyvALqnayJELRVIrY2F",
			"originalText": "CICD\n- run all tests\n- Jenksins\n- make ",
			"lineHeight": 1.25,
			"baseline": 167
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1991.857142857143,
		"scrollY": 2868.597237723214,
		"zoom": {
			"value": 0.35000000000000003
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