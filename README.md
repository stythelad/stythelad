# Hi, I'm stythe 👋

Self-taught developer from Kathmandu. I build small, sharp tools in Go and Python.
## Featured projects

### [auteur](https://github.com/stythelad/auteur) &nbsp;`Go`

`git blame` tells you *who* wrote a line. Auteur tells you whether it was a **human or a model**, and which model, session, and prompt produced it. The ledger is a plain text file committed with your repo: no server, no database, no telemetry. It also ships a policy engine so CI can block agent-written code in sensitive paths.

```
$ auteur blame auth/login.py:42
  author:  claude-code (claude-opus-5.5)
  origin:  agent   [confidence: high]
```

### [asha-windows](https://github.com/stythelad/asha-windows) &nbsp;`Python`

Research into streaming audio to ASHA hearing aids from Windows. Scanning, pairing, and GATT discovery work today; the audio channel is blocked by a gap in the Windows Bluetooth API. The repo documents exactly where and why, for anyone who wants to pick it up.

### [hey-cli](https://github.com/stythelad/hey-cli) &nbsp;`Python`

Natural language to shell commands, running 100% locally through Ollama. No API key, no internet required.

```
$ hey "show disk usage"
df -h
```

## Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## Right now

- **auteur**: working toward v1.0
- **asha-windows**: looking for people to test other hearing aid brands (Phonak, Starkey, Widex)
- Always glad to get feedback. Open an issue on any repo above.
