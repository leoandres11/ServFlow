# ServFlow
A modern FTP &amp; SFTP server for Android with configurable ports, persistent credentials, network interface selection, and a clean dark UI.

# ServFlow

> A modern FTP & SFTP server for Android.

ServFlow allows you to run FTP and SFTP file servers directly from your Android device. It provides a simple interface for starting and managing servers while giving you control over network interfaces, IP addresses, ports, and authentication.

## ✨ Features

* 📁 FTP server support
* 🔐 SFTP server support
* 🌐 Network interface and IP address selection
* 🔌 Custom FTP and SFTP ports
* 👤 Configurable username and password
* 💾 Persistent server configuration
* ▶️ Simple start and stop controls
* 📊 Server status and connection information
* ⚙️ Advanced server settings
* 🎨 Modern dark glassmorphic interface

## 📱 Screenshots

Screenshots will be added as the project develops.

<!--
Example:

<p align="center">
  <img src="docs/images/home.png" width="250">
  <img src="docs/images/settings.png" width="250">
</p>
-->

## 🚀 Installation

Download the latest APK from the [Releases](../../releases) page and install it on your Android device.

You may need to allow installation from unknown sources depending on your Android version and device settings.

## 🛠️ Building from Source

### Requirements

* Android Studio
* Android SDK
* JDK compatible with the project configuration
* Gradle

### Build

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/ServFlow.git
```

Open the project in Android Studio and allow Gradle to sync.

Then build the debug APK:

```bash
./gradlew assembleDebug
```

The generated APK will normally be available in:

```text
app/build/outputs/apk/debug/
```

## ⚙️ Configuration

ServFlow allows configuration of:

* FTP port
* SFTP port
* Username
* Password
* Network interface
* IP address binding
* Server startup options

Configuration remains saved until manually changed.

## 🔒 Security

Running an FTP or SFTP server exposes files and network services on your device.

Please:

* Use a strong password.
* Prefer SFTP when possible.
* Avoid exposing the server directly to the public internet unless you understand the security implications.
* Only grant the app access to files you intend to share.
* Review your network and firewall configuration.

## 🗺️ Roadmap


* [ ] FTP server
* [ ] SFTP server
* [ ] Network interface selection
* [ ] Custom IP binding
* [ ] Persistent configuration
* [ ] Server activity logs
* [ ] Connected client information
* [ ] File access controls
* [ ] Background service support
* [ ] Material You customization

## 🤝 Contributing

Contributions, bug reports, feature requests, and improvements are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test the application.
5. Submit a pull request.

For major changes, please open an issue first to discuss the proposed change.

## 📄 License

This project is licensed under the GNU General Public License v3.0.

See the [LICENSE](LICENSE) file for details.

---

**ServFlow** — Simple, secure file serving from Android.

