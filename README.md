# Move_Project_Cross-hospital-medical-record-access
# 🏥 Cross-Hospital Medical Record Access (Move Smart Contract)

A secure, patient-consent-driven smart contract on the Aptos blockchain that allows **cross-hospital access to medical records**. This project enables decentralized and interoperable healthcare data sharing while preserving **privacy**, **security**, and **auditability**.

---

## 💡 Overview

Patients often receive care from multiple hospitals, but their health records remain siloed. This smart contract enables hospitals to request and receive access to a patient's medical record **with explicit patient consent**, recorded immutably on-chain.

---

## ⚙️ Features

- 🔐 **Patient-controlled access** to medical records
- 🏥 **Cross-hospital sharing** of records
- 📜 **On-chain auditability** of who accessed what
- 🧾 Minimal and privacy-preserving metadata storage

---

## 🧱 Smart Contract Structure

### 📦 Structs

```move

struct MedicalRecordAccess has store, key {
    has_granted_access: bool,
}
```
## Transaction Id = 0x4ce3756b2bee483ee91d8ea64ec50f204e94b0234acbe83dd2141693bfaacf0b

