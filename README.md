# NETWORKWALKS-MOHAMMEDSUFIYANAHMED-B084H-WK1-PM1-CYBERSECURITY-LAB-SETUP
# WK1-PM1: Cybersecurity Lab Setup

Week 1 lab setup for the NetworkWalks Cybersecurity Internship. The lab uses Kali Linux as the attacker VM connected to a NAT network.

## Lab Overview

| Item | Configuration / Status |
| :--- | :--- |
| **Attacker VM** | Kali Linux, VirtualBox |
| **Network** | NATNetwork, 10.0.0.0/24 |
| **Kali Address** | 10.0.0.2/24 (static) |
| **Gateway & DNS** | Gateway 10.0.0.1, DNS 8.8.8.8 |
| **Clipboard** | Copy/paste enabled |
| **Shared Folder** | Enabled (/downloads mounted) |
| **Baseline** | Clean snapshot taken |

See [TROUBLESHOOTING.md](TROUBLESHOOTING.md) for reported DNS/connectivity issues and shared-folder behavior.

## Setup Notes

1. **Configure Networking:** Set NATNetwork in VirtualBox to `10.0.0.0/24` with gateway `10.0.0.1`[span_30](start_span)[span_30](end_span)[span_31](start_span)[span_31](end_span).
2. **Set up Kali Networking:** Configure Kali with static address `10.0.0.2/24`, gateway `10.0.0.1`, and DNS `8.8.8.8`[span_32](start_span)[span_32](end_span)[span_33](start_span)[span_33](end_span).
3. **Check Connectivity:** Run terminal commands (`ip a`, `ping -c 3 google.com`) to verify connection[span_34](start_span)[span_34](end_span)[span_35](start_span)[span_35](end_span).
4. **Configure Sharing:** Enable copy/paste and share the host Downloads folder with Kali[span_36](start_span)[span_36](end_span)[span_37](start_span)[span_37](end_span).
5. **Take Snapshot:** Take a clean baseline snapshot after complete setup[span_38](start_span)[span_38](end_span).
6.
