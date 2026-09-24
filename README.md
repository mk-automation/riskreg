# CUD Enterprise Risk Register — GitHub Pages Demo

A static demonstration application for an institutional Enterprise Risk Register, styled in a CUD-inspired maroon/white theme.

## Live-demo deployment on GitHub Pages

1. Create a new GitHub repository, for example `cud-risk-register-demo`.
2. Upload all files from this package to the **root** of the repository.
3. Commit the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then Save.
7. GitHub will provide the public Pages link after deployment.

## Demo features

- Executive risk dashboard
- Full institutional risk register
- Add / edit / delete risks
- Initial likelihood (A–E) and impact (1–5)
- Automatic initial risk priority
- Risk treatment and mitigation plan
- Revised likelihood and impact
- Automatic residual/revised risk priority
- 5×5 risk matrix
- Category distribution
- Search and priority filters
- CSV export
- Browser localStorage persistence
- Responsive interface

## Important

This is a **front-end demonstration**. Data is stored in the browser using `localStorage`. Do not enter confidential institutional information into a public GitHub Pages deployment.

A production version should use authenticated CUD access/SSO, a secure database/API, role-based permissions, audit history, document/evidence storage, approvals and automated notifications.
