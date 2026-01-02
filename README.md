# CVE-2025-67268 and CVE-2025-67269: Vulnerabilities in gpsd

Two security vulnerabilities discovered in gpsd by Jaehyun Lee.

## Vulnerabilities

- **[CVE-2025-67268](CVE-2025-67268/)**: Heap-based Out-of-Bounds Write in NMEA2000 Driver (PGN 129540 Handling)
- **[CVE-2025-67269](CVE-2025-67269/)**: Integer Underflow Leading to Denial of Service in NAVCOM Packet Parsing

## Discovery and Disclosure

- Discovered by: Jaehyun Lee
- Reported to: The GPSD Project
- Vendor acknowledged and fixed both issues (Fixed in 3.27.1)
- CVE IDs assigned by MITRE on December 17, 2025
- Public disclosure: December 21, 2025

## References

- gpsd GitHub (ntpsec fork): https://github.com/ntpsec/gpsd
- gpsd GitLab (upstream): https://gitlab.com/gpsd/gpsd

For detailed technical write-ups, please see the individual CVE folders.
