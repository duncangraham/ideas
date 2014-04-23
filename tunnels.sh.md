# Tunnels.sh

*SSH Tunnels for the Rest Of Us.*

It' a microsite that details the ins and outs of ssh tunnels. Also, that domain is available. If it's cool, it might get lots of
views.. ad revenue? 

Cool graphic of portal-like tunnel representation. Mirror mouse on hover? - http://codepen.io/jshawl/pen/tzydx/

## Secure your traffic with a SOCKS proxy

Dynamic port forwarding, `-D`

If you're on a public wi-fi network, anyone can see and understand your internet traffic that's being sent from your computer. Using a SOCKS proxy will pass that unencrypted traffic through an encrypted connection.

1. `ssh -D 9059 destination.com`
2. System Preferences > Network > Advanced... > Proxies
3. Check [ ] SOCKS Proxy
4. SOCKS Proxy Server: localhost
5. SOCKS port: 9059

This will SSH into destination.com and tunnel all of your traffic through destination.com

## Access the Outside

Local port forwarding, `-L`

## Access the Inside

Remote port forwarding, `-R`

## Screen Share with Mom

Tunnel in a tunnel - inception!
