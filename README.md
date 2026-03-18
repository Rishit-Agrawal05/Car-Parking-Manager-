# Car-Parking-Manager

A command-line garage management tool built to practice 2D arrays and dictionary mapping. It simulates a 3-floor building with real-time occupancy tracking and automated billing.

**What this project does:**
1. **Visual Grid System:** Uses a 2D list to display a live map of the garage, marking occupied spots with [X] and empty ones with [ ].
2. **Tiered Access:** Restricts Floor 2 specifically for VIP users, while Floors 0 and 1 are available for standard parking.
3. **Real-time Tracking:** Maps license plates to exact coordinates (Floor/Row), preventing double-booking of the same spot.
4. **Automated Billing:** Calculates fees at ₹100/hr, automatically adding a ₹50 surcharge for VIP status during checkout.
5. **Spot Reset:** Once a user checks out, the system automatically clears their spot and removes their data from the registry.

**How to test the VIP features:**
1. **Status:** Type vip when prompted during the parking process.
2. **Access:** Choose Floor 2 to test the restricted entry logic and see the premium rate applied in the final bill.
