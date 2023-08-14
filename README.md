# Replay Frames

Replay Frames is an interactive bash utility script designed to replay specific frames from a PCAP (Packet Capture) file to some specified destination.
It is useful ally for simulating network traffic for testing and debugging.

## Features

- Interactively select the frames you wish to replay.
- Set the destination IP and port.
- Configurable `tshark` decoder definitions so the frames are displayed correctly.

## Usage

```bash
./replay-frames <path-to-pcap-file>
            [--destination <destination-ip:port> (default: 127.0.0.1:8000)]
            [--tshark-decoder <decoder-definition>]
```

## Dependencies

- tshark (CLI version of Wireshark)
- netcat (nc)

## Installation

1. Clone this repository.
2. Make sure you have `tshark` and `netcat` installed on your system.
3. Provide execute permissions to the script: `chmod +x replay-frames`.
4. Run the script as per the usage guidelines.

## Licensing

This project is licensed under the MIT License. For more details, see the LICENSE file in the repository.

---

## Contributing

Contributions, issues, and feature requests are welcome!

---

Give a ⭐️ if this project helped you!
