
#  PastPortals – AI-Powered Historical Time Travel

[![GitHub Stars](https://img.shields.io/github/stars/Muppala-Jasvanth-Varma/pastportals?style=social)](https://github.com/Muppala-Jasvanth-Varma/pastportals)
[![Forks](https://img.shields.io/github/forks/Muppala-Jasvanth-Varma/pastportals?style=social)](https://github.com/Muppala-Jasvanth-Varma/pastportals/fork)
[![License](https://img.shields.io/github/license/your-username/pastportals)](LICENSE)

**PastPortals** is an AI-driven mobile + web platform that transforms historical data into immersive video stories using text-to-image and image-to-video synthesis. Explore history like never before with dynamic AI visuals and Wikipedia-based summaries.

---

## 📥 Clone & Run Locally

### Backend (Node.js + Express)

```bash
git clone https://github.com/your-username/pastportals.git
cd pastportals/backend
npm install
npm run dev
````

> Create a `.env` file with:
>
> ```
> OPENAI_API_KEY=your_key_here
> ```

### Frontend (Android - Kotlin)

1. Open `pastportals/frontend` in **Android Studio**
2. Sync Gradle and run on emulator/device
3. Ensure the backend API is accessible (localhost/remote)

---

## 🔍 Features

* 🔎 Search history by **year**, **event**, or **famous person**
* 🖼️ **AI-generated images** from prompts
* 🎥 **Video generation** via frame interpolation
* 📚 Wikipedia-powered summaries
* 🎨 Kotlin UI using Jetpack Compose
* ⚙️ Node.js backend with REST APIs

---

## 🧱 Tech Stack

| Layer       | Technology                                     |
| ----------- | ---------------------------------------------- |
| Frontend    | Kotlin, Jetpack Compose                        |
| Backend     | Node.js, Express.js                            |
| API         | Pictory API                                    |
| Data Source | Wikipedia API                                  |
| Hosting     | Vercel / Render / Firebase (optional)          |

---

## 🗂️ Project Structure

```
pastportals/
├── backend/                 # Express backend API
│   ├── routes/
│   ├── controllers/
│   └── utils/
├── frontend/                # Android app (Jetpack Compose)
│   ├── ui/
│   ├── viewmodels/
│   └── networking/
└── README.md
```

---

## 🌐 API Endpoints

| Method | Endpoint            | Description                           |
| ------ | ------------------- | ------------------------------------- |
| GET    | `/api/event/:query` | Fetch historical summary and visuals  |
| GET    | `/api/year/:year`   | Fetch major events of a specific year |
| GET    | `/api/person/:name` | Fetch data about a historical figure  |

---

## 🎯 Future Enhancements

* [ ] Add user accounts + history
* [ ] Voice-based search
* [ ] Narrated video generation (TTS)
* [ ] Export/share generated videos

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

---

## 📬 Contact

Developed by **Jasvanth Varma Muppala**
✉️ [jasvanthvarmamuppala@gmail.com](mailto:jasvanthvarmamuppala@gmail.com)
🔗 [LinkedIn](www.linkedin.com/in/jasvanth-varma-muppala-275jb)

---

## 📄 License

This project is licensed under the **MIT License**.
See [LICENSE](./LICENSE) for details.


---
