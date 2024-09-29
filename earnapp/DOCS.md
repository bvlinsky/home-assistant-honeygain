# Home Assistant EarnApp Add-on

Note! These are referral links, and by signing up through them,
you directly contribute to future updates and maintenance.

## Quick Configuration Guide

1. If you don't have a PacketStream account, sign up at [earnapp.com](https://earnapp.com/i/4LLxaYrb).
2. In Home Assistant, go to "Supervisor" > "Add-on Store" > EarnApp add-on > "Configuration" tab.
3. In the add-on configuration, set EARNAPP_UUID, use existing id or create new (instruction below).
4. Go to `https://earnapp.com/r/{EARNAPP_UUID}` to register device.

## New ID
1. Go to [www.uuidgenerator.net](https://www.uuidgenerator.net/)
2. Generate a UUID v4
3. Remove hyphens from the UUID
4. Prepend `sdk-node-` to the result

Example: sdk-node-123e4567e89b12d3a456426614174000
