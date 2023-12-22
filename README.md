port: 7890
socks-port: 7891
allow-lan: true
bind-address: '*'
mode: rule
log-level: info
ipv6: true
external-controller: '127.0.0.1:9090'
dns:
    enable: true
    ipv6: false
    listen: '0.0.0.0:53'
    enhanced-mode: redir-host
    nameserver: [117.50.10.10, 119.29.29.29, 114.114.114.114, 223.5.5.5, 223.6.6.6]
    Auto: ['tls://1.1.1.1:853', 'tls://1.0.0.1:853', 'tls://dns.google:853']
proxies:
    - { name: US_Reality_Node_1, type: vless, server: us1.speed-mitce.top, port: 80, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: US_Reality_Node_2, type: vless, server: us2.speed-mitce.top, port: 443, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: US_Reality_Node_3, type: vless, server: us3.speed-mitce.top, port: 10203, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: US_Reality_Node_4, type: vless, server: us4.speed-mitce.top, port: 8888, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { type: hysteria2, name: US_hysteria2_Node_5, server: hy2us.speed-mitce.top, port: 37062, password: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, sni: hy2usa.vtor.io }
    - { name: JP_Reality_Node_1, type: vless, server: jp1.speed-mitce.top, port: 80, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: JP_Reality_Node_2, type: vless, server: jp2.speed-mitce.top, port: 443, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: JP_Reality_Node_3, type: vless, server: jp3.speed-mitce.top, port: 10203, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: JP_Reality_Node_4, type: vless, server: jp4.speed-mitce.top, port: 8888, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { type: hysteria2, name: JP_hysteria2_Node_5, server: hy2jp.speed-mitce.top, port: 39148, password: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, sni: hy2jp.vtor.io }
    - { name: SG_Reality_Node_1, type: vless, server: sg1.speed-mitce.top, port: 80, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: SG_Reality_Node_2, type: vless, server: sg2.speed-mitce.top, port: 443, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: SG_Reality_Node_3, type: vless, server: sg3.speed-mitce.top, port: 10203, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: SG_Reality_Node_4, type: vless, server: sg4.speed-mitce.top, port: 8888, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { type: hysteria2, name: SG_hysteria2_Node_5, server: hy2sg.speed-mitce.top, port: 26000, password: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, sni: hy2sg.vtor.io }
    - { name: UK_Reality_Node_1, type: vless, server: uk1.speed-mitce.top, port: 80, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: UK_Reality_Node_2, type: vless, server: uk2.speed-mitce.top, port: 443, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: UK_Reality_Node_3, type: vless, server: uk3.speed-mitce.top, port: 10203, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { name: UK_Reality_Node_4, type: vless, server: uk4.speed-mitce.top, port: 8888, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: s0.awsstatic.com, reality-opts: { public-key: dR1QmDjsiujobG0AxdPdsom9gNkgf8qnJglB49-XclM, short-id: 01fc5e98a68e5e7b } }
    - { type: hysteria2, name: HK_hysteria2_Node_5, server: hy2hk.speed-mitce.top, port: 39722, password: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, sni: hy2hk.vtor.io }
    - { name: HK_Reality_Node_1, type: vless, server: hk1.speed-mitce.top, port: 10010, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: updates.cdn-apple.com, reality-opts: { public-key: VeSd-1DDMfD2iPPGmU4V9182toJsKrseyhBsrp_zhAo, short-id: 01fc5e98a68e5e7b } }
    - { name: HK_Reality_Node_2, type: vless, server: hk2.speed-mitce.top, port: 10011, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: updates.cdn-apple.com, reality-opts: { public-key: VeSd-1DDMfD2iPPGmU4V9182toJsKrseyhBsrp_zhAo, short-id: 01fc5e98a68e5e7b } }
    - { name: HK_Reality_Node_3, type: vless, server: hk3.speed-mitce.top, port: 10203, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: updates.cdn-apple.com, reality-opts: { public-key: VeSd-1DDMfD2iPPGmU4V9182toJsKrseyhBsrp_zhAo, short-id: 01fc5e98a68e5e7b } }
    - { name: HK_Reality_Node_4, type: vless, server: hk4.speed-mitce.top, port: 8888, uuid: E85AF974-F0BD-4906-89CD-BE99E7F36745, udp: true, tls: true, flow: xtls-rprx-vision, client-fingerprint: chrome, servername: updates.cdn-apple.com, reality-opts: { public-key: VeSd-1DDMfD2iPPGmU4V9182toJsKrseyhBsrp_zhAo, short-id: 01fc5e98a68e5e7b } }
proxy-groups:
    - { name: 'Main Node', type: select, proxies: ['Auto Choose', US_Reality_Node_1, US_Reality_Node_2, US_Reality_Node_3, US_Reality_Node_4, US_hysteria2_Node_5, JP_Reality_Node_1, JP_Reality_Node_2, JP_Reality_Node_3, JP_Reality_Node_4, JP_hysteria2_Node_5, SG_Reality_Node_1, SG_Reality_Node_2, SG_Reality_Node_3, SG_Reality_Node_4, SG_hysteria2_Node_5, UK_Reality_Node_1, UK_Reality_Node_2, UK_Reality_Node_3, UK_Reality_Node_4, HK_hysteria2_Node_5, HK_Reality_Node_1, HK_Reality_Node_2, HK_Reality_Node_3, HK_Reality_Node_4] }
    - { name: 'HK Nodes', type: url-test, proxies: [HK_Reality_Node_1, HK_Reality_Node_2, HK_Reality_Node_3, HK_Reality_Node_4, HK_hysteria2_Node_5], url: 'http://www.gstatic.com/generate_204', interval: 300 }
    - { name: 'Apple Services', type: select, proxies: ['Main Node', 'Auto Choose', US_Reality_Node_1, US_Reality_Node_2, US_Reality_Node_3, US_Reality_Node_4, US_hysteria2_Node_5, JP_Reality_Node_1, JP_Reality_Node_2, JP_Reality_Node_3, JP_Reality_Node_4, JP_hysteria2_Node_5, SG_Reality_Node_1, SG_Reality_Node_2, SG_Reality_Node_3, SG_Reality_Node_4, SG_hysteria2_Node_5, UK_Reality_Node_1, UK_Reality_Node_2, UK_Reality_Node_3, UK_Reality_Node_4, HK_hysteria2_Node_5, HK_Reality_Node_1, HK_Reality_Node_2, HK_Reality_Node_3, HK_Reality_Node_4] }
    - { name: 'Google Services', type: select, proxies: ['Main Node', 'Auto Choose', US_Reality_Node_1, US_Reality_Node_2, US_Reality_Node_3, US_Reality_Node_4, US_hysteria2_Node_5, JP_Reality_Node_1, JP_Reality_Node_2, JP_Reality_Node_3, JP_Reality_Node_4, JP_hysteria2_Node_5, SG_Reality_Node_1, SG_Reality_Node_2, SG_Reality_Node_3, SG_Reality_Node_4, SG_hysteria2_Node_5, UK_Reality_Node_1, UK_Reality_Node_2, UK_Reality_Node_3, UK_Reality_Node_4, HK_hysteria2_Node_5, HK_Reality_Node_1, HK_Reality_Node_2, HK_Reality_Node_3, HK_Reality_Node_4] }
    - { name: 'Blocked Domains', type: select, proxies: ['Main Node', 'Auto Choose', US_Reality_Node_1, US_Reality_Node_2, US_Reality_Node_3, US_Reality_Node_4, US_hysteria2_Node_5, JP_Reality_Node_1, JP_Reality_Node_2, JP_Reality_Node_3, JP_Reality_Node_4, JP_hysteria2_Node_5, SG_Reality_Node_1, SG_Reality_Node_2, SG_Reality_Node_3, SG_Reality_Node_4, SG_hysteria2_Node_5, UK_Reality_Node_1, UK_Reality_Node_2, UK_Reality_Node_3, UK_Reality_Node_4, HK_hysteria2_Node_5, HK_Reality_Node_1, HK_Reality_Node_2, HK_Reality_Node_3, HK_Reality_Node_4] }
    - { name: 'CHN Mainland', type: select, proxies: [Directly, 'Main Node', 'Auto Choose', US_Reality_Node_1, US_Reality_Node_2, US_Reality_Node_3, US_Reality_Node_4, US_hysteria2_Node_5, JP_Reality_Node_1, JP_Reality_Node_2, JP_Reality_Node_3, JP_Reality_Node_4, JP_hysteria2_Node_5, SG_Reality_Node_1, SG_Reality_Node_2, SG_Reality_Node_3, SG_Reality_Node_4, SG_hysteria2_Node_5, UK_Reality_Node_1, UK_Reality_Node_2, UK_Reality_Node_3, UK_Reality_Node_4, HK_hysteria2_Node_5, HK_Reality_Node_1, HK_Reality_Node_2, HK_Reality_Node_3, HK_Reality_Node_4] }
    - { name: 'Auto Choose', type: fallback, proxies: [US_Reality_Node_1, US_Reality_Node_2, US_Reality_Node_3, US_Reality_Node_4, US_hysteria2_Node_5, JP_Reality_Node_1, JP_Reality_Node_2, JP_Reality_Node_3, JP_Reality_Node_4, JP_hysteria2_Node_5, SG_Reality_Node_1, SG_Reality_Node_2, SG_Reality_Node_3, SG_Reality_Node_4, SG_hysteria2_Node_5, UK_Reality_Node_1, UK_Reality_Node_2, UK_Reality_Node_3, UK_Reality_Node_4, HK_hysteria2_Node_5, HK_Reality_Node_1, HK_Reality_Node_2, HK_Reality_Node_3, HK_Reality_Node_4], url: 'http://www.gstatic.com/generate_204', interval: 300 }
    - { name: Directly, type: select, proxies: [DIRECT] }
rule-providers:
    reject: { type: http, behavior: domain, url: 'https://mitce.com/modules/servers/v2Net/subscribe/release/reject.txt', path: ./ruleset/reject.yaml, interval: 86400 }
    icloud: { type: http, behavior: domain, url: 'https://mitce.com/modules/servers/v2Net/subscribe/release/icloud.txt', path: ./ruleset/icloud.yaml, interval: 86400 }
    apple: { type: http, behavior: domain, url: 'https://mitce.com/modules/servers/v2Net/subscribe/release/apple.txt', path: ./ruleset/apple.yaml, interval: 86400 }
    google: { type: http, behavior: domain, url: 'https://mitce.com/modules/servers/v2Net/subscribe/release/google.txt', path: ./ruleset/google.yaml, interval: 86400 }
    proxy: { type: http, behavior: domain, url: 'https://mitce.com/modules/servers/v2Net/subscribe/release/proxy.txt', path: ./ruleset/proxy.yaml, interval: 86400 }
    direct: { type: http, behavior: domain, url: 'https://mitce.com/modules/servers/v2Net/subscribe/release/direct.txt', path: ./ruleset/direct.yaml, interval: 86400 }
    cncidr: { type: http, behavior: ipcidr, url: 'https://mitce.com/modules/servers/v2Net/subscribe/release/cncidr.txt', path: ./ruleset/cncidr.yaml, interval: 86400 }
    lancidr: { type: http, behavior: ipcidr, url: 'https://mitce.com/modules/servers/v2Net/subscribe/release/lancidr.txt', path: ./ruleset/lancidr.yaml, interval: 86400 }
rules:
    - 'PROCESS-NAME,v2ray,DIRECT'
    - 'PROCESS-NAME,Surge%203,DIRECT'
    - 'PROCESS-NAME,ss-local,DIRECT'
    - 'PROCESS-NAME,privoxy,DIRECT'
    - 'PROCESS-NAME,trojan,DIRECT'
    - 'PROCESS-NAME,trojan-go,DIRECT'
    - 'PROCESS-NAME,naive,DIRECT'
    - 'PROCESS-NAME,Thunder,DIRECT'
    - 'PROCESS-NAME,DownloadService,DIRECT'
    - 'PROCESS-NAME,qBittorrent,DIRECT'
    - 'PROCESS-NAME,Transmission,DIRECT'
    - 'PROCESS-NAME,fdm,DIRECT'
    - 'PROCESS-NAME,aria2c,DIRECT'
    - 'PROCESS-NAME,Folx,DIRECT'
    - 'PROCESS-NAME,NetTransport,DIRECT'
    - 'PROCESS-NAME,uTorrent,DIRECT'
    - 'PROCESS-NAME,WebTorrent,DIRECT'
    - 'RULE-SET,icloud,Apple Services'
    - 'RULE-SET,apple,Apple Services'
    - 'RULE-SET,google,Google Services'
    - 'RULE-SET,proxy,Blocked Domains'
    - 'RULE-SET,cncidr,CHN Mainland'
    - 'RULE-SET,direct,DIRECT'
    - 'RULE-SET,lancidr,DIRECT,no-resolve'
    - 'MATCH,Main Node'
