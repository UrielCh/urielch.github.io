# My Github pages

Hi, After a decade of Java developpement, I was upset by the slow evolution of Java, I switch to `nodeJS` for my new project. It was hard to give up years of Java experience.

So I early adopted Typescript to keep strict typing; that was not easy at the time, because most projects had no typing.

Since, I convert to typescript most of the project I use if I do not find a proper typing in [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped).

Within the almost 100 projects that I converted to typescript, 99% of them had bug reval by converting them to Typescript.

## There is some of my forked project

### Personal public projects

| Type | Project name                                                                                                 | Description                                                                                       |
|------|--------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| API |[voicemaker-api](https://github.com/UrielCh/voicemaker)                                                       | Use TTS from nodejs project, give access to [voicemaker](https://voicemaker.in/) TTS engine.      |
| API |[proxmox-api](https://github.com/UrielCh/proxmox-api)                                                         | A super easy api to control Proxmox server                                                        |
| Virtualisation |[proxmox-usb-hotplug](https://github.com/UrielCh/proxmox-api/tree/master/proxmox-usb-hotplug)                 | Transforme a Proxmox server to a usable PC/Mac, by adding hotplug USB devices to a main VM        |
| Automation |[zombie-plugin](https://github.com/UrielCh/zombie-plugin)                                                     | A sandbox Chrome plugin that can do mostly anything except :coffee:, (Set proxy, read QR-code on screen, run automatic test, archive cookies...) |
| API |[api-ovh-node](https://github.com/UrielCh/api-ovh-node)                                                       | A massive signle repo, containing my OVH-Cloud API SDK                                  |
| Acounting |[ovh-bill-importer](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-bill-importer)            | Export your OVH-Cloud billing for your accounting.                                      |
| Cloud |[ovh-cleaner](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-cleaner)                        | Cleanup you OVH-Cloud Account                                                           |
| VOIP |[ovh-telephony-dump-consumption](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-delete-service)| Download OVH-Cloud current month telephony consumption                                |
| VOIP |[ovh-dump-telephony](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-dump-telephony)          | Simply dump your OVH-Cloud telephony services                                           |
| Hosting |[ovh-dynhost2](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-dynhost2)                      | Maintain an Dynamic Dns Host IP value, or a regular DNS entry with a 60 sec TTL         |
| Networing |[ovh-move-failover](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-move-failover)            | Command line utility to move your IP-Failover on OVH-Cloud server                       |
| VOIP  |[ovh-telephony-events](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-telephony-events)      |Import OVH-Cloud Api Events to a queueing service (Redis) so it can be easily integrate to your system |
| Cloud |[ovh-upload-doc](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-upload-doc)                  | CLI tool to upload document to an OVH bucket                                            |
| Networing |[ovh-vps-config-failover](https://github.com/UrielCh/api-ovh-node/tree/master/samples/ovh-vps-config-failover)| Quickly configure OVH-Cloud Server IP-Failover                                          |
| OS |[node-dev-input-reader](https://github.com/UrielCh/node-dev-input-reader)                                     | Read input from /dev/input/* on a linux Host for Action triggering (I use it to switch OS on my Proxmox Desktop PCs) |
| Automation |[webRobotJS](https://github.com/UrielCh/webRobotJS)                                                           | Controls your mouse / keyboard with http.Requests                                         |
| VOIP |[yealink](https://github.com/UrielCh/yealink)                                                                 | Controls your Yealink phone from you node.project                                         |
| Automation |[puppeteer-jquery](https://github.com/UrielCh/puppeteer-jquery/tree/master/puppeteer-jquery)                  | Use JQuery selector in your Putteter Code with the same syntax you would use a browser.   |
| Automation |[playwright-jquery](https://github.com/UrielCh/puppeteer-jquery/tree/master/playwright-jquery)                | Use JQuery selector in your Playwright Code with the same syntax you would use a browser. |
| Algorithmic |[@u4/prime](https://www.npmjs.com/package/@u4/prime)                                                          | Because Prime number generator on NPM are all :shit:, I had to make my own.               |
| IoT / Monitoring |[mitemp2prometheus](https://github.com/UrielCh/mitemp2prometheus)                                             | Export Xiaomi Bluetooth thermometer data to an Prometheus server. This one is python :expressionless: |
| Backup |[FtpArchiveCleaner](https://github.com/UrielCh/FtpArchiveCleaner/blob/master/index.js)                        | A simple FTP Archive cleaner to respond to "I want to Keep a X Backup a week, Y backup a month, Z backup a Year." that should be use as a job interview question |
| Optimisation |[mirror-selector](https://github.com/UrielCh/mirror-selector)                                                 | Lib to find the best link to access a service.                                           |
| UX |[serve4code](https://www.npmjs.com/package/serve4code)                                                        | Integrate a webcallback to a non web project.                                            |
| Virtualisation |[@u4/spice](https://www.npmjs.com/package/@u4/spice)     | Manage hundruds of VM on multiple proxmox (No documentation yet, some generalisation needed + need to publish source code). |
| SysOps |[@u4/http-proxy](https://github.com/UrielCh/http-proxy)  | An Http proxy server in typescript. |
| NodeJS |[@u4/tinyrequest](https://www.npmjs.com/package/@u4/tinyrequest) | Tiny Http Request Helper for nodejs, to build small webpacked js script 300Ko smaller that common packages. |
| VPN |[wireguard key manager](https://github.com/UrielCh/wireguard) | Bash script to create and manage wireguard keys |
| UX | [gamepad-ts](https://www.npmjs.com/package/gamepad-ts) | Access gamepad from Nodejs + intermap different Pad brand |
| Automation |[cdp-reverter](https://www.npmjs.com/package/cdp-reverter)    |  Generate Chrome DevTools Protocol Session code from a listen-to session. |
| Automation |[remote-droid](https://hub.docker.com/r/urielch/remote-droid) |  Share your remote device via an HTTP REST API  |
| Kubernetes |[dyn-ingress](https://hub.docker.com/repository/docker/urielch/dyn-ingress) |  Maintain Ingress and Services to each Pod in a Deployement, DaemonSet, StateFulset|



### Divergent Forked projects
Those project contains to much change to be merged.

| Project name | Description | change |
|--------------|-------------|--------|
|[adbkit](https://urielch.github.io/adbkit/)                                          | An Android-Device-Bridge wrapper for Nodejs  | add lots of third party features |
|[@u4/opencv-build](https://www.npmjs.com/package/@u4/opencv-build) | opencv build helper for NodeJs | ported to typescript, now the official version :+1: |
|[@u4/opencv4nodejs](https://www.npmjs.com/package/@u4/opencv4nodejs)| nodeJS Wrapper for OpenCV     | ported to typescript, now the official version :+1: |
|[@u4/chrome-remote-interface](https://github.com/UrielCh/ChromeDevToolsProtocol)   | client for chrome-remote-interface    | Converted to deno mostly rewrited |




### Forked projects

| Type | Project name | Description | change | merged |
|------|--------------|-------------|--------|--------|
| IoT  |[rpio-pwm](https://github.com/UrielCh/rpio-pwm)                                          | Access GPIO                                  | Make It works with nodeJS 8+ add support for RGBW strip              | No     |
| Automation |[robotjs](https://github.com/UrielCh/robotjs)                                            | Emulate keyboard / mouse                     | Change calls return to give duration in ms.                          | No     |
| IoT |[rpi-ws281x](https://github.com/UrielCh/rpi-ws281x)                                      | Control ws281x chips a raspberry pi          | Upgrade native code to works with nodeJS 8+                          | No     |
| NodeJs |[commander.js](https://github.com/UrielCh/commander.js)                                  | MERGED the famous commander.JS               | Improve Typing                                                       | Yes    |
| Automation |[chromeExtensionAsync](https://github.com/UrielCh/chromeExtensionAsync)                  | Typing for Chrome browser                    | Add some missing call in typing                                      | No     |
| Optimisation |[node-worker-threads-pool-ts](https://www.npmjs.com/package/node-worker-threads-pool-ts) | Use worker in threads pool                   | Add progress events / convert to typescript / support typescritp worker | No     |
| Networking |[node-dhcp](https://github.com/UrielCh/node-dhcp)                                         | A pure NodeJS DHCP server                    | Convert to Typescript and rewrite most of the code                   | [on Hold](https://github.com/nodejs/node/issues/35769) |
| Automation |[adbkit](https://github.com/UrielCh/adbkit)                                                   | An Android-Device-Bridge wrapper for Nodejs  | Convert to Typescript and make it more Object Oriented               | Yes    |
| UI |[telephony-example-cti-dashboard](https://github.com/UrielCh/telephony-example-cti-dashboard) | A website monitor OVH-Cloud VOIP Lines       | Convert to Typescript to make it more readable                       | Discontinued |
| UI |[reganam](https://github.com/UrielCh/reganam)                                                 | An OVH-Cloud dashboard                       | convert to Typescript to plug it to my OVH-Cloud API, and test React | No     |
| Admin |[alpine-ts](https://www.npmjs.com/package/alpine-ts)                                           | An apache log parser                         | convert to Typescript + reduce bundle size + add features            | No     |
| Automation |[puppeteer-extra](https://www.npmjs.com/package/puppeteer-extra)                               | Plugins for puppeter                         | convert to Typescript + adding features, PRs in progress...          | inProgress |
| Templating |[github:UrielCh/ejs](https://github.com/UrielCh/ejs)       | Embedded JavaScript templates     | Add i18n feature keeping ejs file size unchanged | No   |
| Automation |[@u4/adbkit](https://www.npmjs.com/package/@u4/adbkit)     | Android Device Bridge for NodeJs  | Converted to Typescript + add features           | Yes |
| Video Processing |[@u4/beamcoder](https://github.com/UrielCh/beamcoder)   | nodejs Wrapper for ffmpeg lib          | Converted to typescript   | segfault on large stream. |
| Deno | [node_deno_shims](https://github.com/denoland/node_deno_shims) | Deno shims for Node.js      | add napping  | Yes |


## Web-Services / internal project

| Type | Project address    | Description                                             | stack |  status  |
|------|--------------------|---------------------------------------------------------|----|----------|
| VOIP | [track.over.ovh](https://track.over.ovh/)   | tracker build for yealink phones, make it easy to connect VOIP to a CRM | TS / nestJS / Redis / mongoDB | in production |
| VOIP | gophone     | Capture an push IP captured data to a REDIS stream                                                          | GOlang | retired |
| IoT  | dootab  | kiosk mode for android with content sync, for restaurant usage                                              | Android / Java | retired |
| VOIP | visual V1          | interface to display VOIP activity based on network captered IP data                                 | JS / AngularJs 1.3 / Bootstrap / JQuery | retired |
| VOIP | rec.over.ovh V1    | REST API collect OVH VOIP events                                                                     | Java / Kafka / Mysql / pcap        | retired |
| VOIP | visual V2          | interface to display VOIP activity based on network captered IP data                                 | TS / express / redis / bitbucket   | retired |
| VOIP | rec.over.ovh v2    | REST API collect OVH VOIP events                                                                     | TS / express / mongoDB / handlebars| retired |
| VOIP | [visual.over.ovh V3](https://visual.over.ovh/) | sample interface to display your track.over.ovh event                    | TS / vuejs 3 / tailwindCSs         | in production |
| VOIP | [rec.over.ovh v3](https://rec.over.ovh/)       | API to imprort and request Ovh request                                   | TS / nestJS / mongoDB / ejs | in production |
| VOIP | --- rec-viewer --- | Interface to search / listen / comment records from rec.over.ovh                                     | Angular 5 / primeNG / bitbucket | deprecated |
| Security | botcop.click       | Rules based fraud-click programe, working without external server, detect most fraud, generate Execl files + IPs block list | TS   | internal only |
| Automation | Droid-pilot  | Nodejs automation script to controle multiple phones.                                                          | TS / levelDB / openCV / adb / tesseract Kubernetes | internal only |
| Security | ---dyn-proxy---   | Smart whitelist based http-proxy used to secure office intranet (need need to be convert to public service) | TS / fastify / jQuery / Bootstrap  | to publish |
| Security | ---workspaces---   | Proxmox + RDP + raspberry pi + dyn-proxy + PXE low cost highly secure office environnement (to be convert for pupic usage) | TS / iptables / dnsmasq / bash | internal only |
| Networking | --u4-dhcp-office-- | Nodejs bundle httpproxy + dhcpserver + backoffice + iptables + ip route (iptables / ip helper ...)                         | TS / express / jQuery / Bootstrap | to publish |
| Automation |  playImap     | receives and recognize voice mail and push message in base for further usage                                                    | TS / Google cloud / ffmpeg    | deprecated |
| Automation |  code-reader  | receives and recognize code send to your phone when you do not have you phone                                                   | TS / Google cloud / ffmpeg    | in production |
| Monitoring |  tel-rotate   | monitor callcenter incomming call, and change lines configuration depending on call volume, can also change public number on website | TS / voicemaker-api      | in production |

## Java projects from a distant past

| Project name                                                                                 | Description                                         |
|----------------------------------------------------------------------------------------------|-----------------------------------------------------|
|[json-smart-v2](https://github.com/netplex/json-smart-v2)                                     | A JSON parser for JAVA                              |
|[json-smart-v1](https://github.com/netplex/json-smart-v1)                                     | A JSON parser for JAVA                              |
|[ovh-java-sdk](https://github.com/UrielCh/ovh-java-sdk)                                       | An API client for OVH-Cloud                         |
|[enhanced-vnc-thumbnail-viewer](https://github.com/UrielCh/enhanced-vnc-thumbnail-viewer)     | Forked version of a muti-VNC viewer with bug Fixed |

## Misc

[daily used npm libs](./favorite.md)

## PGP

My PGP public sign: [0x1D0690E353BE126D](https://pgp.mit.edu/pks/lookup?op=get&search=0x1D0690E353BE126D)
