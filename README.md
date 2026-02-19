 Ghost Wire Surveillance System (FiveM Script)

A specialized ESX resource utilizing `pma-voice` to facilitate undercover operations and wiretapping.

### Core Features
* **Covert Monitoring**: Allows detectives to listen to a target's audio in real-time without holding a radio or playing animations.
* **The Handover Mechanic**: Detectives can "plant" the wire on a Confidential Informant (CI). The CI becomes the transmitter, and the Detective becomes the receiver.
* **Visual Indicators**: An on-screen "REC" overlay confirms when the device is active for bodycam recording purposes.
* **Job Restriction**: Usage is strictly limited to CID/DTF).

### Usage Guide
1.  **Self-Wire**: Use the `cid_wire` item while alone to wear the wire yourself. You will broadcast to the monitoring frequency.
2.  **Planting**: Use the `cid_wire` item while standing next to another player (CI). The device will be transferred to them, and you will automatically connect to their audio feed.
3.  **Monitoring**: Other officers can listen in by setting their radio/call channel to the frequency displayed on the handler's screen.

### Technical Requirements
* Framework: ESX Legacy
* Voice System: pma-voice
* Inventory: ox_inventory (recommended) or esx_inventoryhud

### Installation
1.  Place the `esx_cidwire` folder into your server's `resources` directory.
2.  Add `ensure esx_cidwire` to your `server.cfg`.
3.  Insert the `cid_wire` item into your database items table.

---
