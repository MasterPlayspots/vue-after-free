# Vue-After-Free (Local Fork)

Local copy of [Vue-After-Free](https://github.com/AStrizh/vue-after-free) — a PlayStation 4 userland code execution exploit.

## What It Does

Exploits CVE-2017-7117 (WebKit vulnerability) to achieve userland code execution on PS4. Chained with kernel exploits (Lapse, Netctrl/Poopsploit) for full jailbreak.

## Vulnerability Scope

| Component | Firmware Range |
|-----------|---------------|
| Vue-After-Free (Userland) | 5.05 - 13.04 |
| Lapse (Kernel) | 1.01 - 12.02 |
| Netctrl (Kernel) | 1.01 - 13.00 |

## Supported Firmwares

Full jailbreak tested on: 7.00 - 13.00

## Tech Stack

- TypeScript + Babel transpilation
- ESLint for code quality

## Building

```bash
npm install
npm run build
```

Output goes to `dist/`.

## Upstream

Original project with community contributions.

## Author

Fork maintained by Kevin Fröba
