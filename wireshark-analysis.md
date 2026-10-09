# Wireshark Packet Analysis — Task 03

## Objective

Capture and inspect network traffic from the authorized local lab using Wireshark.

## Capture Details

* Tool: Wireshark on Windows
* Interface: Adapter for loopback traffic capture
* Target address attempted: `127.0.0.1:8080`
* Capture file: `task03-lab-capture.pcapng`
* Screenshot: `03-tcp-filter.png`

## Method

1. Started a packet capture on the loopback interface.
2. Attempted to access the authorized local training application.
3. Stopped and saved the capture.
4. Applied the TCP display filter to inspect TCP packets.

## Observations

[Record the actual packets, protocols, addresses, ports, and connection behavior visible in the capture. Do not invent findings.]

## Limitations

The capture represents only traffic observed on the selected interface during the capture period. The presence of a packet does not by itself establish a vulnerability.

## Security Recommendations

* Keep testing within the authorized lab scope.
* Use synthetic data.
* Avoid publishing credentials, session cookies, or sensitive packet contents.
* Base risk ratings on verified evidence.

## Evidence

See `03-tcp-filter.png` and `task03-lab-capture.pcapng`, if these files are present in the repository.
