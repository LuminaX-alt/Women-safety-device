# Women-safety-device
Voice-activated emergency trigger
This Women’s Safety SOS Device is a standalone emergency alert system designed to detect distress situations and provide immediate assistance. It listens for the voice command "help help help" three times and initiates an alert sequence. If the user confirms the alert, the device sends an emergency message with location details to pre-configured contacts and triggers a phone call and video call for real-time assistance.
Features
✅ Voice-activated emergency trigger – Detects "help help help" repeated three times
✅ Confirmation step – Prevents false alarms by allowing the user to confirm before sending alerts
✅ Location tracking – Sends real-time GPS coordinates to emergency contacts
✅ Emergency call feature – Uses Twilio API to place an automatic call to pre-set contacts
✅ Video call support – Integrates Skype API for live video streaming
✅ Standalone hardware – Works independently without requiring a smartphone
✅ Low power consumption – Optimized for continuous operation
Technical Details
Hardware Components
Microcontroller: [Specify the microcontroller you used, e.g., ESP32 / Raspberry Pi / Arduino]

Microphone Module: For voice command detection

GPS Module: To get the user’s real-time location

Wi-Fi / GSM Module: For sending alerts and making calls

Battery / Power Source: Rechargeable lithium-ion battery for portability

Software Stack
Programming Language: Python / C++ (based on the microcontroller)

Machine Learning Model: Custom speech recognition for "help help help"

APIs Used:

Twilio API – For emergency phone calls

Skype API – For video call functionality

Google Maps API – For location tracking

Working Mechanism
Voice Detection: Continuously listens for the trigger phrase ("help help help").

Confirmation Step: The device asks the user to confirm the distress signal via a small screen or buzzer feedback.

Alert Transmission: If confirmed, it:

Sends an SMS alert with GPS location to emergency contacts.

Makes an automatic phone call to a trusted person.

Starts a video call via Skype for real-time monitoring.

Safety Acknowledgment: If the user cancels the alert, no messages or calls are sent.

Setup Instructions
Hardware Assembly: Connect the microphone, GPS module, and GSM/Wi-Fi module to the microcontroller.

Software Installation: Flash the firmware onto the microcontroller and configure API keys for Twilio, Skype, and Google Maps.

Emergency Contact Configuration: Add trusted contacts who will receive alerts.

Testing: Simulate the "help help help" command and verify alert responses.

Future Improvements
AI-based Threat Detection: Use AI to recognize distress in voice tone.

Wearable Version: Convert into a compact pendant or wristband.

Offline Mode: Implement an SMS-only mode for areas with no internet.

Integration with Police Helplines: Directly notify law enforcement during emergencies.


