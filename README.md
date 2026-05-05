# scoop-mzgb

Scoop bucket for [mzgb](https://github.com/mukesudo/mzgb) — fast CLI for filtering very large log files.

## Install

```powershell
scoop bucket add mzgb https://github.com/mukesudo/scoop-mzgb
scoop install mzgb
```

## Usage

```powershell
mzgb --level ERROR app.log
mzgb --pattern "timeout" -C 2 app.log
mzgb --summary app.log
Get-Content app.log | mzgb --level ERROR
```
