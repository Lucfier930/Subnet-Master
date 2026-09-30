🌊 SUBNET MASTER

 ███████╗██╗   ██╗██████╗ ███╗   ██╗███████╗████████╗
 ██╔════╝██║   ██║██╔══██╗████╗  ██║██╔════╝╚══██╔══╝
 ███████╗██║   ██║██████╔╝██╔██╗ ██║█████╗     ██║
 ╚════██║██║   ██║██╔══██╗██║╚██╗██║██╔══╝     ██║
 ███████║╚██████╔╝██████╔╝██║ ╚████║███████╗   ██║
 ╚══════╝ ╚═════╝ ╚═════╝ ╚═╝  ╚═══╝╚══════╝   ╚═╝

 ███╗   ███╗ █████╗ ███████╗████████╗███████╗██████╗
 ████╗ ████║██╔══██╗██╔════╝╚══██╔══╝██╔════╝██╔══██╗
 ██╔████╔██║███████║███████╗   ██║   █████╗  ██████╔╝
 ██║╚██╔╝██║██╔══██║╚════██║   ██║   ██╔══╝  ██╔══██╗
 ██║ ╚═╝ ██║██║  ██║███████║   ██║   ███████╗██║  ██║
 ╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝   ╚═╝   ╚══════╝╚═╝  ╚═╝

                 NETWORK SUBNETTING STUDIO

A modern browser-based IPv4 subnetting calculator for learning,
planning, and network analysis.

✨ Overview

Subnet Master is a single-page web application for IPv4 subnet
calculations. It provides two modes:

FLSM --- Fixed Length Subnet Masking

VLSM --- Variable Length Subnet Masking

The interface uses a dark Deep Ocean theme with blue, teal, and gold
accents. It also provides an interactive bit-level view showing the
network/host boundary as the CIDR prefix changes.

🚀 Features

FLSM --- Fixed Length Subnetting

Network address input

Automatic or manual Class A, B, and C selection

Custom CIDR prefix

Configurable subnet count

Automatic subnet calculations

Network and broadcast addresses

First and last usable hosts

Usable hosts per subnet

Complete subnet table

Copy results to clipboard

CSV export

VLSM --- Variable Length Subnetting

Starting network address

Starting CIDR prefix

Multiple named subnet requirements

Required host counts

Largest-to-smallest requirement processing

Automatic prefix sizing

Network, mask, prefix, requested hosts, usable hosts, first host,
last host, and broadcast output

Copy results to clipboard

CSV export

🧮 Bit-Level Breakdown

Interactive /0--/32 CIDR slider

Network bits and host bits

Four IPv4 octets

Decimal octet values

Subnet mask

Network address

Broadcast address

Total addresses

Usable hosts

🖥️ Interface

SUBNET MASTER
│
├── Live Status
│
├── FLSM · Fixed Length
│   ├── Configuration
│   ├── Bit-Level Breakdown
│   ├── Results
│   └── Subnet Table
│
└── VLSM · Variable Length
    ├── Configuration
    ├── Subnet Requirements
    ├── Bit-Level Breakdown
    └── VLSM Results

📊 Results

FLSM

Network
Prefix
Subnet Mask
Broadcast
First Host
Last Host
Usable Hosts
Host Range

Subnets
Hosts / Subnet
New Prefix

The subnet table includes:

# | Subnet (CIDR) | Network | Subnet Mask |
  | Broadcast | Usable Range | Usable Hosts | Reserved

VLSM

# | Name | Network | Mask | Prefix |
  | Requested | Usable | First | Last | Broadcast

🛠️ Technology

HTML5

CSS3

Vanilla JavaScript

Inter

JetBrains Mono

No frontend framework or build system is required.

📁 Project Structure

.
└── index(2).html

The application is contained in one HTML file with the UI, styling,
subnetting logic, binary visualization, clipboard handling, and CSV
export.

▶️ Run Locally

Open the HTML file directly in a modern browser:

index(2).html

Or use a local server:

python -m http.server 8000

Then visit:

http://localhost:8000

🔢 Example --- FLSM

Network Address : 192.168.1.0
CIDR            : /24
Subnets         : 4

Subnet Master calculates the new prefix and generates the subnet
information and table.

🔢 Example --- VLSM

Engineering  → 100 hosts
Sales        → 50 hosts
Management   → 25 hosts
Guest        → 10 hosts

The calculator allocates variable-length subnets based on the requested
host counts.

📚 Learning Use Cases

IPv4 subnetting practice

FLSM exercises

VLSM exercises

CIDR learning

Binary subnet-mask visualization

Network planning

Networking classroom demonstrations

Quick subnet calculations

🎨 Design

The application follows a Deep Ocean visual style:

Primary    → Ocean Blue
Accent     → Teal
Highlight  → Warm Gold
Background → Deep Navy

It also includes responsive layouts for smaller screens.

⚠️ Notes

Subnet Master is a browser-based IPv4 subnetting calculator intended for
educational, planning, and network-administration use.

Verify calculated network plans against your real infrastructure
requirements before deployment.

📄 License

No license is specified in the provided source.

If you publish this repository publicly, add a license that reflects how
you want others to use, modify, and distribute the project.

👨‍💻 Project

SUBNET MASTER

A practical IPv4 subnetting and network-planning studio.

⭐ If this project helps you learn networking, consider starring the
repository.
