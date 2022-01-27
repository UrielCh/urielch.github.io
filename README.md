# My Github pages

Hi, After a decade of Java developpement, I was upset by the slow evolution of Java, I switch to `nodeJS` for my new project. It was hard to give up years of Java experience.

So I early adopted Typescript to keep strict typing; that was not easy at the time, because most projects had no typing.

Since, I convert to typescript most of the project I use if I do not find a proper typing in [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped).

Within the almost 100 projects that I converted to typescript, 99% of them had bug reval by converting them to Typescript.

## There is some of my forked project

### Personal public projects

| Project name                                                                                                 | Description                                                                                       |
|--------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
|[voicemaker-api](https://github.com/UrielCh/voicemaker)                                                       | Use TTS from nodejs project, give access to [voicemaker](https://voicemaker.in/) TTS engine.      |
|[proxmox-api](https://github.com/UrielCh/proxmox-api)                                                         | A super easy api to control Proxmox server                                                        |
|[proxmox-usb-hotplug](https://github.com/UrielCh/proxmox-api/tree/master/proxmox-usb-hotplug)                 | Transforme a Proxmox server to a usable PC/Mac, by adding hotplug USB devices to a main VM        |
|[zombie-plugin](https://github.com/UrielCh/zombie-plugin)                                                     | A sandbox Chrome plugin that can do mostly anything except :coffee:, (Set proxy, read QR-code on screen, run automatic test, archive cookies...) |
|[api-ovh-node](https://github.com/UrielCh/api-ovh-node)                                                       | A massive signle repo, containing my OVH-Cloud API SDK                                  |
|[ovh-bill-importer](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-bill-importer)            | Export your OVH-Cloud billing for your accounting.                                      |
|[ovh-cleaner](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-cleaner)                        | Cleanup you OVH-Cloud Account                                                           |
|[ovh-telephony-dump-consumption](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-delete-service)| Download OVH-Cloud current month telephony consumption                                |
|[ovh-dump-telephony](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-dump-telephony)          | Simply dump your OVH-Cloud telephony services                                           |
|[ovh-dynhost2](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-dynhost2)                      | Maintain an Dynamic Dns Host IP value, or a regular DNS entry with a 60 sec TTL         |
|[ovh-move-failover](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-move-failover)            | Command line utility to move your IP-Failover on OVH-Cloud server                       |
|[ovh-telephony-events](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-telephony-events)      |Import OVH-Cloud Api Events to a queueing service (Redis) so it can be easily integrate to your system |
|[ovh-upload-doc](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-upload-doc)                  | CLI tool to upload document to an OVH bucket                                            |
|[ovh-vps-config-failover](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-vps-config-failover)| Quickly configure OVH-Cloud Server IP-Failover                                          |
|[node-dev-input-reader](https://github.com/UrielCh/node-dev-input-reader)                                     | Read input from /dev/input/* on a linux Host for Action triggering (I use it to switch OS on my Proxmox Desktop PCs) |
|[webRobotJS](https://github.com/UrielCh/webRobotJS)                                                           | Controls your mouse / keyboard with http.Requests                                         |
|[yealink](https://github.com/UrielCh/yealink)                                                                 | Controls your Yealink phone from you node.project                                         |
|[puppeteer-jquery](https://github.com/UrielCh/puppeteer-jquery/tree/master/puppeteer-jquery)                  | Use JQuery selector in your Putteter Code with the same syntax you would use a browser.   |
|[playwright-jquery](https://github.com/UrielCh/puppeteer-jquery/tree/master/playwright-jquery)                | Use JQuery selector in your Playwright Code with the same syntax you would use a browser. |
|[@u4/prime](https://www.npmjs.com/package/@u4/prime)                                                          | Because Prime number generator on NPM are all :shit:, I had to make my own.               |
|[mitemp2prometheus](https://github.com/UrielCh/mitemp2prometheus)                                             | Export Xiaomi Bluetooth thermometer data to an Prometheus server. This one is python :expressionless: |
|[FtpArchiveCleaner](https://github.com/UrielCh/FtpArchiveCleaner/blob/master/index.js)                        | A simple FTP Archive cleaner to respond to "I want to Keep a X Backup a week, Y backup a month, Z backup a Year." that should be use as a job interview question |
|[mirror-selector](https://github.com/UrielCh/mirror-selector)                                                 | Lib to find the best link to access a service.                                           |
|[serve4code](https://www.npmjs.com/package/serve4code)                                                        | Integrate a webcallback to a non web project.                                            |
|[@u4/spice](https://www.npmjs.com/package/@u4/spice) | Manage hundruds of VM on multiple proxmox (No documentation yet, some generalisation needed + need to publish source code). |
|[@u4/http-proxy](https://github.com/UrielCh/http-proxy) | An Http proxy server in typescript. |
|[@u4/tinyrequest](https://www.npmjs.com/package/@u4/tinyrequest) | Tiny Http Request Helper for nodejs, to build small webpacked js script 300Ko smaller that common packages. |
|[wireguard key manager](https://github.com/UrielCh/wireguard) | Bash script to create and manage wireguard keys |

### Forked projects

| Project name | Description | change | merged |
|--------------|-------------|--------|--------|
|[rpio-pwm](https://github.com/UrielCh/rpio-pwm)                                          | Access GPIO                                  | Make It works with nodeJS 8+ add support for RGBW strip              | No     |
|[robotjs](https://github.com/UrielCh/robotjs)                                            | Emulate keyboard / mouse                     | Change calls return to give duration in ms.                          | No     |
|[rpi-ws281x](https://github.com/UrielCh/rpi-ws281x)                                      | Control ws281x chips a raspberry pi          | Upgrade native code to works with nodeJS 8+                          | No     |
|[commander.js](https://github.com/UrielCh/commander.js)                                  | MERGED the famous commander.JS               | Improve Typing                                                       | Yes    |
|[chromeExtensionAsync](https://github.com/UrielCh/chromeExtensionAsync)                  | Typing for Chrome browser                    | Add some missing call in typing                                      | No     |
|[node-worker-threads-pool-ts](https://www.npmjs.com/package/node-worker-threads-pool-ts) | Use worker in threads pool                   | Add progress events / convert to typescript                          | No     |
|[node-dhcp](https://github.com/UrielCh/node-dhcp)                                         | A pure NodeJS DHCP server                    | Convert to Typescript and rewrite most of the code                   | [on Hold](https://github.com/nodejs/node/issues/35769) |
|[adbkit](https://github.com/UrielCh/adbkit)                                                   | An Android-Device-Bridge wrapper for Nodejs  | Convert to Typescript and make it more Object Oriented               | Yes    |
|[telephony-example-cti-dashboard](https://github.com/UrielCh/telephony-example-cti-dashboard) | A website monitor OVH-Cloud VOIP Lines       | Convert to Typescript to make it more readable                       | Discontinued |
|[reganam](https://github.com/UrielCh/reganam)                                                 | An OVH-Cloud dashboard                       | convert to Typsecript to plug it to my OVH-Cloud API, and test React | No     |
|[alpine-ts](https://www.npmjs.com/package/alpine-ts)                                           | An apache log parser                         | convert to Typsecript + reduce bundle size + add features            | No     |
|[puppeteer-extra](https://www.npmjs.com/package/puppeteer-extra)                               | Plugins for puppeter                         | convert to Typsecript + adding features, PRs in progress...          | inProgress |
|[github:UrielCh/ejs](https://github.com/UrielCh/ejs)       | Embedded JavaScript templates     | Add i18n feature keeping ejs file size unchanged | No   |
|[@u4/adbkit](https://www.npmjs.com/package/@u4/adbkit)     | Android Device Bridge for NodeJs  | Converted to Typescript + add features           | Yes + hard fork |
|[@u4/opencv-build](https://www.npmjs.com/package/@u4/opencv-build) | opencv build helper for NodeJs | Enforce Typescript code, + big changes      | Can not contact author, hard fork |
|[@u4/opencv4nodejs](https://www.npmjs.com/package/@u4/opencv4nodejs)| nodeJS Wrapper for OpenCV     | Convert project to typescript + extend project  | Can not contact author, hard fork |

## Web-Services / internal project

| Project address    | Description                                             | stack |  status  |
|--------------------|---------------------------------------------------------|----|----------|
| [track.over.ovh](https://track.over.ovh/)   | tracker build for yealink phones, make it easy to connect VOIP to a CRM | TS / nestJS / Redis / mongoDB | in production |
| gophone     | Capture an push IP captured data to a REDIS stream                                                          | GOlang | retired |
| dootab      | kiosk mode for android with content sync, for restaurant usage                                              | Android / Java | retired |
| visual V1          | interface to display VOIP activity based on network captered IP data                                 | JS / AngularJs 1.3 / Bootstrap / JQuery | retired |
| rec.over.ovh V1    | REST API collect OVH VOIP events                                                                     | Java / Kafka / Mysql / pcap        | retired |
| visual V2          | interface to display VOIP activity based on network captered IP data                                 | TS / express / redis / bitbucket   | retired |
| rec.over.ovh v2    | REST API collect OVH VOIP events                                                                     | TS / express / mongoDB / handlebars| retired |
| [visual.over.ovh V3](https://visual.over.ovh/) | sample interface to display your track.over.ovh event                    | TS / vuejs 3 / tailwindCSs         | in production |
| [rec.over.ovh v3](https://rec.over.ovh/)       | API to imprort and request Ovh request                                   | TS / nestJS / mongoDB / ejs | in production |
| --- rec-viewer --- | Interface to search / listen / comment records from rec.over.ovh                                     | Angular 5 / primeNG / bitbucket | deprecated |
| botcop.click       | Rules based fraud-click programe, working without external server, detect most fraud, generate Execl files + IPs block list | TS   | internal only |
| ---no name---      | Nodejs automation script to controle multiple phones.                                                                      | TS / levelDB / openCV / adb / tesseract | internal only |
| ---dyn-proxy---    | Smart whitelist based http-proxy used to secure office intranet (need need to be convert to public service) | TS / fastify / jQuery / Bootstrap  | internal only |
| ---workspaces---   | Proxmox + RDP + raspberry pi + dyn-proxy + PXE low cost highly secure office environnement (to be convert for pupic usage) | TS / iptables / dnsmasq / bash | internal only |
| --u4-dhcp-office-- | Nodejs bundle httpproxy + dhcpserver + backoffice + iptables + ip route (iptables / ip helper ...)                         | TS / express / jQuery / Bootstrap | to publish |
|  playImap     | recices and recognize voice mail and push message in base for further usage                                                     | TS / Google cloud / ffmpeg    | deprecated |
|  code-reader  | recices and recognize code send to your phone when you do not have you phone                                                    | TS / Google cloud / ffmpeg    | in production |

## Java projects from a distant past

| Project name                                                                                 | Description                                         |
|----------------------------------------------------------------------------------------------|-----------------------------------------------------|
|[json-smart-v2](https://github.com/netplex/json-smart-v2)                                     | A JSON parser for JAVA                              |
|[json-smart-v1](https://github.com/netplex/json-smart-v1)                                     | A JSON parser for JAVA                              |
|[ovh-java-sdk](https://github.com/UrielCh/ovh-java-sdk)                                       | An API client for OVH-Cloud                         |
|[enhanced-vnc-thumbnail-viewer](https://github.com/UrielCh/enhanced-vnc-thumbnail-viewer)     | Forcked version of a muti-VNC viewer with bug Fixed |

## Misc

[daily used npm libs](./favorite.md)

## PGP

My PGP public sign: [0x1D0690E353BE126D](https://pgp.mit.edu/pks/lookup?op=get&search=0x1D0690E353BE126D)
