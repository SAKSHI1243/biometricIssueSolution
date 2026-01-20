# biometricIssueSolution
# BiometricFail360 – UIDAI Data Hackathon 2026

Predictive model to identify Aadhaar biometric authentication failure hotspots at PIN-code level, and recommend targeted interventions.

## 1. Problem

High biometric failure rates (e.g., Jharkhand 49%, Rajasthan 37%) are excluding beneficiaries from PDS, MGNREGA and health schemes. Current detection is post-failure at PoS; no proactive mechanism.

## 2. Solution

BiometricFail360 is a Random Forest–based model that:
- Uses state failure rates + local age distribution
- Produces a risk score (0–1) for each PIN code
- Identifies 79,377 high-risk PIN codes for intervention

## 3. Repository Structure

(then paste the tree from above)

## 4. How to Run

```bash
git clone https://github.com/<your-user>/BiometricFail360.git
cd BiometricFail360
pip install -r requirements.txt
