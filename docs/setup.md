# Raspberry Pi Setup Guide

## Prerequisites
- A Raspberry Pi 4 or later.
- A microSD card with at least 16 GB of storage.
- Ethernet or Wi-Fi for network connectivity.

## Installation Steps
1. Download and flash Ubuntu Server onto your microSD card using tools like Balena Etcher.
2. Boot the Raspberry Pi and connect via SSH:
   \`\`\`bash
   ssh ubuntu@<raspberry_pi_ip>
   \`\`\`
   Default username: ubuntu, password: ubuntu.

3. Update the system:
   \`\`\`bash
   sudo apt update && sudo apt upgrade -y
   \`\`\`

4. Install Docker:
   \`\`\`bash
   sudo apt install -y docker.io
   \`\`\`

5. Verify installation:
   \`\`\`bash
   docker --version
   \`\`\`" > docs/setup.md

