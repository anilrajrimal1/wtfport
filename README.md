# wtfport

**Find what’s hogging a TCP/UDP port on your system.**

```bash
wtfport 6969
```

If a process is listening, you'll see:

> Port 6969 is being used by `node server.js` (PID 1234) for 5:12:04.

If free:

> WOW! Nothing on 6969 It's free!

## Installation

### From PyPI:

```bash
pip install wtfport
```

### From `.deb` package:

```bash
sudo dpkg -i wtfport_1.0.0-1_all.deb
```

## Dependencies

- Python 3.9+
- `psutil`

## 📝 License

MIT