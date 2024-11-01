🚗Smart Parking System 🚗
Key Features:
- 4 IR sensors for vehicle detection
- Servo-controlled gate opening
- RGB LEDs indicate parking slot status:
    - Green: Slot 1 available
    - Yellow: Slots 1 & 2 occupied
    - Red: Slots 1, 2 & 3 occupied (full)
    - No glow: 0 slots available
- LCD display and Telegram Bot notifications
Working:
1. Entry IR sensor detects vehicle, servo opens gate.
2. Vehicle occupies slot, corresponding LED glows, LCD displays, and Telegram Bot sends notification.
3. Subsequent slots fill, LED color changes, indicating occupancy.
