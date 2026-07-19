# Ransomware Simulation (EHA361 - Milestone 4)

## 📋 Overview
Educational ransomware simulation developed in Kali Linux with reversible encryption and one-click activation.

## 🎯 Key Features
- ✅ XOR encryption with password protection
- ✅ Reversible decryption demonstrated
- ✅ Realistic popup notifications
- ✅ One-click desktop launcher
- ✅ Safety mode with clear warnings

## 🛠️ Technologies Used
- Python 3
- Tkinter (GUI)
- Kali Linux
- XOR Encryption

## 🔧 Key Functions
```python
def scramble_text(text):
    key = 42
    return ''.join(chr(ord(c) ^ key) for c in text)

def unscramble_text(scrambled):
    return scramble_text(scrambled)  # XOR is reversible
