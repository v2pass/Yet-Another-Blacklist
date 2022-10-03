# Intro

A blacklist in regex form that help prevent users from accessing to some websites that proxy providers think harmful. By applying this rule both of two sides are able to surf the Internet more safely.

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
