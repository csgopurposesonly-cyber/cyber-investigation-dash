Cyber Investigation Dashboard

A desktop and web-based OSINT launcher built with React, Vite, and Electron.

Features

One-click launcher for OSINT and cyber investigation tools

Domain, IP, email, username, and wallet investigation workflows

Categories for infrastructure, people, breach, GEO-OSINT, crypto, malware analysis, scams, and reporting

Favorites system for commonly used tools

Searchable OSINT tool library

Electron desktop application support

Tech Stack

React

Vite

Electron

Lucide React

Run Locally
npm install
npm run dev

The application will run at:

http://localhost:5173
Build Desktop Application

To build the Windows desktop application:

npm run package-win

The compiled desktop app will appear in:

release-builds/
Project Structure
src/
  App.jsx
  osint_toolkit_dashboard.jsx
public/
main.cjs
package.json
vite.config.js
index.html
Example Investigation Workflows

The dashboard supports launching OSINT tools based on the target type.

Domain

Tools like:

Shodan

Censys

VirusTotal

crt.sh

Wayback Machine

IP Address

Tools like:

AbuseIPDB

Shodan

GreyNoise

IPinfo

Email

Tools like:

HaveIBeenPwned

Hunter

EmailRep

Username

Tools like:

Sherlock

WhatsMyName

Namechk

Crypto Wallet

Tools like:

TronScan

Etherscan

Blockchain Explorer

Screenshot

Add a screenshot of the dashboard here:

![Dashboard Screenshot](screenshot.png)
