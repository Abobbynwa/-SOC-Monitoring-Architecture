NetSentinel – Custom SOC Monitoring & Recon Platform
Overview

NetSentinel is a custom-built Security Operations Center (SOC) style monitoring platform developed using Python, FastAPI, and Nmap. It performs active network reconnaissance, device classification, service enumeration, and detection logic simulation within a controlled lab environment.

This project demonstrates blue-team security engineering concepts including detection design, alert logic creation, and SOC architecture modeling.

Architecture

NetSentinel consists of:

Ubuntu-based monitoring server

Nmap scanning engine

FastAPI dashboard

Device intelligence database

Alert & detection logic module

Secure remote access via Tailscale VPN

The system actively scans LAN devices and classifies them based on service and OS fingerprint results.

Features

Live host discovery

Service enumeration (-sV)

OS fingerprinting (-O)

MAC vendor detection

Automatic device classification (Router / PC / IoT)

Rogue device detection

Offline tracking & SLA uptime calculation

Port scan detection simulation

Web-based SOC dashboard

Secure remote VPN access

Technologies Used

Python

FastAPI

Nmap

SQLite

HTML / CSS

Tailscale (Zero-Trust Remote Access)

Skills Demonstrated

Network reconnaissance

Detection engineering

SOC architecture design

Alert logic development

Threat modeling

Service enumeration analysis

OS fingerprint interpretation

Disclaimer

This project was developed in a controlled lab environment for educational and defensive security purposes only.
