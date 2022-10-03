# Intro

Yet-Another-Blacklist is a blacklist in regex form that help prevent users from accessing globally to some Chinese social websites <sup>[note 1](https://github.com/XTLS/Xray-core/discussions/593#discussioncomment-845165)</sup> and some oversea political sites focusing on propaganda. By applying this rule both of users and proxy providers are able to surf the Internet more safely although their freedom of the press may be detained.

# Why not using outbound blackhole with the help of geosite?

Becuase shadowsocks and trojan do not support this feature.

# Usage

For XrayR:

1. Edit config file:

```yml
ApiConfig:
    RuleListPath: /etc/XrayR/blacklist #Path to local rulelist file
```

2. Download blacklist:

```
wget https://raw.githubusercontent.com/v2werf5ef/Yet-Another-Blacklist/main/blacklist -O /etc/XrayR/blacklist
```

, where */etc/XrayR/blacklist* is the default rule path and you can change it for your own purpose.

# ToDo

Automatically merge from some famous repos like [domain-list-community
](https://github.com/v2fly/domain-list-community).
