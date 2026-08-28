<img width="706" height="1461" alt="5" src="https://github.com/user-attachments/assets/33827360-1dd4-4579-ad7e-cc51945421cb" /><img width="706" height="1455" alt="4" src="https://github.com/user-attachments/assets/3e20c1ec-f91a-47b8-b05b-b5cdf48f72aa" /><img width="706" height="1463" alt="3" src="https://github.com/user-attachments/assets/9ee0b5be-f5fa-481e-9502-c7e8622edfb9" /># ServFlow

> A modern SFTP server for Android.

ServFlow allows you to run an SFTP file server directly from your Android device. It provides a simple and modern interface for starting and managing your server while giving you control over network interfaces, IP addresses, ports, and authentication.

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

<img width="706" height="1464" alt="1" src="https://github.com/user-attachments/assets/b2aa2112-4a8f-4669-95a1-a1640d95b1a7" />
<img width="706" height="1459" alt="2" src="https://github.com/user-attachments/assets/9d846d69-cbe0-4e7d-b2c3-1ead51605d52" />
<img width="706" height="1463" alt="3" src="https://github.com/user-attachments/assets/5e44f6fe-ebe6-4991-98b5-497d8f284fe1" />
<img width="706" height="1455" alt="4" src="https://github.com/user-attachments/assets/b876c0a1-dd94-47fa-a926-67d760131c39" />
<img width="706" height="1461" alt="5" src="https://github.com/user-attachments/assets/0bcf01bd-3cb0-4562-8726-bb0b0740d64c" />
<img width="706" height="1471" alt="6" src="https://github.com/user-attachments/assets/3a1544be-b203-4f87-ab8a-afdeaed96f6c" />


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
