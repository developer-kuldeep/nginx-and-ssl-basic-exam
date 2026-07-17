# Nginx and SSL Server Operations Interactive Assessment

A highly interactive, client-side web application designed to test and reinforce standard operating procedures (SOPs) for **Nginx Server Configurations, systemd lifecycle commands, UFW host-based firewalls, and Certbot SSL certificate automation**.

---

## 👤 Created By & Contact Information
*   **Lead DevOps Engineer:** KULDEEP
*   **Email Address:** [kuldeephimachal83@gmail.com](mailto:kuldeephimachal83@gmail.com)
*   **GitHub Profile:** [github.com/developer-kuldeep](https://github.com/developer-kuldeep)
*   **LinkedIn Profile:** [linkedin.com/in/kuldeep-engineer/](https://www.linkedin.com/in/kuldeep-engineer/)

---

## 🌐 Live Assessment Link
**Take the exam online now:** [https://developer-kuldeep.github.io/nginx-and-ssl-basic-exam/](https://developer-kuldeep.github.io/nginx-and-ssl-basic-exam/)

---

## 🎯 Project Overview
This specialized, lightweight, and zero-setup testing tool is designed for Systems Administrators, DevOps Engineers, and Cloud Developers. It provides a curated set of scenario-based multiple-choice questions focusing directly on commands executed in production Linux environments.

### Key Features
*   **Targeted Learning Loop:** Focuses specifically on Nginx virtual hosting (`sites-available` vs `sites-enabled`), DNS record checks, and Let's Encrypt automation.
*   **Client-Side Execution:** Zero database configurations required. Operates completely inside your modern web browser.
*   **Integrated Timer:** Simulates a realistic 15-minute test window for fast-paced system assessments.
*   **Detailed Explanations:** Upon completion, the application details a precise *Operational Logic Rationale* for every correct and incorrect answer to maximize learning retention.
*   **Instructor Grading Dispatch:** Instantly packages results and generates an automated email template targeting the course instructor.

---

## 🛠️ Core Topics Evaluated
1.  **Virtual Hosts Configuration:** Standard paths (`/etc/nginx/sites-available`), symlink rules (`ln -s`), and document root paths (`/var/www/html`).
2.  **Configuration Auditing:** Running syntax health checks (`nginx -t`) before applying live reloads.
3.  **Process Management:** Inspecting and toggling services with systemd (`systemctl start/stop/enable/status`).
4.  **DNS & IP Discovery:** Inspecting active records (`dig +short`) and finding public server IPs (`curl ifconfig.me`).
5.  **Host Firewalls:** Configuring UFW rules (`sudo ufw allow 'Nginx Full'`).
6.  **SSL/TLS Certificates:** Creating and verifying Certbot parameters (`certbot --nginx`, `certbot certificates`).

---

## 💻 Tech Stack
*   **Frontend Design:** Tailwind CSS, FontAwesome, Plus Jakarta Sans Typography.
*   **Logic Engine:** Pure vanilla JavaScript (ES6+).
*   **Hosting Compatibility:** Fully optimized for GitHub Pages or direct local browser execution.

---

## 🚀 How to Run Locally
1. Clone this repository:
   
```bash
   git clone [https://github.com/developer-kuldeep/nginx-and-ssl-basic-exam.git](https://github.com/developer-kuldeep/nginx-and-ssl-basic-exam.git)
