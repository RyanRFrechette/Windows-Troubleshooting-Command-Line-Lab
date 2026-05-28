# Windows Command-Line Troubleshooting Lab — Real Diagnostic Output and Support Notes

## Recruiter TL;DR

This repo proves practical Windows troubleshooting ability using real command-line diagnostics and privacy-cleaned evidence. It covers commands support technicians use every day, including `ipconfig`, `ping`, `tracert`, `nslookup`, `systeminfo`, `tasklist`, and `netstat`, with notes explaining what each command checks and how it supports help desk escalation.

## About This Project

This portfolio lab demonstrates practical Windows troubleshooting using real command-line tools and privacy-cleaned command output. It is designed for remote IT support, help desk, cloud support, and junior sysadmin roles where technicians need to gather evidence, diagnose issues, and communicate findings clearly.

The lab focuses on common support workflows such as network configuration review, connectivity testing, DNS troubleshooting, route tracing, system inventory, process review, and active network connection awareness.

## Goal

Demonstrate practical command-line troubleshooting skills using real command outputs, privacy-cleaned documentation, and support-style notes.

## Commands Covered

- `ipconfig /all`
- `ping 8.8.8.8`
- `ping google.com`
- `tracert google.com`
- `nslookup google.com`
- `systeminfo`
- `tasklist`
- `netstat -ano`

## Project Sections

### `command-outputs`

Contains captured command output files with private details redacted.

### `troubleshooting-notes`

Contains short support notes explaining what each command checks, why support technicians use it, and what issues it can help diagnose.

## Skills Demonstrated

- Windows command-line troubleshooting
- Network configuration review
- Internet connectivity testing
- DNS troubleshooting
- Route/path testing
- System inventory review
- Running process awareness
- Network connection awareness
- Privacy-conscious documentation
- Technical writing for support workflows

## Interview Talking Points

- I used real Windows diagnostic commands and documented what each one proves in a support context.
- I redacted private system details before publishing, which shows care around privacy and safe documentation.
- This project demonstrates how I gather evidence before escalating an issue instead of guessing.

## Hiring Relevance

Remote IT support roles often require clear troubleshooting, accurate documentation, and the ability to gather evidence before escalating. This lab demonstrates those skills with real command-line examples.

## Related Training

This lab reinforces foundational support skills from the Google IT Support Professional Certificate, including Windows troubleshooting, command-line diagnostics, operating system concepts, and structured problem solving.

## Status

MVP complete.

## Visual Evidence

| Command | What it proves | Output | Screenshot |
|---|---|---|---|

| `ipconfig /all` | Reviews adapter configuration, DHCP, gateway, DNS, and network adapter details after privacy redaction. | [ipconfig-output.txt](command-outputs/ipconfig-output.txt) | [01-ipconfig-all.png](screenshots/01-ipconfig-all.png) |

| `ping 8.8.8.8` | Tests basic internet connectivity without depending on DNS name resolution. | [ping-output.txt](command-outputs/ping-output.txt) | [02-ping-ip.png](screenshots/02-ping-ip.png) |

| `ping google.com` | Tests internet connectivity and confirms DNS name resolution works. | [ping-output.txt](command-outputs/ping-output.txt) | [03-ping-domain.png](screenshots/03-ping-domain.png) |

| `tracert google.com` | Shows the route traffic takes to a destination while keeping network details redacted. | [tracert-output.txt](command-outputs/tracert-output.txt) | [04-tracert-google.png](screenshots/04-tracert-google.png) |

| `nslookup google.com` | Confirms DNS can resolve a domain name using a public DNS server. | [nslookup-output.txt](command-outputs/nslookup-output.txt) | [05-nslookup-google.png](screenshots/05-nslookup-google.png) |

| `systeminfo` | Collects safe Windows system inventory details useful for support escalation. | [systeminfo-output.txt](command-outputs/systeminfo-output.txt) | [06-systeminfo.png](screenshots/06-systeminfo.png) |
