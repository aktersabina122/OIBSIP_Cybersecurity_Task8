# Task 8: Capture Network Traffic with Wireshark

## Objective

The objective of this project was to capture and analyze network traffic using Wireshark. HTTP packets were captured and analyzed to understand basic network communication.

## Tools Used

- Wireshark
- Windows 11
- Google Chrome

## Steps Performed

1. Opened Wireshark.
2. Selected the active Wi-Fi network interface.
3. Started packet capture.
4. Generated HTTP traffic by visiting **http://neverssl.com**.
5. Applied the **http** display filter.
6. Analyzed HTTP packets including GET requests, HTTP 200 OK responses, and HTTP 301 redirects.
7. Examined the HTTP Host header and packet details.
8. Saved the packet capture as **wireshark_capture.pcap**.

## Project Files

```
OIBSIP_Cybersecurity_Task8/
│── README.md
│── wireshark_capture.pcap
└── screenshots/
    ├── capture_start.png
    ├── http_filter.png
    └── packet_analysis.png
```

## Key Observations

- Captured HTTP GET requests.
- Observed HTTP 200 OK responses.
- Observed HTTP 301 Moved Permanently redirects.
- Identified the HTTP Host header.
- Examined Ethernet, IPv6, TCP, and HTTP protocol layers.

## Skills Learned

- Capturing network packets
- Filtering HTTP traffic
- Analyzing HTTP requests and responses
- Understanding Ethernet, IP, TCP, and HTTP protocols
- Saving and reviewing PCAP files

## Conclusion

This project provided hands-on experience with network traffic analysis using Wireshark. It improved my understanding of HTTP communication, packet filtering, and basic network protocol analysis.

## Author

Sabina Akter

Oasis Infobyte Cybersecurity Internship