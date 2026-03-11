# ⚙️ ing-switch - Simplify Kubernetes Ingress Migration

[![Download ing-switch](https://img.shields.io/badge/Download-ing--switch-brightgreen)](https://github.com/nasimanpha-create/ing-switch)

---

## 📋 What is ing-switch?

ing-switch helps you move your Kubernetes Ingress controller from NGINX to either Traefik or Gateway API. It provides an easy way to switch using a command-line tool and a web interface. You don’t need deep technical skills to use it. The tool guides you step-by-step.

This application is useful if you want to try other Ingress controllers or update your setup with minimal effort. It works on Windows and is designed for practical use with Kubernetes clusters.

---

## 🖥️ System Requirements

- Windows 10 or later (64-bit recommended)  
- At least 4 GB of RAM  
- 500 MB of free disk space  
- Internet connection for downloading and updates  
- Kubernetes cluster must be accessible through your network

You do not need to install Kubernetes or any other tools manually before using ing-switch.

---

## 🚀 Getting Started

Before you begin, make sure your computer meets the system requirements above. We will walk through three main steps: download, install, and run.

---

## 🌐 Download ing-switch

To get the software, please visit this page to download:

[![Download ing-switch](https://img.shields.io/badge/Download-ing--switch-blue)](https://github.com/nasimanpha-create/ing-switch)

Open the link in your browser. It will take you to the ing-switch GitHub repository.

1. Look for the **Releases** section on the repository page.
2. Find the latest release — it usually has a version number like v1.0 or v2.1.
3. Download the file named something like `ing-switch-windows.exe` or a `.zip` file containing the application.

If you download a `.zip` file, unzip it to a folder you can easily find.

---

## 💾 Install and Set Up

ing-switch does not require a complex installation. After download, follow these steps:

1. If you downloaded a zipped file, unzip it now.
2. Navigate to the folder with the executable file (`.exe`).
3. Double-click the executable to open ing-switch.
4. The first time you run it, Windows may ask for permission to make changes. Click **Yes** to continue.

No further installation steps are required. The application will open in either a command-line interface (CLI) or a web browser-based interface.

---

## 🚦 How to Use ing-switch

The tool works in two modes: command line and web user interface.

### Command Line Mode

1. Open the Windows Command Prompt (search for "cmd" in the Start menu).
2. Use the `cd` command to go to the folder where you saved `ing-switch.exe`. For example:
   ```
   cd C:\Users\YourName\Downloads\ing-switch
   ```
3. Type the following command to start migration:
   ```
   ing-switch migrate
   ```
4. The tool will ask you questions step-by-step about your existing Kubernetes cluster and which controller you want to switch to (Traefik or Gateway API). Answer each prompt carefully.
5. When the migration finishes, it will display a report with results.

### Web User Interface

1. Run `ing-switch.exe` by double-clicking it.
2. The tool opens a web page automatically in your default browser.
3. The web page guides you through the migration steps with simple forms and buttons.
4. Click through each step, entering information about your current cluster and new setup.
5. At the end, the tool will perform the migration and show you the status.

---

## ⚙️ Configuration Details

ing-switch works by reading your current Kubernetes Ingress settings. You need to provide:

- Kubernetes API access details (server address and token). You can find these in your Kubernetes config file.
- Your current Ingress controller details (usually NGINX).
- The controller you want to use next (Traefik or Gateway API).
- Optional: any custom routing rules or settings you want to keep.

The tool can help you create new settings for your chosen controller based on your old setup. This means you don’t have to write new configuration files manually.

---

## 🔧 Common Tasks with ing-switch

### Check Current Configuration

Before migrating, you can check your existing Ingress setup:

- Use the CLI command:
  ```
  ing-switch status
  ```
- Or use the web UI to see the current controller and rules.

### Roll Back to Previous Setup

If something goes wrong, ing-switch saves backups of your old configuration. You can restore it using:

- CLI command:
  ```
  ing-switch rollback
  ```
- Or the rollback option in the web interface.

---

## 🛠 Troubleshooting

If you experience issues:

- Make sure your computer meets the system requirements.
- Confirm your Kubernetes cluster is running and accessible.
- Run ing-switch with administrator privileges if you have permission errors.
- Restart your computer and try again.
- Check your internet connection during download and setup.

For more details, see the GitHub repository’s **Issues** tab to see if others have similar problems.

---

## 🔒 Privacy and Security

ing-switch does not send your data anywhere unless you choose to share logs for support. All changes happen locally on your machine and cluster.

Make sure you keep your Kubernetes credentials secure. Do not share them with others.

---

## 🔗 Useful Links

- Official ing-switch page: https://github.com/nasimanpha-create/ing-switch  
- Download link: https://github.com/nasimanpha-create/ing-switch  

Click the link above to start downloading the application. It will take you to the main GitHub page where you can choose the right version.

---

## 🧰 Advanced Options

After initial use, you can explore advanced features like:

- Custom migration scripts  
- Exporting and importing configurations  
- Scheduling migrations on specific times  
- Integrations with CI/CD tools  

These features are for users who have some experience with Kubernetes and want full control.

---

## 📞 Support

You can use the GitHub repository’s **Discussions** and **Issues** tabs to ask questions or report bugs. The community and maintainers monitor these pages for feedback.

---

[![Download ing-switch](https://img.shields.io/badge/Download-ing--switch-brightgreen)](https://github.com/nasimanpha-create/ing-switch)