WebRTC IP Location Tracker for OmeTV (JavaScript Tool)

About:
This browser-based JavaScript tool captures the public IP addresses of users during video chats on OmeTV (or any WebRTC-supported site). It then uses the IPGeolocation API to trace approximate locations such as city, country, ISP, and coordinates.

Features:
- Real-time IP logging from WebRTC (ICE Candidates)
- Location data shown in browser console
- Uses IPGeolocation.io for accurate results

How It Works:
This script modifies the WebRTC connection process to extract the peer’s public IP address. When an ICE candidate of type “srflx” (server reflexive) is detected, the script sends the IP to the geolocation API and displays the results in the console.

⚠️ VPN Warning:
Always use a **VPN before running this script**. It will expose your **own public IP address** through WebRTC unless you're protected.

To stay anonymous:
- Use a **reliable VPN**
- Never expose your real IP address on public video chat platforms
- Never misuse this tool or use it to harass or stalk people

⚠️ LEGAL NOTICE:
This tool is for **educational purposes only**. You are responsible for any misuse. Do not violate laws, privacy rights, or platform terms of service.
