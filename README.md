<h1 align="center">👋 Welcome to Abanoub Nagy Azmy's GitHub! 🚀</h1>
<h3 align="center">Android Developer | Kotlin Enthusiast | Building Seamless Mobile Experiences</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&duration=3500&pause=1000&color=34C759&center=true&vCenter=true&width=600&lines=Crafting+Innovative+Android+Apps+with+Kotlin;Passionate+about+Clean+Architecture+and+MVI;Contributing+to+Open+Source+with+Love;Turning+Ideas+into+Pixel-Perfect+Experiences" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Abanoub-Nagy&style=flat-square&color=brightgreen" alt="Profile Views" />
</p>

---

## 🌟 About Me
👨‍💻 I'm **Abanoub Nagy Azmy**, an Android Developer from Egypt with a passion for building high-quality, user-centric mobile applications. My expertise lies in **Kotlin**, **Jetpack Compose**, and modern Android architectures like **MVI** and **Clean Architecture**. I thrive on creating apps that are not only functional but also delightful to use, leveraging tools like **Retrofit**, **Room**, and **Dagger-Hilt** to deliver robust solutions.

🔥 My journey includes contributing to open-source projects, writing about functional programming in Kotlin (check out my [LinkedIn article](https://www.linkedin.com/in/abanoub-nagy/)!), and building apps that solve real-world problems. Whether it's a weather-based clothing suggester or a task management app, I’m all about clean code, SOLID principles, and seamless user experiences.

🌍 When I'm not coding, you can find me exploring new tech trends, sharing knowledge with the dev community, or sipping coffee while brainstorming my next big project!

---

## ⚡ Tech Stack
- **Languages**: Kotlin, Java, XML
- **Android Frameworks**: Jetpack Compose, ViewModel, LiveData, Navigation, WorkManager
- **Libraries**: Retrofit, Room, Dagger-Hilt, Coroutines, Flow
- **Tools**: Android Studio, Git, Firebase, Gradle, Postman
- **Architectures**: MVI, MVVM, Clean Architecture
- **Testing**: JUnit, MockK, Espresso
- **Others**: REST APIs, Material Design, GPS Integration, Offline Caching

<p align="center">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?&style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?&style=for-the-badge&logo=android&logoColor=white" alt="Jetpack Compose" />
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?&style=for-the-badge&logo=android-studio&logoColor=white" alt="Android Studio" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?&style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Git-F05032?&style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

## 🌟 GitHub Highlights

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Abanoub-Nagy&show_icons=true&theme=tokyonight&hide_border=true" alt="Abanoub's GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Abanoub-Nagy&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abanoub-Nagy&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

## 🎯 Featured Projects

| Project | Tech Stack | Description | Repository | Demo |
|---------|------------|-------------|------------|------|
| **ClothesSuggesterApp** | Kotlin, Jetpack Compose, Retrofit, Clean Architecture | A CLI-based app suggesting clothing based on weather data from Open-Meteo API, built with MVI and SOLID principles. | [Repo](https://github.com/Abanoub-Nagy/ClothesSuggesterApp) | [Demo](#) |
| **PlanMate** | Kotlin, MongoDB, Coroutines, TDD | A task management app with user roles, dynamic states, and audit logging, using Clean Architecture and MongoDB. | [Repo](https://github.com/Abanoub-Nagy/PlanMate) | [Demo](#) |
| **WeatherTracker** | Jetpack Compose, MVI, GPS, REST API | A mobile app displaying current and 5-day weather forecasts with offline caching, built without third-party libraries. | [Repo](https://github.com/Abanoub-Nagy/WeatherTracker) | [Demo](#) |

> *Note*: Replace `[Demo]` links with actual Google Play Store links or video demos. Update repository links if names differ. Add more projects to showcase your work!

---

## 💻 Code Snippets
Here’s a glimpse of my Kotlin code for functional programming, inspired by my [LinkedIn post](https://www.linkedin.com/in/abanoub-nagy/) on pure functions:

```kotlin
// Pure function for calculating clothing suggestion based on weather
fun suggestClothing(temperature: Double, isRaining: Boolean): String {
    return when {
        temperature < 10 -> "Wear a heavy jacket${if (isRaining) " and bring an umbrella" else ""}"
        temperature < 20 -> "A light sweater${if (isRaining) " and waterproof shoes" else ""}"
        else -> "T-shirt and shorts${if (isRaining) " with a raincoat" else ""}"
    }
}
