# OmTeBly Clash Rules

This repository contains custom rule sets for use with Clash.Meta (mihomo) configurations.

## Usage

To use in your config:

```yaml
rule-providers:
  openai:
    type: http
    behavior: classical
    url: "https://raw.githubusercontent.com/omtebly/clash-rules/main/ruleset/openai.yaml"
    interval: 86400
    path: ./ruleset/openai.yaml
