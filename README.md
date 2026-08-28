# ServFlow

> A modern SFTP server for Android.

ServFlow allows you to run an SFTP file server directly from your Android device. It provides a simple and modern interface for starting and managing your server while giving you control over network interfaces, IP addresses, ports, and authentication.

> 🚧 **ServFlow is currently under active development.** Features, functionality, and the user interface may change as the project continues to evolve.

## ✨ Features

* 🔐 SFTP server support
* 🌐 Network interface and IP address selection
* 🔌 Custom SFTP port
* 👤 Configurable username and password
* 💾 Persistent credentials and server configuration
* ▶️ Simple start and stop controls
* 📊 Server status and connection information
* ⚙️ Advanced server settings
* 🎨 Modern dark glassmorphic interface

## 📱 Preview

Screenshots coming soon.

## 🛠️ Building from Source

### Requirements

* Android Studio
* Android SDK
* JDK compatible with the project configuration
* Gradle

### Build

Clone the repository:

```bash
git clone https://github.com/LeoAndres11/ServFlow.git
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

ServFlow allows you to configure:

* SFTP port
* Username
* Password
* Network interface
* IP address binding
* Server startup options

Your username, password, and server configuration remain saved until you manually change them.

## 🔒 Security

Running an SFTP server makes files on your device accessible over a network.

Please:

* Use a strong password.
* Only share your server with trusted users.
* Avoid exposing the server directly to the public internet unless you understand the security implications.
* Only grant the app access to files you intend to share.
* Review your network and firewall configuration before allowing external connections.

## 🤝 Contributing

Contributions, bug reports, feature requests, and improvements are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test the application.
5. Submit a pull request.

For major changes, please open an issue first to discuss the proposed change.

## 📄 License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

You are free to use, modify, and distribute this project under the terms of the GPL-3.0 license. Any distributed modifications or derivative works must also be licensed under GPL-3.0.

See the [LICENSE](LICENSE) file for more details.

---

Built with passion by — Arif Khan ❤️
