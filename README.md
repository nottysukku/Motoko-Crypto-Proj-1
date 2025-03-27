# 💰 DBank - Decentralized Banking on the Internet Computer

Welcome to **DBank**, a decentralized banking application built on the **Internet Computer**. This project demonstrates how to create a simple yet powerful banking system using **Motoko**, **JavaScript**, and **Webpack**.

---

## 🚀 Features

- 🌟 **Top-Up** your account balance.
- 💸 **Withdraw** funds securely.
- 📈 **Compound Interest** applied automatically over time.
- 🔗 Fully decentralized and hosted on the Internet Computer.
- 🎨 Clean and responsive UI.

---

## 📂 Project Structure

```
dbank/
├── .gitignore
├── canister_ids.json
├── dfx.json
├── package.json
├── README.md
├── webpack.config.js
├── src/
│   ├── dbank/
│   │   └── main.mo
│   ├── dbank_assets/
│   │   ├── assets/
│   │   │   ├── dbank_logo.png
│   │   │   ├── favicon.ico
│   │   │   ├── main.css
│   │   │   └── sample-asset.txt
│   │   ├── src/
│   │   │   ├── index.html
│   │   │   └── index.js
│   ├── declarations/
│       ├── dbank/
│       ├── dbank_assets/
```

---

## 🛠️ Installation & Setup

### Prerequisites
- Install [Node.js](https://nodejs.org/)
- Install [DFX SDK](https://internetcomputer.org/docs/current/developer-docs/setup/install/)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/nottysukku/dbank.git
   cd dbank
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the Internet Computer local replica:
   ```bash
   dfx start --clean
   ```

4. Deploy the canisters:
   ```bash
   dfx deploy
   ```

5. Start the development server:
   ```bash
   npm start
   ```

6. Open your browser and navigate to:
   ```
   http://localhost:8080
   ```

---

## 🖼️ Screenshots

### Home Page
![DBank Home Page](src/dbank_assets/assets/dbank_logo.png)

---

## 🧑‍💻 Technologies Used

- **Motoko**: For backend logic.
- **JavaScript**: For frontend interactivity.
- **Webpack**: For bundling assets.
- **HTML/CSS**: For UI design.
- **DFX SDK**: For deploying and managing canisters.

---

## 📜 Scripts

| Command            | Description                                  |
|--------------------|----------------------------------------------|
| `npm start`        | Starts the development server.              |
| `npm run build`    | Builds the project for production.          |
| `dfx deploy`       | Deploys the canisters to the Internet Computer. |

---

## 🛡️ Security

This project is for educational purposes. Do not use it for real financial transactions.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🌟 Acknowledgments

- [DFINITY Foundation](https://dfinity.org/) for the Internet Computer.
- [Motoko Programming Language](https://internetcomputer.org/docs/current/motoko/main/motoko-introduction/).

---

## 📬 Contact

For any questions or feedback, feel free to reach out:

- **Email**: sukritchopra76@gmail.com
- **GitHub**: [nottysukku](https://github.com/nottysukku)

---

Made with ❤️ by [Sukrit](https://github.com/nottysukku)