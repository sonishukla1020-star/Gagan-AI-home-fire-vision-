# Gagan-AI-home-fire-vision-
Gagan Fire-Eye is an AI kitchen defense system. Using IR arrays and OpenCV, it detects stove fires before ignition. If unattended (EDGE_NEURAL: NO_HUMAN_DETECTED), it sprays a cold aerosol mist to freeze thermal chaos. Calculus: P_Ignition=∮(∇·J_Thermal)dV-C_Aerosol(∂Oxidizer/∂t)⟹0 An offline solenoid valve snaps the gas pipe shut instantly.
Gagan Home Fire Vision is an advanced AI-powered project designed to predict and prevent household and kitchen fires before they even start.
The video is divided into two main sections:
1. 
The Problem: The video opens with a statistic stating that 48\% of home fires originate in the kitchen. Traditional smoke alarms only trigger after smoke has already accumulated, which is often too late to prevent damage.
The Solution: Developed by Shreya and Madhav (Madhay.ai), this AI device doesn't wait for smoke. It uses computer vision (OpenCV) and thermal imaging to monitor temperatures and human presence in real-time.
If someone leaves a stove unattended, it immediately sends a high-priority alert to their phone.
2. Real Product Demonstration
The Demo Setup: Featured as a project, the live demo shows an elderly woman (Asha Didi) leaving milk to boil on the stove while she gets distracted by her phone in another room.
Flaws in Traditional Tech: The video explains why standard motion sensors or timers fail—for instance, a pet moving around can easily trick a basic motion detector.
Advanced Technology at Work: As soon as the person leaves the kitchen, the system detects the absence of human presence and enters Phase-2 (Hazard Acceleration Tracking).
Sensor Fusion & Action: * The system isolates the exact frequency of boiling and sizzling sounds at 3.4 \text{ kHz}.
Simultaneously, the thermal sensor tracks a rapid temperature rise exceeding +4.5^{\circ}\text{C/sec}.
Once the internal threat score crosses 35, the device acts within a mere 0.28 seconds. Operating independently of local Wi-Fi via a local radio mesh network, it triggers an electronic solenoid valve to instantly shut off the gas supply.
It also overrides silent or DND modes on the user's phone to deliver a loud emergency notification.
the underlying science—including blackbody radiation and Convolutional Neural Networks (CNN)—which allows the AI to accurately differentiate between normal cooking activities and an actual kitchen hazard