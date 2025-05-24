
# Mobile Phone Detector

This repository presents the implementation of a simple RF signal-based mobile phone detector. The circuit utilizes an LM358 operational amplifier, capacitors, and a BC548 transistor to detect the presence of active mobile phones by sensing electromagnetic signals generated during calls, SMS, or data transmission. This project was completed as part of the ECT301 – Linear Integrated Circuits course.

---

## 🎯 Project Aim

To design and construct a mobile phone detector circuit that senses electromagnetic radiation from mobile phones in the range of 900 MHz to 2 GHz using a low-cost op-amp-based solution.

---

## 🔧 Components Used

| Component             | Specification/Value          |
|----------------------|------------------------------|
| Op-Amp IC            | LM358 (Dual Operational Amplifier) |
| Resistors            | 1 kΩ, 100 kΩ, 220 kΩ          |
| Potentiometer        | 2.2 MΩ                        |
| Capacitors           | 1 µF, 100 µF                  |
| Transistor           | BC548 (NPN)                   |
| LED                  | Standard indicator LED        |
| Power Supply         | 5V–9V DC                      |

---

## ⚙️ Circuit Description

- **Capacitor C2** acts as an RF signal absorber.
- **LM358** amplifies the signal received from the capacitor.
- **BC548 Transistor** acts as a switch to activate the LED.
- **LED** indicates the detection of an active mobile phone.
- **Potentiometer RV1** is used to adjust the sensitivity or detection range.

---

## 🧪 Working Principle

When a mobile phone transmits or receives a signal, it emits RF radiation. Capacitor C2 absorbs this signal and sends it to the LM358 op-amp. The op-amp amplifies the signal, which is then used to activate a transistor that switches on the LED. The LED glows, indicating the presence of a nearby mobile phone.

---

## 📍 Applications

- Detection of unauthorized mobile usage in:
  - Examination halls
  - Confidential areas
  - Prisons
  - Religious and historical places
- Useful for surveillance and security enhancement in sensitive areas.

---

## 📈 Conclusion

The designed circuit effectively detects RF radiation emitted by mobile phones. It is compact, cost-effective, and can be used to enforce mobile restrictions in sensitive zones.

---

## 📚 References

- [www.google.com](https://www.google.com)  
- [www.wikipedia.org](https://www.wikipedia.org)  
- [www.efymag.com](https://www.efymag.com)

---

## 👥 Project Team

- **Aravind Sunil** 
- **Kavya M** 
- **Keerthana N** 
- **Krishna V Sunil** 

**Guide**: Dr. Geetha G  
**Department**: Electronics and Communication Engineering  
**Institution**: NSS College of Engineering, Palakkad  
**University**: APJ Abdul Kalam Technological University

---

## 📁 Folder Structure (Suggested)

