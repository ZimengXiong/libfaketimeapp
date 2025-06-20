# OSX Fake Time App Wrapper Generator Tool

A simple macOS command-line utility that wraps an application to run under a specified fake system time using faketime.

## Installation

1. Make the script executable and move it into your PATH:

   ```bash
   chmod +x faketimeapp
   mv faketimeapp /usr/local/bin/
   ```

## Usage

```bash
faketimeapp [--arch <arch>] "<YYYY-MM-DD HH:MM:SS>" "<Application Name>"
```

## Examples

```bash
faketimeapp "2000-01-01 00:00:00" "Safari"
faketimeapp --arch x86_64 "2000-01-01 00:00:00" "Google Chrome"
```

## License

MIT
