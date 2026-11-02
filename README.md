# Yash Marketing - Attendance & Payroll OS

Enterprise web application for employee attendance tracking, real-time chronometrics, Short Break deductions, 50m geofence radius verification, and CEO/Management admin oversight.

---

## ?? Management & Role Privileges (CEO / Owner)
- **Role Transfer Complete**: All Owner management controls have been transferred to the **CEO** role (both `CEO` and `Owner` are supported).
- **Admin Command Center**: CEO has full access to the Command Center (`adminControlView`), pending leave approvals queue (`adminPendingLeaves`), and the all-staff chronometric salary ledger (`allStaffPayrollGrid`).
- **Roaming Verification Bypass**: CEO and roaming staff (`Sales Boy`) are exempt from the 50m warehouse geofence constraint and can punch in/out from anywhere with verified GPS coords.
- **Management Payroll Rule**: CEO/Owner accounts are evaluated strictly on leadership criteria without automatic weekly off day additions.

---

## ?? Google Apps Script & Cloud Setup
- **Linked Script ID**: `1_6DlcMPwzemHko_D3dTx21ay1vbm3JdOr04WSRHigvgsnnPvIqlW3qxU`
- **GitHub Repository**: `yashmbarlota007/attendance-app`
- **Sync Method**: Use **Google Apps Script GitHub Assistant** browser extension to push and pull between this repo (`main` branch) and the GAS editor.

---

## ?? Repository Structure
- `Code.gs`: Server-side Google Apps Script backend (Authentication, Punch Logs, Short Breaks, Photo upload to Google Drive, and Chronometric Payroll).
- `Index.html`: Responsive frontend single-page application with Leaflet/GPS verification, camera snapshot modal, calendar grid, and CEO Command Center.
- `.clasp.json`: Google Apps Script configuration file for deployment and sync.
