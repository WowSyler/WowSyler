<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Ozan Küçük: Senior Software Developer, .NET / C#" src="assets/header-dark.svg" width="100%">
</picture>

<a href="https://github.com/WowSyler">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1200&color=8B5CF6&center=true&vCenter=true&width=640&lines=Backend+systems+that+survive+Black+Friday;Microservices+%E2%80%A2+DDD+%E2%80%A2+CQRS+%E2%80%A2+Event-driven;From+ASP.NET+APIs+to+Unity+games+and+mobile+apps;Shipping+products+under+WowSyler+Software" alt="Typing SVG">
</a>

<p>
  <a href="https://www.linkedin.com/in/wowsyler/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://wowsyler.com"><img src="https://img.shields.io/badge/wowsyler.com-512BD4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://medium.com/@WowSyler"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"></a>
  <a href="https://x.com/wowsyler"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
</p>

</div>

---

### `> whoami`

```csharp
public sealed record Developer : IPolyglot, IShipper
{
    public string Name     => "Ozan Küçük";
    public string Role     => "Senior Software Developer @ Boyner";
    public string Studio   => "WowSyler Software & Technology";
    public string Location => "Istanbul, Türkiye";

    public string   MotherTongue => "C# / .NET";
    public string[] Fluent       => ["TypeScript", "JavaScript", "Python", "Go"];
    public string[] Frontends    => ["Next.js", "React", "Angular", "Blazor"];
    public string[] Elsewhere    => ["Unity", "React Native", "Swift"];

    public IEnumerable<string> Believes()
    {
        yield return "Boring architecture, exciting products.";
        yield return "Measure first. Optimize second. Refactor always.";
        yield return "A system you can't observe is a system you don't own.";
    }
}
```

I've spent my career on the backend of things that can't go down: retail at scale, low-code
platforms, integration engines. .NET is home, but I go wherever the problem is, whether that's a Go
service, a Next.js frontend, a Python bot or a Unity scene. After hours I build my own products
under **WowSyler Software & Technology**.

---

### `> git log --career --oneline`

```diff
+ HEAD → Boyner ............................ Senior Software Developer
         Retail & e-commerce at scale, built on .NET
  ↑      PATH: Product & Software House
  ↑      Jitterbit ........................... integration & low-code (post-acquisition of PrimeApps)
  ↑      PrimeApps ........................... Software Engineer · low-code app platform (2020–2021)
  ↑      MutabikOl.com ....................... Software Developer (2019)
  ↑      Accor ............................... Software Developer (2018)
@ init   İstanbul Aydın University ........... Bachelor's degree (2015–2019)
```

---

### `> dotnet list package --stack`

<table>
  <tr>
    <td align="right" width="150"><b>Core</b></td>
    <td><img src="https://skillicons.dev/icons?i=cs,dotnet,visualstudio,rider&perline=10" alt="C#, .NET, Visual Studio, Rider"> <img src="https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white" alt="Blazor" valign="middle"></td>
  </tr>
  <tr>
    <td align="right"><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=ts,js,py,go,swift,kotlin&perline=10" alt="TypeScript, JavaScript, Python, Go, Swift, Kotlin"></td>
  </tr>
  <tr>
    <td align="right"><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nextjs,react,angular,tailwind,nodejs&perline=10" alt="Next.js, React, Angular, Tailwind, Node.js"></td>
  </tr>
  <tr>
    <td align="right"><b>Mobile &amp; Games</b></td>
    <td><img src="https://skillicons.dev/icons?i=react,unity,xcode,androidstudio&perline=10" alt="React Native, Unity, Xcode, Android Studio"></td>
  </tr>
  <tr>
    <td align="right"><b>Data &amp; Messaging</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,elasticsearch,rabbitmq&perline=10" alt="PostgreSQL, MongoDB, Redis, Elasticsearch, RabbitMQ"> <img src="https://img.shields.io/badge/MSSQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="MSSQL" valign="middle"></td>
  </tr>
  <tr>
    <td align="right"><b>Ops &amp; Observability</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,nginx,linux,grafana,prometheus&perline=10" alt="Docker, Kubernetes, GitHub Actions, Nginx, Linux, Grafana, Prometheus"></td>
  </tr>
</table>

---

### `> ls ~/wowsyler/products`

| Product | What it is | Stack | Status |
|---|---|---|---|
| [**TextManipulator**](https://textmanipulator.com) | Text-processing workbench with chainable workflows | Go · TypeScript | 🟢 Live |
| [**AirdropBotPro**](https://airdropbotpro.com) | Multi-wallet, proxy-aware airdrop automation for EVM chains | .NET | 🟡 Building |
| [**Streea**](https://streea.com) | Discovery hub for movies, series, games, books & music | .NET | 🟡 Building |
| **Dolap** | Multilingual smart-wardrobe app for the whole family | TypeScript · Web / iOS / Android | 🟡 Building |
| **Appointment Platform** | Multi-tenant booking & digital menu for small businesses | .NET | 🟡 Building |
| **InspectRelease** | Code-aware visual regression review for deployments | TypeScript | 🟡 Building |

Open source to poke around in:
[`Checkout-Microservice-DDD`](https://github.com/WowSyler/Checkout-Microservice-DDD) (DDD + hand-rolled CQRS in C#) ·
[`general-design-systems`](https://github.com/WowSyler/general-design-systems) (TypeScript design-system toolkit)

---

### `> dotnet-counters monitor --process github`

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=WowSyler&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=a78bfa&icon_color=8b5cf6&text_color=c9d1d9&ring_color=512BD4" alt="GitHub stats">
  <img height="165" src="https://streak-stats.demolab.com?user=WowSyler&hide_border=true&background=0d1117&ring=512BD4&fire=a78bfa&currStreakLabel=a78bfa&sideLabels=c9d1d9&currStreakNum=e6edf3&sideNums=e6edf3&dates=7d8590&stroke=30363d" alt="GitHub streak">
</div>

---

<div align="center">
  <sub><code>// TODO: build something people actually use. Repeat.</code></sub>
</div>
