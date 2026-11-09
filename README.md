GOBIKEY
(NOT a Yubikey)

This is for week 5 of Hackclub Half Life, and its a fairly simple (?) key thingy. It consists of USB A connection, a nRF52840 QIAA chip, two buttons, two lights, and some GPIO pins for testing purposes. It is not only for passwords and 2FA (although that was the original purpose), and should double as a devboard kinda thing if i did it right. Without further adeu, my (please please dont slime me for my bad wiring) designs:








<img width="565" height="544" alt="Screenshot_20261108_222024" src="https://github.com/user-attachments/assets/d1dec1a5-1618-40e3-8f7d-6d56630af1bb" />






<img width="1060" height="737" alt="Screenshot_20261108_222036" src="https://github.com/user-attachments/assets/8295c042-edcb-4300-919b-74898323f16a" />






<img width="554" height="723" alt="Screenshot_20261108_222045" src="https://github.com/user-attachments/assets/15e51c22-f7ca-4989-87d8-3521cc864f95" />





Despite it being a simple board (for some ig), it took a lot of mental brainpower for me to complete this, and im not sure if it even works properly (try at own risk lol). It was inspired in part by this (https://docs.nordicsemi.com/r/bundle/ug_nrf52840_dongle/page/ug/nrf52840_dongle/kit_hw_content.html), and yubikeys in general.


To install the firmware, for now just look at this (https://docs.zephyrproject.org/latest/services/authentication/fido2/index.html), im not done with the firmware yet.


# Bill of Materials (BOM)

| Part | Quantity | Unit Price (USD) | Total (USD) | Vendor |
|---|---:|---:|---:|---|
| Button | 2 | $0.54 | $1.08 | [DigiKey](https://www.digikey.com/en/products/detail/würth-elektronik/434133025816/9950810?s=N4IgTCBcDaICwGY4EYEIAxgKwA5kDYQBdAXyA) |
| LED | 2 | $0.19 | $0.38 | [DigiKey](https://www.digikey.com/en/products/detail/würth-elektronik/150060VS55040/8557182) |
| 1k Resistor | 2 | $0.10 | $0.20 | [DigiKey](https://www.digikey.com/en/products/detail/vishay-dale/CRCW06031K00FKEA/1174668) |
| 10k Resistor | 1 | $0.10 | $0.10 | [DigiKey](https://www.digikey.com/en/products/detail/vishay-dale/CRCW060310K0FKEA/1174782) |
| nRF52840 Chip | 1 | $8.81 | $8.81 | [DigiKey](https://www.digikey.com/en/products/detail/nordic-semiconductor-asa/NRF52840-QIAA-R/7725407) |
| PCB | 1 | $10.70 | $10.70 | [JLCPCB](https://cart.jlcpcb.com/shopcart/cart/) |

---

## Cost Summary

| Description | Cost (USD) |
|---|---:|
| Component Subtotal | $10.57 |
| PCB Cost | $10.70 |
| **Grand Total** | **$21.27** |


(PCB cost accounts for shipping, hopefully if i get all my grants at once shipping will be a one time thing)
