# SECURITY.md

## Security Policy

### Reporting a Vulnerability

If you discover a security vulnerability in **YouandAI — Far Shore** or any of its components, **never** disclose it publicly until it is fixed.

**Strict procedure:**

1. Email the core security team at **[youandaicontact@gmail.com](mailto:youandaicontact@gmail.com)** immediately.
2. Include:

   * Full technical details and proof-of-concept
   * Steps to reproduce
   * Severity assessment
   * Suggested mitigation if possible
3. Expect acknowledgement within **48 hours** and a full response within **7 days**.

**Anonymous reporting** is supported — whistleblowers’ identities will be protected.

### Public Contribution Review Process

* Any **new contribution** (code, scripts, or assets) will first be placed in a **public review poll**.
* The poll will remain visible for community inspection so viewers can **spot and report suspicious activity, malicious code, or unsafe scripts**.
* Reports will be reviewed by the core security team.
* Only after **community feedback review and security approval** will the contribution proceed to merging.

### Disclosure Timeline

* **Critical issues**: Patched and released within **72 hours** of confirmation.
* **High severity**: Fixed within **7 days**.
* **Low severity**: Addressed in the next scheduled release.
* Public disclosure only occurs after a verified fix or mitigation is in place.
* Coordinated disclosure is mandatory; leaks before fixes are strictly prohibited.

### Secure Development Standards

* Every change **must** pass a **formal security review** before merging.
* All dependencies are scanned for vulnerabilities before release.
* All commits require **code signing** for authenticity.
* Mandatory static and dynamic security analysis on every PR.
* Security unit tests must pass before approval.
* Introducing any of the following will result in **immediate removal, permanent ban, and possible legal action**:

  * Weakening or bypassing encryption
  * Exposing private or identifying user data
  * Circumventing consent mechanisms or privacy safeguards
  * Creating backdoors or malicious code paths
  * Adding third-party trackers or telemetry without approval
  * Embedding unvetted binaries or compiled code

### Incident Response

* If an active exploit is found, the affected component will be **immediately pulled** from public use.
* Users will be notified through all official channels.
* Emergency patches will override normal release cycles.
* Repeat or deliberate offenders will be reported to relevant legal authorities.
