Kong Upstream Environment Route Plugin
====================

This plugin allows you to re-route and modify the `env` in the request host. 

The original host is available via the `X-Host-Original` header

### Usage
Source: `test`

  - Environment / subdomain you wish to replace

Target: `dev`
    
  - Final environment / subdomain to replace the source with

All routes that contain `test` in the `Host` will be replaced with `dev`.

#### Examples

1. myroute.test.exp.com > myroute.dev.exp.com
2. test.exp.com > dev.exp.com
